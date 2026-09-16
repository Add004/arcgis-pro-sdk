# TerrainWindowSizeProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Analyst3D.html">Analyst3D</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TerrainWindowSizeProperties.yml" sourcestartlinenumber="1">Represents the window size properties of the terrain. See <xref href="ArcGIS.Core.Data.Analyst3D.TerrainDefinition.GetPyramidWindowSizeProperties" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class TerrainWindowSizeProperties
```


## Members

### Method

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TerrainWindowSizeProperties.yml" sourcestartlinenumber="1">Gets the window size method.</p>


```csharp
public TerrainWindowSizeMethod Method { get; }
```
### ZThreshold

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TerrainWindowSizeProperties.yml" sourcestartlinenumber="1">Gets the secondary thinning threshold.</p>


```csharp
public double ZThreshold { get; }
```
### ZThresholdStrategy

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TerrainWindowSizeProperties.yml" sourcestartlinenumber="1">Gets the secondary thinning strategy method. Applies if the <xref href="ArcGIS.Core.Data.Analyst3D.TerrainWindowSizeProperties.ZThreshold" data-throw-if-not-resolved="false"></xref> is greater than 0.</p>


```csharp
public TerrainZThresholdStrategy ZThresholdStrategy { get; }
```


