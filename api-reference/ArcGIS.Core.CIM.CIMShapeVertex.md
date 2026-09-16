# CIMShapeVertex

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMShapeVertex.yml" sourcestartlinenumber="1">Represents a shape vertex.</p>


## Object Signature

```csharp
public class CIMShapeVertex : CIMObject, INotifyPropertyChanged, IXmlSerializable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.CIMShapeVertex.yml" sourcestartlinenumber="1">Each Vertex in a 3DShapeGraphic is represented by three points, contained in a ShapeVertex. The first point is the actual position of the Vertex. The second represents the normalized vector that describes the orientation of the point. The last point is optional - it defines the coordinates of the texture that correspond with this point in the shape. In this case only x and y are used as the traditional texture coordinates S and T.</p>


## Members

### CIMShapeVertex()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMShapeVertex.yml" sourcestartlinenumber="1">Represents a shape vertex.</p>


```csharp
public CIMShapeVertex()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMShapeVertex.yml" sourcestartlinenumber="1">Creates a deep copy of CIMShapeVertex.</p>


```csharp
public CIMShapeVertex Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMShapeVertex.yml" sourcestartlinenumber="1">Reconstructs the CIMShapeVertex with a specified state from a JSON encoding.</p>


```csharp
public static CIMShapeVertex FromJson(string json, JsonDeserializationSettings settings = null)
```
### NormalVector

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMShapeVertex.yml" sourcestartlinenumber="1">Gets or sets the normal vector.</p>


```csharp
public MapPoint NormalVector { get; set; }
```
### Position

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMShapeVertex.yml" sourcestartlinenumber="1">Gets or sets the position.</p>


```csharp
public MapPoint Position { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMShapeVertex.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### TextureCoordinate

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMShapeVertex.yml" sourcestartlinenumber="1">Gets or sets the texture coordinate.</p>


```csharp
public MapPoint TextureCoordinate { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMShapeVertex.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMShapeVertex and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMShapeVertex.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


