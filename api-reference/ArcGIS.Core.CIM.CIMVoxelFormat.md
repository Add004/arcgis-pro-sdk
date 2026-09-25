# CIMVoxelFormat

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelFormat.yml" sourcestartlinenumber="1">Represents a voxel format.</p>


## Object Signature

```csharp
public class CIMVoxelFormat : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMVoxelFormat()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelFormat.yml" sourcestartlinenumber="1">Represents a voxel format.</p>


```csharp
public CIMVoxelFormat()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelFormat.yml" sourcestartlinenumber="1">Creates a deep copy of CIMVoxelFormat.</p>


```csharp
public CIMVoxelFormat Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelFormat.yml" sourcestartlinenumber="1">Reconstructs the CIMVoxelFormat with a specified state from a JSON encoding.</p>


```csharp
public static CIMVoxelFormat FromJson(string json, JsonDeserializationSettings settings = null)
```
### NoDataValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelFormat.yml" sourcestartlinenumber="1">Gets or sets the native no data value.</p>


```csharp
public double NoDataValue { get; set; }
```
### Offset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelFormat.yml" sourcestartlinenumber="1">Gets or sets the offset for fixed point encoded data.</p>


```csharp
public double Offset { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelFormat.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ScalarFormat

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelFormat.yml" sourcestartlinenumber="1">Gets or sets the scalar format.</p>


```csharp
public VoxelScalarFormat ScalarFormat { get; set; }
```
### Scale

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelFormat.yml" sourcestartlinenumber="1">Gets or sets the scaling factor for fixed point encoded data.</p>


```csharp
public double Scale { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelFormat.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMVoxelFormat and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseNoDataValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelFormat.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the native no data value should be used.</p>


```csharp
public bool UseNoDataValue { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelFormat.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


