# GeodesicEllipseParameter

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.GeodesicEllipseParameter.yml" sourcestartlinenumber="1">Options for creating a geodesic ellipse with the <xref href="ArcGIS.Core.Geometry.GeometryEngine.GeodesicEllipse(ArcGIS.Core.Geometry.GeodesicEllipseParameter%2cArcGIS.Core.Geometry.SpatialReference)" data-throw-if-not-resolved="false"></xref> function.</p>


## Object Signature

```csharp
public sealed class GeodesicEllipseParameter
```


## Members

### GeodesicEllipseParameter()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.GeodesicEllipseParameter.yml" sourcestartlinenumber="1">Createa an empty GeodesicEllipseParameter object for use in the <xref href="ArcGIS.Core.Geometry.GeometryEngine.GeodesicEllipse(ArcGIS.Core.Geometry.GeodesicEllipseParameter%2cArcGIS.Core.Geometry.SpatialReference)" data-throw-if-not-resolved="false"></xref> method.</p>


```csharp
public GeodesicEllipseParameter()
```
### AxisDirection

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeodesicEllipseParameter.yml" sourcestartlinenumber="1">Gets or sets the direction of the major axis of the ellipse as an angle in degrees.</p>


```csharp
public double AxisDirection { get; set; }
```
### Center

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeodesicEllipseParameter.yml" sourcestartlinenumber="1">Gets or sets the center of the ellipse in the coordinates of the spatial reference.</p>


```csharp
public Coordinate2D Center { get; set; }
```
### LinearUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeodesicEllipseParameter.yml" sourcestartlinenumber="1">Gets or sets the linear unit of the SemiAxis1Length, SemiAxis2Length. Default is meters.</p>


```csharp
public LinearUnit LinearUnit { get; set; }
```
### OutGeometryType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeodesicEllipseParameter.yml" sourcestartlinenumber="1">Gets or sets the type of geometry that will be created.  Only multipoint, polyline and polygon are supported.</p>


```csharp
public GeometryType OutGeometryType { get; set; }
```
### SemiAxis1Length

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeodesicEllipseParameter.yml" sourcestartlinenumber="1">Gets or sets the length of the first semi axis.</p>


```csharp
public double SemiAxis1Length { get; set; }
```
### SemiAxis2Length

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeodesicEllipseParameter.yml" sourcestartlinenumber="1">Gets or sets the length of the second semi axis.</p>


```csharp
public double SemiAxis2Length { get; set; }
```
### VertexCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeodesicEllipseParameter.yml" sourcestartlinenumber="1">Gets or sets the number of vertices in the ellipse before projection to the spatial reference.</p>


```csharp
public uint VertexCount { get; set; }
```


