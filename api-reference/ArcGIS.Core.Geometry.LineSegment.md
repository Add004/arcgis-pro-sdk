# LineSegment

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.LineSegment.yml" sourcestartlinenumber="1">A class representing a straight line between a start and end point for use in a <xref href="ArcGIS.Core.Geometry.Multipart?text=Multipart" data-throw-if-not-resolved="false"></xref> geometry. To create a line segment use
the <xref href="ArcGIS.Core.Geometry.LineBuilderEx" data-throw-if-not-resolved="false"></xref> object.</p>


## Object Signature

```csharp
public sealed class LineSegment : Segment
```

## Remarks

<p></p>
<img src="images/ArcGIS.Core.Geometry/LineSegment.png" alt="Line Segment">


## Members

### Angle

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.LineSegment.yml" sourcestartlinenumber="1">The angle in radians between the positive X-axis and this line in a counterclockwise direction.</p>


```csharp
public double Angle { get; }
```
### Get2DEnvelope()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.LineSegment.yml" sourcestartlinenumber="1">Gets the 2D envelope of this line segment.</p>


```csharp
public Envelope Get2DEnvelope()
```
### IsCurve

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.LineSegment.yml" sourcestartlinenumber="1">Gets if this line segment is a curve. Always returns false for LineSegment.</p>


```csharp
public override bool IsCurve { get; }
```
### Length

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.LineSegment.yml" sourcestartlinenumber="1">Gets the 2D length of this instance.</p>


```csharp
public override double Length { get; }
```
### Length3D

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.LineSegment.yml" sourcestartlinenumber="1">Gets the 3D length of this instance.</p>


```csharp
public double Length3D { get; }
```
### SegmentType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.LineSegment.yml" sourcestartlinenumber="1">Gets the segment type. Always returns <xref href="ArcGIS.Core.Geometry.SegmentType.Line" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public override SegmentType SegmentType { get; }
```


