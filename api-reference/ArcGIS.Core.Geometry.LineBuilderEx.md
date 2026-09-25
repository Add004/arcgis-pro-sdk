# LineBuilderEx

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.LineBuilderEx.yml" sourcestartlinenumber="1">Builder for creating a <xref href="ArcGIS.Core.Geometry.LineSegment?text=LineSegment" data-throw-if-not-resolved="false"></xref> whose methods can be called on any thread.</p>


## Object Signature

```csharp
public sealed class LineBuilderEx : SegmentBuilderEx
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Geometry.LineBuilderEx.yml" sourcestartlinenumber="1">Use the LineBuilderEx class to to create and/or modify a <xref href="ArcGIS.Core.Geometry.LineSegment?text=LineSegment" data-throw-if-not-resolved="false"></xref> shape. A LineSegment is based upon the parent <xref href="ArcGIS.Core.Geometry.Segment?text=Segment" data-throw-if-not-resolved="false"></xref> class. The Segment class is
immutable which means that you can not change its shape once it is created. Hence, the LineBuilderEx provides the way to make changes when working with a
LineSegment. Use the <xref href="ArcGIS.Core.Geometry.LineBuilderEx.ToSegment?text=LineBuilderEx.ToSegment" data-throw-if-not-resolved="false"></xref> method to get the LineSegment from the builder.</p>
<p>A line segment is a straight line between a start point and an end point.</p><p></p>
<p sourcefile="api/ArcGIS.Core.Geometry.LineBuilderEx.yml" sourcestartlinenumber="7">The LineBuilderEx methods can be called on any thread.</p>


## Members

### LineBuilderEx(Coordinate2D, Coordinate2D, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.LineBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the LineBuilderEx class defined from the start and end point.</p>


```csharp
public LineBuilderEx(Coordinate2D startPoint, Coordinate2D endPoint, SpatialReference spatialReference = null)
```
### LineBuilderEx(Coordinate3D, Coordinate3D, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.LineBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the LineBuilderEx class defined from the start and end point.</p>


```csharp
public LineBuilderEx(Coordinate3D startPoint, Coordinate3D endPoint, SpatialReference spatialReference = null)
```
### LineBuilderEx(LineSegment, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.LineBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the LineBuilderEx class defined from the input segment.</p>


```csharp
public LineBuilderEx(LineSegment segment, SpatialReference spatialReference = null)
```
### LineBuilderEx(MapPoint, MapPoint, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.LineBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the LineBuilderEx class defined from the start and end point.</p>


```csharp
public LineBuilderEx(MapPoint startPoint, MapPoint endPoint, SpatialReference spatialReference = null)
```
### CreateLineSegment(Coordinate2D, Coordinate2D, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.LineBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the LineSegment class.</p>


```csharp
public static LineSegment CreateLineSegment(Coordinate2D startPoint, Coordinate2D endPoint, SpatialReference spatialReference = null)
```
### CreateLineSegment(Coordinate3D, Coordinate3D, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.LineBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the LineSegment class.</p>


```csharp
public static LineSegment CreateLineSegment(Coordinate3D startPoint, Coordinate3D endPoint, SpatialReference spatialReference = null)
```
### CreateLineSegment(LineSegment, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.LineBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the LineSegment class.</p>


```csharp
public static LineSegment CreateLineSegment(LineSegment segment, SpatialReference spatialReference = null)
```
### CreateLineSegment(MapPoint, MapPoint, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.LineBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the LineSegment class.</p>


```csharp
public static LineSegment CreateLineSegment(MapPoint startPoint, MapPoint endPoint, SpatialReference spatialReference = null)
```
### QueryCoords(out MapPoint, out MapPoint)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.LineBuilderEx.yml" sourcestartlinenumber="1">Copies the endpoints of this builder to <code class="paramref">startPoint</code> and <code class="paramref">endPoint</code>'.</p>


```csharp
public void QueryCoords(out MapPoint startPoint, out MapPoint endPoint)
```
### SetCoords(MapPoint, MapPoint)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.LineBuilderEx.yml" sourcestartlinenumber="1">Sets this builders start and end points to be <code class="paramref">startPoint</code>  and <code class="paramref">endPoint</code>.</p>


```csharp
public void SetCoords(MapPoint startPoint, MapPoint endPoint)
```
### ToSegment()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.LineBuilderEx.yml" sourcestartlinenumber="1">Returns a <xref href="ArcGIS.Core.Geometry.LineSegment" data-throw-if-not-resolved="false"></xref> instance representing the current state of the builder.</p>


```csharp
public override LineSegment ToSegment()
```


