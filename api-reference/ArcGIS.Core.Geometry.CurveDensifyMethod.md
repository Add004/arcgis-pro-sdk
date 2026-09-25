# CurveDensifyMethod

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.CurveDensifyMethod.yml" sourcestartlinenumber="1">Methods to specify curve densification.<br>
Used with <xref href="ArcGIS.Core.Geometry.PolylineBuilderEx.CreatePolyline(ArcGIS.Core.Geometry.MapPoint%2cSystem.Double%2cSystem.Double%2cSystem.Double%2cArcGIS.Core.Geometry.ArcOrientation%2cArcGIS.Core.Geometry.ClothoidCreateMethod%2cSystem.Double%2cArcGIS.Core.Geometry.CurveDensifyMethod%2cSystem.Double%2cArcGIS.Core.Geometry.SpatialReference)" data-throw-if-not-resolved="false"></xref>,
<xref href="ArcGIS.Core.Geometry.GeometryEngine.ConstructGeodeticLineFromPoints(ArcGIS.Core.Geometry.GeodeticCurveType%2cArcGIS.Core.Geometry.MapPoint%2cArcGIS.Core.Geometry.MapPoint%2cArcGIS.Core.Geometry.LinearUnit%2cArcGIS.Core.Geometry.CurveDensifyMethod%2cSystem.Double)" data-throw-if-not-resolved="false"></xref>,
and <xref href="ArcGIS.Core.Geometry.GeometryEngine.ConstructGeodeticLineFromDistance(ArcGIS.Core.Geometry.GeodeticCurveType%2cArcGIS.Core.Geometry.MapPoint%2cSystem.Double%2cSystem.Double%2cArcGIS.Core.Geometry.LinearUnit%2cArcGIS.Core.Geometry.CurveDensifyMethod%2cSystem.Double)" data-throw-if-not-resolved="false"></xref></p>


## Object Signature

```csharp
public enum CurveDensifyMethod
```


## Members

### ByAngle

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.CurveDensifyMethod.yml" sourcestartlinenumber="1">Densify parameter is angle increment. Line segments will become shorter as the curvature increases.
For geodesic ellipses, the angle is with respect to the reference circle.</p>


```csharp
ByAngle = 1
```
### ByDeviation

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.CurveDensifyMethod.yml" sourcestartlinenumber="1">Densify parameter is deviation from the true curve.  Line segments of varying length will be generated.
The curve parameter specifies the maximum allowable distance between a line segment and the portion of the curve that it is approximating.</p>


```csharp
ByDeviation = 2
```
### ByLength

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.CurveDensifyMethod.yml" sourcestartlinenumber="1">Densify parameter is curve length increment. Output line segments will be no longer than the parameter.
This method cannot be used when constructing geodesic circles or ellipses</p>


```csharp
ByLength = 0
```


