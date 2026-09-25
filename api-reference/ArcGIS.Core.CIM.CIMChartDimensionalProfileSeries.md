# CIMChartDimensionalProfileSeries

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileSeries.yml" sourcestartlinenumber="1">Represents a dimensional profile chart series.</p>


## Object Signature

```csharp
public class CIMChartDimensionalProfileSeries : CIMChartSeries, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMChartDimensionalProfileSeries()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileSeries.yml" sourcestartlinenumber="1">Represents a dimensional profile chart series.</p>


```csharp
public CIMChartDimensionalProfileSeries()
```
### Bands

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileSeries.yml" sourcestartlinenumber="1">Gets or sets the bands for a variable to be plotted over time.</p>


```csharp
public CIMChartDimensionalProfileBands Bands { get; set; }
```
### CCDCArguments

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileSeries.yml" sourcestartlinenumber="1">Gets or sets the CCDC options.</p>


```csharp
public CIMChartDimensionalProfileCCDCArguments CCDCArguments { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileSeries.yml" sourcestartlinenumber="1">Creates a deep copy of CIMChartDimensionalProfileSeries.</p>


```csharp
public CIMChartDimensionalProfileSeries Clone()
```
### DateTimeFormat

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileSeries.yml" sourcestartlinenumber="1">Gets or sets the format of the date plotted on the x axis.</p>


```csharp
public string DateTimeFormat { get; set; }
```
### DimensionValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileSeries.yml" sourcestartlinenumber="1">Gets or sets the dimension values for a variable to be plotted over time.</p>


```csharp
public CIMChartDimensionalProfileDimensionValues DimensionValues { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileSeries.yml" sourcestartlinenumber="1">Reconstructs the CIMChartDimensionalProfileSeries with a specified state from a JSON encoding.</p>


```csharp
public static CIMChartDimensionalProfileSeries FromJson(string json, JsonDeserializationSettings settings = null)
```
### LandTrendrArguments

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileSeries.yml" sourcestartlinenumber="1">Gets or sets the LandTrendr options.</p>


```csharp
public CIMChartDimensionalProfileLandTrendrArguments LandTrendrArguments { get; set; }
```
### PlotType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileSeries.yml" sourcestartlinenumber="1">Gets or sets the type of plot for this chart.</p>


```csharp
public ChartDimensionalProfilePlotType PlotType { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileSeries.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShowTrendEquation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to have a trend equation overlay.</p>


```csharp
public bool ShowTrendEquation { get; set; }
```
### ShowTrendLine

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to show the trend line or not.</p>


```csharp
public bool ShowTrendLine { get; set; }
```
### SpatialAggregationType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileSeries.yml" sourcestartlinenumber="1">Gets or sets the spatial aggregation type to be used to calculate cell values.</p>


```csharp
public ChartAggregationType SpatialAggregationType { get; set; }
```
### StandardizeValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to calculate standardized values.</p>


```csharp
public bool StandardizeValues { get; set; }
```
### TimeAggregationType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileSeries.yml" sourcestartlinenumber="1">Gets or sets the type of grouping to be applied on the time values plotted on the x axis.</p>


```csharp
public ChartTimeAggregationType TimeAggregationType { get; set; }
```
### TimeExtent

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileSeries.yml" sourcestartlinenumber="1">Gets or sets the time extent used by the chart.</p>


```csharp
public TimeExtent TimeExtent { get; set; }
```
### TimeIntervalSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileSeries.yml" sourcestartlinenumber="1">Gets or sets the interval size for the time plotted on the x axis.</p>


```csharp
public double TimeIntervalSize { get; set; }
```
### TimeIntervalUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileSeries.yml" sourcestartlinenumber="1">Gets or sets the unit of time for the interval size.</p>


```csharp
public esriTimeUnits TimeIntervalUnits { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileSeries.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMChartDimensionalProfileSeries and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TrendLineFitType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileSeries.yml" sourcestartlinenumber="1">Gets or sets a trend line fit type.</p>


```csharp
public ChartTrendLineFitType TrendLineFitType { get; set; }
```
### TrendLineSymbolProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileSeries.yml" sourcestartlinenumber="1">Gets or sets the symbol properties for the trend line.</p>


```csharp
public CIMChartLineSymbolProperties TrendLineSymbolProperties { get; set; }
```
### TrendOrder

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileSeries.yml" sourcestartlinenumber="1">Gets or sets the order of the equation when a polynomial or Fourier fit type is used.</p>


```csharp
public int TrendOrder { get; set; }
```
### TrimIncompleteTimeInterval

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether incomplete time intervals at the ends of time interval
ranges are trimmed in order to avoid bias.</p>


```csharp
public bool TrimIncompleteTimeInterval { get; set; }
```
### Variables

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileSeries.yml" sourcestartlinenumber="1">Gets or sets the variables to be plotted over time.</p>


```csharp
public CIMChartDimensionalProfileVariable[] Variables { get; set; }
```
### VerticalOrientation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this is a vertical (true) or horizontal (false) orientation of a dimensional series.</p>


```csharp
public bool VerticalOrientation { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileSeries.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


