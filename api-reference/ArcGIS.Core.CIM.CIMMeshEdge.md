# CIMMeshEdge

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeshEdge.yml" sourcestartlinenumber="1">Represents a stroke drawn at specified edges of a mesh.</p>


## Object Signature

```csharp
public abstract class CIMMeshEdge : CIMSymbolLayer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMeshEdge()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeshEdge.yml" sourcestartlinenumber="1">Represents a stroke drawn at specified edges of a mesh.</p>


```csharp
protected CIMMeshEdge()
```
### ApplyThresholdAngleToBothSidesOfFaces

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeshEdge.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether threshold angle applies to both sides of faces.</p>


```csharp
public bool ApplyThresholdAngleToBothSidesOfFaces { get; set; }
```
### Color

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeshEdge.yml" sourcestartlinenumber="1">Gets or sets the color of the mesh stroke.</p>


```csharp
public CIMColor Color { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeshEdge.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ThresholdAngle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeshEdge.yml" sourcestartlinenumber="1">Gets or sets the minimum edge angle between two neighboring face normals.</p>


```csharp
public double ThresholdAngle { get; set; }
```
### Width

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeshEdge.yml" sourcestartlinenumber="1">Gets or sets the width (in points) of the mesh stroke.</p>


```csharp
public double Width { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeshEdge.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


