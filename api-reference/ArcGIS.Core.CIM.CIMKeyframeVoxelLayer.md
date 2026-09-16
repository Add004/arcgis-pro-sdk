# CIMKeyframeVoxelLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeVoxelLayer.yml" sourcestartlinenumber="1">Represents a voxel layer keyframe.</p>


## Object Signature

```csharp
public class CIMKeyframeVoxelLayer : CIMKeyframeLayer, INotifyPropertyChanged, IXmlSerializable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeVoxelLayer.yml" sourcestartlinenumber="1">The voxel layer keyframe stores properties specific to voxel layer.</p>


## Members

### CIMKeyframeVoxelLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeVoxelLayer.yml" sourcestartlinenumber="1">Represents a voxel layer keyframe.</p>


```csharp
public CIMKeyframeVoxelLayer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeVoxelLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKeyframeVoxelLayer.</p>


```csharp
public CIMKeyframeVoxelLayer Clone()
```
### DataFilterMax

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeVoxelLayer.yml" sourcestartlinenumber="1">Gets or sets the maximum data value.</p>


```csharp
public double DataFilterMax { get; set; }
```
### DataFilterMin

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeVoxelLayer.yml" sourcestartlinenumber="1">Gets or sets the minimum data value.</p>


```csharp
public double DataFilterMin { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeVoxelLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMKeyframeVoxelLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMKeyframeVoxelLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### Isosurfaces

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeVoxelLayer.yml" sourcestartlinenumber="1">Gets or sets the voxel surfaces.</p>


```csharp
public CIMIsosurface[] Isosurfaces { get; set; }
```
### LockedSections

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeVoxelLayer.yml" sourcestartlinenumber="1">Gets or sets the static cross section planes.</p>


```csharp
public CIMKeyframeVoxelPlane[] LockedSections { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeVoxelLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Sections

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeVoxelLayer.yml" sourcestartlinenumber="1">Gets or sets the dynamic cross section planes.</p>


```csharp
public CIMKeyframeVoxelPlane[] Sections { get; set; }
```
### ShowSurface

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeVoxelLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the surface is shown instead of the volume.</p>


```csharp
public bool ShowSurface { get; set; }
```
### Slices

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeVoxelLayer.yml" sourcestartlinenumber="1">Gets or sets the slice planes.</p>


```csharp
public CIMKeyframeVoxelPlane[] Slices { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeVoxelLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKeyframeVoxelLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### VariableName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeVoxelLayer.yml" sourcestartlinenumber="1">Gets or sets the name of the current symbolizer variable.</p>


```csharp
public string VariableName { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeVoxelLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


