# CIMChartScatterPlotMatrixSeries

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartScatterPlotMatrixSeries.yml" sourcestartlinenumber="1">Provides access to members that control scatter plot matrix series.</p>


## Object Signature

```csharp
public class CIMChartScatterPlotMatrixSeries : CIMChartSeries, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMChartScatterPlotMatrixSeries()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartScatterPlotMatrixSeries.yml" sourcestartlinenumber="1">Provides access to members that control scatter plot matrix series.</p>


```csharp
public CIMChartScatterPlotMatrixSeries()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartScatterPlotMatrixSeries.yml" sourcestartlinenumber="1">Creates a deep copy of CIMChartScatterPlotMatrixSeries.</p>


```csharp
public CIMChartScatterPlotMatrixSeries Clone()
```
### DiagonalOption

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartScatterPlotMatrixSeries.yml" sourcestartlinenumber="1">Gets or sets the display option for the diagonal.</p>


```csharp
public ChartSPMDiagonalOption DiagonalOption { get; set; }
```
### DisplayOption

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartScatterPlotMatrixSeries.yml" sourcestartlinenumber="1">Gets or sets the display option for the upper right of the scatter plot matrix.</p>


```csharp
public ChartSPMDisplayOption DisplayOption { get; set; }
```
### FieldLabels

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartScatterPlotMatrixSeries.yml" sourcestartlinenumber="1">Gets or sets the labels for scatter plot and histogram series' axes.</p>


```csharp
public string[] FieldLabels { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartScatterPlotMatrixSeries.yml" sourcestartlinenumber="1">Reconstructs the CIMChartScatterPlotMatrixSeries with a specified state from a JSON encoding.</p>


```csharp
public static CIMChartScatterPlotMatrixSeries FromJson(string json, JsonDeserializationSettings settings = null)
```
### HistogramFillSymbolProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartScatterPlotMatrixSeries.yml" sourcestartlinenumber="1">Gets or sets the fill symbol properties of histograms.</p>


```csharp
public CIMChartFillSymbolProperties HistogramFillSymbolProperties { get; set; }
```
### LowerLeftBreakColors

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartScatterPlotMatrixSeries.yml" sourcestartlinenumber="1">Gets or sets the color for each break in the lower left.</p>


```csharp
public CIMColor[] LowerLeftBreakColors { get; set; }
```
### LowerLeftColorRamp

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartScatterPlotMatrixSeries.yml" sourcestartlinenumber="1">Gets or sets the color ramp for the lower left when RSquared or Pearson's R is selected.</p>


```csharp
public CIMColorRamp LowerLeftColorRamp { get; set; }
```
### LowerLeftDisplayOption

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartScatterPlotMatrixSeries.yml" sourcestartlinenumber="1">Gets or sets the display option for the lower left of the scatter plot matrix.
PreviewPlot currently is not supported in lower left.</p>


```csharp
public ChartSPMDisplayOption LowerLeftDisplayOption { get; set; }
```
### RSquareText

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartScatterPlotMatrixSeries.yml" sourcestartlinenumber="1">Gets or sets the text symbol properties for the RSquare.</p>


```csharp
public CIMChartTextProperties RSquareText { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartScatterPlotMatrixSeries.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ScatterMarkerSymbolProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartScatterPlotMatrixSeries.yml" sourcestartlinenumber="1">Gets or sets the marker symbol properties of scatter plot series.</p>


```csharp
public CIMChartMarkerSymbolProperties ScatterMarkerSymbolProperties { get; set; }
```
### SelectedMiniPlot

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartScatterPlotMatrixSeries.yml" sourcestartlinenumber="1">Gets or sets the index of the selected mini plot (-1 stands for non selected, -2 for uninitialized).</p>


```csharp
public int SelectedMiniPlot { get; set; }
```
### SelectionLineSymbolProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartScatterPlotMatrixSeries.yml" sourcestartlinenumber="1">Gets or sets the line symbol properties of the selection line for the mini plot.</p>


```csharp
public CIMChartLineSymbolProperties SelectionLineSymbolProperties { get; set; }
```
### ShowAsRSquared

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartScatterPlotMatrixSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether show scatter plots as R squared values.</p>


```csharp
[Obsolete("ShowAsRSquared is deprecated at 2.8. ")]
public bool ShowAsRSquared { get; set; }
```
### ShowHistograms

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartScatterPlotMatrixSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to show histograms for all fields.</p>


```csharp
[Obsolete("ShowHistograms is deprecated at 2.8. ")]
public bool ShowHistograms { get; set; }
```
### ShowPValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartScatterPlotMatrixSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to show p-value in the chart.</p>


```csharp
public bool ShowPValue { get; set; }
```
### ShowTrendLine

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartScatterPlotMatrixSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to show a trend line overlay for all scatter plots.</p>


```csharp
public bool ShowTrendLine { get; set; }
```
### SortByType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartScatterPlotMatrixSeries.yml" sourcestartlinenumber="1">Gets or sets the sort by type.</p>


```csharp
public ChartSPMSortByType SortByType { get; set; }
```
### SortDirection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartScatterPlotMatrixSeries.yml" sourcestartlinenumber="1">Gets or sets the direction type of sort order.</p>


```csharp
public ChartSortDirection SortDirection { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartScatterPlotMatrixSeries.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMChartScatterPlotMatrixSeries and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TrendLineFitType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartScatterPlotMatrixSeries.yml" sourcestartlinenumber="1">Gets or sets a trend line fit type.</p>


```csharp
public ChartTrendLineFitType TrendLineFitType { get; set; }
```
### TrendLineSymbolProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartScatterPlotMatrixSeries.yml" sourcestartlinenumber="1">Gets or sets the line symbol properties of the scatter plot series' trend line.</p>


```csharp
public CIMChartLineSymbolProperties TrendLineSymbolProperties { get; set; }
```
### TrendOrder

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartScatterPlotMatrixSeries.yml" sourcestartlinenumber="1">Gets or sets the number of terms in a polynomial or Fourier equation.</p>


```csharp
public int TrendOrder { get; set; }
```
### UpperRightBreakColors

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartScatterPlotMatrixSeries.yml" sourcestartlinenumber="1">Gets or sets the color for each break in the upper right.</p>


```csharp
public CIMColor[] UpperRightBreakColors { get; set; }
```
### UpperRightColorRamp

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartScatterPlotMatrixSeries.yml" sourcestartlinenumber="1">Gets or sets the color ramp for the upper right when RSquared or Pearson's R is selected.</p>


```csharp
public CIMColorRamp UpperRightColorRamp { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartScatterPlotMatrixSeries.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


