# LeftOrRightSide

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.LeftOrRightSide.yml" sourcestartlinenumber="1">When used in <xref href="ArcGIS.Core.Geometry.GeometryEngine.QueryPointAndDistance(ArcGIS.Core.Geometry.Multipart%2cArcGIS.Core.Geometry.SegmentExtensionType%2cArcGIS.Core.Geometry.MapPoint%2cArcGIS.Core.Geometry.AsRatioOrLength%2cSystem.Double%40%2cSystem.Double%40%2cArcGIS.Core.Geometry.LeftOrRightSide%40)" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Core.Geometry.GeometryEngine.QueryPointAndDistance(ArcGIS.Core.Geometry.Segment%2cArcGIS.Core.Geometry.SegmentExtensionType%2cArcGIS.Core.Geometry.MapPoint%2cArcGIS.Core.Geometry.AsRatioOrLength%2cSystem.Double%40%2cSystem.Double%40%2cArcGIS.Core.Geometry.LeftOrRightSide%40)" data-throw-if-not-resolved="false"></xref>,
describes whether the input point is on the left or right side of the curve.
When used in <xref href="ArcGIS.Core.Geometry.GeometryEngine.SideBuffer(ArcGIS.Core.Geometry.Polyline%2cSystem.Double%2cArcGIS.Core.Geometry.LeftOrRightSide%2cArcGIS.Core.Geometry.LineCapType)" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Core.Geometry.GeometryEngine.SideBuffer(System.Collections.Generic.IEnumerable%7bArcGIS.Core.Geometry.Polyline%7d%2cSystem.Double%2cArcGIS.Core.Geometry.LeftOrRightSide%2cArcGIS.Core.Geometry.LineCapType)" data-throw-if-not-resolved="false"></xref>,
describes which side of the input geometry to construct the buffer.
The direction of the curve determines the left and right sides.</p>


## Object Signature

```csharp
public enum LeftOrRightSide
```


## Members

### LeftSide

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.LeftOrRightSide.yml" sourcestartlinenumber="1">The left side of the curve.</p>


```csharp
LeftSide = 0
```
### RightSide

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.LeftOrRightSide.yml" sourcestartlinenumber="1">The right side of the curve.</p>


```csharp
RightSide = 1
```


