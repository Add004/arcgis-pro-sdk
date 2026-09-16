# CIMBaseLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseLayer.yml" sourcestartlinenumber="1">Represents a layer of geographic information in a map.</p>


## Object Signature

```csharp
public abstract class CIMBaseLayer : CIMDefinition, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMBaseLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseLayer.yml" sourcestartlinenumber="1">Represents a layer of geographic information in a map.</p>


```csharp
protected CIMBaseLayer()
```
### AllowDrapingOnIntegratedMesh

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether layer can be draped on integrated mesh.</p>


```csharp
public bool AllowDrapingOnIntegratedMesh { get; set; }
```
### Attribution

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseLayer.yml" sourcestartlinenumber="1">Gets or sets the attribution text that appears on a map that draws this layer.</p>


```csharp
public string Attribution { get; set; }
```
### BlendingMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseLayer.yml" sourcestartlinenumber="1">Gets or sets the blending mode for the layer.</p>


```csharp
public BlendingMode BlendingMode { get; set; }
```
### Charts

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseLayer.yml" sourcestartlinenumber="1">Gets or sets identifier the layer's charts.</p>


```csharp
public CIMChart[] Charts { get; set; }
```
### CustomProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseLayer.yml" sourcestartlinenumber="1">Gets or sets the custom properties of the layer. Custom properties are limited to key / value pairs of strings and developers are fully responsible for stored content.</p>


```csharp
public CIMStringMap[] CustomProperties { get; set; }
```
### Description

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseLayer.yml" sourcestartlinenumber="1">Gets or sets the description.</p>


```csharp
public string Description { get; set; }
```
### DisplayCacheType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseLayer.yml" sourcestartlinenumber="1">Gets or sets the display cache type.</p>


```csharp
public DisplayCacheType DisplayCacheType { get; set; }
```
### EnableLayerEffects

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to enable any type of effects on the layer.</p>


```csharp
public bool EnableLayerEffects { get; set; }
```
### Expanded

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this layer is expanded in the contents pane.</p>


```csharp
public bool Expanded { get; set; }
```
### Layer3DProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseLayer.yml" sourcestartlinenumber="1">Gets or sets the 3D layer properties.</p>


```csharp
public CIM3DLayerProperties Layer3DProperties { get; set; }
```
### LayerEffects

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseLayer.yml" sourcestartlinenumber="1">Gets or sets the layer effects for the layer.</p>


```csharp
public CIMLayerEffect[] LayerEffects { get; set; }
```
### LayerElevation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseLayer.yml" sourcestartlinenumber="1">Gets or sets the layer elevation.</p>


```csharp
public CIMLayerElevationSurface LayerElevation { get; set; }
```
### LayerMasks

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseLayer.yml" sourcestartlinenumber="1">Gets or sets the URIs of the layers used as masks.</p>


```csharp
public string[] LayerMasks { get; set; }
```
### LayerScaleVisibilityOptions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseLayer.yml" sourcestartlinenumber="1">Gets or sets the layer's scale visibility options.</p>


```csharp
public CIMLayerScaleVisibilityOptions LayerScaleVisibilityOptions { get; set; }
```
### LayerTemplate

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseLayer.yml" sourcestartlinenumber="1">Gets or sets the layer template.</p>


```csharp
public CIMLayerTemplate LayerTemplate { get; set; }
```
### LayerType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseLayer.yml" sourcestartlinenumber="1">Gets or sets the map layer type.</p>


```csharp
public MapLayerType LayerType { get; set; }
```
### MaxDisplayCacheAge

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseLayer.yml" sourcestartlinenumber="1">Gets or sets the maximum display cache age.</p>


```csharp
public double MaxDisplayCacheAge { get; set; }
```
### MaxScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseLayer.yml" sourcestartlinenumber="1">Gets or sets the maximum scale for layer draw (set as the denominator of the scale's representative fraction).</p>


```csharp
public double MaxScale { get; set; }
```
### MinScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseLayer.yml" sourcestartlinenumber="1">Gets or sets the minimum scale for layer draw (set as the denominator of the scale's representative fraction).</p>


```csharp
public double MinScale { get; set; }
```
### PopupInfo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseLayer.yml" sourcestartlinenumber="1">Gets or sets the pop-up info.</p>


```csharp
public CIMPopupInfo PopupInfo { get; set; }
```
### RasterizeOnExport

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether layer should be rasterized when exporting.</p>


```csharp
public bool RasterizeOnExport { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RefreshRate

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseLayer.yml" sourcestartlinenumber="1">Gets or sets the amount of time to wait between refreshing the layer.</p>


```csharp
public double RefreshRate { get; set; }
```
### RefreshRateUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseLayer.yml" sourcestartlinenumber="1">Gets or sets the units for the amount of time to wait between refreshing the layer.</p>


```csharp
public esriTimeUnits RefreshRateUnit { get; set; }
```
### Searchable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not this layer should be included in the search. This property is honored only by layers that support search.</p>


```csharp
public bool Searchable { get; set; }
```
### ServiceLayerID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseLayer.yml" sourcestartlinenumber="1">Gets or sets identifier that will be used to identify the layer in server.</p>


```csharp
public int ServiceLayerID { get; set; }
```
### ShowLegends

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to show legends.</p>


```csharp
public bool ShowLegends { get; set; }
```
### ShowMapTips

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not the value of the display field or expression is shown when hovering over a layer in the view.</p>


```csharp
public bool ShowMapTips { get; set; }
```
### ShowPopups

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to show pop-ups.</p>


```csharp
public bool ShowPopups { get; set; }
```
### Transparency

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseLayer.yml" sourcestartlinenumber="1">Gets or sets the transparency of the layer as a percentage.</p>


```csharp
public double Transparency { get; set; }
```
### UseVisibilityTimeExtent

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to use a fixed time extent for layer visibility. When true, the map time must overlap this extent for the layer to be visible.</p>


```csharp
public bool UseVisibilityTimeExtent { get; set; }
```
### Visibility

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not this layer is visible.</p>


```csharp
public bool Visibility { get; set; }
```
### VisibilityTimeExtent

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseLayer.yml" sourcestartlinenumber="1">Gets or sets the fixed time extent for layer visibility.</p>


```csharp
public TimeExtent VisibilityTimeExtent { get; set; }
```
### WebMapLayerID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseLayer.yml" sourcestartlinenumber="1">Gets or sets an identifier that will be used to identify the layer in a web map. This value is present if the layer originated in a web map and facilitates matching the layer back to its origin when updating the web map.</p>


```csharp
public string WebMapLayerID { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


