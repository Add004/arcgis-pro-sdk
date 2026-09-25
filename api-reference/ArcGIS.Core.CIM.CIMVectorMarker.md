# CIMVectorMarker

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMVectorMarker.yml" sourcestartlinenumber="1">Represents a vector marker which can represent vector graphics. It's constructed from MarkerGraphics which are geometries and symbols used as building blocks for the marker.</p>


## Object Signature

```csharp
public class CIMVectorMarker : CIMMarker, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMVectorMarker()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMVectorMarker.yml" sourcestartlinenumber="1">Represents a vector marker which can represent vector graphics. It's constructed from MarkerGraphics which are geometries and symbols used as building blocks for the marker.</p>


```csharp
public CIMVectorMarker()
```
### ClippingPath

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVectorMarker.yml" sourcestartlinenumber="1">Gets or sets a clipping path for the vector marker graphics.</p>


```csharp
public CIMClippingPath ClippingPath { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVectorMarker.yml" sourcestartlinenumber="1">Creates a deep copy of CIMVectorMarker.</p>


```csharp
public CIMVectorMarker Clone()
```
### Depth3D

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVectorMarker.yml" sourcestartlinenumber="1">Gets or sets the depth of the marker when drawn in 3D.</p>


```csharp
public double Depth3D { get; set; }
```
### Frame

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVectorMarker.yml" sourcestartlinenumber="1">Gets or sets the outer boundary of the entire vector marker.</p>


```csharp
public Envelope Frame { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVectorMarker.yml" sourcestartlinenumber="1">Reconstructs the CIMVectorMarker with a specified state from a JSON encoding.</p>


```csharp
public static CIMVectorMarker FromJson(string json, JsonDeserializationSettings settings = null)
```
### MarkerGraphics

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVectorMarker.yml" sourcestartlinenumber="1">Gets or sets the vector graphics that define the shape of the marker.</p>


```csharp
public CIMMarkerGraphic[] MarkerGraphics { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVectorMarker.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RespectFrame

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVectorMarker.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the frame of the vector marker should be honored when drawing the marker.</p>


```csharp
public bool RespectFrame { get; set; }
```
### ScaleSymbolsProportionally

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVectorMarker.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the strokes and or fills of a marker are scaled proportionally when the symbol size is changed.</p>


```csharp
public bool ScaleSymbolsProportionally { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVectorMarker.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMVectorMarker and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### VerticalOrientation3D

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVectorMarker.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the marker stands upright as though locked in place. The marker can be viewed from all angles.</p>


```csharp
public bool VerticalOrientation3D { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVectorMarker.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


