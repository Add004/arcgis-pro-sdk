# CIMChartBarSeries

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBarSeries.yml" sourcestartlinenumber="1">Provides access to members that control bar chart series.</p>


## Object Signature

```csharp
public class CIMChartBarSeries : CIMChartSeries, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMChartBarSeries()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBarSeries.yml" sourcestartlinenumber="1">Provides access to members that control bar chart series.</p>


```csharp
public CIMChartBarSeries()
```
### BarSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBarSeries.yml" sourcestartlinenumber="1">Gets or sets the relative width of the bar as a percentage.</p>


```csharp
public int BarSize { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBarSeries.yml" sourcestartlinenumber="1">Creates a deep copy of CIMChartBarSeries.</p>


```csharp
public CIMChartBarSeries Clone()
```
### FillSymbolProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBarSeries.yml" sourcestartlinenumber="1">Gets or sets the properties of the fill symbol border.</p>


```csharp
public CIMChartFillSymbolProperties FillSymbolProperties { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBarSeries.yml" sourcestartlinenumber="1">Reconstructs the CIMChartBarSeries with a specified state from a JSON encoding.</p>


```csharp
public static CIMChartBarSeries FromJson(string json, JsonDeserializationSettings settings = null)
```
### MatchLayerSymbology

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBarSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether bar chart should match layer symbology.</p>


```csharp
public bool MatchLayerSymbology { get; set; }
```
### MovingAverageLineSymbolProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBarSeries.yml" sourcestartlinenumber="1">Gets or sets the line symbol for the moving average.</p>


```csharp
public CIMChartLineSymbolProperties MovingAverageLineSymbolProperties { get; set; }
```
### MovingAveragePeriod

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBarSeries.yml" sourcestartlinenumber="1">Gets or sets a period value for moving average calculation.</p>


```csharp
public long MovingAveragePeriod { get; set; }
```
### MultipleBarType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBarSeries.yml" sourcestartlinenumber="1">Gets or sets the type of multiple bar-series chart.</p>


```csharp
public ChartMultiBarType MultipleBarType { get; set; }
```
### NullCategoryFillSymbolProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBarSeries.yml" sourcestartlinenumber="1">Gets or sets the fill symbol for the null category.</p>


```csharp
public CIMChartFillSymbolProperties NullCategoryFillSymbolProperties { get; set; }
```
### NullCategoryLabel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBarSeries.yml" sourcestartlinenumber="1">Gets or sets the label for the null category.</p>


```csharp
public string NullCategoryLabel { get; set; }
```
### NullPolicy

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBarSeries.yml" sourcestartlinenumber="1">Gets or sets the policy for handling missing data.</p>


```csharp
public ChartNullPolicy NullPolicy { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBarSeries.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShowMovingAverage

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBarSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to show a moving average line overlay.</p>


```csharp
public bool ShowMovingAverage { get; set; }
```
### ShowNullCategory

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBarSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to show null category values as a separate category.</p>


```csharp
public bool ShowNullCategory { get; set; }
```
### SortedCategoryValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBarSeries.yml" sourcestartlinenumber="1">Gets or sets the array of sorted category values for custom sort.</p>


```csharp
public string[] SortedCategoryValues { get; set; }
```
### TimeBinningProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBarSeries.yml" sourcestartlinenumber="1">Gets or sets the time binning properties for bar category field values.
If null, bar series will use unique values to create bar categories.</p>


```csharp
public CIMChartTimeBinningProperties TimeBinningProperties { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBarSeries.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMChartBarSeries and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### VerticalOrientation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBarSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this bar chart is vertically oriented.</p>


```csharp
public bool VerticalOrientation { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBarSeries.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


