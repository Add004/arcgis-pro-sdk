# CIMVoxelVariableProfile

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelVariableProfile.yml" sourcestartlinenumber="1">Represents a voxel layer variable profile.</p>


## Object Signature

```csharp
public class CIMVoxelVariableProfile : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMVoxelVariableProfile()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelVariableProfile.yml" sourcestartlinenumber="1">Represents a voxel layer variable profile.</p>


```csharp
public CIMVoxelVariableProfile()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelVariableProfile.yml" sourcestartlinenumber="1">Creates a deep copy of CIMVoxelVariableProfile.</p>


```csharp
public CIMVoxelVariableProfile Clone()
```
### DataType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelVariableProfile.yml" sourcestartlinenumber="1">Gets or sets the variable data type.</p>


```csharp
public VoxelVariableDataType DataType { get; set; }
```
### Description

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelVariableProfile.yml" sourcestartlinenumber="1">Gets or sets the variable description.</p>


```csharp
public string Description { get; set; }
```
### Filters

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelVariableProfile.yml" sourcestartlinenumber="1">Gets or sets the filters.</p>


```csharp
public CIMVoxelFilter[] Filters { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelVariableProfile.yml" sourcestartlinenumber="1">Reconstructs the CIMVoxelVariableProfile with a specified state from a JSON encoding.</p>


```csharp
public static CIMVoxelVariableProfile FromJson(string json, JsonDeserializationSettings settings = null)
```
### Isosurfaces

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelVariableProfile.yml" sourcestartlinenumber="1">Gets or sets a collection of isosurfaces.</p>


```csharp
public CIMIsosurface[] Isosurfaces { get; set; }
```
### Precision

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelVariableProfile.yml" sourcestartlinenumber="1">Gets or sets the variable precision.</p>


```csharp
public VoxelVariablePrecision Precision { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelVariableProfile.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Renderer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelVariableProfile.yml" sourcestartlinenumber="1">Gets or sets the symbol renderer.</p>


```csharp
public CIMVoxelRenderer Renderer { get; set; }
```
### Signature

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelVariableProfile.yml" sourcestartlinenumber="1">Gets or sets the signature for the variable.</p>


```csharp
public string Signature { get; set; }
```
### SignatureVersion

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelVariableProfile.yml" sourcestartlinenumber="1">Gets or sets the signature version for the variable.</p>


```csharp
public int SignatureVersion { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelVariableProfile.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMVoxelVariableProfile and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Variable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelVariableProfile.yml" sourcestartlinenumber="1">Gets or sets the variable that the profile is associated with.</p>


```csharp
public string Variable { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelVariableProfile.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


