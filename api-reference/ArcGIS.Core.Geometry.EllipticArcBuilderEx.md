# EllipticArcBuilderEx

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">A builder for creating an <xref href="ArcGIS.Core.Geometry.EllipticArcSegment" data-throw-if-not-resolved="false"></xref> whose methods can be called on any thread.</p>


## Object Signature

```csharp
public sealed class EllipticArcBuilderEx : SegmentBuilderEx
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">Use the EllipticArcBuilderEx class to create and/or modify an <xref href="ArcGIS.Core.Geometry.EllipticArcSegment?text=EllipticArcSegment" data-throw-if-not-resolved="false"></xref> shape.
An EllipticArcSegment is based upon the parent <xref href="ArcGIS.Core.Geometry.Segment?text=Segment" data-throw-if-not-resolved="false"></xref> class. The Segment class is
immutable which means that you cannot change its shape once it is created. Hence, the EllipticArcBuilderEx provides the way to make changes when working with an
EllipticArcSegment. Use the <xref href="ArcGIS.Core.Geometry.EllipticArcBuilderEx.ToSegment?text=EllipticArcBuilderEx.ToSegment" data-throw-if-not-resolved="false"></xref> method to get the EllipticArcSegment from the builder.</p>
<p>An elliptic arc is the portion of the boundary of a 2D ellipse that connects two points.</p><p></p>
<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="8">Most of the EllipticArcBuilderEx methods can be called on any thread. If a method must be called on the MCT thread, it is noted in the summary.</p>


## Members

### EllipticArcBuilderEx(Coordinate2D, double, ArcOrientation, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the EllipticArcBuilderEx class.
The new instance will be a circle from a center point and radius.</p>


```csharp
public EllipticArcBuilderEx(Coordinate2D centerPt, double radius, ArcOrientation orientation, SpatialReference spatialReference = null)
```
### EllipticArcBuilderEx(Coordinate2D, double, double, double, ArcOrientation, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the EllipticArcBuilderEx class.
The new instance will be an ellipse.</p>


```csharp
public EllipticArcBuilderEx(Coordinate2D centerPt, double rotationAngle, double semiMajorAxis, double minorMajorRatio, ArcOrientation orientation, SpatialReference spatialReference = null)
```
### EllipticArcBuilderEx(Coordinate2D, double, double, double, double, double, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the EllipticArcBuilderEx class. The new instance will be an elliptic arc.</p>


```csharp
public EllipticArcBuilderEx(Coordinate2D centerPt, double startAngle, double centralAngle, double rotationAngle, double semiMajorAxis, double minorMajorRatio, SpatialReference spatialReference = null)
```
### EllipticArcBuilderEx(EllipticArcSegment, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the EllipticArcBuilderEx class from another elliptic arc segment.</p>


```csharp
public EllipticArcBuilderEx(EllipticArcSegment ellipticArc, SpatialReference spatialReference = null)
```
### EllipticArcBuilderEx(MapPoint, MapPoint, Coordinate2D, ArcOrientation, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the EllipticArcBuilderEx class.
The new instance will be a circular arc from end points and the center point.</p>


```csharp
public EllipticArcBuilderEx(MapPoint startPt, MapPoint endPt, Coordinate2D centerPt, ArcOrientation orientation, SpatialReference spatialReference = null)
```
### EllipticArcBuilderEx(MapPoint, MapPoint, Coordinate2D, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the EllipticArcBuilderEx class. The new instance will be a circular arc from three points.</p>


```csharp
public EllipticArcBuilderEx(MapPoint startPt, MapPoint endPt, Coordinate2D interiorPt, SpatialReference spatialReference = null)
```
### EllipticArcBuilderEx(MapPoint, MapPoint, double, double, double, MinorOrMajor, ArcOrientation, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the EllipticArcBuilderEx class. The new instance will be an elliptic arc.</p>


```csharp
public EllipticArcBuilderEx(MapPoint startPt, MapPoint endPt, double semiMajorAxis, double minorMajorRatio, double rotationAngle, MinorOrMajor minorOrMajor, ArcOrientation orientation, SpatialReference spatialReference = null)
```
### EllipticArcBuilderEx(MapPoint, double, double, double, ArcOrientation, MinorOrMajor, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the EllipticArcBuilderEx class.
The new instance will be a circular arc.</p>


```csharp
public EllipticArcBuilderEx(MapPoint startPt, double chordLength, double chordBearing, double radius, ArcOrientation orientation, MinorOrMajor minorOrMajor, SpatialReference spatialReference = null)
```
### EllipticArcBuilderEx(MapPoint, double, double, double, ArcOrientation, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the EllipticArcBuilderEx class.
The new instance will be a circular arc.</p>


```csharp
public EllipticArcBuilderEx(MapPoint startPt, double chordLength, double chordBearing, double arcLength, ArcOrientation orientation, SpatialReference spatialReference = null)
```
### EllipticArcBuilderEx(Segment, ArcOrientation, bool, double, double, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the EllipticArcBuilderEx class. The new instance will be a circular arc.</p>


```csharp
public EllipticArcBuilderEx(Segment tangentSegment, ArcOrientation orientation, bool atStart, double chordLength, double arcLength, SpatialReference spatialReference = null)
```
### EllipticArcBuilderEx(Segment, Segment, double, Coordinate2D, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the EllipticArcBuilderEx class.
The new instance will be a circular arc of the given radius and tangent to two segments.</p>


```csharp
public EllipticArcBuilderEx(Segment segment1, Segment segment2, double radius, Coordinate2D hintPoint, SpatialReference spatialReference = null)
```
### EllipticArcBuilderEx(Segment, bool, ArcOrientation, double, double, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the EllipticArcBuilderEx class. The new instance will be a circular arc.</p>


```csharp
public EllipticArcBuilderEx(Segment tangentSegment, bool atStart, ArcOrientation orientation, double radius, double arcLength, SpatialReference spatialReference = null)
```
### EllipticArcBuilderEx(double, double, Coordinate2D, double, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the EllipticArcBuilderEx class.
The new instance will be a circular arc.</p>


```csharp
public EllipticArcBuilderEx(double startAngle, double centralAngle, Coordinate2D centerPt, double radius, SpatialReference spatialReference = null)
```
### CenterPoint

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">Gets or sets the center point of the arc.</p>


```csharp
public Coordinate2D CenterPoint { get; set; }
```
### CentralAngle

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">Gets or sets the central angle in radians.</p>


```csharp
public double CentralAngle { get; set; }
```
### CreateCircle(Coordinate2D, double, ArcOrientation, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the EllipticArcSegment class.
The segment will be a circle built from a center point and radius.</p>


```csharp
public static EllipticArcSegment CreateCircle(Coordinate2D centerPt, double radius, ArcOrientation orientation, SpatialReference spatialReference = null)
```
### CreateCircularArc(MapPoint, MapPoint, Coordinate2D, ArcOrientation, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the EllipticArcSegment class.
The segment will be a circular arc built from end points and the center point.</p>


```csharp
public static EllipticArcSegment CreateCircularArc(MapPoint startPt, MapPoint endPt, Coordinate2D centerPt, ArcOrientation orientation, SpatialReference spatialReference = null)
```
### CreateCircularArc(MapPoint, MapPoint, Coordinate2D, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the EllipticArcSegment class.
The segment will be a circular arc built from three points.</p>


```csharp
public static EllipticArcSegment CreateCircularArc(MapPoint startPt, MapPoint endPt, Coordinate2D interiorPt, SpatialReference spatialReference = null)
```
### CreateCircularArc(MapPoint, double, double, double, ArcOrientation, MinorOrMajor, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the EllipticArcSegment class.
The segment will be a circular arc.</p>


```csharp
public static EllipticArcSegment CreateCircularArc(MapPoint startPt, double chordLength, double chordBearing, double radius, ArcOrientation orientation, MinorOrMajor minorOrMajor, SpatialReference spatialReference = null)
```
### CreateCircularArc(MapPoint, double, double, double, ArcOrientation, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the EllipticArcSegment class.
The segment will be a circular arc.</p>


```csharp
public static EllipticArcSegment CreateCircularArc(MapPoint startPt, double chordLength, double chordBearing, double arcLength, ArcOrientation orientation, SpatialReference spatialReference = null)
```
### CreateCircularArc(Segment, ArcOrientation, bool, double, double, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the EllipticArcSegment class. The new instance will be a circular arc.</p>


```csharp
public static EllipticArcSegment CreateCircularArc(Segment tangentSegment, ArcOrientation orientation, bool atStart, double chordLength, double arcLength, SpatialReference spatialReference = null)
```
### CreateCircularArc(Segment, Segment, double, Coordinate2D, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the EllipticArcSegment class.
The segment will be a circular arc of the given radius and tangent to two segments.</p>


```csharp
public static EllipticArcSegment CreateCircularArc(Segment segment1, Segment segment2, double radius, Coordinate2D hintPoint, SpatialReference spatialReference = null)
```
### CreateCircularArc(Segment, bool, ArcOrientation, double, double, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">Builds a new instance of the EllipticArcSegment class. The new instance will be a circular arc.</p>


```csharp
public static EllipticArcSegment CreateCircularArc(Segment tangentSegment, bool atStart, ArcOrientation orientation, double radius, double arcLength, SpatialReference spatialReference = null)
```
### CreateCircularArc(double, double, Coordinate2D, double, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the EllipticArcSegment class.
The segment will be a circular arc.</p>


```csharp
public static EllipticArcSegment CreateCircularArc(double startAngle, double centralAngle, Coordinate2D centerPt, double radius, SpatialReference spatialReference = null)
```
### CreateEllipse(Coordinate2D, double, double, double, ArcOrientation, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the EllipticArcSegment class.
The segment will be an ellipse.</p>


```csharp
public static EllipticArcSegment CreateEllipse(Coordinate2D centerPt, double rotationAngle, double semiMajorAxis, double minorMajorRatio, ArcOrientation orientation, SpatialReference spatialReference = null)
```
### CreateEllipticArcSegment(Coordinate2D, double, double, double, double, double, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the EllipticArcSegment class. The new instance will be an elliptic arc.</p>


```csharp
public static EllipticArcSegment CreateEllipticArcSegment(Coordinate2D centerPt, double startAngle, double centralAngle, double rotationAngle, double semiMajorAxis, double minorMajorRatio, SpatialReference spatialReference = null)
```
### CreateEllipticArcSegment(EllipticArcSegment, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the EllipticArcSegment class from another elliptic arc segment.</p>


```csharp
public static EllipticArcSegment CreateEllipticArcSegment(EllipticArcSegment ellipticArc, SpatialReference spatialReference = null)
```
### CreateEllipticArcSegment(MapPoint, MapPoint, double, double, double, MinorOrMajor, ArcOrientation, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the EllipticArcSegment class. The new instance will be an elliptic arc.</p>


```csharp
public static EllipticArcSegment CreateEllipticArcSegment(MapPoint startPt, MapPoint endPt, double semiMajorAxis, double minorMajorRatio, double rotationAngle, MinorOrMajor minorOrMajor, ArcOrientation orientation, SpatialReference spatialReference = null)
```
### EndAngle

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">Gets or sets the end angle in radians.</p>


```csharp
public double EndAngle { get; set; }
```
### EndPoint

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">Gets or sets the end point.</p>


```csharp
public override MapPoint EndPoint { get; set; }
```
### GetAxes(out double, out double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">Gets the semi-major and semi-minor axes.</p>


```csharp
public void GetAxes(out double semiMajorAxis, out double semiMinorAxis)
```
### IsCircular

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">Gets if this elliptic arc is actually circular (that is major and minor axes have the same length).</p>


```csharp
public bool IsCircular { get; }
```
### IsMinor

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">Gets if the arc is a minor arc.
The arc is a minor arc if the absolute value of the central angle is less than PI radians (180 degrees).</p>


```csharp
public bool IsMinor { get; }
```
### MinorMajorRatio

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">Gets or sets the minor-major ratio.</p>


```csharp
public double MinorMajorRatio { get; set; }
```
### Orientation

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">Gets the orientation of this elliptic arc.</p>


```csharp
public ArcOrientation Orientation { get; set; }
```
### QueryCoords(out Coordinate2D, out double, out double, out double, out double, out double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">Copies the center point, start angle, central angle, rotation angle, semi-major/semi-minor axes into the method parameters.</p>


```csharp
public void QueryCoords(out Coordinate2D centerPt, out double startAngle, out double centralAngle, out double rotationAngle, out double semiMajorAxis, out double semiMinorAxis)
```
### QueryFilletRadiusRange(Segment, Segment, Coordinate2D)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">Gets the minimum and maximum radius for a fillet arc to touch both input segments. <code class="paramref">hintPoint</code> specifies a location near the desired fillet.
<xref href="ArcGIS.Core.Geometry.EllipticArcBuilderEx.CreateCircularArc(ArcGIS.Core.Geometry.Segment%2cArcGIS.Core.Geometry.Segment%2cSystem.Double%2cArcGIS.Core.Geometry.Coordinate2D%2cArcGIS.Core.Geometry.SpatialReference)" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static Tuple<double, double> QueryFilletRadiusRange(Segment segment1, Segment segment2, Coordinate2D hintPoint)
```
### RotationAngle

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">Gets or sets the rotation angle of the major axis in radians.</p>


```csharp
public double RotationAngle { get; set; }
```
### SemiMajorAxis

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">Gets or sets the length of the semi-major axis.</p>


```csharp
public double SemiMajorAxis { get; set; }
```
### SetAxes(double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">Sets the semi-major and semi-minor axes.</p>


```csharp
public void SetAxes(double semiMajorAxis, double semiMinorAxis)
```
### SetCoords(Coordinate2D, double, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">Sets the center point, start angle, central angle, radius for a circular arc.</p>


```csharp
public void SetCoords(Coordinate2D centerPt, double startAngle, double centralAngle, double radius)
```
### SetCoords(Coordinate2D, double, double, double, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">Sets the center point, start angle, central angle, rotation angle, semi-major/semi-minor axes.</p>


```csharp
public void SetCoords(Coordinate2D centerPt, double startAngle, double centralAngle, double rotationAngle, double semiMajorAxis, double semiMinorAxis)
```
### SetRadius(double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">Sets the radius of a circular arc. If the arc is not circular, sets both the semi-major and semi-minor axes to
the same value.</p>


```csharp
public void SetRadius(double radius)
```
### StartAngle

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">Gets or sets the start angle in radians.</p>


```csharp
public double StartAngle { get; set; }
```
### StartPoint

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">Gets or sets the start point.</p>


```csharp
public override MapPoint StartPoint { get; set; }
```
### ToSegment()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">Returns an <xref href="ArcGIS.Core.Geometry.EllipticArcSegment" data-throw-if-not-resolved="false"></xref> instance representing the current state of the builder.</p>


```csharp
public override EllipticArcSegment ToSegment()
```


