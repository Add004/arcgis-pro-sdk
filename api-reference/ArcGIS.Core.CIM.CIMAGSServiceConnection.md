# CIMAGSServiceConnection

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMAGSServiceConnection.yml" sourcestartlinenumber="1">Represents an ArcGIS Server service connection.</p>


## Object Signature

```csharp
public class CIMAGSServiceConnection : CIMServiceConnection, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMAGSServiceConnection()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMAGSServiceConnection.yml" sourcestartlinenumber="1">Represents an ArcGIS Server service connection.</p>


```csharp
public CIMAGSServiceConnection()
```
### Capabilities

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAGSServiceConnection.yml" sourcestartlinenumber="1">Gets or sets the capabilities.</p>


```csharp
public string Capabilities { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAGSServiceConnection.yml" sourcestartlinenumber="1">Creates a deep copy of CIMAGSServiceConnection.</p>


```csharp
public CIMAGSServiceConnection Clone()
```
### CustomParameters

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAGSServiceConnection.yml" sourcestartlinenumber="1">Gets or sets vendor specific parameters.</p>


```csharp
public CIMStringMap[] CustomParameters { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAGSServiceConnection.yml" sourcestartlinenumber="1">Reconstructs the CIMAGSServiceConnection with a specified state from a JSON encoding.</p>


```csharp
public static CIMAGSServiceConnection FromJson(string json, JsonDeserializationSettings settings = null)
```
### GdbVersion

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAGSServiceConnection.yml" sourcestartlinenumber="1">Gets or sets the name of the geodatabase version to use in service requests.</p>


```csharp
public string GdbVersion { get; set; }
```
### ObjectName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAGSServiceConnection.yml" sourcestartlinenumber="1">Gets or sets the object name.</p>


```csharp
public string ObjectName { get; set; }
```
### ObjectType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAGSServiceConnection.yml" sourcestartlinenumber="1">Gets or sets the object type.</p>


```csharp
public string ObjectType { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAGSServiceConnection.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ServerConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAGSServiceConnection.yml" sourcestartlinenumber="1">Gets or sets the server connection.</p>


```csharp
public CIMServerConnection ServerConnection { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAGSServiceConnection.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMAGSServiceConnection and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### URL

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAGSServiceConnection.yml" sourcestartlinenumber="1">Gets or sets the URL.</p>


```csharp
public string URL { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAGSServiceConnection.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


