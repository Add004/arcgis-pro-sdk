# LockedSectionDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Voxel.html">Voxel</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.LockedSectionDefinition.yml" sourcestartlinenumber="1">Represents the definition of a locked section. Refer to <xref href="ArcGIS.Desktop.Mapping.VoxelLayer" data-throw-if-not-resolved="false"></xref></p>


## Object Signature

```csharp
public class LockedSectionDefinition
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.LockedSectionDefinition.yml" sourcestartlinenumber="1">A locked section is a &quot;dynamic&quot; section that has been locked or &quot;tied&quot; to a
specific voxel variable. Once locked, the section position and orientation can no
longer be changed and are not updated if the selected voxel variable profile is
changed. Locked sections are useful for comparing sections for different variable
profiles. Refer to
<a href="https://pro.arcgis.com/en/pro-app/help/mapping/layer-properties/voxel-layer-sections.htm">Voxel layer sections</a></p>


## Members

### ID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.LockedSectionDefinition.yml" sourcestartlinenumber="1">Gets the locked section ID.</p>


```csharp
public int ID { get; }
```
### IsExpanded

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.LockedSectionDefinition.yml" sourcestartlinenumber="1">Gets and sets whether the section is expanded or collapsed on the TOC.</p>


```csharp
public bool IsExpanded { get; set; }
```
### IsVisible

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.LockedSectionDefinition.yml" sourcestartlinenumber="1">Gets and sets whether the section is visible.</p>


```csharp
public bool IsVisible { get; set; }
```
### Layer

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.LockedSectionDefinition.yml" sourcestartlinenumber="1">Gets the voxel layer with which the locked section is associated.</p>


```csharp
public VoxelLayer Layer { get; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.LockedSectionDefinition.yml" sourcestartlinenumber="1">Gets and sets the section name.</p>


```csharp
public string Name { get; set; }
```
### Normal

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.LockedSectionDefinition.yml" sourcestartlinenumber="1">Gets the section normal.</p>


```csharp
public Coordinate3D Normal { get; }
```
### VariableName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.LockedSectionDefinition.yml" sourcestartlinenumber="1">Gets the variable name that this section is associated with.</p>


```csharp
public string VariableName { get; }
```
### VoxelPosition

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.LockedSectionDefinition.yml" sourcestartlinenumber="1">Gets the section position in Voxel space.</p>


```csharp
public Coordinate3D VoxelPosition { get; }
```


