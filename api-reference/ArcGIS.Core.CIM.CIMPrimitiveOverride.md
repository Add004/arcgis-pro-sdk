# CIMPrimitiveOverride

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMPrimitiveOverride.yml" sourcestartlinenumber="1">Represents a primitive override.</p>


## Object Signature

```csharp
public class CIMPrimitiveOverride : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMPrimitiveOverride()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMPrimitiveOverride.yml" sourcestartlinenumber="1">Represents a primitive override.</p>


```csharp
public CIMPrimitiveOverride()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPrimitiveOverride.yml" sourcestartlinenumber="1">Creates a deep copy of CIMPrimitiveOverride.</p>


```csharp
public CIMPrimitiveOverride Clone()
```
### Expression

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPrimitiveOverride.yml" sourcestartlinenumber="1">Gets or sets the expression.</p>


```csharp
public string Expression { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPrimitiveOverride.yml" sourcestartlinenumber="1">Reconstructs the CIMPrimitiveOverride with a specified state from a JSON encoding.</p>


```csharp
public static CIMPrimitiveOverride FromJson(string json, JsonDeserializationSettings settings = null)
```
### PrimitiveName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPrimitiveOverride.yml" sourcestartlinenumber="1">Gets or sets the primitive name this override applies to.</p>


```csharp
public string PrimitiveName { get; set; }
```
### PropertyName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPrimitiveOverride.yml" sourcestartlinenumber="1">Gets or sets the property name in the primitive this override applies to.</p>


```csharp
public string PropertyName { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPrimitiveOverride.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPrimitiveOverride.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMPrimitiveOverride and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### ValueExpressionInfo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPrimitiveOverride.yml" sourcestartlinenumber="1">Gets or sets ExpressionInfo that contains the Arcade expression that returns value as a number or a string depending on the PropertyName.</p>


```csharp
public CIMExpressionInfo ValueExpressionInfo { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPrimitiveOverride.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


