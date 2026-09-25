# SliceDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Voxel.html">Voxel</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.SliceDefinition.yml" sourcestartlinenumber="1">Represents the definition of a Slice. Refer to <xref href="ArcGIS.Desktop.Mapping.VoxelLayer" data-throw-if-not-resolved="false"></xref></p>


## Object Signature

```csharp
public class SliceDefinition
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.SliceDefinition.yml" sourcestartlinenumber="1">A slice is a plane that cuts the voxel volume. Use slices to define an
area of interest within a voxel.</p>


## Members

### SliceDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.SliceDefinition.yml" sourcestartlinenumber="1">Default constructor.</p>


```csharp
public SliceDefinition()
```
### CreateHorizontalSliceDefinition()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.SliceDefinition.yml" sourcestartlinenumber="1">Factory method to create a horizontal slice definition with the normal pre-set.</p>


```csharp
public static SliceDefinition CreateHorizontalSliceDefinition()
```
### Id

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.SliceDefinition.yml" sourcestartlinenumber="1">Gets the slice id.</p>


```csharp
public readonly string Id
```
### IsVisible

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.SliceDefinition.yml" sourcestartlinenumber="1">Gets and sets whether the slice is visible.</p>


```csharp
public bool IsVisible { get; set; }
```
### Layer

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.SliceDefinition.yml" sourcestartlinenumber="1">Gets the voxel layer with which the slice is associated.</p>


```csharp
public VoxelLayer Layer { get; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.SliceDefinition.yml" sourcestartlinenumber="1">Gets and sets the slice name.</p>


```csharp
public string Name { get; set; }
```
### Normal

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.SliceDefinition.yml" sourcestartlinenumber="1">Gets and sets the slice normal.</p>


```csharp
public Coordinate3D Normal { get; set; }
```
### Volume

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.SliceDefinition.yml" sourcestartlinenumber="1">Gets the volume with which the slice is associated.</p>


```csharp
public readonly VoxelVolume Volume
```
### VoxelPosition

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.SliceDefinition.yml" sourcestartlinenumber="1">Gets and sets the slice position in Voxel space.</p>


```csharp
public Coordinate3D VoxelPosition { get; set; }
```


