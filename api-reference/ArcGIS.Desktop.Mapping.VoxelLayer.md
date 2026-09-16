# VoxelLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">A voxel layer represents multidimensional spatial and temporal
information in a 3D volumetric visualization.</p>


## Object Signature

```csharp
public sealed class VoxelLayer : Layer, IMetadataInfo, IMetadataSource
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Use voxel layers to visualize atmospheric or oceanic data, a geological
underground model, or space-time cubes. <br>Voxel layers are sourced from
volumetric data stored using
<a href="https://pro.arcgis.com/en/pro-app/help/data/multidimensional/what-is-netcdf-data.htm">NetCDF</a>.<br>
Voxel layers are supported in Local Scenes only. Refer to <xref href="ArcGIS.Desktop.Mapping.MapView.ViewingMode" data-throw-if-not-resolved="false"></xref>.
Use of Voxel layers requires an <b>Advanced</b> licensing level</p>


## Members

### AutoShowExploreDockPane

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Gets and sets whether the voxel exploration dock pane should activate automatically
after an explorable voxel asset (surface, section, or slice) is created.</p>


```csharp
public bool AutoShowExploreDockPane { get; set; }
```
### CanUnlockSection(LockedSectionDefinition)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Determine whether a section can be unlocked.</p>


```csharp
public bool CanUnlockSection(LockedSectionDefinition lockedSectionDef)
```
### CartographicOffset

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Gets the cartographic offset. Value is specified in meters.</p>


```csharp
public double CartographicOffset { get; }
```
### DeleteSection(LockedSectionDefinition)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Delete the specified locked section. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void DeleteSection(LockedSectionDefinition lockedSectionDef)
```
### DiffuseLighting

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Gets the diffused lighting value.</p>


```csharp
public double DiffuseLighting { get; }
```
### GetDataSourceType()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Gets the data source type.</p>


```csharp
public SceneLayerDataSourceType GetDataSourceType()
```
### GetLockedSections()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Gets the collection of locked sections</p>


```csharp
public IList<LockedSectionDefinition> GetLockedSections()
```
### GetNormal(double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Gets the normal unit vector for the provided orientation and tilt.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Coordinate3D GetNormal(double orientation, double tilt)
```
### GetOrientationAndTilt(Coordinate3D)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Gets the orientation and tilt in degrees from the input normal unit vector.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Tuple<double, double> GetOrientationAndTilt(Coordinate3D normal)
```
### GetUniqueTimes()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Gets the collection of unique times.</p>


```csharp
public IList<DateTime> GetUniqueTimes()
```
### GetVariableProfile(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Finds a variable profile via variable name.</p>


```csharp
public VoxelVariableProfile GetVariableProfile(string variableName)
```
### GetVariableProfiles()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Gets the collection of variable profiles.</p>


```csharp
public IList<VoxelVariableProfile> GetVariableProfiles()
```
### GetVolumes()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Gets the collection of volumes.</p>


```csharp
public IList<VoxelVolume> GetVolumes()
```
### IsDiffuseLightingEnabled

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Gets whether diffuse lighting is enabled.</p>


```csharp
public bool IsDiffuseLightingEnabled { get; }
```
### IsIsosurfaceContainerExpanded

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Gets whether the isosurface container appears expanded.</p>


```csharp
public bool IsIsosurfaceContainerExpanded { get; }
```
### IsIsosurfaceContainerVisible

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Gets the isosurface container visibility.</p>


```csharp
public bool IsIsosurfaceContainerVisible { get; }
```
### IsLockedSectionContainerExpanded

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Gets whether the locked section container appears expanded.</p>


```csharp
public bool IsLockedSectionContainerExpanded { get; }
```
### IsLockedSectionContainerVisible

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Gets the locked section container visibility.</p>


```csharp
public bool IsLockedSectionContainerVisible { get; }
```
### IsSectionContainerExpanded

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Gets whether the section container appears expanded.</p>


```csharp
public bool IsSectionContainerExpanded { get; }
```
### IsSectionContainerVisible

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Gets the section container visibility.</p>


```csharp
public bool IsSectionContainerVisible { get; }
```
### IsSliceContainerExpanded

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Gets whether the slice container appears expanded.</p>


```csharp
public bool IsSliceContainerExpanded { get; }
```
### IsSliceContainerVisible

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Gets the slice container visibility.</p>


```csharp
public bool IsSliceContainerVisible { get; }
```
### IsSnappable

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Gets whether feature snapping is enabled</p>


```csharp
public bool IsSnappable { get; }
```
### IsSpecularLightingEnabled

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Gets whether specular lighting is enabled.</p>


```csharp
public bool IsSpecularLightingEnabled { get; }
```
### IsSurfaceContainerExpanded

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Gets whether the surface container appears expanded.</p>


```csharp
public bool IsSurfaceContainerExpanded { get; }
```
### SelectedVariableProfile

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Gets the currently selected variable profile.</p>


```csharp
public VoxelVariableProfile SelectedVariableProfile { get; }
```
### SelectedVolume

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Gets the currently selected volume.</p>


```csharp
public VoxelVolume SelectedVolume { get; }
```
### SetCartographicOffset(double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Sets the cartographic offset. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetCartographicOffset(double offsetInMeters)
```
### SetDiffuseLighting(double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Sets the Diffuse lighting value. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDiffuseLighting(double value)
```
### SetDiffuseLightingEnabled(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Enables/disables Diffuse lighting. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDiffuseLightingEnabled(bool enabled)
```
### SetIsosurfaceContainerExpanded(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Sets the isosurface container expanded or collapsed
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetIsosurfaceContainerExpanded(bool isExpanded)
```
### SetIsosurfaceContainerVisibility(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Sets the isosurface container visibility.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetIsosurfaceContainerVisibility(bool isVisible)
```
### SetLockedSectionContainerExpanded(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Sets the locked section container expanded or collapsed.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetLockedSectionContainerExpanded(bool isExpanded)
```
### SetLockedSectionContainerVisibility(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Sets the locked section container visibility.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetLockedSectionContainerVisibility(bool isVisible)
```
### SetSectionContainerExpanded(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Sets the section container expanded or collapsed.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetSectionContainerExpanded(bool isExpanded)
```
### SetSectionContainerVisibility(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Sets the section container visibility.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetSectionContainerVisibility(bool isVisible)
```
### SetSelectedVariableProfile(VoxelVariableProfile)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Sets the selected variable profile. The selected variable profile controls the renderer
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetSelectedVariableProfile(VoxelVariableProfile variableProfile)
```
### SetSliceContainerExpanded(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Sets the slice container expanded or collapsed.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetSliceContainerExpanded(bool isExpanded)
```
### SetSliceContainerVisibility(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Sets the slice container visibility.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetSliceContainerVisibility(bool isVisible)
```
### SetSnappable(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Enables or disables snapping on the voxel layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetSnappable(bool isSnappable)
```
### SetSpecularLighting(double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Sets the specular lighting value. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetSpecularLighting(double value)
```
### SetSpecularLightingEnabled(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Enables/disables specular lighting. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetSpecularLightingEnabled(bool enabled)
```
### SetSurfaceContainerExpanded(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Sets the surface container expanded or collapsed
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetSurfaceContainerExpanded(bool isExpanded)
```
### SetVerticalExaggeration(double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Sets the vertical exaggeration. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetVerticalExaggeration(double value)
```
### SetVisualization(VoxelVisualization)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Sets the visualization mode.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetVisualization(VoxelVisualization visualization)
```
### SpecularLighting

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Gets the specular lighting value.</p>


```csharp
public double SpecularLighting { get; }
```
### UnlockSection(LockedSectionDefinition)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Unlocks the specified section. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void UnlockSection(LockedSectionDefinition lockedSectionDef)
```
### UpdateSection(LockedSectionDefinition)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Update the specified locked section. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void UpdateSection(LockedSectionDefinition lockedSectionDef)
```
### VerticalExaggeration

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Gets the vertical exaggeration.</p>


```csharp
public double VerticalExaggeration { get; }
```
### Visualization

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.VoxelLayer.yml" sourcestartlinenumber="1">Gets the voxel visualization mode.</p>


```csharp
public VoxelVisualization Visualization { get; }
```


