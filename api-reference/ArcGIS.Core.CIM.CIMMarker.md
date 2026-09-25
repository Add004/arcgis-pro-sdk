# CIMMarker

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarker.yml" sourcestartlinenumber="1">Represents a marker which is a self-contained shape or image that can draw for a point graphic or placed in a repeating arrangement along a stroke or within a fill. It can be a glyph from a font, a picture, a collection of vector geometries, or a 3D model.</p>


## Object Signature

```csharp
public abstract class CIMMarker : CIMSymbolLayer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMarker()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarker.yml" sourcestartlinenumber="1">Represents a marker which is a self-contained shape or image that can draw for a point graphic or placed in a repeating arrangement along a stroke or within a fill. It can be a glyph from a font, a picture, a collection of vector geometries, or a 3D model.</p>


```csharp
protected CIMMarker()
```
### AnchorPoint

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarker.yml" sourcestartlinenumber="1">Gets or sets the specified location where all transformation property operations originate.</p>


```csharp
public MapPoint AnchorPoint { get; set; }
```
### AnchorPointUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarker.yml" sourcestartlinenumber="1">Gets or sets a value which specifies if the anchor point location is considered a percentage of the size or as an absolute distance.</p>


```csharp
public SymbolUnits AnchorPointUnits { get; set; }
```
### AngleX

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarker.yml" sourcestartlinenumber="1">Gets or sets the angle the marker is rotated around the X axis.</p>


```csharp
public double AngleX { get; set; }
```
### AngleY

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarker.yml" sourcestartlinenumber="1">Gets or sets the angle the marker is rotated around the Y axis.</p>


```csharp
public double AngleY { get; set; }
```
### BillboardMode3D

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarker.yml" sourcestartlinenumber="1">Gets or sets the billboard mode of the marker.</p>


```csharp
public BillboardMode BillboardMode3D { get; set; }
```
### DominantSizeAxis3D

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarker.yml" sourcestartlinenumber="1">Gets or sets which axis is considered as the Size in 3D. Only applicable when the marker layer is a 3DShapeMarker.</p>


```csharp
public DominantSizeAxis DominantSizeAxis3D { get; set; }
```
### MarkerPlacement

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarker.yml" sourcestartlinenumber="1">Gets or sets marker placements which determine how markers are placed along a line or within a polygon.</p>


```csharp
public CIMMarkerPlacement MarkerPlacement { get; set; }
```
### OffsetX

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarker.yml" sourcestartlinenumber="1">Gets or sets the value the marker is moved along the X axis from the anchor point. This is applied after all rotation, as opposed to anchor point which is applied before the rotation.</p>


```csharp
public double OffsetX { get; set; }
```
### OffsetY

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarker.yml" sourcestartlinenumber="1">Gets or sets the value the marker is moved along the Y axis from the anchor point. This is applied after all rotation, as opposed to anchor point which is applied before the rotation.</p>


```csharp
public double OffsetY { get; set; }
```
### OffsetZ

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarker.yml" sourcestartlinenumber="1">Gets or sets the value the marker is moved along the Z axis from the anchor point. This is applied after all rotation, as opposed to anchor point which is applied before the rotation.</p>


```csharp
public double OffsetZ { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarker.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RotateClockwise

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarker.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the rotation is applied clockwise or counterclockwise to the marker layer.</p>


```csharp
public bool RotateClockwise { get; set; }
```
### Rotation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarker.yml" sourcestartlinenumber="1">Gets or sets the angle that the marker is rotated around the anchor point, in degrees.</p>


```csharp
public double Rotation { get; set; }
```
### Size

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarker.yml" sourcestartlinenumber="1">Gets or sets the height of the marker. Modifying Size changes the marker's height to the specified size and the width is updated proportionally.</p>


```csharp
public double Size { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarker.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


