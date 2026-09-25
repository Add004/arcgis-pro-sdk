# GeometricEffectControlMeasureLineRule

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectControlMeasureLineRule.yml" sourcestartlinenumber="1">Specifies the rules to transform the input ground control points given as a line.</p>


## Object Signature

```csharp
public enum GeometricEffectControlMeasureLineRule
```


## Members

### Arc90Degrees

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectControlMeasureLineRule.yml" sourcestartlinenumber="1">90 degree arc with ends at vertex 1 and vertex 2. Vertex 3 determines the side of the curve.</p>


```csharp
Arc90Degrees = 36
```
### Arch

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectControlMeasureLineRule.yml" sourcestartlinenumber="1">3 point arched line between vertex 1 and vertex 2. Vertex 3 determines the depth of the arch.</p>


```csharp
Arch = 34
```
### Chevron

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectControlMeasureLineRule.yml" sourcestartlinenumber="1">Chevron with apex at vertex 1 and ends at vertex 2 and vertex 3.</p>


```csharp
Chevron = 15
```
### ChevronArrow

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectControlMeasureLineRule.yml" sourcestartlinenumber="1">Chevron arrow centered on vertex 1.</p>


```csharp
ChevronArrow = 31
```
### ChevronArrowOffset

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectControlMeasureLineRule.yml" sourcestartlinenumber="1">Chevron arrow centered on vertex 1 offset towards vertex 2.</p>


```csharp
ChevronArrowOffset = 32
```
### CircleWithArc

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectControlMeasureLineRule.yml" sourcestartlinenumber="1">Circle centered on vertex 1 with attached arc. Vertex 3 determines the side of the 90 degree arc. If 3 points, vertex 2 determines the length of the arc. If 4 points, vertex 2 determines the radius of the circle and vertex 4 determines the length of the arc.</p>


```csharp
CircleWithArc = 25
```
### ClosedHalfCircle

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectControlMeasureLineRule.yml" sourcestartlinenumber="1">Semi-circle with vertex 1 and vertex 2 at the corners.</p>


```csharp
ClosedHalfCircle = 17
```
### ConcentricCircles

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectControlMeasureLineRule.yml" sourcestartlinenumber="1">Creates 2 or 3 concentric circles centered on vertex 1. Circle radius is based on vertex location.</p>


```csharp
ConcentricCircles = 38
```
### CoverageEdgesWithTicks

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectControlMeasureLineRule.yml" sourcestartlinenumber="1">Lines between vertex 1 to vertex 3 and vertex 2 to vertex 4. Angled ticks at the end of the lines and vertex 1 and vertex 2.</p>


```csharp
CoverageEdgesWithTicks = 12
```
### CrossedArrow

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectControlMeasureLineRule.yml" sourcestartlinenumber="1">Multipoint arrow. Vertex 1 sets the tip and vertex N the width and back of the arrowhead. Crossed at midpoint between vertex 1 and vertex 2.</p>


```csharp
CrossedArrow = 30
```
### CurvedParallelTicks

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectControlMeasureLineRule.yml" sourcestartlinenumber="1">Curved line with ticks. Curve begins on vertex 2 and ends on vertex 3. Ticks on opposite side of vertex 1.</p>


```csharp
CurvedParallelTicks = 35
```
### DoubleCurve

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectControlMeasureLineRule.yml" sourcestartlinenumber="1">Creates a dynamic line with alternating curves at vertex 2.</p>


```csharp
DoubleCurve = 43
```
### DoubleJog

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectControlMeasureLineRule.yml" sourcestartlinenumber="1">Two lines with jogs with gap in between. If there is 3 points the gap is centered on vertex. If 4 points the gap is defined by second segment.</p>


```csharp
DoubleJog = 26
```
### DoubleJogArrow

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectControlMeasureLineRule.yml" sourcestartlinenumber="1">Creates two dynamic lines with jogs centered on vertex 1.</p>


```csharp
DoubleJogArrow = 39
```
### DoublePerpendicular

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectControlMeasureLineRule.yml" sourcestartlinenumber="1">Two lines perpendicular to the first segment. Length of the lines is determined by vertex 3.</p>


```csharp
DoublePerpendicular = 5
```
### EnclosingRoundedRectangle

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectControlMeasureLineRule.yml" sourcestartlinenumber="1">Creates an enclosing rectangle around the line with rounded corners.</p>


```csharp
EnclosingRoundedRectangle = 45
```
### FullGeometry

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectControlMeasureLineRule.yml" sourcestartlinenumber="1">Default: returns the input line.</p>


```csharp
FullGeometry = 0
```
### GapExtentMidline

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectControlMeasureLineRule.yml" sourcestartlinenumber="1">Line centered between first and third segment.</p>


```csharp
GapExtentMidline = 14
```
### GapExtentWithDoubleTicks

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectControlMeasureLineRule.yml" sourcestartlinenumber="1">Two lines with angled ticks on end. Lines created between first and third segments.</p>


```csharp
GapExtentWithDoubleTicks = 13
```
### HalfCircleExtended

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectControlMeasureLineRule.yml" sourcestartlinenumber="1">U shaped line with curve between vertex 2 and vertex 3. Control points on vertex 1 and vertex 3.</p>


```csharp
HalfCircleExtended = 10
```
### HalfCircleFirstSegment

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectControlMeasureLineRule.yml" sourcestartlinenumber="1">Half circle centered on the midpoint of first segment. Orientation is opposite vertex 3.</p>


```csharp
HalfCircleFirstSegment = 8
```
### HalfCircleSecondSegment

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectControlMeasureLineRule.yml" sourcestartlinenumber="1">Half circle ending on vertex 2 opposite vertex 1. Diameter is defined by vertex 3.</p>


```csharp
HalfCircleSecondSegment = 9
```
### LineExcludingLastSegment

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectControlMeasureLineRule.yml" sourcestartlinenumber="1">Line between vertex 1 and vertex N-1.</p>


```csharp
LineExcludingLastSegment = 28
```
### LineWithStraightTicks

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectControlMeasureLineRule.yml" sourcestartlinenumber="1">Creates a dynamic line with vertex 1 in the middle. Vertices 2 and 3 define the length of the ticks and the line.</p>


```csharp
LineWithStraightTicks = 42
```
### LinkedChevrons

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectControlMeasureLineRule.yml" sourcestartlinenumber="1">Creates a dynamic line between vertex 1 and 2 connecting two chevrons. Vertex 3 defines the width of the chevrons.</p>


```csharp
LinkedChevrons = 40
```
### MultivertexArrow

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectControlMeasureLineRule.yml" sourcestartlinenumber="1">Multipoint arrow. Vertex 1 sets the tip and vertex N the width and back of the arrowhead.</p>


```csharp
MultivertexArrow = 29
```
### OffsetOpposite

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectControlMeasureLineRule.yml" sourcestartlinenumber="1">Single line offset from first segment. Offset to opposite side as vertex 3.</p>


```csharp
OffsetOpposite = 23
```
### OffsetSame

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectControlMeasureLineRule.yml" sourcestartlinenumber="1">Single line offset from first segment. Offset to same side as vertex 3.</p>


```csharp
OffsetSame = 24
```
### OpenCircle

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectControlMeasureLineRule.yml" sourcestartlinenumber="1">330 degrees circle centered on vertex 1 starting at vertex 2.</p>


```csharp
OpenCircle = 11
```
### OppositeToFirstSegment

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectControlMeasureLineRule.yml" sourcestartlinenumber="1">Lines perpendicular to vertex 3 and the midpoint of the first segment with the length determined by first segment.</p>


```csharp
OppositeToFirstSegment = 6
```
### Parallel

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectControlMeasureLineRule.yml" sourcestartlinenumber="1">Line between vertex 1 and vertex 2 with a parallel line placed at the width defined by vertex 3.</p>


```csharp
Parallel = 20
```
### ParallelOffset

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectControlMeasureLineRule.yml" sourcestartlinenumber="1">Parallels lines offset from first segment. Offset determined by vertex 3.</p>


```csharp
ParallelOffset = 22
```
### ParallelOffsetByValue

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectControlMeasureLineRule.yml" sourcestartlinenumber="1">Creates dynamic parallel lines offset from the geometry. The offset is determined by a specified value or a defined attribute.</p>


```csharp
ParallelOffsetByValue = 46
```
### ParallelWithTicks

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectControlMeasureLineRule.yml" sourcestartlinenumber="1">Line with angled ticks on ends between vertex 1 and vertex 2 with a mirrored parallel line placed at the width defined by vertex 3.</p>


```csharp
ParallelWithTicks = 19
```
### ParallelWithTicksByWidth

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectControlMeasureLineRule.yml" sourcestartlinenumber="1">Creates a dynamic line with angled ticks on the ends between vertex 2 and vertex 3. A mirrored parallel line is placed at the width defined by vertex 2.</p>


```csharp
ParallelWithTicksByWidth = 44
```
### PartialFirstSegment

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectControlMeasureLineRule.yml" sourcestartlinenumber="1">Line along first segment, starting at vertex 2 extending in the direction and length of vertex 3.</p>


```csharp
PartialFirstSegment = 33
```
### PerpendicularFromFirstSegment

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectControlMeasureLineRule.yml" sourcestartlinenumber="1">Third vertex to first segment midpoint.</p>


```csharp
PerpendicularFromFirstSegment = 1
```
### PerpendicularOffset

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectControlMeasureLineRule.yml" sourcestartlinenumber="1">Line perpendicular from midpoint of second segment. End point is offset from second segment. Vertex 1 sets length of line.</p>


```csharp
PerpendicularOffset = 27
```
### PerpendicularToFirstSegment

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectControlMeasureLineRule.yml" sourcestartlinenumber="1">Line perpendicular to the midpoint of first segment. Length X% longer than vertex 2-vertex 3.</p>


```csharp
PerpendicularToFirstSegment = 21
```
### PerpendicularToSecondSegment

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectControlMeasureLineRule.yml" sourcestartlinenumber="1">Second segment midpoint to first vertex.</p>


```csharp
PerpendicularToSecondSegment = 3
```
### PerpendicularWithArc

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectControlMeasureLineRule.yml" sourcestartlinenumber="1">Line between vertex 1 and vertex 2 with arc off of vertex 2. Cross line is perpendicular to vertex 3.</p>


```csharp
PerpendicularWithArc = 16
```
### ReversedFirstSegment

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectControlMeasureLineRule.yml" sourcestartlinenumber="1">Line between vertex 2 and vertex 1. Line begins at vertex 2.</p>


```csharp
ReversedFirstSegment = 2
```
### SecondSegmentWithTicks

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectControlMeasureLineRule.yml" sourcestartlinenumber="1">Line between vertex 2 and vertex 3 with ticks on ends.</p>


```csharp
SecondSegmentWithTicks = 4
```
### SegmentThenHalfCircle

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectControlMeasureLineRule.yml" sourcestartlinenumber="1">Creates a dynamic line with a straight segment followed by a half circle. The diameter of the circle is determined by the length of the second segment. Vertex 4 determines the side of the half circle.</p>


```csharp
SegmentThenHalfCircle = 41
```
### TipWithPerpendicularAndTicks

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectControlMeasureLineRule.yml" sourcestartlinenumber="1">Dynamic line perpendicular to segment 1, center on vertex 1 and offset towards vertex 2 with ticks.</p>


```csharp
TipWithPerpendicularAndTicks = 37
```
### TripleParallelExtended

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectControlMeasureLineRule.yml" sourcestartlinenumber="1">Three parallel lines of varying length connected to a base line. The base defined by first segment. Vertex 3 is the end of the longest line.</p>


```csharp
TripleParallelExtended = 18
```
### TriplePerpendicular

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectControlMeasureLineRule.yml" sourcestartlinenumber="1">Three lines perpendicular to the first segment. Length of the lines is determined by vertex 3. Top and bottom lines stop at 80% of first segment.</p>


```csharp
TriplePerpendicular = 7
```


