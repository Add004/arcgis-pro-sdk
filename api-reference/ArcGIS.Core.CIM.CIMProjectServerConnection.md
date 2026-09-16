# CIMProjectServerConnection

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMProjectServerConnection.yml" sourcestartlinenumber="1">Represents a project server connection.</p>


## Object Signature

```csharp
public class CIMProjectServerConnection : CIMInternetServerConnectionBase, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMProjectServerConnection()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMProjectServerConnection.yml" sourcestartlinenumber="1">Represents a project server connection.</p>


```csharp
public CIMProjectServerConnection()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProjectServerConnection.yml" sourcestartlinenumber="1">Creates a deep copy of CIMProjectServerConnection.</p>


```csharp
public CIMProjectServerConnection Clone()
```
### ConnectionMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProjectServerConnection.yml" sourcestartlinenumber="1">Gets or sets the connection mode.</p>


```csharp
public ConnectionMode ConnectionMode { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProjectServerConnection.yml" sourcestartlinenumber="1">Reconstructs the CIMProjectServerConnection with a specified state from a JSON encoding.</p>


```csharp
public static CIMProjectServerConnection FromJson(string json, JsonDeserializationSettings settings = null)
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProjectServerConnection.yml" sourcestartlinenumber="1">Gets or sets the name.</p>


```csharp
public string Name { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProjectServerConnection.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ServerType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProjectServerConnection.yml" sourcestartlinenumber="1">Gets or sets the server type.</p>


```csharp
public ServerType ServerType { get; set; }
```
### StagingFolder

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProjectServerConnection.yml" sourcestartlinenumber="1">Gets or sets the staging folder.</p>


```csharp
public string StagingFolder { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProjectServerConnection.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMProjectServerConnection and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseDefaultStagingFolder

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProjectServerConnection.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to use the default staging folder.</p>


```csharp
public bool UseDefaultStagingFolder { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProjectServerConnection.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


