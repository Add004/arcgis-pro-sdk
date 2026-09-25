# CIMChartHistogramSeries

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartHistogramSeries.yml" sourcestartlinenumber="1">Provides access to members that control histogram series.</p>


## Object Signature

```csharp
public class CIMChartHistogramSeries : CIMChartSeries, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMChartHistogramSeries()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartHistogramSeries.yml" sourcestartlinenumber="1">Provides access to members that control histogram series.</p>


```csharp
public CIMChartHistogramSeries()
```
### BinCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartHistogramSeries.yml" sourcestartlinenumber="1">Gets or sets the number of bins in classifying input values.</p>


```csharp
public int BinCount { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartHistogramSeries.yml" sourcestartlinenumber="1">Creates a deep copy of CIMChartHistogramSeries.</p>


```csharp
public CIMChartHistogramSeries Clone()
```
### CountField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartHistogramSeries.yml" sourcestartlinenumber="1">Gets or sets a raster attribute table count field in order to calculate a histogram and statistics for fields that have to be adjusted for counts.</p>


```csharp
public string CountField { get; set; }
```
### DataTransformationParameters

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartHistogramSeries.yml" sourcestartlinenumber="1">Gets or sets parameters of a data transformation.</p>


```csharp
public double[] DataTransformationParameters { get; set; }
```
### DataTransformationType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartHistogramSeries.yml" sourcestartlinenumber="1">Gets or sets the type of a data transformation to apply before calculating histogram bins and counts.</p>


```csharp
public ChartDataTransformationType DataTransformationType { get; set; }
```
### DistributionLineSymbolProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartHistogramSeries.yml" sourcestartlinenumber="1">Gets or sets the line symbol for the comparison distribution.</p>


```csharp
public CIMChartLineSymbolProperties DistributionLineSymbolProperties { get; set; }
```
### FillSymbolProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartHistogramSeries.yml" sourcestartlinenumber="1">Gets or sets the properties of the fill symbol.</p>


```csharp
public CIMChartFillSymbolProperties FillSymbolProperties { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartHistogramSeries.yml" sourcestartlinenumber="1">Reconstructs the CIMChartHistogramSeries with a specified state from a JSON encoding.</p>


```csharp
public static CIMChartHistogramSeries FromJson(string json, JsonDeserializationSettings settings = null)
```
### MeanLineSymbolProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartHistogramSeries.yml" sourcestartlinenumber="1">Gets or sets the mean line symbol properties of the line series.</p>


```csharp
public CIMChartLineSymbolProperties MeanLineSymbolProperties { get; set; }
```
### MedianLineSymbolProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartHistogramSeries.yml" sourcestartlinenumber="1">Gets or sets the median line symbol properties of the line series.</p>


```csharp
public CIMChartLineSymbolProperties MedianLineSymbolProperties { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartHistogramSeries.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShowComparisonDistribution

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartHistogramSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to show a comparison distribution line overlay for the histogram chart.</p>


```csharp
public bool ShowComparisonDistribution { get; set; }
```
### ShowMean

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartHistogramSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to show the mean line on the histogram.</p>


```csharp
public bool ShowMean { get; set; }
```
### ShowMedian

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartHistogramSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to show the median line on a histogram.</p>


```csharp
public bool ShowMedian { get; set; }
```
### ShowStandardDeviation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartHistogramSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to show the standard deviation band on the histogram.</p>


```csharp
public bool ShowStandardDeviation { get; set; }
```
### StandardDeviationLineSymbolProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartHistogramSeries.yml" sourcestartlinenumber="1">Gets or sets the line symbol for the standard deviation.</p>


```csharp
public CIMChartLineSymbolProperties StandardDeviationLineSymbolProperties { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartHistogramSeries.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMChartHistogramSeries and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartHistogramSeries.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


