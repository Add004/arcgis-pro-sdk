# VoxelVariableProfile

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Voxel.html">Voxel</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.VoxelVariableProfile.yml" sourcestartlinenumber="1">Represents a variable for a value stored within a voxel cube.</p>


## Object Signature

```csharp
public class VoxelVariableProfile
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.VoxelVariableProfile.yml" sourcestartlinenumber="1">Voxel layers are structured in dimensional regularly gridded cubes or &quot;voxels&quot;
which store one or more variables. The variables can store values for
either quantitative continuous data or qualitative discrete data. Temperature
measurements are represented as continuous data. Other data, such as lithography
classes of an underground model, are discrete. Refer to <xref href="ArcGIS.Desktop.Mapping.Voxel.VoxelVariableProfile.DataType" data-throw-if-not-resolved="false"></xref></p>


## Members

### CanCreateIsosurface

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.VoxelVariableProfile.yml" sourcestartlinenumber="1">Gets whether an isosurface can be added to this variable profile.</p>


```csharp
public bool CanCreateIsosurface { get; }
```
### CreateIsosurface(IsosurfaceDefinition)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.VoxelVariableProfile.yml" sourcestartlinenumber="1">Create an isosurface for the variable profile.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void CreateIsosurface(IsosurfaceDefinition isosurfaceDef)
```
### DataType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.VoxelVariableProfile.yml" sourcestartlinenumber="1">Gets the variable profile's data type. Data can be continuous or discrete.</p>


```csharp
public VoxelVariableDataType DataType { get; }
```
### DataUnit

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.VoxelVariableProfile.yml" sourcestartlinenumber="1">Gets the variable data unit.</p>


```csharp
public readonly string DataUnit
```
### DeleteIsosurface(IsosurfaceDefinition)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.VoxelVariableProfile.yml" sourcestartlinenumber="1">Delete the specified isosurface. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void DeleteIsosurface(IsosurfaceDefinition isosurfaceDef)
```
### DeleteIsosurfaces(IEnumerable&lt;IsosurfaceDefinition&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.VoxelVariableProfile.yml" sourcestartlinenumber="1">Delete the specified collection of isosurfaces.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void DeleteIsosurfaces(IEnumerable<IsosurfaceDefinition> isosurfaceDefs)
```
### Description

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.VoxelVariableProfile.yml" sourcestartlinenumber="1">Gets the variable profile's description.</p>


```csharp
public string Description { get; }
```
### GetIsosurfaceColor(double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.VoxelVariableProfile.yml" sourcestartlinenumber="1">Gets the corresponding isosurface color for the specific value.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMColor GetIsosurfaceColor(double value)
```
### GetIsosurfaces()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.VoxelVariableProfile.yml" sourcestartlinenumber="1">Gets the collection of isosurfaces</p>


```csharp
public IList<IsosurfaceDefinition> GetIsosurfaces()
```
### MaxNumberOfIsosurfaces

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.VoxelVariableProfile.yml" sourcestartlinenumber="1">Gets the maximum number of isosurface.</p>


```csharp
public int MaxNumberOfIsosurfaces { get; }
```
### Renderer

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.VoxelVariableProfile.yml" sourcestartlinenumber="1">Gets the variable profile renderer.</p>


```csharp
public CIMVoxelRenderer Renderer { get; }
```
### SetRenderer(CIMVoxelRenderer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.VoxelVariableProfile.yml" sourcestartlinenumber="1">Sets the variable profile's renderer object. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetRenderer(CIMVoxelRenderer renderer)
```
### Statistics

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.VoxelVariableProfile.yml" sourcestartlinenumber="1">Gets the variable statistics.</p>


```csharp
public VoxelVariableStatistics Statistics { get; }
```
### UpdateIsosurface(IsosurfaceDefinition)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.VoxelVariableProfile.yml" sourcestartlinenumber="1">Update the specified isosurface. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void UpdateIsosurface(IsosurfaceDefinition isosurfaceDef)
```
### Variable

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.VoxelVariableProfile.yml" sourcestartlinenumber="1">Gets the variable profile variable name.</p>


```csharp
public string Variable { get; }
```
### Volume

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.VoxelVariableProfile.yml" sourcestartlinenumber="1">Gets the volume that this variable profile belong to.</p>


```csharp
public VoxelVolume Volume { get; }
```


