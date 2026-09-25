# CIMChartLineSeries

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLineSeries.yml" sourcestartlinenumber="1">Provides access to members that control line series.</p>


## Object Signature

```csharp
public class CIMChartLineSeries : CIMChartSeries, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMChartLineSeries()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLineSeries.yml" sourcestartlinenumber="1">Provides access to members that control line series.</p>


```csharp
public CIMChartLineSeries()
```
### CalculateAutomaticTimeInterval

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLineSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the time interval units and size are automatically calculated.</p>


```csharp
public bool CalculateAutomaticTimeInterval { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLineSeries.yml" sourcestartlinenumber="1">Creates a deep copy of CIMChartLineSeries.</p>


```csharp
public CIMChartLineSeries Clone()
```
### FillSymbolProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLineSeries.yml" sourcestartlinenumber="1">Gets or sets the properties of the area fill symbol. This property is only being used if ShowAsArea is true.</p>


```csharp
public CIMChartFillSymbolProperties FillSymbolProperties { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLineSeries.yml" sourcestartlinenumber="1">Reconstructs the CIMChartLineSeries with a specified state from a JSON encoding.</p>


```csharp
public static CIMChartLineSeries FromJson(string json, JsonDeserializationSettings settings = null)
```
### LineSymbolProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLineSeries.yml" sourcestartlinenumber="1">Gets or sets the line symbol properties of the line series.</p>


```csharp
public CIMChartLineSymbolProperties LineSymbolProperties { get; set; }
```
### MarkerSymbolProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLineSeries.yml" sourcestartlinenumber="1">Gets or sets the marker symbol properties of the line series.</p>


```csharp
public CIMChartMarkerSymbolProperties MarkerSymbolProperties { get; set; }
```
### MovingAverageLineSymbolProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLineSeries.yml" sourcestartlinenumber="1">Gets or sets the line symbol for the moving average.</p>


```csharp
public CIMChartLineSymbolProperties MovingAverageLineSymbolProperties { get; set; }
```
### MovingAveragePeriod

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLineSeries.yml" sourcestartlinenumber="1">Gets or sets a period value for moving average calculation.</p>


```csharp
public long MovingAveragePeriod { get; set; }
```
### NullPolicy

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLineSeries.yml" sourcestartlinenumber="1">Gets or sets the policy for handling missing data.</p>


```csharp
public ChartNullPolicy NullPolicy { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLineSeries.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ReferenceTime

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLineSeries.yml" sourcestartlinenumber="1">Gets or sets the reference time value. Valid when TimeAggregationType property is set to ReferenceTime.</p>


```csharp
public TimeInstant ReferenceTime { get; set; }
```
### ShowAsArea

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLineSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the line series shows as an area.</p>


```csharp
public bool ShowAsArea { get; set; }
```
### ShowMovingAverage

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLineSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to show a moving average line overlay.</p>


```csharp
public bool ShowMovingAverage { get; set; }
```
### SmoothLine

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLineSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the line is smoothed with curves.</p>


```csharp
public bool SmoothLine { get; set; }
```
### SortedCategoryValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLineSeries.yml" sourcestartlinenumber="1">Gets or sets the array of sorted category values for custom sort.</p>


```csharp
public string[] SortedCategoryValues { get; set; }
```
### StackingType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLineSeries.yml" sourcestartlinenumber="1">Gets or sets the type of series stacking.</p>


```csharp
public ChartStackingType StackingType { get; set; }
```
### TimeAggregationType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLineSeries.yml" sourcestartlinenumber="1">Gets or sets the time aggregation type.</p>


```csharp
public ChartTimeAggregationType TimeAggregationType { get; set; }
```
### TimeIntervalSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLineSeries.yml" sourcestartlinenumber="1">Gets or sets the time interval size.</p>


```csharp
public double TimeIntervalSize { get; set; }
```
### TimeIntervalUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLineSeries.yml" sourcestartlinenumber="1">Gets or sets the units used for the time interval size.</p>


```csharp
public esriTimeUnits TimeIntervalUnits { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLineSeries.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMChartLineSeries and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TrimIncompleteTimeInterval

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLineSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether incomplete time intervals at the ends of time interval ranges are trimmed in order to avoid bias.</p>


```csharp
public bool TrimIncompleteTimeInterval { get; set; }
```
### VerticalOrientation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLineSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this is a vertical (true) or horizontal (false) orientation of a line series.</p>


```csharp
public bool VerticalOrientation { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLineSeries.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


