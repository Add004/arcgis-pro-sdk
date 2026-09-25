# CIMGroupElement

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroupElement.yml" sourcestartlinenumber="1">Represents a collection of layout elements in a group element.</p>


## Object Signature

```csharp
public class CIMGroupElement : CIMFrameElement, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGroupElement()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroupElement.yml" sourcestartlinenumber="1">Represents a collection of layout elements in a group element.</p>


```csharp
public CIMGroupElement()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroupElement.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGroupElement.</p>


```csharp
public CIMGroupElement Clone()
```
### Elements

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroupElement.yml" sourcestartlinenumber="1">Gets or sets a collection of elements.</p>


```csharp
public CIMElement[] Elements { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroupElement.yml" sourcestartlinenumber="1">Reconstructs the CIMGroupElement with a specified state from a JSON encoding.</p>


```csharp
public static CIMGroupElement FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroupElement.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroupElement.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGroupElement and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroupElement.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


