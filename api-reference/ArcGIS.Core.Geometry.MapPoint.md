# MapPoint

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.MapPoint.yml" sourcestartlinenumber="1">A MapPoint represents a single location in space. The location consists of X and Y values and optionally a Z and/or M value.
To create a MapPoint use the <xref href="ArcGIS.Core.Geometry.MapPointBuilderEx" data-throw-if-not-resolved="false"></xref> object.</p>


## Object Signature

```csharp
public sealed class MapPoint : Geometry
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Geometry.MapPoint.yml" sourcestartlinenumber="1">The interior of a point is the point itself, the boundary is the empty set, and the exterior is all other points.</p>
<p>
A MapPoint is based upon the parent <xref href="ArcGIS.Core.Geometry.Geometry?text=Geometry" data-throw-if-not-resolved="false"></xref> class. The Geometry class is immutable which means that you can not change
its shape once it is created. If you need to modify a MapPoint once it has been created, use the <xref href="ArcGIS.Core.Geometry.MapPointBuilderEx?text=MapPointBuilderEx" data-throw-if-not-resolved="false"></xref>
class instead. The <xref href="ArcGIS.Core.Geometry.MapPointBuilderEx.ToGeometry?text=MapPointBuilderEx.ToGeometry" data-throw-if-not-resolved="false"></xref> method will provide you with the MapPoint object. 
</p>


## Members

### Coordinate2D

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.MapPoint.yml" sourcestartlinenumber="1">Gets a <xref href="ArcGIS.Core.Geometry.Coordinate2D" data-throw-if-not-resolved="false"></xref> structure with the X and Y values.</p>


```csharp
public Coordinate2D Coordinate2D { get; }
```
### Coordinate3D

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.MapPoint.yml" sourcestartlinenumber="1">Gets a <xref href="ArcGIS.Core.Geometry.Coordinate3D" data-throw-if-not-resolved="false"></xref> structure with the X, Y, and Z values.</p>


```csharp
public Coordinate3D Coordinate3D { get; }
```
### Extent

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.MapPoint.yml" sourcestartlinenumber="1">Gets the minimum enclosing envelope of the geometry.</p>


```csharp
public override Envelope Extent { get; }
```
### GeometryType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.MapPoint.yml" sourcestartlinenumber="1">Gets the GeometryType of this instance.  Always returns <xref href="ArcGIS.Core.Geometry.GeometryType.Point" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public override GeometryType GeometryType { get; }
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.MapPoint.yml" sourcestartlinenumber="1">Gets the ID value.</p>


```csharp
public int ID { get; }
```
### IsEmpty

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.MapPoint.yml" sourcestartlinenumber="1">Gets a value indicating whether or not the geometry is empty.</p>


```csharp
public override bool IsEmpty { get; }
```
### IsEqual(MapPoint)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MapPoint.yml" sourcestartlinenumber="1">Compares two <xref href="ArcGIS.Core.Geometry.MapPoint" data-throw-if-not-resolved="false"></xref> for equality. This will check the <xref href="ArcGIS.Core.Geometry.SpatialReference" data-throw-if-not-resolved="false"></xref>,
attribute awareness (HasZ, HasM, HasID), and coordinates for a match.</p>


```csharp
public bool IsEqual(MapPoint mapPoint)
```
### IsEqual(MapPoint, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MapPoint.yml" sourcestartlinenumber="1">Compares two map points for equality while considering the given tolerance.</p>


```csharp
public bool IsEqual(MapPoint mapPoint, double tolerance)
```
### M

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.MapPoint.yml" sourcestartlinenumber="1">Gets the measure value.</p>


```csharp
public double M { get; }
```
### PointCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.MapPoint.yml" sourcestartlinenumber="1">Gets the point count of the geometry. This is always 1.</p>


```csharp
public override int PointCount { get; }
```
### ToEsriShape()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MapPoint.yml" sourcestartlinenumber="1">Converts this map point into an Esri shape formatted binary byte buffer.</p>


```csharp
public override byte[] ToEsriShape()
```
### ToEsriShape(ref byte[])

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MapPoint.yml" sourcestartlinenumber="1">Converts this map point into an Esri shape formatted binary byte buffer.</p>


```csharp
public override long ToEsriShape(ref byte[] shapeBuffer)
```
### ToGeoCoordinateString(ToGeoCoordinateParameter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MapPoint.yml" sourcestartlinenumber="1">Converts the point to a geographic string notation specified by the <code class="paramref">toGeoCoordParam</code> parameter.</p>


```csharp
public string ToGeoCoordinateString(ToGeoCoordinateParameter toGeoCoordParam)
```
### X

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.MapPoint.yml" sourcestartlinenumber="1">Gets the X-coordinate.</p>


```csharp
public double X { get; }
```
### Y

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.MapPoint.yml" sourcestartlinenumber="1">Gets the Y-coordinate.</p>


```csharp
public double Y { get; }
```
### Z

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.MapPoint.yml" sourcestartlinenumber="1">Gets the Z-coordinate.</p>


```csharp
public double Z { get; }
```


