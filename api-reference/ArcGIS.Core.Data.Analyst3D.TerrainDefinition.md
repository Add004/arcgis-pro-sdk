# TerrainDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Analyst3D.html">Analyst3D</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TerrainDefinition.yml" sourcestartlinenumber="1">Represents the properties of a <xref href="ArcGIS.Core.Data.Analyst3D.Terrain" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class TerrainDefinition : Definition, IDisposable
```


## Members

### DatasetType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TerrainDefinition.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.DatasetType" data-throw-if-not-resolved="false"></xref> of the terrain dataset.  Returns <xref href="ArcGIS.Core.Data.DatasetType.Terrain" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public override DatasetType DatasetType { get; }
```
### GetExtent()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TerrainDefinition.yml" sourcestartlinenumber="1">Gets an <xref href="ArcGIS.Core.Geometry.Envelope" data-throw-if-not-resolved="false"></xref> representing the maximum extent of the data that is contained by the <xref href="ArcGIS.Core.Data.Analyst3D.Terrain" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Envelope GetExtent()
```
### GetFeatureClassNames()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TerrainDefinition.yml" sourcestartlinenumber="1">Gets the names of all the <xref href="ArcGIS.Core.Data.FeatureClass" data-throw-if-not-resolved="false"></xref>s that participate in the <xref href="ArcGIS.Core.Data.Analyst3D.Terrain" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<string> GetFeatureClassNames()
```
### GetPyramidType()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TerrainDefinition.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Analyst3D.TerrainPyramidType" data-throw-if-not-resolved="false"></xref> of the <xref href="ArcGIS.Core.Data.Analyst3D.Terrain" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public TerrainPyramidType GetPyramidType()
```
### GetPyramidWindowSizeProperties()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TerrainDefinition.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Analyst3D.TerrainWindowSizeProperties" data-throw-if-not-resolved="false"></xref> of the <xref href="ArcGIS.Core.Data.Analyst3D.Terrain" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public TerrainWindowSizeProperties GetPyramidWindowSizeProperties()
```
### GetSpatialReference()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TerrainDefinition.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Geometry.SpatialReference" data-throw-if-not-resolved="false"></xref> for the <xref href="ArcGIS.Core.Data.Analyst3D.Terrain" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SpatialReference GetSpatialReference()
```
### GetTileSize()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TerrainDefinition.yml" sourcestartlinenumber="1">Gets the tile size for the <xref href="ArcGIS.Core.Data.Analyst3D.Terrain" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double GetTileSize()
```


