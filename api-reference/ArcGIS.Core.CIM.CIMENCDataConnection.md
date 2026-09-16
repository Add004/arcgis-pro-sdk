# CIMENCDataConnection

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMENCDataConnection.yml" sourcestartlinenumber="1">Represents an ENC layer data connection.</p>


## Object Signature

```csharp
public class CIMENCDataConnection : CIMDataConnection, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMENCDataConnection()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMENCDataConnection.yml" sourcestartlinenumber="1">Represents an ENC layer data connection.</p>


```csharp
public CIMENCDataConnection()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMENCDataConnection.yml" sourcestartlinenumber="1">Creates a deep copy of CIMENCDataConnection.</p>


```csharp
public CIMENCDataConnection Clone()
```
### CustomParameters

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMENCDataConnection.yml" sourcestartlinenumber="1">Gets or sets vendor specific parameters.</p>


```csharp
public CIMStringMap[] CustomParameters { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMENCDataConnection.yml" sourcestartlinenumber="1">Reconstructs the CIMENCDataConnection with a specified state from a JSON encoding.</p>


```csharp
public static CIMENCDataConnection FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMENCDataConnection.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMENCDataConnection.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMENCDataConnection and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### URI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMENCDataConnection.yml" sourcestartlinenumber="1">Gets or sets the URI of the ENC files or resources.</p>


```csharp
public string URI { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMENCDataConnection.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


