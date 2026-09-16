# CIMSceneDataConnection

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMSceneDataConnection.yml" sourcestartlinenumber="1">Represents a scene data connection.</p>


## Object Signature

```csharp
public class CIMSceneDataConnection : CIMDataConnection, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMSceneDataConnection()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMSceneDataConnection.yml" sourcestartlinenumber="1">Represents a scene data connection.</p>


```csharp
public CIMSceneDataConnection()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSceneDataConnection.yml" sourcestartlinenumber="1">Creates a deep copy of CIMSceneDataConnection.</p>


```csharp
public CIMSceneDataConnection Clone()
```
### CustomParameters

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSceneDataConnection.yml" sourcestartlinenumber="1">Gets or sets vendor specific parameters.</p>


```csharp
public CIMStringMap[] CustomParameters { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSceneDataConnection.yml" sourcestartlinenumber="1">Reconstructs the CIMSceneDataConnection with a specified state from a JSON encoding.</p>


```csharp
public static CIMSceneDataConnection FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSceneDataConnection.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSceneDataConnection.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMSceneDataConnection and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### URI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSceneDataConnection.yml" sourcestartlinenumber="1">Gets or sets the URI.</p>


```csharp
public string URI { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSceneDataConnection.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


