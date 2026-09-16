# CIMChartProbabilityPlotSeries

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartProbabilityPlotSeries.yml" sourcestartlinenumber="1">Provides access to members that control probability plot series.</p>


## Object Signature

```csharp
public class CIMChartProbabilityPlotSeries : CIMChartSeries, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMChartProbabilityPlotSeries()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartProbabilityPlotSeries.yml" sourcestartlinenumber="1">Provides access to members that control probability plot series.</p>


```csharp
public CIMChartProbabilityPlotSeries()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartProbabilityPlotSeries.yml" sourcestartlinenumber="1">Creates a deep copy of CIMChartProbabilityPlotSeries.</p>


```csharp
public CIMChartProbabilityPlotSeries Clone()
```
### DataTransformationParameters

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartProbabilityPlotSeries.yml" sourcestartlinenumber="1">Gets or sets parameters of a data transformation.</p>


```csharp
public double[] DataTransformationParameters { get; set; }
```
### DataTransformationType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartProbabilityPlotSeries.yml" sourcestartlinenumber="1">Gets or sets the type of data transformation to apply before calculating Normal Q-Q Plot.</p>


```csharp
public ChartDataTransformationType DataTransformationType { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartProbabilityPlotSeries.yml" sourcestartlinenumber="1">Reconstructs the CIMChartProbabilityPlotSeries with a specified state from a JSON encoding.</p>


```csharp
public static CIMChartProbabilityPlotSeries FromJson(string json, JsonDeserializationSettings settings = null)
```
### MarkerSymbolProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartProbabilityPlotSeries.yml" sourcestartlinenumber="1">Gets or sets the marker symbol properties of the probability plot series.</p>


```csharp
public CIMChartMarkerSymbolProperties MarkerSymbolProperties { get; set; }
```
### ProbabilityPlotType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartProbabilityPlotSeries.yml" sourcestartlinenumber="1">Gets or sets the type of a probability plot.</p>


```csharp
public ChartProbabilityPlotType ProbabilityPlotType { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartProbabilityPlotSeries.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ReferenceLineSymbolProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartProbabilityPlotSeries.yml" sourcestartlinenumber="1">Gets or sets the line symbol properties of the probability plot series' reference line.</p>


```csharp
public CIMChartLineSymbolProperties ReferenceLineSymbolProperties { get; set; }
```
### ShowReferenceLine

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartProbabilityPlotSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to show a reference line overlay for the probability plot.</p>


```csharp
public bool ShowReferenceLine { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartProbabilityPlotSeries.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMChartProbabilityPlotSeries and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartProbabilityPlotSeries.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


