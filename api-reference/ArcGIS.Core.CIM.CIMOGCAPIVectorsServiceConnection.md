# CIMOGCAPIVectorsServiceConnection

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMOGCAPIVectorsServiceConnection.yml" sourcestartlinenumber="1">Represents a OGC API Vectors service connection.</p>


## Object Signature

```csharp
public class CIMOGCAPIVectorsServiceConnection : CIMServiceConnection, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMOGCAPIVectorsServiceConnection()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMOGCAPIVectorsServiceConnection.yml" sourcestartlinenumber="1">Represents a OGC API Vectors service connection.</p>


```csharp
public CIMOGCAPIVectorsServiceConnection()
```
### CapabilitiesParameters

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMOGCAPIVectorsServiceConnection.yml" sourcestartlinenumber="1">Gets or sets the connection capabilities parameters as a property set.</p>


```csharp
public IDictionary<string, object> CapabilitiesParameters { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMOGCAPIVectorsServiceConnection.yml" sourcestartlinenumber="1">Creates a deep copy of CIMOGCAPIVectorsServiceConnection.</p>


```csharp
public CIMOGCAPIVectorsServiceConnection Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMOGCAPIVectorsServiceConnection.yml" sourcestartlinenumber="1">Reconstructs the CIMOGCAPIVectorsServiceConnection with a specified state from a JSON encoding.</p>


```csharp
public static CIMOGCAPIVectorsServiceConnection FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMOGCAPIVectorsServiceConnection.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ServerConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMOGCAPIVectorsServiceConnection.yml" sourcestartlinenumber="1">Gets or sets the server connection.</p>


```csharp
public CIMInternetServerConnectionBase ServerConnection { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMOGCAPIVectorsServiceConnection.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMOGCAPIVectorsServiceConnection and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMOGCAPIVectorsServiceConnection.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


