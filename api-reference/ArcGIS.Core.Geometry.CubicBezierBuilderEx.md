# CubicBezierBuilderEx

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.CubicBezierBuilderEx.yml" sourcestartlinenumber="1">A builder for creating a <xref href="ArcGIS.Core.Geometry.CubicBezierSegment" data-throw-if-not-resolved="false"></xref> whose methods can be called on any thread.</p>


## Object Signature

```csharp
public sealed class CubicBezierBuilderEx : SegmentBuilderEx
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Geometry.CubicBezierBuilderEx.yml" sourcestartlinenumber="1">Use the CubicBezierBuilderEx class to to create and/or modify a <xref href="ArcGIS.Core.Geometry.CubicBezierSegment?text=CubicBezierSegment" data-throw-if-not-resolved="false"></xref> shape.
A CubicBezierSegment is based upon the parent <xref href="ArcGIS.Core.Geometry.Segment?text=Segment" data-throw-if-not-resolved="false"></xref> class. The Segment class is
immutable which means that you can not change its shape once it is created. Hence, the CubicBezierBuilderEx provides the way to make changes when working with a
CubicBezierSegment. Use the <xref href="ArcGIS.Core.Geometry.CubicBezierBuilderEx.ToSegment?text=CubicBezierBuilderEx.ToSegment" data-throw-if-not-resolved="false"></xref> method to get the CubicBezierSegment from the builder.</p>
<p>
A cubic Bezier curve is a non-linear segment defined by four control points. The Bezier curve starts at control point 0 (start point) 
and ends at control point 3 (end point). The start point and control point 1 define the tangent at the start point. Control point 2 and the end point define the tangent 
at the end point.  The length of these tangent lines and position of the 4 control points determines the shape of the created Bezier curve.
</p><img src="images/ArcGIS.Core.Geometry/BezierCurves.png" alt="Bezier Curves"><p></p><p></p>
<p sourcefile="api/ArcGIS.Core.Geometry.CubicBezierBuilderEx.yml" sourcestartlinenumber="12">The CubicBezierBuilderEx methods can be called on any thread.</p>


## Members

### CubicBezierBuilderEx(Coordinate2D, Coordinate2D, Coordinate2D, Coordinate2D, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.CubicBezierBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the CubicBezierBuilderEx class from four control points.</p>


```csharp
public CubicBezierBuilderEx(Coordinate2D startPoint, Coordinate2D controlPoint1, Coordinate2D controlPoint2, Coordinate2D endPoint, SpatialReference spatialReference = null)
```
### CubicBezierBuilderEx(CubicBezierSegment, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.CubicBezierBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the CubicBezierBuilderEx class from another cubic bezier segment.</p>


```csharp
public CubicBezierBuilderEx(CubicBezierSegment cubicBezier, SpatialReference spatialReference = null)
```
### CubicBezierBuilderEx(MapPoint, Coordinate2D, Coordinate2D, MapPoint, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.CubicBezierBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the CubicBezierBuilderEx class from four control points.</p>


```csharp
public CubicBezierBuilderEx(MapPoint startPoint, Coordinate2D controlPoint1, Coordinate2D controlPoint2, MapPoint endPoint, SpatialReference spatialReference = null)
```
### CubicBezierBuilderEx(MapPoint, MapPoint, MapPoint, MapPoint, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.CubicBezierBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the CubicBezierBuilderEx class from four control points.</p>


```csharp
public CubicBezierBuilderEx(MapPoint startPoint, MapPoint controlPoint1, MapPoint controlPoint2, MapPoint endPoint, SpatialReference spatialReference = null)
```
### CubicBezierBuilderEx(IEnumerable&lt;Coordinate2D&gt;, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.CubicBezierBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the CubicBezierBuilderEx class from a set of coordinates. Four coordinates must be supplied.</p>


```csharp
public CubicBezierBuilderEx(IEnumerable<Coordinate2D> coordinates, SpatialReference spatialReference = null)
```
### CubicBezierBuilderEx(IEnumerable&lt;MapPoint&gt;, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.CubicBezierBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the CubicBezierBuilderEx class from a set of points. Four points must be supplied.</p>


```csharp
public CubicBezierBuilderEx(IEnumerable<MapPoint> points, SpatialReference spatialReference = null)
```
### ControlPoint1

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.CubicBezierBuilderEx.yml" sourcestartlinenumber="1">Gets or sets control point 1.</p>


```csharp
public Coordinate2D ControlPoint1 { get; set; }
```
### ControlPoint2

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.CubicBezierBuilderEx.yml" sourcestartlinenumber="1">Gets or sets control point 2.</p>


```csharp
public Coordinate2D ControlPoint2 { get; set; }
```
### CreateCubicBezierSegment(Coordinate2D, Coordinate2D, Coordinate2D, Coordinate2D, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.CubicBezierBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the CubicBezierSegment class from four control points.</p>


```csharp
public static CubicBezierSegment CreateCubicBezierSegment(Coordinate2D startPoint, Coordinate2D controlPoint1, Coordinate2D controlPoint2, Coordinate2D endPoint, SpatialReference spatialReference = null)
```
### CreateCubicBezierSegment(CubicBezierSegment, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.CubicBezierBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the CubicBezierSegment class from the four control points of a cubic bezier.</p>


```csharp
public static CubicBezierSegment CreateCubicBezierSegment(CubicBezierSegment cubicBezier, SpatialReference spatialReference = null)
```
### CreateCubicBezierSegment(MapPoint, Coordinate2D, Coordinate2D, MapPoint, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.CubicBezierBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the CubicBezierSegment class from four control points.</p>


```csharp
public static CubicBezierSegment CreateCubicBezierSegment(MapPoint startPoint, Coordinate2D controlPoint1, Coordinate2D controlPoint2, MapPoint endPoint, SpatialReference spatialReference = null)
```
### CreateCubicBezierSegment(MapPoint, MapPoint, MapPoint, MapPoint, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.CubicBezierBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the CubicBezierSegment class from four control points.</p>


```csharp
public static CubicBezierSegment CreateCubicBezierSegment(MapPoint startPoint, MapPoint controlPoint1, MapPoint controlPoint2, MapPoint endPoint, SpatialReference spatialReference = null)
```
### CreateCubicBezierSegment(IEnumerable&lt;Coordinate2D&gt;, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.CubicBezierBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the CubicBezierSegment class from four control points.</p>


```csharp
public static CubicBezierSegment CreateCubicBezierSegment(IEnumerable<Coordinate2D> coordinates, SpatialReference spatialReference = null)
```
### CreateCubicBezierSegment(IEnumerable&lt;MapPoint&gt;, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.CubicBezierBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the CubicBezierSegment class from four control points.</p>


```csharp
public static CubicBezierSegment CreateCubicBezierSegment(IEnumerable<MapPoint> points, SpatialReference spatialReference = null)
```
### QueryCoords(out MapPoint, out Coordinate2D, out Coordinate2D, out MapPoint)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.CubicBezierBuilderEx.yml" sourcestartlinenumber="1">Copies this builder's points.</p>


```csharp
public void QueryCoords(out MapPoint startPoint, out Coordinate2D controlPoint1, out Coordinate2D controlPoint2, out MapPoint endPoint)
```
### SetCoords(MapPoint, Coordinate2D, Coordinate2D, MapPoint)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.CubicBezierBuilderEx.yml" sourcestartlinenumber="1">Sets this builder's points.</p>


```csharp
public void SetCoords(MapPoint startPoint, Coordinate2D controlPoint1, Coordinate2D controlPoint2, MapPoint endPoint)
```
### ToSegment()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.CubicBezierBuilderEx.yml" sourcestartlinenumber="1">Returns a <xref href="ArcGIS.Core.Geometry.CubicBezierSegment" data-throw-if-not-resolved="false"></xref> instance representing the current state of the builder.</p>


```csharp
public override CubicBezierSegment ToSegment()
```


