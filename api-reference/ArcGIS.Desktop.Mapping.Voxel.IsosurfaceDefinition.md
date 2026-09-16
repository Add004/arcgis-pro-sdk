# IsosurfaceDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Voxel.html">Voxel</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.IsosurfaceDefinition.yml" sourcestartlinenumber="1">Represents the definition of an Isosurface. Refer to <xref href="ArcGIS.Desktop.Mapping.VoxelLayer" data-throw-if-not-resolved="false"></xref></p>


## Object Signature

```csharp
public class IsosurfaceDefinition
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.IsosurfaceDefinition.yml" sourcestartlinenumber="1">An isosurface is a surface created for a specific <xref href="ArcGIS.Desktop.Mapping.Voxel.VoxelVariableProfile?text=voxel+variable+profile" data-throw-if-not-resolved="false"></xref>
where every voxel has the same value.</p>


## Members

### IsosurfaceDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.IsosurfaceDefinition.yml" sourcestartlinenumber="1">Default constructor</p>


```csharp
public IsosurfaceDefinition()
```
### Color

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.IsosurfaceDefinition.yml" sourcestartlinenumber="1">Gets and sets the isosurface color.</p>


```csharp
public CIMColor Color { get; set; }
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.IsosurfaceDefinition.yml" sourcestartlinenumber="1">Gets the isosurface ID.</p>


```csharp
public string ID { get; }
```
### IsCustomColor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.IsosurfaceDefinition.yml" sourcestartlinenumber="1">Gets and sets whether the color is a custom color.</p>


```csharp
public bool IsCustomColor { get; set; }
```
### IsVisible

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.IsosurfaceDefinition.yml" sourcestartlinenumber="1">Gets and sets whether the isosurface is visible.</p>


```csharp
public bool IsVisible { get; set; }
```
### Layer

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.IsosurfaceDefinition.yml" sourcestartlinenumber="1">Gets the voxel layer with which the isosurface is associated.</p>


```csharp
public VoxelLayer Layer { get; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.IsosurfaceDefinition.yml" sourcestartlinenumber="1">Gets and sets the isosurface name.</p>


```csharp
public string Name { get; set; }
```
### Value

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.IsosurfaceDefinition.yml" sourcestartlinenumber="1">Gets and sets the isosurface value.</p>


```csharp
public double? Value { get; set; }
```


