# Envelope

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.Envelope.yml" sourcestartlinenumber="1">An envelope is an axis-aligned box described by the coordinates
of the lower left corner and the coordinates of the upper right corner. To create an envelope use the
<xref href="ArcGIS.Core.Geometry.EnvelopeBuilderEx" data-throw-if-not-resolved="false"></xref> object.</p>


## Object Signature

```csharp
public sealed class Envelope : Geometry
```


## Members

### Area

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Envelope.yml" sourcestartlinenumber="1">Gets the area of this instance.</p>


```csharp
public double Area { get; }
```
### Center

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Envelope.yml" sourcestartlinenumber="1">Gets the center of this instance as a <xref href="ArcGIS.Core.Geometry.MapPoint" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public MapPoint Center { get; }
```
### CenterAt(double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Envelope.yml" sourcestartlinenumber="1">Center the envelope at the specified X and Y coordinate.</p>


```csharp
public Envelope CenterAt(double x, double y)
```
### CenterCoordinate

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Envelope.yml" sourcestartlinenumber="1">Gets the center of this instance as a <xref href="ArcGIS.Core.Geometry.Coordinate2D" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public Coordinate2D CenterCoordinate { get; }
```
### Depth

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Envelope.yml" sourcestartlinenumber="1">Gets the depth of this instance.</p>


```csharp
public double Depth { get; }
```
### Expand(double, double, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Envelope.yml" sourcestartlinenumber="1">Moves the X and Y coordinates of the envelope sides toward or away from each other to scale the size of the envelope.</p>


```csharp
public Envelope Expand(double dx, double dy, bool asRatio)
```
### Extent

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Envelope.yml" sourcestartlinenumber="1">Gets the minimum enclosing envelope of this instance. Returns null if this geometry has IsEmpty = true.</p>


```csharp
public override Envelope Extent { get; }
```
### GeometryType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Envelope.yml" sourcestartlinenumber="1">Gets the GeometryType of this instance.  Always returns <xref href="ArcGIS.Core.Geometry.GeometryType.Envelope" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public override GeometryType GeometryType { get; }
```
### Height

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Envelope.yml" sourcestartlinenumber="1">Gets the height of this instance.</p>


```csharp
public double Height { get; }
```
### IDMax

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Envelope.yml" sourcestartlinenumber="1">Gets the ID maximum of this instance.</p>


```csharp
public int IDMax { get; }
```
### IDMin

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Envelope.yml" sourcestartlinenumber="1">Gets the ID minimum of this instance.</p>


```csharp
public int IDMin { get; }
```
### Intersection(Envelope)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Envelope.yml" sourcestartlinenumber="1">Calculates the intersection between this instance and the specified envelope.</p>


```csharp
public Envelope Intersection(Envelope envelope)
```
### Intersects(Envelope)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Envelope.yml" sourcestartlinenumber="1">Determines if this instance intersects the supplied envelope.</p>


```csharp
public bool Intersects(Envelope envelope)
```
### IsEmpty

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Envelope.yml" sourcestartlinenumber="1">Gets a value indicating whether or not the geometry is empty.</p>


```csharp
public override bool IsEmpty { get; }
```
### IsEqual(Envelope)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Envelope.yml" sourcestartlinenumber="1">Compares two <xref href="ArcGIS.Core.Geometry.Envelope" data-throw-if-not-resolved="false"></xref> for equality. This will check the <xref href="ArcGIS.Core.Geometry.SpatialReference" data-throw-if-not-resolved="false"></xref>
and coordinates for a match.</p>
<param name="envelope">An envelope to test for equality.<returns>Value to indicate if the two geometries are equal.</returns>


```csharp
public bool IsEqual(Envelope envelope)
```
### IsEqual(Envelope, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Envelope.yml" sourcestartlinenumber="1">Compares two envelopes for equality while considering the given tolerance.</p>


```csharp
public bool IsEqual(Envelope envelope, double tolerance)
```
### Length

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Envelope.yml" sourcestartlinenumber="1">Gets the perimeter length of this instance.</p>


```csharp
public override double Length { get; }
```
### Length3D

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Envelope.yml" sourcestartlinenumber="1">Gets the 3D length of the perimeter of this instance.</p>


```csharp
public double Length3D { get; }
```
### MMax

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Envelope.yml" sourcestartlinenumber="1">Gets the M maximum of this instance.</p>


```csharp
public double MMax { get; }
```
### MMin

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Envelope.yml" sourcestartlinenumber="1">Gets the M minimum of this instance.</p>


```csharp
public double MMin { get; }
```
### PointCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Envelope.yml" sourcestartlinenumber="1">Gets the point count of this instance. Always returns 5.</p>


```csharp
public override int PointCount { get; }
```
### ToEsriShape()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Envelope.yml" sourcestartlinenumber="1">Converts this envelope into an Esri shape formatted binary byte buffer.
Note that the returned buffer will represent a polygon as there is not an Esri shape buffer for envelope geometry type.</p>


```csharp
public override byte[] ToEsriShape()
```
### ToEsriShape(ref byte[])

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Envelope.yml" sourcestartlinenumber="1">Converts this envelope into an Esri shape formatted binary byte buffer.
Note that the returned buffer will represent a polygon as there is not an Esri shape buffer for envelope geometry type.</p>


```csharp
public override long ToEsriShape(ref byte[] shapeBuffer)
```
### Union(Envelope)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Envelope.yml" sourcestartlinenumber="1">Returns the union of this instance and the specified envelope.</p>


```csharp
public Envelope Union(Envelope envelope)
```
### Width

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Envelope.yml" sourcestartlinenumber="1">Gets the width of this instance.</p>


```csharp
public double Width { get; }
```
### XMax

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Envelope.yml" sourcestartlinenumber="1">Gets the X maximum of this instance.</p>


```csharp
public double XMax { get; }
```
### XMin

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Envelope.yml" sourcestartlinenumber="1">Gets the X minimum of this instance.</p>


```csharp
public double XMin { get; }
```
### YMax

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Envelope.yml" sourcestartlinenumber="1">Gets the Y maximum of this instance.</p>


```csharp
public double YMax { get; }
```
### YMin

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Envelope.yml" sourcestartlinenumber="1">Gets the Y minimum of this instance.</p>


```csharp
public double YMin { get; }
```
### ZMax

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Envelope.yml" sourcestartlinenumber="1">Gets the Z maximum of this instance.</p>


```csharp
public double ZMax { get; }
```
### ZMin

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Envelope.yml" sourcestartlinenumber="1">Gets the Z minimum of this instance.</p>


```csharp
public double ZMin { get; }
```


