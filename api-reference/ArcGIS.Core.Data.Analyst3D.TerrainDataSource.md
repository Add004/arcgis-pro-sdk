# TerrainDataSource

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Analyst3D.html">Analyst3D</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TerrainDataSource.yml" sourcestartlinenumber="1">Represents a terrain datasource.  See <xref href="ArcGIS.Core.Data.Analyst3D.Terrain.GetDataSources" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class TerrainDataSource
```


## Members

### AppliesToOverview

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TerrainDataSource.yml" sourcestartlinenumber="1">Gets if the feature class contributes measurements to the coarsest representation of the terrain dataset.</p>


```csharp
public bool AppliesToOverview { get; }
```
### DataSourceName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TerrainDataSource.yml" sourcestartlinenumber="1">Gets the data source name.</p>


```csharp
public string DataSourceName { get; }
```
### Group

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TerrainDataSource.yml" sourcestartlinenumber="1">Gets the group ID.</p>


```csharp
public int Group { get; }
```
### HeightField

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TerrainDataSource.yml" sourcestartlinenumber="1">Gets the height source field.</p>


```csharp
public string HeightField { get; }
```
### IsAnchored

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TerrainDataSource.yml" sourcestartlinenumber="1">Gets if the surface type is anchored.  This only applies if <xref href="ArcGIS.Core.Data.Analyst3D.TerrainDataSource.SurfaceType" data-throw-if-not-resolved="false"></xref> is <xref href="ArcGIS.Core.Data.Analyst3D.TinSurfaceType.MassPoint" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public bool IsAnchored { get; }
```
### IsEmbeded

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TerrainDataSource.yml" sourcestartlinenumber="1">Gets if the surface type is embedded.  This only applies if <xref href="ArcGIS.Core.Data.Analyst3D.TerrainDataSource.SurfaceType" data-throw-if-not-resolved="false"></xref> is <xref href="ArcGIS.Core.Data.Analyst3D.TinSurfaceType.MassPoint" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public bool IsEmbeded { get; }
```
### MaximumResolution

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TerrainDataSource.yml" sourcestartlinenumber="1">Gets the maximum resolution for polyline or polygon surface data.</p>


```csharp
public double MaximumResolution { get; }
```
### MinimumResolution

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TerrainDataSource.yml" sourcestartlinenumber="1">Gets the minimum resolution for polyline or polygon surface data.</p>


```csharp
public double MinimumResolution { get; }
```
### SurfaceType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TerrainDataSource.yml" sourcestartlinenumber="1">Gets the surface type. This defines how the geometry is incorporated into the triangulation for the surface.</p>


```csharp
public TinSurfaceType SurfaceType { get; }
```


