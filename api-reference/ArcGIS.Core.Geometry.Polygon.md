# Polygon

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.Polygon.yml" sourcestartlinenumber="1">A class representing a polygon.</p>


## Object Signature

```csharp
public sealed class Polygon : Multipart
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Geometry.Polygon.yml" sourcestartlinenumber="1">A polygon is defined by a collection of rings. Each ring is a collection of contiguous segments such that the start point and the end point of each <xref href="ArcGIS.Core.Geometry.Segment" data-throw-if-not-resolved="false"></xref>
are the same (that is it is a closed ring). If a polygon has more than one ring, the rings may be separate from one another or they may nest inside one another, but
they should not overlap.  Access the rings of a polygon using the <xref href="ArcGIS.Core.Geometry.Multipart.Parts" data-throw-if-not-resolved="false"></xref> method.</p>
<p>
Note: For a polygon to be topologically correct, exterior rings should be clockwise and interior rings should be counterclockwise. If there is ever a doubt 
about the topological correctness of a polygon, call the <xref href="ArcGIS.Core.Geometry.GeometryEngine.SimplifyAsFeature(ArcGIS.Core.Geometry.Geometry%2cSystem.Boolean)?text=GeometryEngine.SimplifyAsFeature" data-throw-if-not-resolved="false"></xref> 
method to correct any issues. 
</p><p>
The boundary of a polygon is the collection of rings by which the polygon is defined. The boundary contains one or more outer rings and zero or more inner rings. 
An outer ring is oriented clockwise while an inner ring is oriented counter-clockwise. Imagine walking clockwise along an outer ring. The area to your immediate 
right is the interior of the polygon and to your left is the exterior. Similarly, if you were to walk counter-clockwise along an inner ring, the area to your 
immediate right is the interior of the polygon and to your left is the exterior.
</p><p>
A Polygon is based upon the parent <xref href="ArcGIS.Core.Geometry.Geometry?text=Geometry" data-throw-if-not-resolved="false"></xref> class. The Geometry class is immutable which means that you can not change
its shape once it is created. If you need to modify a Polygon once it has been created, use the <xref href="ArcGIS.Core.Geometry.PolygonBuilderEx?text=PolygonBuilderEx" data-throw-if-not-resolved="false"></xref>
class instead. The <xref href="ArcGIS.Core.Geometry.PolygonBuilderEx.ToGeometry?text=PolygonBuilderEx.ToGeometry" data-throw-if-not-resolved="false"></xref> method will provide you with the Polygon object. 
</p>


## Members

### Area

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Polygon.yml" sourcestartlinenumber="1">Gets the area of this instance.</p>


```csharp
public override double Area { get; }
```
### ExteriorRingCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Polygon.yml" sourcestartlinenumber="1">Gets the number of exterior rings in this polygon.</p>


```csharp
public int ExteriorRingCount { get; }
```
### GeometryType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Polygon.yml" sourcestartlinenumber="1">Gets the geometry type. Always returns <xref href="ArcGIS.Core.Geometry.GeometryType.Polygon" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public override GeometryType GeometryType { get; }
```
### GetExteriorRing(int, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Polygon.yml" sourcestartlinenumber="1">Gets the specified exterior ring in this polygon.</p>


```csharp
public Polygon GetExteriorRing(int index, bool setSpatialReference = true)
```
### GetExteriorRings(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Polygon.yml" sourcestartlinenumber="1">Gets all of the exterior rings in this polygon.</p>


```csharp
public IList<Polygon> GetExteriorRings(bool setSpatialReference = true)
```
### IsEqual(Polygon)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Polygon.yml" sourcestartlinenumber="1">Compares two <xref href="ArcGIS.Core.Geometry.Polygon" data-throw-if-not-resolved="false"></xref> for equality. This will
check that the <xref href="ArcGIS.Core.Geometry.SpatialReference" data-throw-if-not-resolved="false"></xref>, attribute awareness (HasZ, HasM, HasID), and the content of
<xref href="ArcGIS.Core.Geometry.Multipart.Parts" data-throw-if-not-resolved="false"></xref> match. The order of parts must match too.</p>


```csharp
public bool IsEqual(Polygon polygon)
```
### IsEqual(Polygon, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Polygon.yml" sourcestartlinenumber="1">Compares two polygons for equality while considering the given tolerance.</p>


```csharp
public bool IsEqual(Polygon polygon, double tolerance)
```
### IsExteriorRing(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Polygon.yml" sourcestartlinenumber="1">Determines if the specified part of this polygon is an exterior ring.</p>


```csharp
public bool IsExteriorRing(int index)
```


