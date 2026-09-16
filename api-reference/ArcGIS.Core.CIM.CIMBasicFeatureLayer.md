# CIMBasicFeatureLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMBasicFeatureLayer.yml" sourcestartlinenumber="1">Represents a basic feature layer, the base class for all layer types that draw feature classes as features.</p>


## Object Signature

```csharp
public abstract class CIMBasicFeatureLayer : CIMBaseLayer, INotifyPropertyChanged, IXmlSerializable, ICIMBasicFeatureLayer
```


## Members

### CIMBasicFeatureLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMBasicFeatureLayer.yml" sourcestartlinenumber="1">Represents a basic feature layer, the base class for all layer types that draw feature classes as features.</p>


```csharp
protected CIMBasicFeatureLayer()
```
### AutoGenerateFeatureTemplates

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBasicFeatureLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to automatically generate feature templates from the renderer.</p>


```csharp
public bool AutoGenerateFeatureTemplates { get; set; }
```
### DisplayFilterChoices

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBasicFeatureLayer.yml" sourcestartlinenumber="1">Gets or sets the current set of display filters.</p>


```csharp
public CIMDisplayFilter[] DisplayFilterChoices { get; set; }
```
### DisplayFilterName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBasicFeatureLayer.yml" sourcestartlinenumber="1">Gets or sets the name of the active display filter.</p>


```csharp
public string DisplayFilterName { get; set; }
```
### DisplayFilters

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBasicFeatureLayer.yml" sourcestartlinenumber="1">Gets or sets the current set of scale based display filters.</p>


```csharp
public CIMDisplayFilter[] DisplayFilters { get; set; }
```
### DisplayFiltersType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBasicFeatureLayer.yml" sourcestartlinenumber="1">Gets or sets DisplayFiltersType value.</p>


```csharp
public DisplayFilterType DisplayFiltersType { get; set; }
```
### EnableDisplayFilters

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBasicFeatureLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the current set of display filters are honored during drawing.</p>


```csharp
public bool EnableDisplayFilters { get; set; }
```
### Extrusion

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBasicFeatureLayer.yml" sourcestartlinenumber="1">Gets or sets the feature extrusion.</p>


```csharp
public CIMFeatureExtrusion Extrusion { get; set; }
```
### FeatureBlendingMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBasicFeatureLayer.yml" sourcestartlinenumber="1">Gets or sets the per-feature blending mode which allows features in a layer to blend against other features in the same layer that have already drawn.</p>


```csharp
public BlendingMode FeatureBlendingMode { get; set; }
```
### FeatureCacheType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBasicFeatureLayer.yml" sourcestartlinenumber="1">Gets or sets the feature cache type.</p>


```csharp
public FeatureCacheType FeatureCacheType { get; set; }
```
### FeatureEffects

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBasicFeatureLayer.yml" sourcestartlinenumber="1">Gets or sets the collection of layer effects that apply to subset of features.</p>


```csharp
public CIMFeatureLayerEffect FeatureEffects { get; set; }
```
### FeatureElevationExpression

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBasicFeatureLayer.yml" sourcestartlinenumber="1">Gets or sets the feature elevation expression.</p>


```csharp
public string FeatureElevationExpression { get; set; }
```
### FeatureElevationExpressionInfo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBasicFeatureLayer.yml" sourcestartlinenumber="1">Gets or sets the expression for setting the feature elevation.</p>


```csharp
public CIMExpressionInfo FeatureElevationExpressionInfo { get; set; }
```
### FeatureSortInfos

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBasicFeatureLayer.yml" sourcestartlinenumber="1">Gets or sets the collection of field names and sort directions used to sort features during draw.</p>


```csharp
public CIMFeatureSortInfo[] FeatureSortInfos { get; set; }
```
### FeatureTable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBasicFeatureLayer.yml" sourcestartlinenumber="1">Gets or sets the feature table.</p>


```csharp
public CIMFeatureTable FeatureTable { get; set; }
```
### FeatureTemplates

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBasicFeatureLayer.yml" sourcestartlinenumber="1">Gets or sets the feature templates.</p>


```csharp
public CIMEditingTemplate[] FeatureTemplates { get; set; }
```
### HtmlPopupEnabled

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBasicFeatureLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether HTML pop-ups are enabled.</p>


```csharp
public bool HtmlPopupEnabled { get; set; }
```
### HtmlPopupFormat

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBasicFeatureLayer.yml" sourcestartlinenumber="1">Gets or sets the HTML pop-ups format.</p>


```csharp
public CIMHtmlPopupFormat HtmlPopupFormat { get; set; }
```
### IsFlattened

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBasicFeatureLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the layer is rasterized and draped against the surface in 3D scenes.</p>


```csharp
public bool IsFlattened { get; set; }
```
### LayerEffectsMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBasicFeatureLayer.yml" sourcestartlinenumber="1">Gets or sets the layer effects mode.</p>


```csharp
public LayerEffectsMode LayerEffectsMode { get; set; }
```
### PageDefinition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBasicFeatureLayer.yml" sourcestartlinenumber="1">Gets or sets the page definition which allows for using current map series page to filter features.</p>


```csharp
public CIMPageDefinition PageDefinition { get; set; }
```
### PolygonSelectionFillColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBasicFeatureLayer.yml" sourcestartlinenumber="1">Gets or sets the selection fill color. Only used for polygons.</p>


```csharp
public CIMColor PolygonSelectionFillColor { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBasicFeatureLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Selectable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBasicFeatureLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the layer is selectable.</p>


```csharp
public bool Selectable { get; set; }
```
### SelectionColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBasicFeatureLayer.yml" sourcestartlinenumber="1">Gets or sets the selection color. For polygons, this is used as the outline color.</p>


```csharp
public CIMColor SelectionColor { get; set; }
```
### SelectionSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBasicFeatureLayer.yml" sourcestartlinenumber="1">Gets or sets the selection symbol.</p>


```csharp
public CIMSymbolReference SelectionSymbol { get; set; }
```
### UseSelectionSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBasicFeatureLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to use the selection symbol.</p>


```csharp
public bool UseSelectionSymbol { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBasicFeatureLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


