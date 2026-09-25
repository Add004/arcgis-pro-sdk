# CIMChartDimensionalProfileLandTrendrArguments

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileLandTrendrArguments.yml" sourcestartlinenumber="1">Represents arguments to be used to plot change detection over time.</p>


## Object Signature

```csharp
public class CIMChartDimensionalProfileLandTrendrArguments : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMChartDimensionalProfileLandTrendrArguments()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileLandTrendrArguments.yml" sourcestartlinenumber="1">Represents arguments to be used to plot change detection over time.</p>


```csharp
public CIMChartDimensionalProfileLandTrendrArguments()
```
### BestModelProportion

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileLandTrendrArguments.yml" sourcestartlinenumber="1">Gets or sets the best model proportion value.</p>


```csharp
public double BestModelProportion { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileLandTrendrArguments.yml" sourcestartlinenumber="1">Creates a deep copy of CIMChartDimensionalProfileLandTrendrArguments.</p>


```csharp
public CIMChartDimensionalProfileLandTrendrArguments Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileLandTrendrArguments.yml" sourcestartlinenumber="1">Reconstructs the CIMChartDimensionalProfileLandTrendrArguments with a specified state from a JSON encoding.</p>


```csharp
public static CIMChartDimensionalProfileLandTrendrArguments FromJson(string json, JsonDeserializationSettings settings = null)
```
### MaximumSegments

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileLandTrendrArguments.yml" sourcestartlinenumber="1">Gets or sets the maximum number of segments to be fitted to the time series for each pixel.</p>


```csharp
public int MaximumSegments { get; set; }
```
### MinimumObservations

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileLandTrendrArguments.yml" sourcestartlinenumber="1">Gets or sets the minimum number of valid observations required to perform fitting.</p>


```csharp
public int MinimumObservations { get; set; }
```
### OutputOtherBands

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileLandTrendrArguments.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether other bands will be included in the segmentation process.</p>


```csharp
public bool OutputOtherBands { get; set; }
```
### PValueThreshold

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileLandTrendrArguments.yml" sourcestartlinenumber="1">Gets or sets the p-value threshold for a model to be selected.</p>


```csharp
public double PValueThreshold { get; set; }
```
### PreventOneYearRecovery

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileLandTrendrArguments.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether segments that exhibit a one year recovery will be excluded.</p>


```csharp
public bool PreventOneYearRecovery { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileLandTrendrArguments.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RecoveryIncreasingTrend

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileLandTrendrArguments.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the recovery has an increasing (positive) trend.</p>


```csharp
public bool RecoveryIncreasingTrend { get; set; }
```
### RecoveryThreshold

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileLandTrendrArguments.yml" sourcestartlinenumber="1">Gets or sets the recovery threshold value in years.</p>


```csharp
public double RecoveryThreshold { get; set; }
```
### SnappingDate

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileLandTrendrArguments.yml" sourcestartlinenumber="1">Gets or sets the date in the format MM-DD used to select a slice for each year.</p>


```csharp
public string SnappingDate { get; set; }
```
### SpikeThreshold

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileLandTrendrArguments.yml" sourcestartlinenumber="1">Gets or sets the threshold to use for dampening spikes or anomalies in the pixel value trajectory.</p>


```csharp
public double SpikeThreshold { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileLandTrendrArguments.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMChartDimensionalProfileLandTrendrArguments and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### VertexCountOvershoot

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileLandTrendrArguments.yml" sourcestartlinenumber="1">Gets or sets the number of additional vertices beyond MaximumSegments + 1 that can be used to fit the model during the initial stage of identifying vertices.</p>


```csharp
public int VertexCountOvershoot { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartDimensionalProfileLandTrendrArguments.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


