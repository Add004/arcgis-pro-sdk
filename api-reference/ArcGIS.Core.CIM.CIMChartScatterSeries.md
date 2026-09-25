# CIMChartScatterSeries

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartScatterSeries.yml" sourcestartlinenumber="1">Provides access to members that control point chart series.</p>


## Object Signature

```csharp
public class CIMChartScatterSeries : CIMChartSeries, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMChartScatterSeries()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartScatterSeries.yml" sourcestartlinenumber="1">Provides access to members that control point chart series.</p>


```csharp
public CIMChartScatterSeries()
```
### BubbleMaximumSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartScatterSeries.yml" sourcestartlinenumber="1">Gets or sets the maximum size of the bubbles. Units in pixels.</p>


```csharp
public double BubbleMaximumSize { get; set; }
```
### BubbleMinimumSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartScatterSeries.yml" sourcestartlinenumber="1">Gets or sets the minimum size of the bubbles. Units in pixels.</p>


```csharp
public double BubbleMinimumSize { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartScatterSeries.yml" sourcestartlinenumber="1">Creates a deep copy of CIMChartScatterSeries.</p>


```csharp
public CIMChartScatterSeries Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartScatterSeries.yml" sourcestartlinenumber="1">Reconstructs the CIMChartScatterSeries with a specified state from a JSON encoding.</p>


```csharp
public static CIMChartScatterSeries FromJson(string json, JsonDeserializationSettings settings = null)
```
### MarkerSymbolProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartScatterSeries.yml" sourcestartlinenumber="1">Gets or sets the marker symbol properties of the point series.</p>


```csharp
public CIMChartMarkerSymbolProperties MarkerSymbolProperties { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartScatterSeries.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShowTrendEquation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartScatterSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to have a trend equation overlay.</p>


```csharp
public bool ShowTrendEquation { get; set; }
```
### ShowTrendLine

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartScatterSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to show the trend line or not.</p>


```csharp
public bool ShowTrendLine { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartScatterSeries.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMChartScatterSeries and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TrendLineFitType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartScatterSeries.yml" sourcestartlinenumber="1">Gets or sets a trend line fit type.</p>


```csharp
public ChartTrendLineFitType TrendLineFitType { get; set; }
```
### TrendLineSymbolProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartScatterSeries.yml" sourcestartlinenumber="1">Gets or sets the symbol properties for the trend line symbol.</p>


```csharp
public CIMChartLineSymbolProperties TrendLineSymbolProperties { get; set; }
```
### TrendOrder

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartScatterSeries.yml" sourcestartlinenumber="1">Gets or sets the number of terms in a polynomial or Fourier equation.</p>


```csharp
public int TrendOrder { get; set; }
```
### VisualAggregationGridColumnCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartScatterSeries.yml" sourcestartlinenumber="1">Gets or sets the number of columns for visual aggregation grid.</p>


```csharp
public long VisualAggregationGridColumnCount { get; set; }
```
### VisualAggregationGridRowCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartScatterSeries.yml" sourcestartlinenumber="1">Gets or sets the number of rows for visual aggregation grid.</p>


```csharp
public long VisualAggregationGridRowCount { get; set; }
```
### VisualAggregationThreshold

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartScatterSeries.yml" sourcestartlinenumber="1">Gets or sets the number of points in a scatter plot series that will trigger visual aggregation.</p>


```csharp
public long VisualAggregationThreshold { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartScatterSeries.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


