# TerrainPyramidLevel

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Analyst3D.html">Analyst3D</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TerrainPyramidLevel.yml" sourcestartlinenumber="1">Represents a pyramid level of a <xref href="ArcGIS.Core.Data.Analyst3D.Terrain" data-throw-if-not-resolved="false"></xref>.  See <xref href="ArcGIS.Core.Data.Analyst3D.Terrain.GetPyramidLevels" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class TerrainPyramidLevel
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TerrainPyramidLevel.yml" sourcestartlinenumber="1">Terrain data is organized for fast retrieval. This organization involves the creation of terrain pyramids that are used to
quickly retrieve only the data necessary to construct a surface of the required level of detail (LOD) for a given area of interest (AOI) from the database.</p>


## Members

### ID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TerrainPyramidLevel.yml" sourcestartlinenumber="1">Represents the ID of the pyramid level.</p>


```csharp
public int ID { get; }
```
### MaximumScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TerrainPyramidLevel.yml" sourcestartlinenumber="1">The maximum scale of the pyramid level.</p>


```csharp
public int MaximumScale { get; }
```
### Resolution

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TerrainPyramidLevel.yml" sourcestartlinenumber="1">The resolution of the pyramid level. If the <xref href="ArcGIS.Core.Data.Analyst3D.TerrainDefinition.GetPyramidType" data-throw-if-not-resolved="false"></xref> is <xref href="ArcGIS.Core.Data.Analyst3D.TerrainPyramidType.ZTolerance" data-throw-if-not-resolved="false"></xref>
this is the Z tolerance value.  If the PyramidType is <xref href="ArcGIS.Core.Data.Analyst3D.TerrainPyramidType.WindowSize" data-throw-if-not-resolved="false"></xref> this value is the window size.</p>


```csharp
public double Resolution { get; }
```


