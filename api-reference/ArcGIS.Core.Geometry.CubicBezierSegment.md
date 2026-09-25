# CubicBezierSegment

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.CubicBezierSegment.yml" sourcestartlinenumber="1">Represents a third degree cubic Bezier curve for use in a <xref href="ArcGIS.Core.Geometry.Multipart?text=Multipart" data-throw-if-not-resolved="false"></xref> geometry.  To create a cubic bezier segment use
the <xref href="ArcGIS.Core.Geometry.CubicBezierBuilderEx" data-throw-if-not-resolved="false"></xref> object.</p>


## Object Signature

```csharp
public sealed class CubicBezierSegment : Segment
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Geometry.CubicBezierSegment.yml" sourcestartlinenumber="1">A cubic Bezier curve is a non-linear segment defined by four control points. The Bezier curve starts at control point 0 (start point)
and ends at control point 3 (end point).
The start point and control point 1 define the tangent at the start point. Control point 2 and the end point define the tangent
at the end point.  The length of these tangent lines and position of the 4 control points determines the shape of the created Bezier curve.</p>
<pre><code sourcefile="api/ArcGIS.Core.Geometry.CubicBezierSegment.yml" sourcestartlinenumber="6">        &lt;p&gt;&lt;/p&gt;&lt;img src=&quot;images/ArcGIS.Core.Geometry/BezierCurves.png&quot; alt=&quot;Bezier Curves&quot; /&gt;
</code></pre>


## Members

### ControlPoint1

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.CubicBezierSegment.yml" sourcestartlinenumber="1">Gets the first control point as a <xref href="ArcGIS.Core.Geometry.Coordinate2D" data-throw-if-not-resolved="false"></xref> structure.</p>


```csharp
public Coordinate2D ControlPoint1 { get; }
```
### ControlPoint2

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.CubicBezierSegment.yml" sourcestartlinenumber="1">Gets the second control point as a <xref href="ArcGIS.Core.Geometry.Coordinate2D" data-throw-if-not-resolved="false"></xref> structure.</p>


```csharp
public Coordinate2D ControlPoint2 { get; }
```
### Get2DEnvelope()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.CubicBezierSegment.yml" sourcestartlinenumber="1">Gets the 2D envelope of this cubic bezier segment.</p>


```csharp
public Envelope Get2DEnvelope()
```
### IsCurve

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.CubicBezierSegment.yml" sourcestartlinenumber="1">Gets whether this cubic bezier is a curve.</p>


```csharp
public override bool IsCurve { get; }
```
### Length

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.CubicBezierSegment.yml" sourcestartlinenumber="1">Gets the 2D length of this cubic bezier.</p>


```csharp
public override double Length { get; }
```
### SegmentType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.CubicBezierSegment.yml" sourcestartlinenumber="1">Gets the segment type. Always returns <xref href="ArcGIS.Core.Geometry.SegmentType.Bezier" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public override SegmentType SegmentType { get; }
```


