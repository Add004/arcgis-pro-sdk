# CIMChart

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMChart.yml" sourcestartlinenumber="1">Provides access to members that control chart properties.</p>


## Object Signature

```csharp
public class CIMChart : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMChart()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMChart.yml" sourcestartlinenumber="1">Provides access to members that control chart properties.</p>


```csharp
public CIMChart()
```
### Axes

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChart.yml" sourcestartlinenumber="1">Gets or sets the properties of chart axis.</p>


```csharp
public CIMChartAxis[] Axes { get; set; }
```
### ChartType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChart.yml" sourcestartlinenumber="1">Gets or sets the type of chart.</p>


```csharp
public ChartType ChartType { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChart.yml" sourcestartlinenumber="1">Creates a deep copy of CIMChart.</p>


```csharp
public CIMChart Clone()
```
### EnableServerSideProcessing

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChart.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the server-side processing is enabled for supported chart types and data sources.</p>


```csharp
public bool EnableServerSideProcessing { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChart.yml" sourcestartlinenumber="1">Reconstructs the CIMChart with a specified state from a JSON encoding.</p>


```csharp
public static CIMChart FromJson(string json, JsonDeserializationSettings settings = null)
```
### GeneralProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChart.yml" sourcestartlinenumber="1">Gets or sets the general properties of the chart.</p>


```csharp
public CIMChartGeneralProperties GeneralProperties { get; set; }
```
### Legend

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChart.yml" sourcestartlinenumber="1">Gets or sets the legend properties of the chart.</p>


```csharp
public CIMChartLegend Legend { get; set; }
```
### MapSelectionHandling

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChart.yml" sourcestartlinenumber="1">Gets or sets a setting which indicates whether chart handles selection in the input layer by creating series only from the selected data or
highlights selected values on the chart made from entire dataset.</p>


```csharp
public ChartMapSelectionHandling MapSelectionHandling { get; set; }
```
### MetaData

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChart.yml" sourcestartlinenumber="1">Gets or sets the client metadata about the chart.</p>


```csharp
public string MetaData { get; set; }
```
### MultiSeriesChartProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChart.yml" sourcestartlinenumber="1">Gets or sets the multi series chart properties for supported chart types.</p>


```csharp
public CIMMultiSeriesChartProperties MultiSeriesChartProperties { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChart.yml" sourcestartlinenumber="1">Gets or sets the name of the chart.</p>


```csharp
public string Name { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChart.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Series

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChart.yml" sourcestartlinenumber="1">Gets or sets the series properties of the chart.</p>


```csharp
public CIMChartSeries[] Series { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChart.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMChart and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChart.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


