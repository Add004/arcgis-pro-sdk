# GeodeticCurveType

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.GeodeticCurveType.yml" sourcestartlinenumber="1">Curve type options for use with the geodetic functions. See <xref href="ArcGIS.Core.Geometry.GeometryEngine.GeodeticDensifyByLength(ArcGIS.Core.Geometry.Geometry%2cSystem.Double%2cArcGIS.Core.Geometry.LinearUnit%2cArcGIS.Core.Geometry.GeodeticCurveType)" data-throw-if-not-resolved="false"></xref>,
<xref href="ArcGIS.Core.Geometry.GeometryEngine.GeodeticDensifyByDeviation(ArcGIS.Core.Geometry.Geometry%2cSystem.Double%2cArcGIS.Core.Geometry.LinearUnit%2cArcGIS.Core.Geometry.GeodeticCurveType)" data-throw-if-not-resolved="false"></xref> or
<xref href="ArcGIS.Core.Geometry.GeometryEngine.GeodeticMove(System.Collections.Generic.IEnumerable%7bArcGIS.Core.Geometry.MapPoint%7d%2cArcGIS.Core.Geometry.SpatialReference%2cSystem.Double%2cArcGIS.Core.Geometry.LinearUnit%2cSystem.Double%2cArcGIS.Core.Geometry.GeodeticCurveType)" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public enum GeodeticCurveType
```


## Members

### Geodesic

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.GeodeticCurveType.yml" sourcestartlinenumber="1">A geodesic line (shortest path along two points on an ellipsoid).</p>


```csharp
Geodesic = 0
```
### GreatElliptic

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.GeodeticCurveType.yml" sourcestartlinenumber="1">A great elliptic.</p>


```csharp
GreatElliptic = 2
```
### Loxodrome

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.GeodeticCurveType.yml" sourcestartlinenumber="1">A rhumb line (loxodrome).</p>


```csharp
Loxodrome = 1
```
### NormalSection

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.GeodeticCurveType.yml" sourcestartlinenumber="1">A normal section.</p>


```csharp
NormalSection = 3
```
### ShapePreserving

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.GeodeticCurveType.yml" sourcestartlinenumber="1">The segment shape is preserved in the projection where it is defined.</p>


```csharp
ShapePreserving = 4
```


