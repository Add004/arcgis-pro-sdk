# Polyline

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.Polyline.yml" sourcestartlinenumber="1">A class representing a polyline.</p>


## Object Signature

```csharp
public sealed class Polyline : Multipart
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Geometry.Polyline.yml" sourcestartlinenumber="1">A polyline is an ordered collection of paths where each path is a collection of contiguous segments. A <xref href="ArcGIS.Core.Geometry.Segment" data-throw-if-not-resolved="false"></xref> has a start and an end point.
If a polyline has more than one path, the paths may be separate from one another. The paths of a polyline can be obtained using the <xref href="ArcGIS.Core.Geometry.Multipart.Parts" data-throw-if-not-resolved="false"></xref>
method.</p>
<p>
The boundary of a polyline is the set of start and end points of each path, the interior is the set of points in the polyline that are not in the boundary, 
and the exterior is the set of points that are not in the boundary or the interior. 
</p><p>
A Polyline is based upon the parent <xref href="ArcGIS.Core.Geometry.Geometry?text=Geometry" data-throw-if-not-resolved="false"></xref> class. The Geometry class is immutable which means that you can not change
its shape once it is created. If you need to modify a Polyline once it has been created, use the <xref href="ArcGIS.Core.Geometry.PolylineBuilderEx?text=PolylineBuilderEx" data-throw-if-not-resolved="false"></xref>
class instead. The <xref href="ArcGIS.Core.Geometry.PolylineBuilderEx.ToGeometry?text=PolylineBuilderEx.ToGeometry" data-throw-if-not-resolved="false"></xref> method will provide you with the Polyline object. 
</p>


## Members

### Area

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Polyline.yml" sourcestartlinenumber="1">Gets the area of this instance. For a Polyline, always returns 0.</p>


```csharp
public override double Area { get; }
```
### GeometryType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Polyline.yml" sourcestartlinenumber="1">Gets the geometry type. Always returns <xref href="ArcGIS.Core.Geometry.GeometryType.Polyline" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public override GeometryType GeometryType { get; }
```
### IsEqual(Polyline)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Polyline.yml" sourcestartlinenumber="1">Compares two <xref href="ArcGIS.Core.Geometry.Polyline" data-throw-if-not-resolved="false"></xref> for equality.
This will check that the <xref href="ArcGIS.Core.Geometry.SpatialReference" data-throw-if-not-resolved="false"></xref>, attribute awareness (HasZ, HasM, HasID),
and the content of <xref href="ArcGIS.Core.Geometry.Multipart.Parts" data-throw-if-not-resolved="false"></xref> match. The order of parts must match too.</p>


```csharp
public bool IsEqual(Polyline polyline)
```
### IsEqual(Polyline, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Polyline.yml" sourcestartlinenumber="1">Compares two polylines for equality while considering the given tolerance.</p>


```csharp
public bool IsEqual(Polyline polyline, double tolerance)
```


