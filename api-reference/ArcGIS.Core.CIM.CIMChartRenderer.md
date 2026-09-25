# CIMChartRenderer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartRenderer.yml" sourcestartlinenumber="1">Depicts feature values as a chart drawn over the feature itself.</p>


## Object Signature

```csharp
public class CIMChartRenderer : CIMRenderer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMChartRenderer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartRenderer.yml" sourcestartlinenumber="1">Depicts feature values as a chart drawn over the feature itself.</p>


```csharp
public CIMChartRenderer()
```
### BarrierWeight

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartRenderer.yml" sourcestartlinenumber="1">Gets or sets the barrier weight for chart label collision.</p>


```csharp
public BarrierWeight BarrierWeight { get; set; }
```
### BaseSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartRenderer.yml" sourcestartlinenumber="1">Gets or sets the symbol that depicts the underlying feature geometry.</p>


```csharp
public CIMSymbolReference BaseSymbol { get; set; }
```
### ChartSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartRenderer.yml" sourcestartlinenumber="1">Gets or sets the symbol that depicts the chart.</p>


```csharp
public CIMSymbolReference ChartSymbol { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartRenderer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMChartRenderer.</p>


```csharp
public CIMChartRenderer Clone()
```
### ColorRamp

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartRenderer.yml" sourcestartlinenumber="1">Gets or sets the color ramp.</p>


```csharp
public CIMColorRamp ColorRamp { get; set; }
```
### DrawChartSymbolsAboveAllLayers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartRenderer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to draw chart symbols for line or polygon features above all layers.</p>


```csharp
public bool DrawChartSymbolsAboveAllLayers { get; set; }
```
### ExclusionClause

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartRenderer.yml" sourcestartlinenumber="1">Gets or sets the exclusion clause.</p>


```csharp
public string ExclusionClause { get; set; }
```
### ExclusionDescription

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartRenderer.yml" sourcestartlinenumber="1">Gets or sets the exclusion description.</p>


```csharp
public string ExclusionDescription { get; set; }
```
### ExclusionLabel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartRenderer.yml" sourcestartlinenumber="1">Gets or sets the exclusion label.</p>


```csharp
public string ExclusionLabel { get; set; }
```
### ExclusionSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartRenderer.yml" sourcestartlinenumber="1">Gets or sets the exclusion symbol.</p>


```csharp
public CIMSymbolReference ExclusionSymbol { get; set; }
```
### ExclusionSymbolCustomPatch

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartRenderer.yml" sourcestartlinenumber="1">Gets or sets the custom patch for the exclusion symbol.</p>


```csharp
public CIMLegendPatch ExclusionSymbolCustomPatch { get; set; }
```
### ExclusionSymbolPatch

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartRenderer.yml" sourcestartlinenumber="1">Gets or sets the patch shape for the exclusion symbol.</p>


```csharp
public PatchShape ExclusionSymbolPatch { get; set; }
```
### FieldLabels

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartRenderer.yml" sourcestartlinenumber="1">Gets or sets the labels that will be shown next to fields in the legend.</p>


```csharp
public string[] FieldLabels { get; set; }
```
### FieldNames

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartRenderer.yml" sourcestartlinenumber="1">Gets or sets the field names used to populate the chart.</p>


```csharp
public string[] FieldNames { get; set; }
```
### FieldTotals

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartRenderer.yml" sourcestartlinenumber="1">Gets or sets the field totals.</p>


```csharp
public double[] FieldTotals { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartRenderer.yml" sourcestartlinenumber="1">Reconstructs the CIMChartRenderer with a specified state from a JSON encoding.</p>


```csharp
public static CIMChartRenderer FromJson(string json, JsonDeserializationSettings settings = null)
```
### Label

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartRenderer.yml" sourcestartlinenumber="1">Gets or sets the renderer label.</p>


```csharp
public string Label { get; set; }
```
### MaxValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartRenderer.yml" sourcestartlinenumber="1">Gets or sets the maximum value.</p>


```csharp
public double MaxValue { get; set; }
```
### NormalizationField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartRenderer.yml" sourcestartlinenumber="1">Gets or sets the normalization field.</p>


```csharp
public string NormalizationField { get; set; }
```
### NormalizationTotal

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartRenderer.yml" sourcestartlinenumber="1">Gets or sets the normalization total.</p>


```csharp
public double NormalizationTotal { get; set; }
```
### NormalizationType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartRenderer.yml" sourcestartlinenumber="1">Gets or sets the normalization type.</p>


```csharp
public DataNormalizationMethod NormalizationType { get; set; }
```
### PreventChartOverlap

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartRenderer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to prevent charts from visually overlapping on the map.</p>


```csharp
public bool PreventChartOverlap { get; set; }
```
### ProportionalPieSizeOptions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartRenderer.yml" sourcestartlinenumber="1">Gets or sets the proportional pie size options.</p>


```csharp
public CIMProportionalPieSizeOptions ProportionalPieSizeOptions { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartRenderer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShowSizeLegend

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartRenderer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to show a legend group illustrating the chart's size.</p>


```csharp
public bool ShowSizeLegend { get; set; }
```
### SizeLegendHeading

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartRenderer.yml" sourcestartlinenumber="1">Gets or sets the heading of the size legend group.</p>


```csharp
public string SizeLegendHeading { get; set; }
```
### SizeLegendLeaderlineColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartRenderer.yml" sourcestartlinenumber="1">Gets or sets the color of the leader line for the size legend group.</p>


```csharp
public CIMColor SizeLegendLeaderlineColor { get; set; }
```
### SizeLegendOutlineColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartRenderer.yml" sourcestartlinenumber="1">Gets or sets the color of the outline for the size legend group.</p>


```csharp
public CIMColor SizeLegendOutlineColor { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartRenderer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMChartRenderer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseExclusionSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartRenderer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to use the exclusion symbol.</p>


```csharp
public bool UseExclusionSymbol { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartRenderer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


