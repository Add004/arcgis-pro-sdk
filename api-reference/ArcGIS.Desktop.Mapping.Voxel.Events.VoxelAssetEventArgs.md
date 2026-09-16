# VoxelAssetEventArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Voxel.html">Voxel</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Voxel.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.Events.VoxelAssetEventArgs.yml" sourcestartlinenumber="1">Provides data for the <xref href="ArcGIS.Desktop.Mapping.Voxel.Events.VoxelAssetChangedEvent" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class VoxelAssetEventArgs : EventArgs
```


## Members

### AssetType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.Events.VoxelAssetEventArgs.yml" sourcestartlinenumber="1">Gets the type of voxel asset associated with the change.</p>


```csharp
public VoxelAssetEventArgs.VoxelAssetType AssetType { get; }
```
### ChangeType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.Events.VoxelAssetEventArgs.yml" sourcestartlinenumber="1">Gets the type of change to the voxel asset.</p>


```csharp
public VoxelAssetEventArgs.VoxelAssetChangeType ChangeType { get; }
```
### Isosurfaces

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.Events.VoxelAssetEventArgs.yml" sourcestartlinenumber="1">Gets the list of 0 or more isosurfaces changed in the event.</p>


```csharp
public IReadOnlyList<IsosurfaceDefinition> Isosurfaces { get; }
```
### LockedSections

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.Events.VoxelAssetEventArgs.yml" sourcestartlinenumber="1">Gets the list of 0 or more locked sections changed in the event.</p>


```csharp
public IReadOnlyList<LockedSectionDefinition> LockedSections { get; }
```
### Sections

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.Events.VoxelAssetEventArgs.yml" sourcestartlinenumber="1">Gets the list of 0 or more sections changed in the event.</p>


```csharp
public IReadOnlyList<SectionDefinition> Sections { get; }
```
### Slices

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.Events.VoxelAssetEventArgs.yml" sourcestartlinenumber="1">Gets the list of 0 or more slices changed in the event.</p>


```csharp
public IReadOnlyList<SliceDefinition> Slices { get; }
```


