# CIMVectorTileLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMVectorTileLayer.yml" sourcestartlinenumber="1">Represents a VectorTile layer.</p>


## Object Signature

```csharp
public class CIMVectorTileLayer : CIMBaseLayer, INotifyPropertyChanged, IXmlSerializable
```

## Remarks

<p>
    A VectorTileServiceLayer provides rich cartographic content in a fast and efficient vector tile format. It may have multiple styles and if so users can choose which style to use to display the layer's vector geometries.
    </p>
<p>
    Logically a VectorTileServiceLayer is more like a basemap layer in that it is typically composed of several distinct data sources (e.g. roads, cities, hydrology, buildings) that can provide context and background but in a way that is typically more performant than raster tile layers.
    </p>


## Members

### CIMVectorTileLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMVectorTileLayer.yml" sourcestartlinenumber="1">Represents a VectorTile layer.</p>


```csharp
public CIMVectorTileLayer()
```
### AssociatedFeatureLayerURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVectorTileLayer.yml" sourcestartlinenumber="1">Gets or sets the URI for a feature layer (feature service-based or portal item-based) that provides pop-up support for the vector tile layer.</p>


```csharp
public string AssociatedFeatureLayerURI { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVectorTileLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMVectorTileLayer.</p>


```csharp
public CIMVectorTileLayer Clone()
```
### CurrentStyle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVectorTileLayer.yml" sourcestartlinenumber="1">Gets or sets the current style the vector tile layer features should be rendered with.</p>


```csharp
public string CurrentStyle { get; set; }
```
### DataConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVectorTileLayer.yml" sourcestartlinenumber="1">Gets or sets the data connection to the VectorTile resource.</p>


```csharp
public CIMVectorTileDataConnection DataConnection { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVectorTileLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMVectorTileLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMVectorTileLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVectorTileLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVectorTileLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMVectorTileLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVectorTileLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


