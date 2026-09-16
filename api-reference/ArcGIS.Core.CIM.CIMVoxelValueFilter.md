# CIMVoxelValueFilter

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelValueFilter.yml" sourcestartlinenumber="1">Represents a voxel value filter.
Filter based on the value of an specified variable.</p>


## Object Signature

```csharp
public class CIMVoxelValueFilter : CIMVoxelFilter, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMVoxelValueFilter()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelValueFilter.yml" sourcestartlinenumber="1">Represents a voxel value filter.
Filter based on the value of an specified variable.</p>


```csharp
public CIMVoxelValueFilter()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelValueFilter.yml" sourcestartlinenumber="1">Creates a deep copy of CIMVoxelValueFilter.</p>


```csharp
public CIMVoxelValueFilter Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelValueFilter.yml" sourcestartlinenumber="1">Reconstructs the CIMVoxelValueFilter with a specified state from a JSON encoding.</p>


```csharp
public static CIMVoxelValueFilter FromJson(string json, JsonDeserializationSettings settings = null)
```
### Mode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelValueFilter.yml" sourcestartlinenumber="1">Gets or sets the mode that determines if the ValueList is an include list or an exclude list.</p>


```csharp
public VoxelValueFilterMode Mode { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelValueFilter.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelValueFilter.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMVoxelValueFilter and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Values

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelValueFilter.yml" sourcestartlinenumber="1">Gets or sets the values used as exclude or include list.</p>


```csharp
public double[] Values { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelValueFilter.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


