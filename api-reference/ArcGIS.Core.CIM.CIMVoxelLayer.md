# CIMVoxelLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelLayer.yml" sourcestartlinenumber="1">Represents a voxel layer.</p>


## Object Signature

```csharp
public class CIMVoxelLayer : CIMBaseLayer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMVoxelLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelLayer.yml" sourcestartlinenumber="1">Represents a voxel layer.</p>


```csharp
public CIMVoxelLayer()
```
### Alignment

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelLayer.yml" sourcestartlinenumber="1">Gets or sets the voxel alignment.</p>


```csharp
public VoxelAlignment Alignment { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMVoxelLayer.</p>


```csharp
public CIMVoxelLayer Clone()
```
### DataConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelLayer.yml" sourcestartlinenumber="1">Gets or sets the data connection.</p>


```csharp
public CIMDataConnection DataConnection { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMVoxelLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMVoxelLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### IsosurfaceContainerExpanded

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the isosurface container is expanded in the contents pane.</p>


```csharp
public bool IsosurfaceContainerExpanded { get; set; }
```
### IsosurfaceContainerVisible

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the isosurface container is visible.</p>


```csharp
public bool IsosurfaceContainerVisible { get; set; }
```
### Lighting

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelLayer.yml" sourcestartlinenumber="1">Gets or sets the lighting.</p>


```csharp
public CIMVoxelLighting Lighting { get; set; }
```
### Optimization

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelLayer.yml" sourcestartlinenumber="1">Gets or sets the voxel layer optimization.</p>


```csharp
public VoxelLayerOptimization Optimization { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SectionContainerExpanded

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this voxel section container is expanded in the contents pane.</p>


```csharp
public bool SectionContainerExpanded { get; set; }
```
### SectionContainerVisible

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the voxel section container is visible.</p>


```csharp
public bool SectionContainerVisible { get; set; }
```
### SelectedVariable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelLayer.yml" sourcestartlinenumber="1">Gets or sets the selected variable.</p>


```csharp
public string SelectedVariable { get; set; }
```
### SliceContainerExpanded

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this voxel slice container is expanded in the contents pane.</p>


```csharp
public bool SliceContainerExpanded { get; set; }
```
### SliceContainerVisible

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the voxel slice container is visible.</p>


```csharp
public bool SliceContainerVisible { get; set; }
```
### Snappable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this layer participates in snapping in the editor.</p>


```csharp
public bool Snappable { get; set; }
```
### StaticSectionContainerExpanded

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this voxel static section container is expanded in the contents pane.</p>


```csharp
public bool StaticSectionContainerExpanded { get; set; }
```
### StaticSectionContainerVisible

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the voxel static section container is visible.</p>


```csharp
public bool StaticSectionContainerVisible { get; set; }
```
### StaticSections

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelLayer.yml" sourcestartlinenumber="1">Gets or sets a collection of static sections.</p>


```csharp
public CIMVoxelStaticSection[] StaticSections { get; set; }
```
### SurfaceContainerExpanded

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the surface container is expanded in the contents pane.</p>


```csharp
public bool SurfaceContainerExpanded { get; set; }
```
### TimeDefinition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelLayer.yml" sourcestartlinenumber="1">Gets or sets the time definition.</p>


```csharp
public CIMTimeDataDefinition TimeDefinition { get; set; }
```
### TimeDisplayDefinition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelLayer.yml" sourcestartlinenumber="1">Gets or sets the time display definition.</p>


```csharp
public CIMTimeDisplayDefinition TimeDisplayDefinition { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMVoxelLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Visualization

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelLayer.yml" sourcestartlinenumber="1">Gets or sets the voxel visualization.</p>


```csharp
public VoxelVisualization Visualization { get; set; }
```
### Volumes

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelLayer.yml" sourcestartlinenumber="1">Gets or sets the volumes.</p>


```csharp
public CIMVoxelVolume[] Volumes { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


