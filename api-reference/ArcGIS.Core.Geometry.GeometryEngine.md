# GeometryEngine

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Utility for performing geometric operations.</p>


## Object Signature

```csharp
public sealed class GeometryEngine : IGeometryEngine
```


## Members

### AccelerateForRelationalOperations(Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Produces a copy of the given geometry that is an accelerated geometry used to speed up relational operations.
Only polyline and polygon geometries can be accelerated. If the geometry cannot be accelerated, the method returns the
same input geometry.</p>


```csharp
public Geometry AccelerateForRelationalOperations(Geometry geometry)
```
### Area(Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Gets the area of the geometry. This is a planar measurement using 2D Cartesian mathematics to compute the area.</p>


```csharp
public double Area(Geometry geometry)
```
### AutoComplete(Polygon, Polyline)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Constructs a polygon that fills in the gaps between the existing polygon and polyline.</p>


```csharp
public Polygon AutoComplete(Polygon inputPolygon, Polyline completionLine)
```
### Boundary(Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Calculates the boundary of the input geometry.</p>


```csharp
public Geometry Boundary(Geometry geometry)
```
### Buffer(Geometry, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Creates a buffer polygon at the specified distance around the given geometry.</p>


```csharp
public Geometry Buffer(Geometry geometry, double distance)
```
### Buffer(IEnumerable&lt;Geometry&gt;, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Creates buffers at the specified distance around the given geometries. Will union the results of all buffers.</p>


```csharp
public Geometry Buffer(IEnumerable<Geometry> geometries, double distance)
```
### CalculateNonSimpleMs(Multipart, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Calculates M attribute values for each non-simple (NaN) M-value from existing simple (non-NaN) M attributes on the specified geometry.
The non-simple M-values are obtained by extrapolation/interpolation for polylines and interpolation for polygons.</p>


```csharp
public Multipart CalculateNonSimpleMs(Multipart multipart, double defaultMValue)
```
### CalculateNonSimpleZs(Multipart, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Calculates Z attribute values for each non-simple (NaN) Z-value from existing simple (non-NaN) Z attributes on the specified geometry.
The non-simple Z values are obtained by extrapolation/interpolation for polylines and interpolation for polygons.</p>


```csharp
public Multipart CalculateNonSimpleZs(Multipart multipart, double defaultZValue)
```
### CalibrateByMs(Multipart, IEnumerable&lt;MapPoint&gt;, UpdateMMethod, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Calibrates M-values using M-values of input points.</p>


```csharp
public Multipart CalibrateByMs(Multipart multipart, IEnumerable<MapPoint> points, UpdateMMethod updateMMethod, double cutOffDistance)
```
### CalibrateMsByDistance(Multipart, IEnumerable&lt;MapPoint&gt;, UpdateMMethod, bool, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Calibrates M-values using M-values of input points.</p>


```csharp
public Multipart CalibrateMsByDistance(Multipart multipart, IEnumerable<MapPoint> points, UpdateMMethod updateMMethod, bool ignoreGaps, double cutOffDistance)
```
### CenterAt(Envelope, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Center the envelope at the specified X and Y coordinates.</p>


```csharp
public Envelope CenterAt(Envelope envelope, double x, double y)
```
### Centroid(Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Gets the centroid (center of gravity) of the geometry.</p>


```csharp
public MapPoint Centroid(Geometry geometry)
```
### Clip(Geometry, Envelope)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Constructs the polygon created by clipping geometry by envelope.</p>


```csharp
public Geometry Clip(Geometry geometry, Envelope envelope)
```
### ConstructGeodeticLineFromDistance(GeodeticCurveType, MapPoint, double, double, LinearUnit, CurveDensifyMethod, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Constructs a geodetic line with the specified length and azimuth.</p>


```csharp
public Polyline ConstructGeodeticLineFromDistance(GeodeticCurveType curveType, MapPoint fromPoint, double length, double azimuth, LinearUnit linearUnit, CurveDensifyMethod densifyMode, double densifyParameter)
```
### ConstructGeodeticLineFromPoints(GeodeticCurveType, MapPoint, MapPoint, LinearUnit, CurveDensifyMethod, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Constructs a geodetic line connecting the specified points.</p>


```csharp
public Polyline ConstructGeodeticLineFromPoints(GeodeticCurveType curveType, MapPoint fromPoint, MapPoint toPoint, LinearUnit linearUnit, CurveDensifyMethod densifyMode, double densifyParameter)
```
### ConstructMultipatchExtrude(Multipart, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Creates a multipatch from the input polygon or polyline.</p>


```csharp
public Multipatch ConstructMultipatchExtrude(Multipart multipart, double zOffset)
```
### ConstructMultipatchExtrudeAlongLine(Multipart, Coordinate3D, Coordinate3D)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Creates a multipatch from the input polygon or polyline.</p>


```csharp
public Multipatch ConstructMultipatchExtrudeAlongLine(Multipart multipart, Coordinate3D fromCoordinate, Coordinate3D toCoordinate)
```
### ConstructMultipatchExtrudeAlongVector3D(Multipart, Coordinate3D)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Creates a multipatch from the input polygon or polyline.</p>


```csharp
public Multipatch ConstructMultipatchExtrudeAlongVector3D(Multipart multipart, Coordinate3D coordinate)
```
### ConstructMultipatchExtrudeFromToZ(Multipart, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Creates a multipatch from the input polygon or polyline.</p>


```csharp
public Multipatch ConstructMultipatchExtrudeFromToZ(Multipart multipart, double fromZ, double toZ)
```
### ConstructMultipatchExtrudeToZ(Multipart, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Creates a multipatch from the input polygon or polyline.</p>


```csharp
public Multipatch ConstructMultipatchExtrudeToZ(Multipart multipart, double toZ)
```
### ConstructPointFromAngleDistance(MapPoint, double, double, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Constructs a point at a specified angle from the horizontal axis and a specified distance away from the input point.</p>


```csharp
public MapPoint ConstructPointFromAngleDistance(MapPoint inputPoint, double angle, double distance, SpatialReference spatialReference = null)
```
### ConstructPolygonsFromPolylines(IEnumerable&lt;Polyline&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Generates polygons from a set of polylines.</p>


```csharp
public IReadOnlyList<Polygon> ConstructPolygonsFromPolylines(IEnumerable<Polyline> polylines)
```
### Contains(Geometry, Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Returns true if geometry1 contains geometry2.</p>


```csharp
public bool Contains(Geometry geometry1, Geometry geometry2)
```
### ConvexHull(Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Constructs the convex hull of the geometry.</p>


```csharp
public Geometry ConvexHull(Geometry geometry)
```
### Crosses(Geometry, Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Returns true if geometry1 crosses geometry2.</p>


```csharp
public bool Crosses(Geometry geometry1, Geometry geometry2)
```
### Cut(Multipart, Polyline)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Splits this geometry into parts.</p>


```csharp
public IReadOnlyList<Geometry> Cut(Multipart multipart, Polyline cutter)
```
### Cut(Multipart, Polyline, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Splits this geometry into parts.</p>


```csharp
public IReadOnlyList<Geometry> Cut(Multipart multipart, Polyline cutter, bool considerTouch)
```
### DensifyByAngle(Multipart, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Densifies the specified geometry.</p>


```csharp
public Geometry DensifyByAngle(Multipart multipart, double maxAngleDeviation)
```
### DensifyByDeviation(Geometry, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Densifies the specified geometry.</p>


```csharp
public Geometry DensifyByDeviation(Geometry geometry, double maxDeviationMeters)
```
### DensifyByLength(Geometry, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Densifies the specified geometry.</p>


```csharp
public Geometry DensifyByLength(Geometry geometry, double maxSegmentLength)
```
### DensifyByLength3D(Geometry, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Densifies the specified geometry.</p>


```csharp
public Geometry DensifyByLength3D(Geometry geometry, double maxSegmentLength)
```
### Difference(Geometry, Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Performs the topological difference operation on the two geometries.</p>


```csharp
public Geometry Difference(Geometry geometry1, Geometry geometry2)
```
### Disjoint(Geometry, Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Returns true if <code class="paramref">geometry1</code> and <code class="paramref">geometry2</code> are disjoint.</p>


```csharp
public bool Disjoint(Geometry geometry1, Geometry geometry2)
```
### Disjoint3D(Geometry, Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Returns true if <code class="paramref">geometry1</code> and <code class="paramref">geometry2</code> are disjoint in a 3-dimensional manner.</p>


```csharp
public bool Disjoint3D(Geometry geometry1, Geometry geometry2)
```
### Distance(Geometry, Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Measures the planar distance between two geometries.</p>


```csharp
public double Distance(Geometry geometry1, Geometry geometry2)
```
### Distance3D(Geometry, Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Measures the 3-dimensional planar distance between two geometries.</p>


```csharp
public double Distance3D(Geometry geometry1, Geometry geometry2)
```
### DropMs(Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Sets all the M-values to NaN.</p>


```csharp
public Geometry DropMs(Geometry geometry)
```
### DropMs(Geometry, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Sets all the M-values to NaN.</p>


```csharp
public Geometry DropMs(Geometry geometry, bool allowNonMGeometry)
```
### DropZs(Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Sets all the Z-values to NaN.</p>


```csharp
public Geometry DropZs(Geometry geometry)
```
### DropZs(Geometry, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Sets all the Z-values to NaN.</p>


```csharp
public Geometry DropZs(Geometry geometry, bool allowNonZGeometry)
```
### Equals(Geometry, Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Returns true if <code class="paramref">geometry1</code> and <code class="paramref">geometry2</code> occupy the same space.</p>


```csharp
public bool Equals(Geometry geometry1, Geometry geometry2)
```
### Expand(Envelope, double, double, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Expands or shrinks the envelope.</p>


```csharp
public Envelope Expand(Envelope envelope, double dx, double dy, bool asRatio)
```
### Expand(Envelope, double, double, double, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Expands or shrinks the envelope in a 3-dimensional manner.</p>


```csharp
public Envelope Expand(Envelope envelope, double dx, double dy, double dz, bool asRatio)
```
### ExportToEsriShape(EsriShapeExportFlags, Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Writes an Esri shapefile formatted version of the input geometry to a buffer.</p>


```csharp
public byte[] ExportToEsriShape(EsriShapeExportFlags exportFlags, Geometry geometry)
```
### ExportToEsriShape(EsriShapeExportFlags, Geometry, ref byte[])

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Writes an Esri shapefile formatted version of the input geometry to the specified buffer.</p>


```csharp
public int ExportToEsriShape(EsriShapeExportFlags exportFlags, Geometry geometry, ref byte[] buffer)
```
### ExportToJson(JsonExportFlags, Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Writes a JSON version of the input geometry to a string.</p>


```csharp
public string ExportToJson(JsonExportFlags exportFlags, Geometry geometry)
```
### ExportToWKB(WkbExportFlags, Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Writes an OGC well-known binary formatted version of the input geometry to a buffer.</p>


```csharp
public byte[] ExportToWKB(WkbExportFlags exportFlags, Geometry geometry)
```
### ExportToWKB(WkbExportFlags, Geometry, ref byte[])

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Writes an OGC well-known binary formatted version of the input geometry to the specified buffer.</p>


```csharp
public int ExportToWKB(WkbExportFlags exportFlags, Geometry geometry, ref byte[] buffer)
```
### ExportToWKT(WktExportFlags, Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Writes an OGC well-known text formatted version of the input geometry to a string.</p>


```csharp
public string ExportToWKT(WktExportFlags exportFlags, Geometry geometry)
```
### Extend(Polyline, Polyline, ExtendFlags)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Performs the extend operation on a polyline using a polyline as the extender. The output polyline will have the first and
last segment of each part extended to the extender if the segments can be interpolated to intersect the extender. In the
case that the segments can be extended to multiple segments of the extender, the shortest extension is chosen. Only end points
for parts that are not shared by the end points of other parts will be extended. If the polyline cannot be extended by the
input extender, then a null will be returned.</p>


```csharp
public Polyline Extend(Polyline polyline, Polyline extender, ExtendFlags extendFlags)
```
### ExtrapolateMs(Multipart, ExtrapolateMMethod, int, int, int, int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Extrapolates the M-values based on the extrapolate range defined by the input indices.</p>


```csharp
public Multipart ExtrapolateMs(Multipart multipart, ExtrapolateMMethod extrapolateMethod, int startPartIndex, int startPointIndex, int endPartIndex, int endPointIndex)
```
### Generalize(Geometry, double, bool, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Performs the generalize operation on the geometry.</p>


```csharp
public Geometry Generalize(Geometry geometry, double maxDeviation, bool removeDegenerateParts, bool preserveCurves)
```
### Generalize3D(Geometry, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Performs the generalize operation on the geometry.</p>


```csharp
public Geometry Generalize3D(Geometry geometry, double maxDeviation)
```
### GeodesicArea(Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Gets the geodesic area of a geometry.</p>


```csharp
public double GeodesicArea(Geometry geometry)
```
### GeodesicArea(Geometry, AreaUnit)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Gets the geodesic area of a geometry.</p>


```csharp
public double GeodesicArea(Geometry geometry, AreaUnit areaUnit)
```
### GeodesicBuffer(Geometry, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Creates a buffer polygon at the specified geodesic distance around the given geometry.</p>


```csharp
public Geometry GeodesicBuffer(Geometry geometry, double distance)
```
### GeodesicBuffer(Geometry, double, LinearUnit)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Creates a buffer polygon at the specified geodesic distance around the given geometry.</p>


```csharp
public Geometry GeodesicBuffer(Geometry geometry, double distance, LinearUnit distanceUnit)
```
### GeodesicBuffer(IEnumerable&lt;Geometry&gt;, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Creates buffers at the specified distance around the given geometries. Will union the results of all buffers.</p>


```csharp
public Geometry GeodesicBuffer(IEnumerable<Geometry> geometries, double distance)
```
### GeodesicBuffer(IEnumerable&lt;Geometry&gt;, double, LinearUnit)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Creates buffers at the specified distance around the given geometries. Will union the results of all buffers.</p>


```csharp
public Geometry GeodesicBuffer(IEnumerable<Geometry> geometries, double distance, LinearUnit distanceUnit)
```
### GeodesicDistance(Geometry, Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Calculates the geodesic distance between two geometries.</p>


```csharp
public double GeodesicDistance(Geometry geometry1, Geometry geometry2)
```
### GeodesicDistance(Geometry, Geometry, LinearUnit)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Calculates the geodesic distance between two geometries.</p>


```csharp
public double GeodesicDistance(Geometry geometry1, Geometry geometry2, LinearUnit distanceUnit)
```
### GeodesicEllipse(GeodesicEllipseParameter, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">The function returns a piecewise approximation of a geodesic ellipse (or
geodesic circle, if semiAxis1Length = semiAxis2Length). Constructs a geodesic
ellipse centered on the specified point. If this method is used to generate
a polygon or a polyline, the result may have more than one part, depending
on the size of the ellipse and its position relative to the horizon of the
coordinate system. When the method generates a polyline or a multipoint,
the result vertices lie on the boundary of the ellipse. When a polygon is
generated, the interior of the polygon is the interior of the ellipse, however
the boundary of the polygon may contain segments from the spatial reference
horizon, or from the GCS extent.</p>


```csharp
public Geometry GeodesicEllipse(GeodesicEllipseParameter parameter, SpatialReference spatialReference)
```
### GeodesicLength(Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Gets the geodesic length of the input geometry.</p>


```csharp
public double GeodesicLength(Geometry geometry)
```
### GeodesicLength(Geometry, LinearUnit)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Gets the geodesic length of the input geometry.</p>


```csharp
public double GeodesicLength(Geometry geometry, LinearUnit outputUnit)
```
### GeodesicSector(GeodesicSectorParameter, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">The function returns a piecewise approximation of a geodesic ellipse (or
geodesic circle, if SemiAxis1Length = SemiAxis2Length).  Constructs a geodesic
ellipse centered on the specified point.  If this method is used to generate
a polygon or a polyline, the result may have more than one part, depending
on the size of the sector and its position relative to the horizon of the
coordinate system.  When the method generates a polyline or a multipoint,
the result vertices lie on the boundary of the ellipse.  When a polygon is
generated, the interior of the polygon is the interior of the sector, however
the boundary of the polygon may contain segments from the spatial reference
horizon, or from the GCS extent.</p>


```csharp
public Geometry GeodesicSector(GeodesicSectorParameter parameter, SpatialReference spatialReference)
```
### GeodeticArea(Geometry, AreaUnit, GeodeticCurveType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Gets the geodetic area of the input geometry.</p>


```csharp
public double GeodeticArea(Geometry geometry, AreaUnit areaUnit, GeodeticCurveType curveType)
```
### GeodeticBuffer(Geometry, double, LinearUnit, double, GeodeticCurveType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Creates a geodetic buffer polygon at the specified geodetic distance around the given geometry.</p>


```csharp
public Geometry GeodeticBuffer(Geometry geometry, double distance, LinearUnit distanceUnit, double maxDeviation, GeodeticCurveType curveType)
```
### GeodeticBuffer(IEnumerable&lt;Geometry&gt;, IEnumerable&lt;double&gt;, LinearUnit, double, GeodeticCurveType, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Creates buffers at the specified geodetic distance around the given geometries.</p>


```csharp
public IReadOnlyList<Geometry> GeodeticBuffer(IEnumerable<Geometry> geometries, IEnumerable<double> distances, LinearUnit distanceUnit, double maxDeviation, GeodeticCurveType curveType, bool unionResult)
```
### GeodeticDensifyByDeviation(Geometry, double, LinearUnit, GeodeticCurveType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Creates geodetic segments connecting existing vertices and densifies the segments.</p>


```csharp
public Geometry GeodeticDensifyByDeviation(Geometry geometry, double maxDeviation, LinearUnit deviationUnit, GeodeticCurveType curveType)
```
### GeodeticDensifyByLength(Geometry, double, LinearUnit, GeodeticCurveType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Creates geodetic segments connecting existing vertices and densifies the segments.</p>


```csharp
public Geometry GeodeticDensifyByLength(Geometry geometry, double maxSegmentLength, LinearUnit lengthUnit, GeodeticCurveType curveType)
```
### GeodeticDistance(Geometry, Geometry, LinearUnit, GeodeticCurveType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Gets the shortest geodetic distance between two geometries.</p>


```csharp
public double GeodeticDistance(Geometry geometry1, Geometry geometry2, LinearUnit distanceUnit, GeodeticCurveType curveType)
```
### GeodeticDistanceAndAzimuth(MapPoint, MapPoint, GeodeticCurveType, LinearUnit, out double, out double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Calculates distance and azimuth on the spheroid between two points using the given geodetic curve type.</p>


```csharp
public double GeodeticDistanceAndAzimuth(MapPoint point1, MapPoint point2, GeodeticCurveType curveType, LinearUnit distanceUnit, out double azimuth12, out double azimuth21)
```
### GeodeticDistanceAndAzimuth(MapPoint, MapPoint, GeodeticCurveType, out double, out double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Calculates distance and azimuth on the spheroid between two points using the given geodetic curve type.</p>


```csharp
public double GeodeticDistanceAndAzimuth(MapPoint point1, MapPoint point2, GeodeticCurveType curveType, out double azimuth12, out double azimuth21)
```
### GeodeticLength(Geometry, LinearUnit, GeodeticCurveType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Gets the geodetic length of the input geometry.</p>


```csharp
public double GeodeticLength(Geometry geometry, LinearUnit lengthUnit, GeodeticCurveType curveType)
```
### GeodeticMove(IEnumerable&lt;MapPoint&gt;, SpatialReference, double, LinearUnit, double, GeodeticCurveType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Moves each point in the input array by the given distance.
The function returns the number of points that has been moved. Points that are outside of the horizon will be discarded.</p>


```csharp
public IReadOnlyList<MapPoint> GeodeticMove(IEnumerable<MapPoint> points, SpatialReference spatialReference, double distance, LinearUnit distanceUnit, double azimuth, GeodeticCurveType curveType)
```
### GetDistancesAtM(Multipart, AsRatioOrLength, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Gets a list of distances along the multipart at points with the specified M-value.</p>


```csharp
public IReadOnlyList<double> GetDistancesAtM(Multipart multipart, AsRatioOrLength asRatioOrLength, double mValue)
```
### GetEsriShapeSize(EsriShapeExportFlags, Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Returns the size of the buffer in bytes that will be required to hold the Esri shapefile version of the input geometry.</p>


```csharp
public int GetEsriShapeSize(EsriShapeExportFlags exportFlags, Geometry geometry)
```
### GetMMonotonic(Multipart)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Determines whether Ms are monotonic, and if so, whether they are ascending or descending.</p>


```csharp
public MonotonicType GetMMonotonic(Multipart multipart)
```
### GetMMonotonicity(Multipart)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Gets a combination of <xref href="ArcGIS.Core.Geometry.Monotonicity" data-throw-if-not-resolved="false"></xref> values that describes all trends in the M-values over the length of the multipart.</p>


```csharp
public Monotonicity GetMMonotonicity(Multipart multipart)
```
### GetMinMaxM(Multipart, out double, out double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Gets the minimum and maximum M-value.</p>


```csharp
public void GetMinMaxM(Multipart multipart, out double minM, out double maxM)
```
### GetMsAtDistance(Multipart, double, AsRatioOrLength, out double, out double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Get the M-values at the specified distance along the multipart. Two M-values can be returned if the specified distance
is exactly at the beginning or the ending of a part.</p>


```csharp
public void GetMsAtDistance(Multipart multipart, double distance, AsRatioOrLength asRatioOrLength, out double mValue1, out double mValue2)
```
### GetNonSimpleReason(Geometry, out NonSimpleReason, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Indicates whether this geometry is topologically correct.</p>


```csharp
public bool GetNonSimpleReason(Geometry geometry, out NonSimpleReason nonSimpleReason, bool forceIsSimple)
```
### GetNormalsAtM(Multipart, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Gets the line segments corresponding to the normal at the locations along the geometry where the specified M occurs.</p>


```csharp
public Polyline GetNormalsAtM(Multipart multipart, double mValue, double length)
```
### GetPointsAtM(Multipart, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Gets a multipoint corresponding to the locations along the multipart where the specified M-value occurs.
Coordinates/measures are interpolated when appropriate.</p>


```csharp
public Multipoint GetPointsAtM(Multipart multipart, double mValue, double offset)
```
### GetPredefinedCoordinateSystemList(CoordinateSystemFilter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Gets the list of predefined coordinate systems for the given filter.</p>


```csharp
public IReadOnlyList<CoordinateSystemListEntry> GetPredefinedCoordinateSystemList(CoordinateSystemFilter filter)
```
### GetPredefinedGeographicTransformationList()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Gets the list of predefined geographic transformations.</p>


```csharp
public IReadOnlyList<GeographicTransformationListEntry> GetPredefinedGeographicTransformationList()
```
### GetSubCurve(Multipart, double, double, AsRatioOrLength)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Gets the subcurve of the input multipart between fromDistance and toDistance.</p>


```csharp
public Polyline GetSubCurve(Multipart multipart, double fromDistance, double toDistance, AsRatioOrLength asRatioOrLength)
```
### GetSubCurve3D(Multipart, double, double, AsRatioOrLength)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Gets the 3D subcurve of the input multipart between fromDistance and toDistance.</p>


```csharp
public Polyline GetSubCurve3D(Multipart multipart, double fromDistance, double toDistance, AsRatioOrLength asRatioOrLength)
```
### GetSubCurveBetweenMs(Multipart, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Gets a polyline corresponding to the subcurve(s) between the specified M-values.</p>


```csharp
public Polyline GetSubCurveBetweenMs(Multipart multipart, double fromM, double toM)
```
### GetSubCurveBetweenMsEx(Multipart, double, double, out MSubCurveRelation, out MSubCurveRelation)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Gets a polyline and other details corresponding to the subcurve(s) between the specified M-values.</p>


```csharp
public Polyline GetSubCurveBetweenMsEx(Multipart multipart, double fromM, double toM, out MSubCurveRelation fromMDetail, out MSubCurveRelation toMDetail)
```
### GetWKBSize(WkbExportFlags, Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Returns the size of the buffer in bytes that will be required to hold the OGC well-known binary version of the input geometry.</p>


```csharp
public int GetWKBSize(WkbExportFlags exportFlags, Geometry geometry)
```
### GraphicBuffer(Geometry, double, LineJoinType, LineCapType, double, double, int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Creates a buffer polygon at the specified distance around the input geometry using graphical joins and caps.</p>


```csharp
public Geometry GraphicBuffer(Geometry geometry, double distance, LineJoinType joinType, LineCapType capType, double miterLimit, double maxDeviation, int maxVerticesInFullCircle)
```
### GraphicBuffer(IEnumerable&lt;Geometry&gt;, double, LineJoinType, LineCapType, double, double, int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Creates a buffer polygon at the specified distance around the input geometry using graphical joins and caps.</p>


```csharp
public IReadOnlyList<Geometry> GraphicBuffer(IEnumerable<Geometry> geometries, double distance, LineJoinType joinType, LineCapType capType, double miterLimit, double maxDeviation, int maxVerticesInFullCircle)
```
### ImportFromEsriShape(EsriShapeImportFlags, byte[], SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Creates a geometry based on the contents of the input Esri shapefile formatted buffer.</p>


```csharp
public Geometry ImportFromEsriShape(EsriShapeImportFlags importFlags, byte[] buffer, SpatialReference spatialReference)
```
### ImportFromJson(JsonImportFlags, string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Creates a geometry from the input JSON string.</p>


```csharp
public Geometry ImportFromJson(JsonImportFlags importFlags, string jsonString)
```
### ImportFromWKB(WkbImportFlags, byte[], SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Creates a geometry based on the contents of the input well-known binary buffer.</p>


```csharp
public Geometry ImportFromWKB(WkbImportFlags importFlags, byte[] buffer, SpatialReference spatialReference)
```
### ImportFromWKT(WktImportFlags, string, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Creates a geometry from the input well-known text string.</p>


```csharp
public Geometry ImportFromWKT(WktImportFlags importFlags, string wktString, SpatialReference spatialReference)
```
### InsertMAtDistance(Multipart, double, double, AsRatioOrLength, bool, out bool, out int, out int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Sets the M-value at the given distance along the multipart.</p>


```csharp
public Multipart InsertMAtDistance(Multipart multipart, double mValue, double distance, AsRatioOrLength asRatioOrLength, bool createNewPart, out bool splitHappened, out int partIndex, out int segmentIndex)
```
### Instance

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Gets the GeometryEngine instance.</p>


```csharp
public static IGeometryEngine Instance { get; }
```
### InterpolateMsBetween(Multipart, int, int, int, int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Generates M-values by linear interpolation over a range of points.</p>


```csharp
public Multipart InterpolateMsBetween(Multipart multipart, int fromPart, int fromPoint, int toPart, int toPoint)
```
### Intersection(Geometry, Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Constructs the set-theoretic intersection between two geometries.</p>


```csharp
public Geometry Intersection(Geometry geometry1, Geometry geometry2)
```
### Intersection(Geometry, Geometry, GeometryDimensionType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Constructs the set-theoretic intersection between two geometries.
Use different resultDimensionType values to generate results of different dimensions.</p>


```csharp
public Geometry Intersection(Geometry geometry1, Geometry geometry2, GeometryDimensionType resultDimensionType)
```
### Intersects(Geometry, Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Returns true if geometry1 and geometry2 intersect.</p>


```csharp
public bool Intersects(Geometry geometry1, Geometry geometry2)
```
### IsMSimple(Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Determines if all the M-values are numbers.</p>


```csharp
public bool IsMSimple(Geometry geometry)
```
### IsSimpleAsFeature(Geometry, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Indicates whether this geometry is known to be topologically consistent according to the geometry type for storage in a database.</p>


```csharp
public bool IsSimpleAsFeature(Geometry geometry, bool forceIsSimple)
```
### IsSimpleOgc(Geometry, out NonSimpleReason, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Indicates if the given geometry is topologically consistent according to the Open Geospatial Consortium (OGC) validation specification.</p>


```csharp
public bool IsSimpleOgc(Geometry geometry, out NonSimpleReason nonSimpleReason, bool forceIsSimple)
```
### LabelPoint(Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Performs the LabelPoint operation on the geometry.</p>


```csharp
public MapPoint LabelPoint(Geometry geometry)
```
### Length(Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Gets the length for a specified geometry. This is a planar measurement using 2D Cartesian mathematics.</p>


```csharp
public double Length(Geometry geometry)
```
### Length3D(Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Gets the 3D length for a specified geometry.</p>


```csharp
public double Length3D(Geometry geometry)
```
### Move(Geometry, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Moves a geometry.</p>


```csharp
public Geometry Move(Geometry geometry, double dx, double dy)
```
### Move(Geometry, double, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Moves the geometry in a 3-dimensional manner.</p>


```csharp
public Geometry Move(Geometry geometry, double dx, double dy, double dz)
```
### MovePointAlongLine(Multipart, double, bool, double, SegmentExtensionType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Constructs a point the specified distance along a polyline or polygon.</p>


```csharp
public MapPoint MovePointAlongLine(Multipart multipart, double distanceAlong, bool asRatio, double offset, SegmentExtensionType extensionType)
```
### MultipartToSinglePart(Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Separates the components of a geometry into single component geometries.</p>


```csharp
public IReadOnlyList<Geometry> MultipartToSinglePart(Geometry geometry)
```
### MultiplyMs(Geometry, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Multiplies all the M-values by a factor.</p>


```csharp
public Geometry MultiplyMs(Geometry geometry, double factor)
```
### NearestPoint(Geometry, MapPoint)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Finds the nearest point in the geometry to a specified point.</p>


```csharp
public ProximityResult NearestPoint(Geometry geometry, MapPoint point)
```
### NearestPoint3D(Geometry, MapPoint)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Finds the nearest point, in 3D space, on a Z-Aware geometry to a specified point.</p>


```csharp
public ProximityResult NearestPoint3D(Geometry geometry, MapPoint point)
```
### NearestVertex(Geometry, MapPoint)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Finds the nearest vertex in the geometry to a specified point.</p>


```csharp
public ProximityResult NearestVertex(Geometry geometry, MapPoint point)
```
### NormalizeCentralMeridian(Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Folds the geometry into a range of 360 degrees. This may be necessary when wrap around is enabled on the map.
If <code class="paramref">geometry</code> is an Envelope then a Polygon will be returned unless the Envelope is empty in which case an empty Envelope will be returned.</p>


```csharp
public Geometry NormalizeCentralMeridian(Geometry geometry)
```
### Offset(Geometry, double, OffsetType, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Constructs the offset version of the input geometry.  The offset operation creates
a geometry that is a constant distance from an input polyline or polygon.
It is similar to buffering, but produces a one sided result. If offset distance</p>
<blockquote sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="4">
<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="4">0, then the offset geometry is constructed to the right of the oriented
input geometry, otherwise it is constructed to the left. For a simple polygon,
the orientation of outer rings is clockwise and for inner rings it is counter
clockwise. So the &quot;right side&quot; of a simple polygon is always its inside.
The bevelRatio is multiplied by the offset distance and the result determines
how far a mitered offset intersection can be from the input curve before
it is beveled.</p>
</blockquote>


```csharp
public Geometry Offset(Geometry geometry, double distance, OffsetType offsetType, double bevelRatio)
```
### OffsetMs(Geometry, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Adds an offset value to each of the M-values.</p>


```csharp
public Geometry OffsetMs(Geometry geometry, double offset)
```
### OrientByMs(Polyline)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Reorients the polyline such that all M-values are non-decreasing, if possible.</p>


```csharp
public Polyline OrientByMs(Polyline polyline)
```
### Overlaps(Geometry, Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Returns true if geometry1 and geometry2 overlap.</p>


```csharp
public bool Overlaps(Geometry geometry1, Geometry geometry2)
```
### Project(Geometry, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Projects the given geometry to a new spatial reference.
Same as GeometryEngine.ProjectEx(geometry, ProjectionTransformation.Create(geometry.SpatialReference, outputSpatialReference));
or, if both spatial references have vertical coordinate systems same as GeometryEngine.ProjectEx(geometry, ProjectionTransformation.CreateWithVertical(geometry.SpatialReference, outputSpatialReference));</p>


```csharp
public Geometry Project(Geometry geometry, SpatialReference outputSpatialReference)
```
### ProjectEx(Geometry, ProjectionTransformation)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Projects the given geometry to a new spatial reference.</p>


```csharp
public Geometry ProjectEx(Geometry geometry, ProjectionTransformation projTransformation)
```
### QueryFirstLastM(Polyline, out double, out double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Gets the first and last defined M-values in the polyline.</p>


```csharp
public void QueryFirstLastM(Polyline polyline, out double firstM, out double lastM)
```
### QueryNormal(Multipart, SegmentExtensionType, double, AsRatioOrLength, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Constructs a line normal to a segment from a point at a specified distance along the segment.</p>


```csharp
public Polyline QueryNormal(Multipart multipart, SegmentExtensionType extensionType, double distanceAlongCurve, AsRatioOrLength asRatioOrLength, double normalLength)
```
### QueryNormal(Segment, SegmentExtensionType, double, AsRatioOrLength, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Constructs a line normal to a segment from a point at a specified distance along the segment.</p>


```csharp
public LineSegment QueryNormal(Segment segment, SegmentExtensionType extensionType, double distanceAlongCurve, AsRatioOrLength asRatioOrLength, double normalLength)
```
### QueryPoint(Multipart, SegmentExtensionType, double, AsRatioOrLength)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Constructs a <xref href="ArcGIS.Core.Geometry.MapPoint" data-throw-if-not-resolved="false"></xref> at a given distance along the curve or the extended curve.</p>


```csharp
public MapPoint QueryPoint(Multipart multipart, SegmentExtensionType extensionType, double distanceAlongCurve, AsRatioOrLength asRatioOrLength)
```
### QueryPoint(Segment, SegmentExtensionType, double, AsRatioOrLength)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Constructs a <xref href="ArcGIS.Core.Geometry.MapPoint" data-throw-if-not-resolved="false"></xref> at a given distance along the curve or the extended curve.</p>


```csharp
public MapPoint QueryPoint(Segment segment, SegmentExtensionType extensionType, double distanceAlongCurve, AsRatioOrLength asRatioOrLength)
```
### QueryPointAndDistance(Multipart, SegmentExtensionType, MapPoint, AsRatioOrLength, out double, out double, out LeftOrRightSide)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Finds the point on the curve closest to inPoint, then copies that point to outPoint. Also calculates related items.</p>


```csharp
public MapPoint QueryPointAndDistance(Multipart multipart, SegmentExtensionType extensionType, MapPoint inPoint, AsRatioOrLength asRatioOrLength, out double distanceAlongCurve, out double distanceFromCurve, out LeftOrRightSide whichSide)
```
### QueryPointAndDistance(Segment, SegmentExtensionType, MapPoint, AsRatioOrLength, out double, out double, out LeftOrRightSide)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Finds the point on the curve closest to inPoint, then copies that point to outPoint. Also calculates related items.</p>


```csharp
public MapPoint QueryPointAndDistance(Segment segment, SegmentExtensionType extensionType, MapPoint inPoint, AsRatioOrLength asRatioOrLength, out double distanceAlongCurve, out double distanceFromCurve, out LeftOrRightSide whichSide)
```
### QueryPointAndDistance3D(Multipart, SegmentExtensionType, MapPoint, AsRatioOrLength, out double, out double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Finds the point on the curve closest to inPoint, then copies that point to outPoint. The operation is performed in 3D space. Also calculates related items.</p>


```csharp
public MapPoint QueryPointAndDistance3D(Multipart multipart, SegmentExtensionType extensionType, MapPoint inPoint, AsRatioOrLength asRatioOrLength, out double distanceAlongCurve, out double distanceFromCurve)
```
### QueryPointAndDistance3D(Segment, SegmentExtensionType, MapPoint, AsRatioOrLength, out double, out double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Finds the point on the curve closest to inPoint, then copies that point to outPoint. The operation is performed in 3D space. Also calculates related items.</p>


```csharp
public MapPoint QueryPointAndDistance3D(Segment segment, SegmentExtensionType extensionType, MapPoint inPoint, AsRatioOrLength asRatioOrLength, out double distanceAlongCurve, out double distanceFromCurve)
```
### QueryPoints(Multipart, SegmentExtensionType, IEnumerable&lt;double&gt;, AsRatioOrLength)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Constructs a readonly list of <xref href="ArcGIS.Core.Geometry.MapPoint" data-throw-if-not-resolved="false"></xref>s at distances along the curve or the extended curve.</p>


```csharp
public IReadOnlyList<MapPoint> QueryPoints(Multipart multipart, SegmentExtensionType extensionType, IEnumerable<double> distancesAlongCurve, AsRatioOrLength asRatioOrLength)
```
### QueryPoints(Segment, SegmentExtensionType, IEnumerable&lt;double&gt;, AsRatioOrLength)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Constructs a readonly list of  <xref href="ArcGIS.Core.Geometry.MapPoint" data-throw-if-not-resolved="false"></xref>s at distances along the curve or the extended curve.</p>


```csharp
public IReadOnlyList<MapPoint> QueryPoints(Segment segment, SegmentExtensionType extensionType, IEnumerable<double> distancesAlongCurve, AsRatioOrLength asRatioOrLength)
```
### QueryTangent(Multipart, SegmentExtensionType, double, AsRatioOrLength, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Constructs a line tangent to a multipart from a point at a specified distance along the curve.</p>


```csharp
public Polyline QueryTangent(Multipart multipart, SegmentExtensionType extensionType, double distanceAlongCurve, AsRatioOrLength asRatioOrLength, double tangentLength)
```
### QueryTangent(Segment, SegmentExtensionType, double, AsRatioOrLength, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Constructs a line tangent to a segment from a point at a specified distance along the segment.</p>


```csharp
public LineSegment QueryTangent(Segment segment, SegmentExtensionType extensionType, double distanceAlongCurve, AsRatioOrLength asRatioOrLength, double tangentLength)
```
### ReflectAboutLine(Geometry, LineSegment)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Reflects the input geometry about the given line.</p>


```csharp
public Geometry ReflectAboutLine(Geometry geometry, LineSegment reflectionLine)
```
### Relate(Geometry, Geometry, string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Performs custom relational operations between two geometries using a Dimensionally Extended Nine-Intersection Model, DE-9IM, formatted string.</p>


```csharp
public bool Relate(Geometry geometry1, Geometry geometry2, string relateString)
```
### ReplaceNaNZs(Geometry, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Replaces each non-simple (NaN) Z-value on the geometry with the specified Z-value.  All other simple (non-NaN) Z-values are unchanged.</p>


```csharp
public Geometry ReplaceNaNZs(Geometry geometry, double zValue)
```
### Reshape(Multipart, Polyline)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Reshapes a polygon or polyline with a single path polyline.</p>


```csharp
public Multipart Reshape(Multipart multipart, Polyline reshaper)
```
### ReverseMs(Multipart)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Reverses the order of the M-values along the multipart.</p>


```csharp
public Multipart ReverseMs(Multipart multipart)
```
### ReverseOrientation(Multipart)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Reverse the orientation of the geometry.</p>


```csharp
public Multipart ReverseOrientation(Multipart multipart)
```
### Rotate(Geometry, MapPoint, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Rotates the geometry about the specified origin point.</p>


```csharp
public Geometry Rotate(Geometry geometry, MapPoint origin, double rotationAngle)
```
### Scale(Geometry, MapPoint, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Scales the geometry about the specified origin.</p>


```csharp
public Geometry Scale(Geometry geometry, MapPoint origin, double sx, double sy)
```
### Scale(Geometry, MapPoint, double, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Scales the geometry about the specified origin in a 3-dimensional manner.</p>


```csharp
public Geometry Scale(Geometry geometry, MapPoint origin, double sx, double sy, double sz)
```
### SetAndInterpolateMsBetween(Multipart, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Sets the Ms at the beginning and the end of the geometry and interpolates the M-values between these values.</p>


```csharp
public Multipart SetAndInterpolateMsBetween(Multipart multipart, double fromM, double toM)
```
### SetConstantZ(Multipart, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Replaces each Z value on the geometry with the specified Z-value.</p>


```csharp
public Multipart SetConstantZ(Multipart multipart, double zValue)
```
### SetMsAsDistance(Multipart, AsRatioOrLength)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Sets the M-values to the cumulative length from the start of the multipart.</p>


```csharp
public Multipart SetMsAsDistance(Multipart multipart, AsRatioOrLength asRatioOrLength)
```
### SetMsAsDistance(Polyline, Coordinate2D, double, double, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Sets the M-values of the vertices as scaled and offset distances measured along the polyline.</p>


```csharp
public Polyline SetMsAsDistance(Polyline polyline, Coordinate2D origin, double scale, double offset, bool ignoreGaps)
```
### ShapePreservingArea(Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Calculates the area of the geometry on the surface of the Earth ellipsoid. This method
preserves the shape of the geometry in its coordinate system.</p>


```csharp
public double ShapePreservingArea(Geometry geometry)
```
### ShapePreservingArea(Geometry, AreaUnit)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Calculates the area of the geometry on the surface of the Earth ellipsoid. This method
preserves the shape of the geometry in its coordinate system.</p>


```csharp
public double ShapePreservingArea(Geometry geometry, AreaUnit areaUnit)
```
### ShapePreservingLength(Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Calculates the length of the geometry on the surface of the Earth ellipsoid. This method preserves the shape of the geometry in its coordinate system.</p>


```csharp
public double ShapePreservingLength(Geometry geometry)
```
### ShapePreservingLength(Geometry, LinearUnit)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Utility for performing geometric operations.</p>


```csharp
public double ShapePreservingLength(Geometry geometry, LinearUnit lengthUnit)
```
### SideBuffer(Polyline, double, LeftOrRightSide, LineCapType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Constructs a buffer on one side of a polyline</p>


```csharp
public Geometry SideBuffer(Polyline polyline, double distance, LeftOrRightSide side, LineCapType capType)
```
### SideBuffer(IEnumerable&lt;Polyline&gt;, double, LeftOrRightSide, LineCapType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Constructs a buffer on one side of a polyline</p>


```csharp
public IReadOnlyList<Geometry> SideBuffer(IEnumerable<Polyline> polylines, double distance, LeftOrRightSide side, LineCapType capType)
```
### SimplifyAsFeature(Geometry, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Simplifies the given geometry to make it topologically consistent according
to the geometry type for storage in a database. For instance, it rectifies polygons that may be self-intersecting.</p>


```csharp
public Geometry SimplifyAsFeature(Geometry geometry, bool forceSimplify)
```
### SimplifyOgc(Geometry, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Simplifies the given geometry according to the Open Geospatial Consortium (OGC) validation specification.</p>


```csharp
public Geometry SimplifyOgc(Geometry geometry, bool forceSimplify)
```
### SimplifyPolyline(Polyline, SimplifyType, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Use either planar, nonplanar, or network simplify regardless of <code class="paramref">polyline</code> M-awareness.</p>


```csharp
public Polyline SimplifyPolyline(Polyline polyline, SimplifyType simplifyType, bool forceSimplify)
```
### SlicePolygonIntoEqualParts(Polygon, int, double, SliceType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Slices a polygon into a set of equal area parts.</p>


```csharp
public IReadOnlyList<Polygon> SlicePolygonIntoEqualParts(Polygon polygon, int numParts, double angle, SliceType sliceType)
```
### Smooth(Multipart, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Converts the multipart into a multipart containing only Bezier curves segments.</p>


```csharp
public Multipart Smooth(Multipart multipart, double maxDeviation)
```
### SnapMsToSpatialReference(Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Snaps the M-values to the M-precision (1 / MScale) of the spatial reference associated with the input geometry.</p>


```csharp
public Geometry SnapMsToSpatialReference(Geometry geometry)
```
### SplitAtPoint(Multipart, MapPoint, bool, bool, out bool, out int, out int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Adds a new vertex along the multipoint at the specified input point or the projection onto the multipart of the specified input point.</p>


```csharp
public Multipart SplitAtPoint(Multipart multipart, MapPoint splitPoint, bool projectOnto, bool createPart, out bool splitOccurred, out int partIndex, out int segmentIndex)
```
### SymmetricDifference(Geometry, Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Performs the symmetric difference operation on the two geometries. The symmetric difference
is the union of the geometries minus the intersection.</p>


```csharp
public Geometry SymmetricDifference(Geometry geometry1, Geometry geometry2)
```
### Touches(Geometry, Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Returns true if geometry1 touches geometry2.</p>


```csharp
public bool Touches(Geometry geometry1, Geometry geometry2)
```
### Transform2D(Coordinate2D[], ProjectionTransformation, ref Coordinate2D[], bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Transforms an enumeration of 2D coordinates. Returns an enumeration of transformed 2D coordinates.</p>


```csharp
public int Transform2D(Coordinate2D[] inCoordinates, ProjectionTransformation projectionTransformation, ref Coordinate2D[] outCoordinates, bool removeClippedCoordinates = true)
```
### Transform3D(Coordinate3D[], ProjectionTransformation, ref Coordinate3D[], bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Transforms an enumeration of 3D coordinates. Returns an enumeration of transformed 3D coordinates.</p>


```csharp
public int Transform3D(Coordinate3D[] inCoordinates, ProjectionTransformation projectionTransformation, ref Coordinate3D[] outCoordinates, bool removeClippedCoordinates = true)
```
### Union(Geometry, Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Constructs the set-theoretic union of the input geometries.</p>


```csharp
public Geometry Union(Geometry geometry1, Geometry geometry2)
```
### Union(IEnumerable&lt;Geometry&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Constructs the set-theoretic union of the input geometries.</p>


```csharp
public Geometry Union(IEnumerable<Geometry> geometries)
```
### UpdateAllMsByMs(Polyline, Coordinate2D, double, double, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Updates M-values on all vertices as scaled and offset distances based on existing M-values.</p>


```csharp
public Polyline UpdateAllMsByMs(Polyline polyline, Coordinate2D origin, double scale, double offset, bool ignoreGaps)
```
### UpdateMsByDistance(Polyline, int, int, int, int, double, double, UpdateMMethod, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Updates M-values along the shortest path between the specified vertices. The interpolation ratio is determined by
the input M-values and Euclidean distance along that path.</p>


```csharp
public Polyline UpdateMsByDistance(Polyline polyline, int fromPartIndex, int fromPointIndex, int toPartIndex, int toPointIndex, double fromM, double toM, UpdateMMethod updateMMethod, bool ignoreGaps)
```
### UpdateMsByMs(Polyline, int, int, int, int, double, double, UpdateMMethod)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Updates M-values along the shortest path between the specified vertices. The interpolation ratio is determined by
the existing M-values along that path and the input M-values.</p>


```csharp
public Polyline UpdateMsByMs(Polyline polyline, int fromPartIndex, int fromPointIndex, int toPartIndex, int toPointIndex, double fromM, double toM, UpdateMMethod updateMMethod)
```
### Weed(Multipart, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Generalizes the multipart using a small tolerance based upon either the units of the geometry's spatial reference
or the geometry's bounding box.</p>


```csharp
public Multipart Weed(Multipart multipart, double maxDeviation)
```
### Within(Geometry, Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Returns true if geometry1 is within geometry2.</p>


```csharp
public bool Within(Geometry geometry1, Geometry geometry2)
```


