# VoxelVolume

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Voxel.html">Voxel</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.VoxelVolume.yml" sourcestartlinenumber="1">Represents the voxel volume associated with a particular voxel variable profile</p>


## Object Signature

```csharp
public class VoxelVolume
```


## Members

### CanLockSection(SectionDefinition)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.VoxelVolume.yml" sourcestartlinenumber="1">Determines whether a section can be locked. Sections are locked to the current variable profile.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool CanLockSection(SectionDefinition sectionDef)
```
### CreateSection(SectionDefinition)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.VoxelVolume.yml" sourcestartlinenumber="1">Create a (dynamic) section. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void CreateSection(SectionDefinition sectionDef)
```
### CreateSlice(SliceDefinition)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.VoxelVolume.yml" sourcestartlinenumber="1">Create a slice. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void CreateSlice(SliceDefinition sliceDef)
```
### DeleteSection(SectionDefinition)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.VoxelVolume.yml" sourcestartlinenumber="1">Delete the specified section. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void DeleteSection(SectionDefinition sectionDef)
```
### DeleteSlice(SliceDefinition)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.VoxelVolume.yml" sourcestartlinenumber="1">Deletes the specified slice. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void DeleteSlice(SliceDefinition sliceDef)
```
### GetPositionRange(Coordinate3D, Coordinate3D)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.VoxelVolume.yml" sourcestartlinenumber="1">Gets the range of positions in voxel coordinates.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Tuple<Coordinate3D, Coordinate3D> GetPositionRange(Coordinate3D point, Coordinate3D normal)
```
### GetSections()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.VoxelVolume.yml" sourcestartlinenumber="1">Gets the collection of (dynamic) sections</p>


```csharp
public IList<SectionDefinition> GetSections()
```
### GetSlices()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.VoxelVolume.yml" sourcestartlinenumber="1">Gets the collection of slices</p>


```csharp
public IList<SliceDefinition> GetSlices()
```
### GetVariableProfile(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.VoxelVolume.yml" sourcestartlinenumber="1">Get the variable profile with the given name.</p>


```csharp
public VoxelVariableProfile GetVariableProfile(string variable)
```
### GetVariableProfiles()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.VoxelVolume.yml" sourcestartlinenumber="1">Gets the collection of variable profiles.</p>


```csharp
public IList<VoxelVariableProfile> GetVariableProfiles()
```
### GetVolumeSize()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.VoxelVolume.yml" sourcestartlinenumber="1">Gets the volume size in voxel coordinates.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public (double X, double Y, double Z) GetVolumeSize()
```
### Id

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.VoxelVolume.yml" sourcestartlinenumber="1">Gets the ID of the volume</p>


```csharp
public readonly int Id
```
### LockSection(SectionDefinition)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.VoxelVolume.yml" sourcestartlinenumber="1">Locks the specified section to the currently selected variable profile.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void LockSection(SectionDefinition sectionDef)
```
### UpdateSection(SectionDefinition)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.VoxelVolume.yml" sourcestartlinenumber="1">Updates the section identified by the input <xref href="ArcGIS.Desktop.Mapping.Voxel.SectionDefinition" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void UpdateSection(SectionDefinition sectionDef)
```
### UpdateSlice(SliceDefinition)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.VoxelVolume.yml" sourcestartlinenumber="1">Updates the slice identified by the input <xref href="ArcGIS.Desktop.Mapping.Voxel.SliceDefinition" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void UpdateSlice(SliceDefinition sliceDef)
```
### VoxelCoordinateToWorld(Coordinate3D)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.VoxelVolume.yml" sourcestartlinenumber="1">Convert a position from voxel space to world or &quot;layer&quot; space.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Coordinate3D VoxelCoordinateToWorld(Coordinate3D voxelLocation)
```
### VoxelNormalToWorld(Coordinate3D)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.VoxelVolume.yml" sourcestartlinenumber="1">Convert a vector normal from voxel space to world or &quot;layer&quot; space.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Coordinate3D VoxelNormalToWorld(Coordinate3D voxelNormalVector)
```
### WorldCoordinateToVoxel(Coordinate3D)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.VoxelVolume.yml" sourcestartlinenumber="1">Convert a position from world or &quot;layer&quot; space to voxel space.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Coordinate3D WorldCoordinateToVoxel(Coordinate3D worldLocation)
```
### WorldNormalToVoxel(Coordinate3D)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.VoxelVolume.yml" sourcestartlinenumber="1">Convert a vector normal from world or &quot;layer&quot; space to voxel space.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Coordinate3D WorldNormalToVoxel(Coordinate3D worldNormalVector)
```


