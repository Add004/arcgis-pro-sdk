# CIMGeoFeatureLayerBase

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeoFeatureLayerBase.yml" sourcestartlinenumber="1">Represents a layer that draws geographic feature data using a renderer.</p>


## Object Signature

```csharp
public abstract class CIMGeoFeatureLayerBase : CIMBasicFeatureLayer, INotifyPropertyChanged, IXmlSerializable, ICIMBasicFeatureLayer
```


## Members

### CIMGeoFeatureLayerBase()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeoFeatureLayerBase.yml" sourcestartlinenumber="1">Represents a layer that draws geographic feature data using a renderer.</p>


```csharp
protected CIMGeoFeatureLayerBase()
```
### Actions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeoFeatureLayerBase.yml" sourcestartlinenumber="1">Gets or sets the layer actions.</p>


```csharp
[Obsolete("Actions is deprecated at 3.4. This property is obsolete.")]
public CIMLayerAction[] Actions { get; set; }
```
### ExclusionSet

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeoFeatureLayerBase.yml" sourcestartlinenumber="1">Gets or sets the set of excluded features.</p>


```csharp
public long[] ExclusionSet { get; set; }
```
### FeatureMasks

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeoFeatureLayerBase.yml" sourcestartlinenumber="1">Gets or sets the data connection of the masking data.</p>


```csharp
public CIMDataConnection[] FeatureMasks { get; set; }
```
### FeatureReduction

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeoFeatureLayerBase.yml" sourcestartlinenumber="1">Gets or sets the feature reduction technique in use by this layer.</p>


```csharp
public CIMFeatureReduction FeatureReduction { get; set; }
```
### LabelClasses

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeoFeatureLayerBase.yml" sourcestartlinenumber="1">Gets or sets the collection of label class definitions.</p>


```csharp
public CIMLabelClass[] LabelClasses { get; set; }
```
### LabelVisibility

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeoFeatureLayerBase.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to display labels for this layer's label classes.</p>


```csharp
public bool LabelVisibility { get; set; }
```
### MaskedSymbolLayers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeoFeatureLayerBase.yml" sourcestartlinenumber="1">Gets or sets the masked symbol layers. Each SymbolLayerMasking gives the symbol layers that are masked by that masking layer.</p>


```csharp
public CIMSymbolLayerMasking[] MaskedSymbolLayers { get; set; }
```
### PreviousObservationsCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeoFeatureLayerBase.yml" sourcestartlinenumber="1">Gets or sets the previous observation count.</p>


```csharp
public int PreviousObservationsCount { get; set; }
```
### PreviousObservationsRenderer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeoFeatureLayerBase.yml" sourcestartlinenumber="1">Gets or sets the previous observations renderer.</p>


```csharp
public CIMRenderer PreviousObservationsRenderer { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeoFeatureLayerBase.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Renderer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeoFeatureLayerBase.yml" sourcestartlinenumber="1">Gets or sets the primary symbol renderer.</p>


```csharp
public CIMRenderer Renderer { get; set; }
```
### ScaleSymbols

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeoFeatureLayerBase.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to scale the symbols in this layer based on the map's reference scale.</p>


```csharp
public bool ScaleSymbols { get; set; }
```
### ShowPreviousObservations

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeoFeatureLayerBase.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether previous observations are being drawn.</p>


```csharp
public bool ShowPreviousObservations { get; set; }
```
### ShowTracks

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeoFeatureLayerBase.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether track lines are being drawn.</p>


```csharp
public bool ShowTracks { get; set; }
```
### Snappable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeoFeatureLayerBase.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this layer participates in snapping in the editor.</p>


```csharp
public bool Snappable { get; set; }
```
### SymbolLayerDrawing

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeoFeatureLayerBase.yml" sourcestartlinenumber="1">Gets or sets the symbol layer drawing properties.</p>


```csharp
public CIMSymbolLayerDrawing SymbolLayerDrawing { get; set; }
```
### TrackLinesRenderer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeoFeatureLayerBase.yml" sourcestartlinenumber="1">Gets or sets the track renderer when displaying tracks.</p>


```csharp
public CIMRenderer TrackLinesRenderer { get; set; }
```
### UseRealWorldSymbolSizes

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeoFeatureLayerBase.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to use real world symbols sizes (meters) vs. points.</p>


```csharp
public bool UseRealWorldSymbolSizes { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeoFeatureLayerBase.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


