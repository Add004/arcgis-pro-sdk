# SectionDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Voxel.html">Voxel</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.SectionDefinition.yml" sourcestartlinenumber="1">Represents the definition of a section. Refer to <xref href="ArcGIS.Desktop.Mapping.VoxelLayer" data-throw-if-not-resolved="false"></xref></p>


## Object Signature

```csharp
public class SectionDefinition
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.SectionDefinition.yml" sourcestartlinenumber="1">A section is a snapshot of data in the voxel that creates a plane. The plane
is defined by a position and a direction defined by a normal unit vector.
Refer to
<a href="https://pro.arcgis.com/en/pro-app/help/mapping/layer-properties/voxel-layer-sections.htm">Voxel layer sections</a></p>


## Members

### SectionDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.SectionDefinition.yml" sourcestartlinenumber="1">Default constructor</p>


```csharp
public SectionDefinition()
```
### CreateHorizontalSectionDefinition()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.SectionDefinition.yml" sourcestartlinenumber="1">Factory method for creating a horizontal section</p>


```csharp
public static SectionDefinition CreateHorizontalSectionDefinition()
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.SectionDefinition.yml" sourcestartlinenumber="1">Gets the section ID.</p>


```csharp
public string ID { get; }
```
### IsVisible

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.SectionDefinition.yml" sourcestartlinenumber="1">Gets and sets whether the section is visible.</p>


```csharp
public bool IsVisible { get; set; }
```
### Layer

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.SectionDefinition.yml" sourcestartlinenumber="1">Gets the voxel layer with which the section is associated.</p>


```csharp
public VoxelLayer Layer { get; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.SectionDefinition.yml" sourcestartlinenumber="1">Gets and sets the section name.</p>


```csharp
public string Name { get; set; }
```
### Normal

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.SectionDefinition.yml" sourcestartlinenumber="1">Gets and sets the section normal.</p>


```csharp
public Coordinate3D Normal { get; set; }
```
### Volume

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.SectionDefinition.yml" sourcestartlinenumber="1">Gets the volume  with which the section is associated.</p>


```csharp
public VoxelVolume Volume { get; }
```
### VoxelPosition

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.SectionDefinition.yml" sourcestartlinenumber="1">Gets and sets the section position in Voxel space.</p>


```csharp
public Coordinate3D VoxelPosition { get; set; }
```


