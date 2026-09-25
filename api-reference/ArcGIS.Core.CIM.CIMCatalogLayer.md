# CIMCatalogLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMCatalogLayer.yml" sourcestartlinenumber="1">Represents a layer which dynamically loads its sublayers according to scale and extent constraints.</p>


## Object Signature

```csharp
public class CIMCatalogLayer : CIMBasicFeatureLayer, INotifyPropertyChanged, IXmlSerializable, ICIMBasicFeatureLayer
```


## Members

### CIMCatalogLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMCatalogLayer.yml" sourcestartlinenumber="1">Represents a layer which dynamically loads its sublayers according to scale and extent constraints.</p>


```csharp
public CIMCatalogLayer()
```
### CatalogDynamicGroupLayer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCatalogLayer.yml" sourcestartlinenumber="1">Gets or sets the path of the composite layer that contains all the currently-visible layers.
The layers inside the composite layer are updated as the extent of the active view changes.</p>


```csharp
public string CatalogDynamicGroupLayer { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCatalogLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMCatalogLayer.</p>


```csharp
public CIMCatalogLayer Clone()
```
### FootprintLayer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCatalogLayer.yml" sourcestartlinenumber="1">Gets or sets the path of the footprint feature layer.</p>


```csharp
public string FootprintLayer { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCatalogLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMCatalogLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMCatalogLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### MaximumVisibleSublayers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCatalogLayer.yml" sourcestartlinenumber="1">Gets or sets upper bound for number of layers in view.</p>


```csharp
public int MaximumVisibleSublayers { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCatalogLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCatalogLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMCatalogLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCatalogLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


