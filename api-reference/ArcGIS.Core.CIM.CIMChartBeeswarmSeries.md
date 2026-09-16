# CIMChartBeeswarmSeries

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBeeswarmSeries.yml" sourcestartlinenumber="1">Provides access to members that control beeswarm series.</p>


## Object Signature

```csharp
public class CIMChartBeeswarmSeries : CIMChartSeries, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMChartBeeswarmSeries()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBeeswarmSeries.yml" sourcestartlinenumber="1">Provides access to members that control beeswarm series.</p>


```csharp
public CIMChartBeeswarmSeries()
```
### BubbleMaximumSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBeeswarmSeries.yml" sourcestartlinenumber="1">Gets or sets the maximum size of the bubbles. Units in pixels.</p>


```csharp
public double BubbleMaximumSize { get; set; }
```
### BubbleMinimumSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBeeswarmSeries.yml" sourcestartlinenumber="1">Gets or sets the minimum size of the bubbles. Units in pixels.</p>


```csharp
public double BubbleMinimumSize { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBeeswarmSeries.yml" sourcestartlinenumber="1">Creates a deep copy of CIMChartBeeswarmSeries.</p>


```csharp
public CIMChartBeeswarmSeries Clone()
```
### ColorRamp

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBeeswarmSeries.yml" sourcestartlinenumber="1">Gets or sets the color ramp for the series.</p>


```csharp
public CIMColorRamp ColorRamp { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBeeswarmSeries.yml" sourcestartlinenumber="1">Reconstructs the CIMChartBeeswarmSeries with a specified state from a JSON encoding.</p>


```csharp
public static CIMChartBeeswarmSeries FromJson(string json, JsonDeserializationSettings settings = null)
```
### MarkerSymbolProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBeeswarmSeries.yml" sourcestartlinenumber="1">Gets or sets the marker symbol properties for the series.</p>


```csharp
public CIMChartMarkerSymbolProperties MarkerSymbolProperties { get; set; }
```
### NormalizeAmplitude

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBeeswarmSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to normalize the amplitude of all beeswarms in a chart.</p>


```csharp
public bool NormalizeAmplitude { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBeeswarmSeries.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SortedCategoryValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBeeswarmSeries.yml" sourcestartlinenumber="1">Gets or sets the array of sorted category values for custom sort.</p>


```csharp
public string[] SortedCategoryValues { get; set; }
```
### StandardizeValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBeeswarmSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to calculate standardized values for beeswarm chart.</p>


```csharp
public bool StandardizeValues { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBeeswarmSeries.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMChartBeeswarmSeries and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### VerticalOrientation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBeeswarmSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the chart is vertically oriented.</p>


```csharp
public bool VerticalOrientation { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBeeswarmSeries.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


