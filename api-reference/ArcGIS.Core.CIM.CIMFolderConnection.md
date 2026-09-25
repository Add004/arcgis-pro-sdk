# CIMFolderConnection

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFolderConnection.yml" sourcestartlinenumber="1">Represents a folder connection.</p>


## Object Signature

```csharp
public class CIMFolderConnection : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFolderConnection()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFolderConnection.yml" sourcestartlinenumber="1">Represents a folder connection.</p>


```csharp
public CIMFolderConnection()
```
### Alias

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFolderConnection.yml" sourcestartlinenumber="1">Gets or sets the connection alias.</p>


```csharp
public string Alias { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFolderConnection.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFolderConnection.</p>


```csharp
public CIMFolderConnection Clone()
```
### FolderConnectionString

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFolderConnection.yml" sourcestartlinenumber="1">Gets or sets the folder connection string.</p>


```csharp
public string FolderConnectionString { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFolderConnection.yml" sourcestartlinenumber="1">Reconstructs the CIMFolderConnection with a specified state from a JSON encoding.</p>


```csharp
public static CIMFolderConnection FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFolderConnection.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFolderConnection.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFolderConnection and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFolderConnection.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


