# SegmentType

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.SegmentType.yml" sourcestartlinenumber="1">Describes the type of line segment. See the <xref href="ArcGIS.Core.Geometry.Segment.SegmentType" data-throw-if-not-resolved="false"></xref> property.</p>


## Object Signature

```csharp
public enum SegmentType
```


## Members

### Bezier

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.SegmentType.yml" sourcestartlinenumber="1">A third degree cubic Bezier curve. A non-linear segment defined by four control points. The Bezier curve starts at control point 0 (start point)
and ends at control point 3 (end point)
The start point and control point 1 define the tangent at the start point. Control point 2 and the end point define the tangent
at the end point.  The length of these tangent lines and position of the 4 control points determines the shape of the created Bezier curve.</p>


```csharp
Bezier = 1
```
### EllipticArc

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.SegmentType.yml" sourcestartlinenumber="1">An elliptic arc is the portion of the boundary of a 2D ellipse that connects two points.</p>


```csharp
EllipticArc = 2
```
### Line

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.SegmentType.yml" sourcestartlinenumber="1">A straight line segment between a start point and end point.</p>


```csharp
Line = 0
```


