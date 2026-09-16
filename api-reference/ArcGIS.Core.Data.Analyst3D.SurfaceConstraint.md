# SurfaceConstraint

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Analyst3D.html">Analyst3D</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.SurfaceConstraint.yml" sourcestartlinenumber="1">Represents a surface constraint in a LAS dataset.  See <xref href="ArcGIS.Core.Data.Analyst3D.LasDataset.GetSurfaceConstraints" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class SurfaceConstraint
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.SurfaceConstraint.yml" sourcestartlinenumber="1">Surface constraints are features whose geometry capture or define the characteristics of the surface.
Breaklines, water polygons, or area clipping boundaries are all examples of surface constraints.
Surface constraints can be feature classes or shapefiles.</p>


## Members

### DataSourceName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.SurfaceConstraint.yml" sourcestartlinenumber="1">Gets the data source name.</p>


```csharp
public string DataSourceName { get; }
```
### HeightField

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.SurfaceConstraint.yml" sourcestartlinenumber="1">Gets the height source field.</p>


```csharp
public string HeightField { get; }
```
### SurfaceType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.SurfaceConstraint.yml" sourcestartlinenumber="1">Gets the surface type. This defines how the geometry is incorporated into the triangulation for the surface.</p>


```csharp
public TinSurfaceType SurfaceType { get; }
```
### TagField

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.SurfaceConstraint.yml" sourcestartlinenumber="1">Gets the tag source field.</p>


```csharp
public string TagField { get; }
```
### WorkspacePath

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.SurfaceConstraint.yml" sourcestartlinenumber="1">Gets the workspace path.</p>


```csharp
public string WorkspacePath { get; }
```


