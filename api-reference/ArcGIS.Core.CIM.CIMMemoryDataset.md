# CIMMemoryDataset

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMemoryDataset.yml" sourcestartlinenumber="1">Represents a dataset in an in-memory workspace.</p>


## Object Signature

```csharp
public class CIMMemoryDataset : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMemoryDataset()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMemoryDataset.yml" sourcestartlinenumber="1">Represents a dataset in an in-memory workspace.</p>


```csharp
public CIMMemoryDataset()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMemoryDataset.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMemoryDataset.</p>


```csharp
public CIMMemoryDataset Clone()
```
### DatasetURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMemoryDataset.yml" sourcestartlinenumber="1">Gets or sets the URI of the binary reference containing the serialized dataset.</p>


```csharp
public string DatasetURI { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMemoryDataset.yml" sourcestartlinenumber="1">Reconstructs the CIMMemoryDataset with a specified state from a JSON encoding.</p>


```csharp
public static CIMMemoryDataset FromJson(string json, JsonDeserializationSettings settings = null)
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMemoryDataset.yml" sourcestartlinenumber="1">Gets or sets the name of the dataset.</p>


```csharp
public string Name { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMemoryDataset.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMemoryDataset.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMemoryDataset and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMemoryDataset.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


