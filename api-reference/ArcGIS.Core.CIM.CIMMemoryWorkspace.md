# CIMMemoryWorkspace

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMemoryWorkspace.yml" sourcestartlinenumber="1">Represents an in-memory workspace stored in the project.</p>


## Object Signature

```csharp
public class CIMMemoryWorkspace : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMemoryWorkspace()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMemoryWorkspace.yml" sourcestartlinenumber="1">Represents an in-memory workspace stored in the project.</p>


```csharp
public CIMMemoryWorkspace()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMemoryWorkspace.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMemoryWorkspace.</p>


```csharp
public CIMMemoryWorkspace Clone()
```
### Datasets

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMemoryWorkspace.yml" sourcestartlinenumber="1">Gets or sets the datasets that belong to this workspace.</p>


```csharp
public CIMMemoryDataset[] Datasets { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMemoryWorkspace.yml" sourcestartlinenumber="1">Reconstructs the CIMMemoryWorkspace with a specified state from a JSON encoding.</p>


```csharp
public static CIMMemoryWorkspace FromJson(string json, JsonDeserializationSettings settings = null)
```
### InstanceID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMemoryWorkspace.yml" sourcestartlinenumber="1">Gets or sets a string that uniquely identifies the workspace in the project.</p>


```csharp
public string InstanceID { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMemoryWorkspace.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMemoryWorkspace.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMemoryWorkspace and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMemoryWorkspace.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


