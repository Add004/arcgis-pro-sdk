# CIMOGCAPIVectorTileDataConnection

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMOGCAPIVectorTileDataConnection.yml" sourcestartlinenumber="1">Represents an OGCAPI vector tile data connection.</p>


## Object Signature

```csharp
public class CIMOGCAPIVectorTileDataConnection : CIMVectorTileDataConnection, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMOGCAPIVectorTileDataConnection()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMOGCAPIVectorTileDataConnection.yml" sourcestartlinenumber="1">Represents an OGCAPI vector tile data connection.</p>


```csharp
public CIMOGCAPIVectorTileDataConnection()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMOGCAPIVectorTileDataConnection.yml" sourcestartlinenumber="1">Creates a deep copy of CIMOGCAPIVectorTileDataConnection.</p>


```csharp
public CIMOGCAPIVectorTileDataConnection Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMOGCAPIVectorTileDataConnection.yml" sourcestartlinenumber="1">Reconstructs the CIMOGCAPIVectorTileDataConnection with a specified state from a JSON encoding.</p>


```csharp
public static CIMOGCAPIVectorTileDataConnection FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMOGCAPIVectorTileDataConnection.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### TileMatrixSet

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMOGCAPIVectorTileDataConnection.yml" sourcestartlinenumber="1">Gets or sets the tile matrix set.</p>


```csharp
public string TileMatrixSet { get; set; }
```
### TileSetURL

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMOGCAPIVectorTileDataConnection.yml" sourcestartlinenumber="1">Gets or sets the tile set url.</p>


```csharp
public string TileSetURL { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMOGCAPIVectorTileDataConnection.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMOGCAPIVectorTileDataConnection and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMOGCAPIVectorTileDataConnection.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


