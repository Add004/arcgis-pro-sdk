# Terrain

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Analyst3D.html">Analyst3D</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.Terrain.yml" sourcestartlinenumber="1">Represents a terrain dataset.</p>


## Object Signature

```csharp
public sealed class Terrain : Dataset, IDisposable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.Terrain.yml" sourcestartlinenumber="1">A terrain is a multiresolution, TIN-based surface built from measurements stored as features in a geodatabase.
They're typically made from lidar, sonar, and photogrammetric sources.
Terrains have participating feature classes and rules. See <xref href="ArcGIS.Core.Data.Analyst3D.TerrainDataSource" data-throw-if-not-resolved="false"></xref> .</p>
<p></p>
<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.Terrain.yml" sourcestartlinenumber="7">Terrain data is organized for fast retrieval. This organization involves the creation of terrain pyramids that are used to
quickly retrieve only the data necessary to construct a surface of the required level of detail (LOD) for a given area of interest (AOI) from the database.
See <xref href="ArcGIS.Core.Data.Analyst3D.TerrainPyramidLevel" data-throw-if-not-resolved="false"></xref>.</p>


## Members

### GetDataSourceCount()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.Terrain.yml" sourcestartlinenumber="1">Gets the number of datasources used in this terrain.  Also see <xref href="ArcGIS.Core.Data.Analyst3D.Terrain.GetDataSources" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int GetDataSourceCount()
```
### GetDataSources()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.Terrain.yml" sourcestartlinenumber="1">Gets the list of <xref href="ArcGIS.Core.Data.Analyst3D.TerrainDataSource" data-throw-if-not-resolved="false"></xref> used in this terrain.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<TerrainDataSource> GetDataSources()
```
### GetDefinition()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.Terrain.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Analyst3D.TerrainDefinition" data-throw-if-not-resolved="false"></xref> of this terrain dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public TerrainDefinition GetDefinition()
```
### GetExtent()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.Terrain.yml" sourcestartlinenumber="1">Gets an <xref href="ArcGIS.Core.Geometry.Envelope" data-throw-if-not-resolved="false"></xref> representing the maximum extent of the data that has been stored in this terrain.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Envelope GetExtent()
```
### GetFeatureDataset()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.Terrain.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.FeatureDataset" data-throw-if-not-resolved="false"></xref> in which this terrain is contained.
This method must be called on the MCT. Use QueuedTask.Run</p>


```csharp
public FeatureDataset GetFeatureDataset()
```
### GetPointCount()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.Terrain.yml" sourcestartlinenumber="1">Gets the number of points in this terrain.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double GetPointCount()
```
### GetPyramidLevelCount()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.Terrain.yml" sourcestartlinenumber="1">Gets the number of pyramid levels in this terrain.  Also see <xref href="ArcGIS.Core.Data.Analyst3D.Terrain.GetPyramidLevels" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int GetPyramidLevelCount()
```
### GetPyramidLevels()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.Terrain.yml" sourcestartlinenumber="1">Gets the pyramid level information for this terrain.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<TerrainPyramidLevel> GetPyramidLevels()
```
### GetTileProperties()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.Terrain.yml" sourcestartlinenumber="1">Gets the tile properties of the terrain.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public TerrainTileProperties GetTileProperties()
```
### IsDirty()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.Terrain.yml" sourcestartlinenumber="1">Gets if the terrain is dirty.  That is, it has been edited since it was last built.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool IsDirty()
```
### IsValid()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.Terrain.yml" sourcestartlinenumber="1">Gets if the terrain is valid.<br>
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool IsValid()
```
### NeedsRebuild()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.Terrain.yml" sourcestartlinenumber="1">Gets if the terrain needs rebuilding.  That is, it has been edited or is invalid since it was last built.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool NeedsRebuild()
```
### Type

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.Terrain.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.DatasetType" data-throw-if-not-resolved="false"></xref> of this terrain dataset.  Returns <xref href="ArcGIS.Core.Data.DatasetType.Terrain" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public override DatasetType Type { get; }
```
### UsesConstrainedDelaunay()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.Terrain.yml" sourcestartlinenumber="1">Gets if the terrain is defined using the Constrained Delaunay triangulation technique.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool UsesConstrainedDelaunay()
```


