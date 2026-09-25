# EllipticArcSegment

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcSegment.yml" sourcestartlinenumber="1">Represents an elliptic arc segment for use in a <xref href="ArcGIS.Core.Geometry.Multipart?text=Multipart" data-throw-if-not-resolved="false"></xref> geometry.  To create an elliptic arc segment use
the <xref href="ArcGIS.Core.Geometry.EllipticArcBuilderEx" data-throw-if-not-resolved="false"></xref> object.</p>


## Object Signature

```csharp
public sealed class EllipticArcSegment : Segment
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcSegment.yml" sourcestartlinenumber="1">An elliptic arc is the portion of the boundary of a 2D ellipse that connects two points.</p>


## Members

### CenterPoint

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcSegment.yml" sourcestartlinenumber="1">Gets the center point of the arc.</p>


```csharp
public Coordinate2D CenterPoint { get; }
```
### CentralAngle

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcSegment.yml" sourcestartlinenumber="1">Gets the central angle in radians.</p>


```csharp
public double CentralAngle { get; }
```
### EndAngle

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcSegment.yml" sourcestartlinenumber="1">Gets the end angle in radians.</p>


```csharp
public double EndAngle { get; }
```
### Get2DEnvelope()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcSegment.yml" sourcestartlinenumber="1">Gets the 2-dimensional envelope of this elliptic arc.</p>


```csharp
public Envelope Get2DEnvelope()
```
### GetAxes(out double, out double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcSegment.yml" sourcestartlinenumber="1">Gets the semi-major and semi-minor axes.</p>


```csharp
public void GetAxes(out double semiMajorAxis, out double semiMinorAxis)
```
### IsCircular

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcSegment.yml" sourcestartlinenumber="1">Gets if this elliptic arc segment is a portion of the boundary of a 2D circle.</p>


```csharp
public bool IsCircular { get; }
```
### IsCounterClockwise

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcSegment.yml" sourcestartlinenumber="1">Gets if this elliptic arc segment is counter-clockwise.</p>


```csharp
public bool IsCounterClockwise { get; }
```
### IsCurve

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcSegment.yml" sourcestartlinenumber="1">Gets if this elliptic arc segment is a curve. Always returns true.</p>


```csharp
public override bool IsCurve { get; }
```
### IsMinor

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcSegment.yml" sourcestartlinenumber="1">Gets if this elliptic arc is a minor arc.</p>


```csharp
public bool IsMinor { get; }
```
### Length

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcSegment.yml" sourcestartlinenumber="1">Gets the 2D length of this elliptic arc segment.</p>


```csharp
public override double Length { get; }
```
### MinorMajorRatio

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcSegment.yml" sourcestartlinenumber="1">Gets the ratio of the semi-minor to the semi-major axis.</p>


```csharp
public double MinorMajorRatio { get; }
```
### QueryCoords(out Coordinate2D, out double, out double, out double, out double, out double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcSegment.yml" sourcestartlinenumber="1">Copies the center coordinate, start angle, central angle, rotation angle, semi-major/semi-minor axes into the method parameters.</p>


```csharp
public void QueryCoords(out Coordinate2D centerCoordinate, out double startAngle, out double centralAngle, out double rotationAngle, out double semiMajorAxis, out double semiMinorAxis)
```
### RotationAngle

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcSegment.yml" sourcestartlinenumber="1">Gets the rotation angle in radians.</p>


```csharp
public double RotationAngle { get; }
```
### SegmentType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcSegment.yml" sourcestartlinenumber="1">Gets the segment type. This always returns <xref href="ArcGIS.Core.Geometry.SegmentType.EllipticArc" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public override SegmentType SegmentType { get; }
```
### SemiMajorAxis

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcSegment.yml" sourcestartlinenumber="1">Gets the semi-major axis. The semi-major axis is the larger of the two axes, and the semi-minor axis is the smaller axis.  The semi-major axis always lies on the line between 0 and PI radians.</p>


```csharp
public double SemiMajorAxis { get; }
```
### SemiMinorAxis

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcSegment.yml" sourcestartlinenumber="1">Gets the semi-minor axis. The semi-minor axis is the smaller of the two axes. The semi-minor axis always lies on the line between PI/2 and 3*PI/2 radians.</p>


```csharp
public double SemiMinorAxis { get; }
```
### StartAngle

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcSegment.yml" sourcestartlinenumber="1">Gets the start angle in radians.</p>


```csharp
public double StartAngle { get; }
```


