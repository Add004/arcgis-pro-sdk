# CIMImageServiceLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMImageServiceLayer.yml" sourcestartlinenumber="1">Represents an image service layer corresponding to an ArcGIS Server image service.</p>


## Object Signature

```csharp
public class CIMImageServiceLayer : CIMRasterLayer, INotifyPropertyChanged, IXmlSerializable, ICIMBasicFeatureLayer
```


## Members

### CIMImageServiceLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMImageServiceLayer.yml" sourcestartlinenumber="1">Represents an image service layer corresponding to an ArcGIS Server image service.</p>


```csharp
public CIMImageServiceLayer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMImageServiceLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMImageServiceLayer.</p>


```csharp
public CIMImageServiceLayer Clone()
```
### Compression

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMImageServiceLayer.yml" sourcestartlinenumber="1">Gets or sets the compression as a string.</p>


```csharp
public string Compression { get; set; }
```
### CompressionQuality

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMImageServiceLayer.yml" sourcestartlinenumber="1">Gets or sets the compression quality.</p>


```csharp
public int CompressionQuality { get; set; }
```
### DrawFootprints

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMImageServiceLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to draw footprints.</p>


```csharp
public bool DrawFootprints { get; set; }
```
### FeatureTable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMImageServiceLayer.yml" sourcestartlinenumber="1">Gets or sets the feature table.</p>


```csharp
public CIMFeatureTable FeatureTable { get; set; }
```
### FootprintDrawMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMImageServiceLayer.yml" sourcestartlinenumber="1">Gets or sets the footprint draw mode.</p>


```csharp
public RasterFootprintDrawMode FootprintDrawMode { get; set; }
```
### FootprintSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMImageServiceLayer.yml" sourcestartlinenumber="1">Gets or sets the footprint symbol.</p>


```csharp
public CIMSymbolReference FootprintSymbol { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMImageServiceLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMImageServiceLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMImageServiceLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### IgnoreRenderingRuleOnIdentify

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMImageServiceLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to ignore the rendering rule on identify.</p>


```csharp
public bool IgnoreRenderingRuleOnIdentify { get; set; }
```
### MosaicRule

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMImageServiceLayer.yml" sourcestartlinenumber="1">Gets or sets the mosaic rule.</p>


```csharp
public CIMMosaicRule MosaicRule { get; set; }
```
### PageDefinition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMImageServiceLayer.yml" sourcestartlinenumber="1">Gets or sets the page definition which allows for using current map series page to filter features.</p>


```csharp
public CIMPageDefinition PageDefinition { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMImageServiceLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Selectable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMImageServiceLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not the layer is selectable.</p>


```csharp
public bool Selectable { get; set; }
```
### SelectionColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMImageServiceLayer.yml" sourcestartlinenumber="1">Gets or sets the selection color.</p>


```csharp
public CIMColor SelectionColor { get; set; }
```
### SelectionSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMImageServiceLayer.yml" sourcestartlinenumber="1">Gets or sets the selection symbol.</p>


```csharp
public CIMSymbolReference SelectionSymbol { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMImageServiceLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMImageServiceLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseSelectionSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMImageServiceLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to use the selection symbol.</p>


```csharp
public bool UseSelectionSymbol { get; set; }
```
### UseServiceCache

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMImageServiceLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to use the service cache.</p>


```csharp
public bool UseServiceCache { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMImageServiceLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


