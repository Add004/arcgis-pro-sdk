# CIMLegend

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegend.yml" sourcestartlinenumber="1">Represents a legend on a layout.</p>


## Object Signature

```csharp
public class CIMLegend : CIMMapSurround, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMLegend()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegend.yml" sourcestartlinenumber="1">Represents a legend on a layout.</p>


```csharp
public CIMLegend()
```
### AutoAdd

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegend.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether items should automatically be added to the legend.</p>


```csharp
public bool AutoAdd { get; set; }
```
### AutoFonts

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegend.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether legend fonts should automatically be sized.</p>


```csharp
public bool AutoFonts { get; set; }
```
### AutoReorder

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegend.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the items should automatically be ordered when added.</p>


```csharp
public bool AutoReorder { get; set; }
```
### AutoVisibility

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegend.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the items should display when not in the visible extent.</p>


```csharp
public bool AutoVisibility { get; set; }
```
### BalanceColumns

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegend.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to balance the columns or simply &quot;pour&quot; the text into each column.</p>


```csharp
public bool BalanceColumns { get; set; }
```
### ClassGap

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegend.yml" sourcestartlinenumber="1">Gets or sets the gap between classes. Units in points.</p>


```csharp
public double ClassGap { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegend.yml" sourcestartlinenumber="1">Creates a deep copy of CIMLegend.</p>


```csharp
public CIMLegend Clone()
```
### Columns

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegend.yml" sourcestartlinenumber="1">Gets or sets the number of legend columns when either of the following fitting strategies is in ///effect: SpecifyColumnsAndAdjustFrame or SpecifyColumnsAndAdjustSize.</p>


```csharp
public int Columns { get; set; }
```
### DefaultLegendItem

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegend.yml" sourcestartlinenumber="1">Gets or sets the default legend item used as the basis for new legend item creation.</p>


```csharp
public CIMLegendItem DefaultLegendItem { get; set; }
```
### DefaultPatchHeight

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegend.yml" sourcestartlinenumber="1">Gets or sets an items default patch height. Units in points.</p>


```csharp
public double DefaultPatchHeight { get; set; }
```
### DefaultPatchWidth

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegend.yml" sourcestartlinenumber="1">Gets or sets an items default patch width. Units in points.</p>


```csharp
public double DefaultPatchWidth { get; set; }
```
### DescriptionWidth

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegend.yml" sourcestartlinenumber="1">Gets or sets the description width threshold. Units in points.</p>


```csharp
public double DescriptionWidth { get; set; }
```
### ExcludedLayers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegend.yml" sourcestartlinenumber="1">Gets or sets a collection of layer URIs from the associated map that are explicitly excluded from the legend.</p>


```csharp
public string[] ExcludedLayers { get; set; }
```
### FeatureCountPrefix

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegend.yml" sourcestartlinenumber="1">Gets or sets the feature count prefix.
Deprecated in 1.4. Use count prefix in legend item instead.</p>


```csharp
public string FeatureCountPrefix { get; set; }
```
### FeatureCountSuffix

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegend.yml" sourcestartlinenumber="1">Gets or sets the feature count suffix.
Deprecated in 1.4. Use count suffix in legend item instead.</p>


```csharp
public string FeatureCountSuffix { get; set; }
```
### FittingStrategy

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegend.yml" sourcestartlinenumber="1">Gets or sets the legends fitting strategy.</p>


```csharp
public LegendFittingStrategy FittingStrategy { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegend.yml" sourcestartlinenumber="1">Reconstructs the CIMLegend with a specified state from a JSON encoding.</p>


```csharp
public static CIMLegend FromJson(string json, JsonDeserializationSettings settings = null)
```
### GroupGap

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegend.yml" sourcestartlinenumber="1">Gets or sets the gap between groups. Units in points.</p>


```csharp
public double GroupGap { get; set; }
```
### GroupLayerNameGap

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegend.yml" sourcestartlinenumber="1">Gets or sets the gap following the group layer name.</p>


```csharp
public double GroupLayerNameGap { get; set; }
```
### HeadingGap

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegend.yml" sourcestartlinenumber="1">Gets or sets the heading gap. Units in points.</p>


```csharp
public double HeadingGap { get; set; }
```
### HorizontalItemGap

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegend.yml" sourcestartlinenumber="1">Gets or sets the gap between horizontal items. Units in points.</p>


```csharp
public double HorizontalItemGap { get; set; }
```
### ItemGap

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegend.yml" sourcestartlinenumber="1">Gets or sets the gap between items. Units in points,.</p>


```csharp
public double ItemGap { get; set; }
```
### Items

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegend.yml" sourcestartlinenumber="1">Gets or sets a collection of items in a layout.</p>


```csharp
public CIMLegendItem[] Items { get; set; }
```
### LabelWidth

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegend.yml" sourcestartlinenumber="1">Gets or sets the label width. Units in points.</p>


```csharp
public double LabelWidth { get; set; }
```
### LayerNameGap

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegend.yml" sourcestartlinenumber="1">Gets or sets the layer name gap. Units in points.</p>


```csharp
public double LayerNameGap { get; set; }
```
### MakeColumnsSameWidth

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegend.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to ensure all the columns are the same width.</p>


```csharp
public bool MakeColumnsSameWidth { get; set; }
```
### MinFontSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegend.yml" sourcestartlinenumber="1">Gets or sets the minimum font size. Units in points.</p>


```csharp
public double MinFontSize { get; set; }
```
### PatchGap

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegend.yml" sourcestartlinenumber="1">Gets or sets the gap between patches. Units in points.</p>


```csharp
public double PatchGap { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegend.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RightToLeft

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegend.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether right to left orientation should be applied.</p>


```csharp
public bool RightToLeft { get; set; }
```
### ScaleSymbols

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegend.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether symbols should be scaled.</p>


```csharp
public bool ScaleSymbols { get; set; }
```
### ShowTitle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegend.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the legend title should be displayed.</p>


```csharp
public bool ShowTitle { get; set; }
```
### TextGap

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegend.yml" sourcestartlinenumber="1">Gets or sets the gap between text. Units in points.</p>


```csharp
public double TextGap { get; set; }
```
### Title

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegend.yml" sourcestartlinenumber="1">Gets or sets the title for the legend.</p>


```csharp
public string Title { get; set; }
```
### TitleGap

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegend.yml" sourcestartlinenumber="1">Gets or sets the title gap. Units in points.</p>


```csharp
public double TitleGap { get; set; }
```
### TitleSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegend.yml" sourcestartlinenumber="1">Gets or sets the symbol for the title.</p>


```csharp
public CIMSymbolReference TitleSymbol { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegend.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMLegend and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegend.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


