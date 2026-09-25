# CIMVideoDataConnection

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoDataConnection.yml" sourcestartlinenumber="1">Represents a video data connection.</p>


## Object Signature

```csharp
public class CIMVideoDataConnection : CIMDataConnection, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMVideoDataConnection()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoDataConnection.yml" sourcestartlinenumber="1">Represents a video data connection.</p>


```csharp
public CIMVideoDataConnection()
```
### Anonymous

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoDataConnection.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not this is an anonymous connection.</p>


```csharp
public bool Anonymous { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoDataConnection.yml" sourcestartlinenumber="1">Creates a deep copy of CIMVideoDataConnection.</p>


```csharp
public CIMVideoDataConnection Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoDataConnection.yml" sourcestartlinenumber="1">Reconstructs the CIMVideoDataConnection with a specified state from a JSON encoding.</p>


```csharp
public static CIMVideoDataConnection FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoDataConnection.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoDataConnection.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMVideoDataConnection and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### URI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoDataConnection.yml" sourcestartlinenumber="1">Gets or sets the URI of the video files.</p>


```csharp
public string URI { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoDataConnection.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


