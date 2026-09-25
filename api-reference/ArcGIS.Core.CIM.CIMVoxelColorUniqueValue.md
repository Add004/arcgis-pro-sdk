# CIMVoxelColorUniqueValue

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelColorUniqueValue.yml" sourcestartlinenumber="1">Represents a voxel color unique value.</p>


## Object Signature

```csharp
public class CIMVoxelColorUniqueValue : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMVoxelColorUniqueValue()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelColorUniqueValue.yml" sourcestartlinenumber="1">Represents a voxel color unique value.</p>


```csharp
public CIMVoxelColorUniqueValue()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelColorUniqueValue.yml" sourcestartlinenumber="1">Creates a deep copy of CIMVoxelColorUniqueValue.</p>


```csharp
public CIMVoxelColorUniqueValue Clone()
```
### Color

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelColorUniqueValue.yml" sourcestartlinenumber="1">Gets or sets the class color.</p>


```csharp
public CIMColor Color { get; set; }
```
### Description

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelColorUniqueValue.yml" sourcestartlinenumber="1">Gets or sets the description.</p>


```csharp
public string Description { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelColorUniqueValue.yml" sourcestartlinenumber="1">Reconstructs the CIMVoxelColorUniqueValue with a specified state from a JSON encoding.</p>


```csharp
public static CIMVoxelColorUniqueValue FromJson(string json, JsonDeserializationSettings settings = null)
```
### Label

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelColorUniqueValue.yml" sourcestartlinenumber="1">Gets or sets the class label.</p>


```csharp
public string Label { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelColorUniqueValue.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelColorUniqueValue.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMVoxelColorUniqueValue and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Value

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelColorUniqueValue.yml" sourcestartlinenumber="1">Gets or sets the class value as a integer.</p>


```csharp
public int Value { get; set; }
```
### Visible

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelColorUniqueValue.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this class is visible.</p>


```csharp
public bool Visible { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelColorUniqueValue.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


