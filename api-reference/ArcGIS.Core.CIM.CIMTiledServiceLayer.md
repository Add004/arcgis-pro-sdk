# CIMTiledServiceLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMTiledServiceLayer.yml" sourcestartlinenumber="1">Represents a tiled service layer.</p>


## Object Signature

```csharp
public class CIMTiledServiceLayer : CIMServiceLayer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMTiledServiceLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMTiledServiceLayer.yml" sourcestartlinenumber="1">Represents a tiled service layer.</p>


```csharp
public CIMTiledServiceLayer()
```
### AssociatedFeatureLayerURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTiledServiceLayer.yml" sourcestartlinenumber="1">Gets or sets the URI for a feature layer (feature service-based or portal item-based) that provides pop-up support for the tiled service layer.</p>


```csharp
public string AssociatedFeatureLayerURI { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTiledServiceLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMTiledServiceLayer.</p>


```csharp
public CIMTiledServiceLayer Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTiledServiceLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMTiledServiceLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMTiledServiceLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTiledServiceLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTiledServiceLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMTiledServiceLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTiledServiceLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


