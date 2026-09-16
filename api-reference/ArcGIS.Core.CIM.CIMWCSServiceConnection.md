# CIMWCSServiceConnection

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMWCSServiceConnection.yml" sourcestartlinenumber="1">Represents a WCS service connection.</p>


## Object Signature

```csharp
public class CIMWCSServiceConnection : CIMServiceConnection, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMWCSServiceConnection()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMWCSServiceConnection.yml" sourcestartlinenumber="1">Represents a WCS service connection.</p>


```csharp
public CIMWCSServiceConnection()
```
### CapabilitiesParameters

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMWCSServiceConnection.yml" sourcestartlinenumber="1">Gets or sets vendor specific parameters for all WCS requests.</p>


```csharp
public IDictionary<string, object> CapabilitiesParameters { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMWCSServiceConnection.yml" sourcestartlinenumber="1">Creates a deep copy of CIMWCSServiceConnection.</p>


```csharp
public CIMWCSServiceConnection Clone()
```
### CoverageName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMWCSServiceConnection.yml" sourcestartlinenumber="1">Gets or sets the coverage name.</p>


```csharp
public string CoverageName { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMWCSServiceConnection.yml" sourcestartlinenumber="1">Reconstructs the CIMWCSServiceConnection with a specified state from a JSON encoding.</p>


```csharp
public static CIMWCSServiceConnection FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMWCSServiceConnection.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ServerConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMWCSServiceConnection.yml" sourcestartlinenumber="1">Gets or sets the server connection.</p>


```csharp
public CIMInternetServerConnectionBase ServerConnection { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMWCSServiceConnection.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMWCSServiceConnection and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Version

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMWCSServiceConnection.yml" sourcestartlinenumber="1">Gets or sets the version.</p>


```csharp
public string Version { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMWCSServiceConnection.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


