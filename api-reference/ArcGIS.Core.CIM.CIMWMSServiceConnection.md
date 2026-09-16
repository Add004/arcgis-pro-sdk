# CIMWMSServiceConnection

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMWMSServiceConnection.yml" sourcestartlinenumber="1">Represents a WMS service connection.</p>


## Object Signature

```csharp
public class CIMWMSServiceConnection : CIMServiceConnection, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMWMSServiceConnection()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMWMSServiceConnection.yml" sourcestartlinenumber="1">Represents a WMS service connection.</p>


```csharp
public CIMWMSServiceConnection()
```
### CapabilitiesParameters

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMWMSServiceConnection.yml" sourcestartlinenumber="1">Gets or sets vendor specific parameters for GetCapabilities, GetMap and GetFeatureInfo requests.</p>


```csharp
public IDictionary<string, object> CapabilitiesParameters { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMWMSServiceConnection.yml" sourcestartlinenumber="1">Creates a deep copy of CIMWMSServiceConnection.</p>


```csharp
public CIMWMSServiceConnection Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMWMSServiceConnection.yml" sourcestartlinenumber="1">Reconstructs the CIMWMSServiceConnection with a specified state from a JSON encoding.</p>


```csharp
public static CIMWMSServiceConnection FromJson(string json, JsonDeserializationSettings settings = null)
```
### LayerName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMWMSServiceConnection.yml" sourcestartlinenumber="1">Gets or sets the layer name.</p>


```csharp
public string LayerName { get; set; }
```
### MapParameters

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMWMSServiceConnection.yml" sourcestartlinenumber="1">Gets or sets vendor specific parameters for GetMap and GetFeatureInfo requests.</p>


```csharp
public IDictionary<string, object> MapParameters { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMWMSServiceConnection.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ServerConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMWMSServiceConnection.yml" sourcestartlinenumber="1">Gets or sets the server connection.</p>


```csharp
public CIMInternetServerConnectionBase ServerConnection { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMWMSServiceConnection.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMWMSServiceConnection and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Version

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMWMSServiceConnection.yml" sourcestartlinenumber="1">Gets or sets the version.</p>


```csharp
public string Version { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMWMSServiceConnection.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


