# CIMInMemoryDatasetDataConnection

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMInMemoryDatasetDataConnection.yml" sourcestartlinenumber="1">Represents an in-memory dataset data connection.</p>


## Object Signature

```csharp
public class CIMInMemoryDatasetDataConnection : CIMDataConnection, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMInMemoryDatasetDataConnection()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMInMemoryDatasetDataConnection.yml" sourcestartlinenumber="1">Represents an in-memory dataset data connection.</p>


```csharp
public CIMInMemoryDatasetDataConnection()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMInMemoryDatasetDataConnection.yml" sourcestartlinenumber="1">Creates a deep copy of CIMInMemoryDatasetDataConnection.</p>


```csharp
public CIMInMemoryDatasetDataConnection Clone()
```
### Dataset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMInMemoryDatasetDataConnection.yml" sourcestartlinenumber="1">Gets or sets the dataset name.</p>


```csharp
public string Dataset { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMInMemoryDatasetDataConnection.yml" sourcestartlinenumber="1">Reconstructs the CIMInMemoryDatasetDataConnection with a specified state from a JSON encoding.</p>


```csharp
public static CIMInMemoryDatasetDataConnection FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMInMemoryDatasetDataConnection.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMInMemoryDatasetDataConnection.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMInMemoryDatasetDataConnection and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMInMemoryDatasetDataConnection.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


