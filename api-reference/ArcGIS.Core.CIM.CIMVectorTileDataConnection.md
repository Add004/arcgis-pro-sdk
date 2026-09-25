# CIMVectorTileDataConnection

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMVectorTileDataConnection.yml" sourcestartlinenumber="1">Represents a VectorTile layer data connection.</p>


## Object Signature

```csharp
public class CIMVectorTileDataConnection : CIMDataConnection, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMVectorTileDataConnection()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMVectorTileDataConnection.yml" sourcestartlinenumber="1">Represents a VectorTile layer data connection.</p>


```csharp
public CIMVectorTileDataConnection()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVectorTileDataConnection.yml" sourcestartlinenumber="1">Creates a deep copy of CIMVectorTileDataConnection.</p>


```csharp
public CIMVectorTileDataConnection Clone()
```
### CustomParameters

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVectorTileDataConnection.yml" sourcestartlinenumber="1">Gets or sets vendor specific parameters.</p>


```csharp
public CIMStringMap[] CustomParameters { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVectorTileDataConnection.yml" sourcestartlinenumber="1">Reconstructs the CIMVectorTileDataConnection with a specified state from a JSON encoding.</p>


```csharp
public static CIMVectorTileDataConnection FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVectorTileDataConnection.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ResourcesURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVectorTileDataConnection.yml" sourcestartlinenumber="1">Gets or sets the URI of the binary reference containing the external resources.</p>


```csharp
public string ResourcesURI { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVectorTileDataConnection.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMVectorTileDataConnection and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### URI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVectorTileDataConnection.yml" sourcestartlinenumber="1">Gets or sets the URI of the VectorTile files or resources.</p>


```csharp
public string URI { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVectorTileDataConnection.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


