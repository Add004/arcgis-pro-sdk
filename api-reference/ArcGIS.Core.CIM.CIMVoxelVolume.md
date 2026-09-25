# CIMVoxelVolume

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelVolume.yml" sourcestartlinenumber="1">Represents a voxel layer volume.</p>


## Object Signature

```csharp
public class CIMVoxelVolume : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMVoxelVolume()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelVolume.yml" sourcestartlinenumber="1">Represents a voxel layer volume.</p>


```csharp
public CIMVoxelVolume()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelVolume.yml" sourcestartlinenumber="1">Creates a deep copy of CIMVoxelVolume.</p>


```csharp
public CIMVoxelVolume Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelVolume.yml" sourcestartlinenumber="1">Reconstructs the CIMVoxelVolume with a specified state from a JSON encoding.</p>


```csharp
public static CIMVoxelVolume FromJson(string json, JsonDeserializationSettings settings = null)
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelVolume.yml" sourcestartlinenumber="1">Gets or sets the volume ID, which must be unique among all volumes in the layer.</p>


```csharp
public int ID { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelVolume.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Sections

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelVolume.yml" sourcestartlinenumber="1">Gets or sets a collection of sections.</p>


```csharp
public CIMVoxelPlane[] Sections { get; set; }
```
### Slices

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelVolume.yml" sourcestartlinenumber="1">Gets or sets a collection of slices.</p>


```csharp
public CIMVoxelPlane[] Slices { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelVolume.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMVoxelVolume and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### VariableProfiles

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelVolume.yml" sourcestartlinenumber="1">Gets or sets the variable profiles.</p>


```csharp
public CIMVoxelVariableProfile[] VariableProfiles { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelVolume.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


