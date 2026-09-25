# CIMVoxelLighting

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelLighting.yml" sourcestartlinenumber="1">Represents voxel lighting.</p>


## Object Signature

```csharp
public class CIMVoxelLighting : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMVoxelLighting()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelLighting.yml" sourcestartlinenumber="1">Represents voxel lighting.</p>


```csharp
public CIMVoxelLighting()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelLighting.yml" sourcestartlinenumber="1">Creates a deep copy of CIMVoxelLighting.</p>


```csharp
public CIMVoxelLighting Clone()
```
### Diffuse

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelLighting.yml" sourcestartlinenumber="1">Gets or sets the diffuse value.</p>


```csharp
public double Diffuse { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelLighting.yml" sourcestartlinenumber="1">Reconstructs the CIMVoxelLighting with a specified state from a JSON encoding.</p>


```csharp
public static CIMVoxelLighting FromJson(string json, JsonDeserializationSettings settings = null)
```
### IsDiffuseEnabled

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelLighting.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether diffuse lighting is enabled.</p>


```csharp
public bool IsDiffuseEnabled { get; set; }
```
### IsSpecularEnabled

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelLighting.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether specular lighting is enabled.</p>


```csharp
public bool IsSpecularEnabled { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelLighting.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Specular

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelLighting.yml" sourcestartlinenumber="1">Gets or sets the specular value.</p>


```csharp
public double Specular { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelLighting.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMVoxelLighting and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelLighting.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


