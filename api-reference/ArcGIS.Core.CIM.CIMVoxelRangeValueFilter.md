# CIMVoxelRangeValueFilter

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelRangeValueFilter.yml" sourcestartlinenumber="1">Represents a voxel value filter.
Filter based on the value of an specified variable.</p>


## Object Signature

```csharp
public class CIMVoxelRangeValueFilter : CIMVoxelFilter, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMVoxelRangeValueFilter()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelRangeValueFilter.yml" sourcestartlinenumber="1">Represents a voxel value filter.
Filter based on the value of an specified variable.</p>


```csharp
public CIMVoxelRangeValueFilter()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelRangeValueFilter.yml" sourcestartlinenumber="1">Creates a deep copy of CIMVoxelRangeValueFilter.</p>


```csharp
public CIMVoxelRangeValueFilter Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelRangeValueFilter.yml" sourcestartlinenumber="1">Reconstructs the CIMVoxelRangeValueFilter with a specified state from a JSON encoding.</p>


```csharp
public static CIMVoxelRangeValueFilter FromJson(string json, JsonDeserializationSettings settings = null)
```
### Max

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelRangeValueFilter.yml" sourcestartlinenumber="1">Gets or sets the max value.</p>


```csharp
public double Max { get; set; }
```
### Min

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelRangeValueFilter.yml" sourcestartlinenumber="1">Gets or sets the min value.</p>


```csharp
public double Min { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelRangeValueFilter.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelRangeValueFilter.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMVoxelRangeValueFilter and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelRangeValueFilter.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


