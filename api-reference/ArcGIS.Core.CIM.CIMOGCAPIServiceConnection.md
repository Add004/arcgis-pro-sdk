# CIMOGCAPIServiceConnection

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMOGCAPIServiceConnection.yml" sourcestartlinenumber="1">Represents a OGCAPI service connection.</p>


## Object Signature

```csharp
public class CIMOGCAPIServiceConnection : CIMServiceConnection, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMOGCAPIServiceConnection()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMOGCAPIServiceConnection.yml" sourcestartlinenumber="1">Represents a OGCAPI service connection.</p>


```csharp
public CIMOGCAPIServiceConnection()
```
### CapabilitiesParameters

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMOGCAPIServiceConnection.yml" sourcestartlinenumber="1">Gets or sets vendor specific parameters for all OGCAPI requests.</p>


```csharp
public IDictionary<string, object> CapabilitiesParameters { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMOGCAPIServiceConnection.yml" sourcestartlinenumber="1">Creates a deep copy of CIMOGCAPIServiceConnection.</p>


```csharp
public CIMOGCAPIServiceConnection Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMOGCAPIServiceConnection.yml" sourcestartlinenumber="1">Reconstructs the CIMOGCAPIServiceConnection with a specified state from a JSON encoding.</p>


```csharp
public static CIMOGCAPIServiceConnection FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMOGCAPIServiceConnection.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ServerConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMOGCAPIServiceConnection.yml" sourcestartlinenumber="1">Gets or sets the server connection.</p>


```csharp
public CIMInternetServerConnectionBase ServerConnection { get; set; }
```
### ServiceName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMOGCAPIServiceConnection.yml" sourcestartlinenumber="1">Gets or sets the service name.</p>


```csharp
public string ServiceName { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMOGCAPIServiceConnection.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMOGCAPIServiceConnection and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Version

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMOGCAPIServiceConnection.yml" sourcestartlinenumber="1">Gets or sets the version.</p>


```csharp
public string Version { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMOGCAPIServiceConnection.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


