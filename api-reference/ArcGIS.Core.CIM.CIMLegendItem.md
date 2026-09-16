# CIMLegendItem

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegendItem.yml" sourcestartlinenumber="1">Represents a legend item.</p>


## Object Signature

```csharp
public abstract class CIMLegendItem : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMLegendItem()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegendItem.yml" sourcestartlinenumber="1">Represents a legend item.</p>


```csharp
protected CIMLegendItem()
```
### AutoVisibility

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegendItem.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the legend item should be displayed if in the visible extent.</p>


```csharp
public bool AutoVisibility { get; set; }
```
### ClassIndent

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegendItem.yml" sourcestartlinenumber="1">Gets or sets distance from the class name to the edge of the legend.</p>


```csharp
public double ClassIndent { get; set; }
```
### CountFormat

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegendItem.yml" sourcestartlinenumber="1">Gets or sets the  feature count format.</p>


```csharp
public CIMNumberFormat CountFormat { get; set; }
```
### CountPrefix

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegendItem.yml" sourcestartlinenumber="1">Gets or sets the feature count prefix.</p>


```csharp
public string CountPrefix { get; set; }
```
### CountSuffix

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegendItem.yml" sourcestartlinenumber="1">Gets or sets the feature count suffix.</p>


```csharp
public string CountSuffix { get; set; }
```
### DescriptionSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegendItem.yml" sourcestartlinenumber="1">Gets or sets the legend item description symbol.</p>


```csharp
public CIMSymbolReference DescriptionSymbol { get; set; }
```
### GroupFilter

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegendItem.yml" sourcestartlinenumber="1">Gets or sets a value specifying which legend groups are displayed.</p>


```csharp
public int[] GroupFilter { get; set; }
```
### GroupLayerNameSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegendItem.yml" sourcestartlinenumber="1">Gets or sets the symbol used to display the group layer name.</p>


```csharp
public CIMSymbolReference GroupLayerNameSymbol { get; set; }
```
### HeadingIndent

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegendItem.yml" sourcestartlinenumber="1">Gets or sets distance from the heading to the edge of the legend.</p>


```csharp
public double HeadingIndent { get; set; }
```
### HeadingSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegendItem.yml" sourcestartlinenumber="1">Gets or sets the legend item heading symbol.</p>


```csharp
public CIMSymbolReference HeadingSymbol { get; set; }
```
### IsVisible

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegendItem.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the legend item is visible.</p>


```csharp
public bool IsVisible { get; set; }
```
### KeepTogetherOption

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegendItem.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the legend item or group should be kept together.</p>


```csharp
public LegendKeepTogetherOption KeepTogetherOption { get; set; }
```
### LabelSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegendItem.yml" sourcestartlinenumber="1">Gets or sets the legend item label symbol.</p>


```csharp
public CIMSymbolReference LabelSymbol { get; set; }
```
### Layer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegendItem.yml" sourcestartlinenumber="1">Gets or sets the legend item layer's path.</p>


```csharp
public string Layer { get; set; }
```
### LayerNameIndent

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegendItem.yml" sourcestartlinenumber="1">Gets or sets distance of the layer name to the edge of the legend.</p>


```csharp
public double LayerNameIndent { get; set; }
```
### LayerNameSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegendItem.yml" sourcestartlinenumber="1">Gets or sets the legend item symbol.</p>


```csharp
public CIMSymbolReference LayerNameSymbol { get; set; }
```
### ManualColumn

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegendItem.yml" sourcestartlinenumber="1">Gets or sets the manual column assignment for a legend item.</p>


```csharp
public int ManualColumn { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegendItem.yml" sourcestartlinenumber="1">Gets or sets the legend item name.</p>


```csharp
public string Name { get; set; }
```
### NewColumn

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegendItem.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether a legend item should be placed in a new column.</p>


```csharp
public bool NewColumn { get; set; }
```
### PatchHeight

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegendItem.yml" sourcestartlinenumber="1">Gets or sets the legend item patch height. Units in points.</p>


```csharp
public double PatchHeight { get; set; }
```
### PatchWidth

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegendItem.yml" sourcestartlinenumber="1">Gets or sets the legend item patch width. Units in points.</p>


```csharp
public double PatchWidth { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegendItem.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ScaleToPatch

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegendItem.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to scale the symbol to the specified patch size.</p>


```csharp
public bool ScaleToPatch { get; set; }
```
### ShowCounts

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegendItem.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the legend should display count statistics.</p>


```csharp
public bool ShowCounts { get; set; }
```
### ShowDescription

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegendItem.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether a legend item description should be displayed.</p>


```csharp
public bool ShowDescription { get; set; }
```
### ShowGroupLayerName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegendItem.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to show the containing group layer name above the item.</p>


```csharp
public bool ShowGroupLayerName { get; set; }
```
### ShowHeading

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegendItem.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the legend item heading should be displayed.</p>


```csharp
public bool ShowHeading { get; set; }
```
### ShowLabels

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegendItem.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the legend item labels should be displayed.</p>


```csharp
public bool ShowLabels { get; set; }
```
### ShowLayerName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegendItem.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the legend item layer name should be displayed.</p>


```csharp
public bool ShowLayerName { get; set; }
```
### UseMapSeriesShape

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegendItem.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to use map series shape instead of map frame to find dynamic classes.</p>


```csharp
public bool UseMapSeriesShape { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegendItem.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


