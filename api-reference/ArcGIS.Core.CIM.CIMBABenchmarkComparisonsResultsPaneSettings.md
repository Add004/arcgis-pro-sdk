# CIMBABenchmarkComparisonsResultsPaneSettings

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsResultsPaneSettings.yml" sourcestartlinenumber="1">Represents Benchmark Comparison Results Pane settings.</p>


## Object Signature

```csharp
public class CIMBABenchmarkComparisonsResultsPaneSettings : CIMBAResultsPaneSettings, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMBABenchmarkComparisonsResultsPaneSettings()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsResultsPaneSettings.yml" sourcestartlinenumber="1">Represents Benchmark Comparison Results Pane settings.</p>


```csharp
public CIMBABenchmarkComparisonsResultsPaneSettings()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsResultsPaneSettings.yml" sourcestartlinenumber="1">Creates a deep copy of CIMBABenchmarkComparisonsResultsPaneSettings.</p>


```csharp
public CIMBABenchmarkComparisonsResultsPaneSettings Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsResultsPaneSettings.yml" sourcestartlinenumber="1">Reconstructs the CIMBABenchmarkComparisonsResultsPaneSettings with a specified state from a JSON encoding.</p>


```csharp
public static CIMBABenchmarkComparisonsResultsPaneSettings FromJson(string json, JsonDeserializationSettings settings = null)
```
### HistogramVariable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsResultsPaneSettings.yml" sourcestartlinenumber="1">Gets or sets the histogram variable for the histogram chart.</p>


```csharp
public string HistogramVariable { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsResultsPaneSettings.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ScatterplotChartType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsResultsPaneSettings.yml" sourcestartlinenumber="1">Gets or sets the scatterplot chart type.</p>


```csharp
public BAScatterplotChartType ScatterplotChartType { get; set; }
```
### ScatterplotDotSizeField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsResultsPaneSettings.yml" sourcestartlinenumber="1">Gets or sets the field name for the dot size of the scatterplot chart.</p>


```csharp
public string ScatterplotDotSizeField { get; set; }
```
### ScatterplotXAxisField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsResultsPaneSettings.yml" sourcestartlinenumber="1">Gets or sets the field name for the X-Axis of the scatterplot chart.</p>


```csharp
public string ScatterplotXAxisField { get; set; }
```
### ScatterplotYAxisField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsResultsPaneSettings.yml" sourcestartlinenumber="1">Gets or sets the field name for the Y-Axis of the scatterplot chart.</p>


```csharp
public string ScatterplotYAxisField { get; set; }
```
### ShowRegressionLineOnScatterplot

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsResultsPaneSettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the regression line should be shown on the scatterplot chart.</p>


```csharp
public bool ShowRegressionLineOnScatterplot { get; set; }
```
### StatisticsVariable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsResultsPaneSettings.yml" sourcestartlinenumber="1">Gets or sets the variable for statistics in the Summary tab.</p>


```csharp
public string StatisticsVariable { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsResultsPaneSettings.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMBABenchmarkComparisonsResultsPaneSettings and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABenchmarkComparisonsResultsPaneSettings.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


