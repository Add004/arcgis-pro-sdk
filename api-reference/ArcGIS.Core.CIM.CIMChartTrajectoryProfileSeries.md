# CIMChartTrajectoryProfileSeries

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileSeries.yml" sourcestartlinenumber="1">Represents a trajectory profile chart series.</p>


## Object Signature

```csharp
public class CIMChartTrajectoryProfileSeries : CIMChartSeries, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMChartTrajectoryProfileSeries()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileSeries.yml" sourcestartlinenumber="1">Represents a trajectory profile chart series.</p>


```csharp
public CIMChartTrajectoryProfileSeries()
```
### AreaOfInterestURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileSeries.yml" sourcestartlinenumber="1">Gets or sets the AOI to be used for plotting the chart.</p>


```csharp
public string AreaOfInterestURI { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileSeries.yml" sourcestartlinenumber="1">Creates a deep copy of CIMChartTrajectoryProfileSeries.</p>


```csharp
public CIMChartTrajectoryProfileSeries Clone()
```
### DateTimeFormat

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileSeries.yml" sourcestartlinenumber="1">Gets or sets the format of the date plotted on the x axis.</p>


```csharp
public string DateTimeFormat { get; set; }
```
### Features

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileSeries.yml" sourcestartlinenumber="1">Gets or sets the tracks or points to be used to draw the profile.</p>


```csharp
public CIMChartTrajectoryProfileFeature[] Features { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileSeries.yml" sourcestartlinenumber="1">Reconstructs the CIMChartTrajectoryProfileSeries with a specified state from a JSON encoding.</p>


```csharp
public static CIMChartTrajectoryProfileSeries FromJson(string json, JsonDeserializationSettings settings = null)
```
### Layers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileSeries.yml" sourcestartlinenumber="1">Gets or sets the layers to be used as additional inputs for the profile.</p>


```csharp
public CIMChartTrajectoryProfileLayer[] Layers { get; set; }
```
### NullPolicy

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileSeries.yml" sourcestartlinenumber="1">Gets or sets the policy for handling missing data.</p>


```csharp
public ChartNullPolicy NullPolicy { get; set; }
```
### PlotType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileSeries.yml" sourcestartlinenumber="1">Gets or sets the type of plot for this chart.</p>


```csharp
public ChartTrajectoryProfilePlotType PlotType { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileSeries.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### TimeAggregationType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileSeries.yml" sourcestartlinenumber="1">Gets or sets the type of grouping to be applied on the time values plotted on the x axis.</p>


```csharp
public ChartTimeAggregationType TimeAggregationType { get; set; }
```
### TimeIntervalSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileSeries.yml" sourcestartlinenumber="1">Gets or sets the interval size for the time plotted on the x axis.</p>


```csharp
public double TimeIntervalSize { get; set; }
```
### TimeIntervalUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileSeries.yml" sourcestartlinenumber="1">Gets or sets the unit of time for the interval size.</p>


```csharp
public esriTimeUnits TimeIntervalUnits { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileSeries.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMChartTrajectoryProfileSeries and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TrajectoryIDsURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileSeries.yml" sourcestartlinenumber="1">Gets or sets the URI of the binary reference containing the trajectory IDs selected when plot type is Points.</p>


```csharp
public string TrajectoryIDsURI { get; set; }
```
### TrimIncompleteTimeInterval

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether incomplete time intervals at the ends of time interval
ranges are trimmed in order to avoid bias.</p>


```csharp
public bool TrimIncompleteTimeInterval { get; set; }
```
### Variables

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileSeries.yml" sourcestartlinenumber="1">Gets or sets the variables for which the tracks or points are to be plotted.</p>


```csharp
public CIMChartTrajectoryProfileVariable[] Variables { get; set; }
```
### VerticalOrientation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the chart is vertically oriented.</p>


```csharp
public bool VerticalOrientation { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileSeries.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


