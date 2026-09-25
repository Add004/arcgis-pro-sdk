# CIMExpressionInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMExpressionInfo.yml" sourcestartlinenumber="1">Represents the properties required for authoring an Arcade expression.</p>


## Object Signature

```csharp
public class CIMExpressionInfo : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMExpressionInfo()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMExpressionInfo.yml" sourcestartlinenumber="1">Represents the properties required for authoring an Arcade expression.</p>


```csharp
public CIMExpressionInfo()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMExpressionInfo.yml" sourcestartlinenumber="1">Creates a deep copy of CIMExpressionInfo.</p>


```csharp
public CIMExpressionInfo Clone()
```
### Expression

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMExpressionInfo.yml" sourcestartlinenumber="1">Gets or sets the Arcade expression used to evaluate and return the value that a property expects.</p>


```csharp
public string Expression { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMExpressionInfo.yml" sourcestartlinenumber="1">Reconstructs the CIMExpressionInfo with a specified state from a JSON encoding.</p>


```csharp
public static CIMExpressionInfo FromJson(string json, JsonDeserializationSettings settings = null)
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMExpressionInfo.yml" sourcestartlinenumber="1">Gets or sets the name of the expression.</p>


```csharp
public string Name { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMExpressionInfo.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ReturnType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMExpressionInfo.yml" sourcestartlinenumber="1">Gets or sets the return type of the expression.</p>


```csharp
public ExpressionReturnType ReturnType { get; set; }
```
### Title

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMExpressionInfo.yml" sourcestartlinenumber="1">Gets or sets the human readable text that describes the expression.</p>


```csharp
public string Title { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMExpressionInfo.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMExpressionInfo and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMExpressionInfo.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


