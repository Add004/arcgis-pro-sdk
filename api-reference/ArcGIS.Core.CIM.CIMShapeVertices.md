# CIMShapeVertices

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMShapeVertices.yml" sourcestartlinenumber="1">Represents shape vertices.</p>


## Object Signature

```csharp
public class CIMShapeVertices : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMShapeVertices()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMShapeVertices.yml" sourcestartlinenumber="1">Represents shape vertices.</p>


```csharp
public CIMShapeVertices()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMShapeVertices.yml" sourcestartlinenumber="1">Creates a deep copy of CIMShapeVertices.</p>


```csharp
public CIMShapeVertices Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMShapeVertices.yml" sourcestartlinenumber="1">Reconstructs the CIMShapeVertices with a specified state from a JSON encoding.</p>


```csharp
public static CIMShapeVertices FromJson(string json, JsonDeserializationSettings settings = null)
```
### Indices

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMShapeVertices.yml" sourcestartlinenumber="1">Gets or sets the indices.</p>


```csharp
public int Indices { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMShapeVertices.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Shapes

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMShapeVertices.yml" sourcestartlinenumber="1">Gets or sets the shape.</p>


```csharp
public string Shapes { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMShapeVertices.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMShapeVertices and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMShapeVertices.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


