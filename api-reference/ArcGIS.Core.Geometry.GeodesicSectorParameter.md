# GeodesicSectorParameter

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.GeodesicSectorParameter.yml" sourcestartlinenumber="1">Options for creating a geodesic sector with the <xref href="ArcGIS.Core.Geometry.GeometryEngine.GeodesicSector(ArcGIS.Core.Geometry.GeodesicSectorParameter%2cArcGIS.Core.Geometry.SpatialReference)" data-throw-if-not-resolved="false"></xref> function.</p>


## Object Signature

```csharp
public sealed class GeodesicSectorParameter
```


## Members

### GeodesicSectorParameter()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.GeodesicSectorParameter.yml" sourcestartlinenumber="1">Create an empty GeodesicSectorParameter object for use in the
<xref href="ArcGIS.Core.Geometry.GeometryEngine.GeodesicSector(ArcGIS.Core.Geometry.GeodesicSectorParameter%2cArcGIS.Core.Geometry.SpatialReference)" data-throw-if-not-resolved="false"></xref> method.</p>


```csharp
public GeodesicSectorParameter()
```
### ArcVertexCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeodesicSectorParameter.yml" sourcestartlinenumber="1">Gets or sets the number of vertices in the arc.</p>


```csharp
public uint ArcVertexCount { get; set; }
```
### AxisDirection

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeodesicSectorParameter.yml" sourcestartlinenumber="1">Gets or sets the direction of the major axis of the arc's ellipse as an angle in degrees.</p>


```csharp
public double AxisDirection { get; set; }
```
### Center

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeodesicSectorParameter.yml" sourcestartlinenumber="1">Gets or sets the center of the sector in the coordinates of the spatial reference.</p>


```csharp
public Coordinate2D Center { get; set; }
```
### LinearUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeodesicSectorParameter.yml" sourcestartlinenumber="1">Gets or sets the linear unit of the SemiAxis1Length, SemiAxis2Length.  Default is meters.</p>


```csharp
public LinearUnit LinearUnit { get; set; }
```
### OutGeometryType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeodesicSectorParameter.yml" sourcestartlinenumber="1">Gets or sets the type of geometry that will be created. Only multipoint, polyline and polygon are supported.</p>


```csharp
public GeometryType OutGeometryType { get; set; }
```
### RadiusVertexCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeodesicSectorParameter.yml" sourcestartlinenumber="1">Gets or sets the number of vertices in the radius.</p>


```csharp
public uint RadiusVertexCount { get; set; }
```
### SectorAngle

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeodesicSectorParameter.yml" sourcestartlinenumber="1">Gets or sets the sweep angle of the sector in degrees.</p>


```csharp
public double SectorAngle { get; set; }
```
### SemiAxis1Length

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeodesicSectorParameter.yml" sourcestartlinenumber="1">Gets or sets the length of the first semi axis.</p>


```csharp
public double SemiAxis1Length { get; set; }
```
### SemiAxis2Length

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeodesicSectorParameter.yml" sourcestartlinenumber="1">Gets or sets the length of the second semi axis.</p>


```csharp
public double SemiAxis2Length { get; set; }
```
### StartDirection

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeodesicSectorParameter.yml" sourcestartlinenumber="1">Gets or sets the direction of starting radius of the sector as an angle in degrees.</p>


```csharp
public double StartDirection { get; set; }
```


