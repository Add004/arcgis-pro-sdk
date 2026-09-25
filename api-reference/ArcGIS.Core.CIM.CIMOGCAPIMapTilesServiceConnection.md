# CIMOGCAPIMapTilesServiceConnection

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMOGCAPIMapTilesServiceConnection.yml" sourcestartlinenumber="1">Represents a OGC API Map Tiles service connection.</p>


## Object Signature

```csharp
public class CIMOGCAPIMapTilesServiceConnection : CIMServiceConnection, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMOGCAPIMapTilesServiceConnection()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMOGCAPIMapTilesServiceConnection.yml" sourcestartlinenumber="1">Represents a OGC API Map Tiles service connection.</p>


```csharp
public CIMOGCAPIMapTilesServiceConnection()
```
### CapabilitiesParameters

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMOGCAPIMapTilesServiceConnection.yml" sourcestartlinenumber="1">Gets or sets the connection capabilities parameters as a property set.</p>


```csharp
public IDictionary<string, object> CapabilitiesParameters { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMOGCAPIMapTilesServiceConnection.yml" sourcestartlinenumber="1">Creates a deep copy of CIMOGCAPIMapTilesServiceConnection.</p>


```csharp
public CIMOGCAPIMapTilesServiceConnection Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMOGCAPIMapTilesServiceConnection.yml" sourcestartlinenumber="1">Reconstructs the CIMOGCAPIMapTilesServiceConnection with a specified state from a JSON encoding.</p>


```csharp
public static CIMOGCAPIMapTilesServiceConnection FromJson(string json, JsonDeserializationSettings settings = null)
```
### ImageFormat

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMOGCAPIMapTilesServiceConnection.yml" sourcestartlinenumber="1">Gets or sets the image format.</p>


```csharp
public string ImageFormat { get; set; }
```
### LayerName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMOGCAPIMapTilesServiceConnection.yml" sourcestartlinenumber="1">Gets or sets the layer name.</p>


```csharp
public string LayerName { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMOGCAPIMapTilesServiceConnection.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ServerConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMOGCAPIMapTilesServiceConnection.yml" sourcestartlinenumber="1">Gets or sets the server connection.</p>


```csharp
public CIMInternetServerConnectionBase ServerConnection { get; set; }
```
### Style

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMOGCAPIMapTilesServiceConnection.yml" sourcestartlinenumber="1">Gets or sets the style.</p>


```csharp
public string Style { get; set; }
```
### TemplateUrl

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMOGCAPIMapTilesServiceConnection.yml" sourcestartlinenumber="1">Gets or sets the template url that can be used for tile requests.</p>


```csharp
public string TemplateUrl { get; set; }
```
### TileMatrixSet

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMOGCAPIMapTilesServiceConnection.yml" sourcestartlinenumber="1">Gets or sets the tile matrix set.</p>


```csharp
public string TileMatrixSet { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMOGCAPIMapTilesServiceConnection.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMOGCAPIMapTilesServiceConnection and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Version

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMOGCAPIMapTilesServiceConnection.yml" sourcestartlinenumber="1">Gets or sets the version.</p>


```csharp
public string Version { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMOGCAPIMapTilesServiceConnection.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


