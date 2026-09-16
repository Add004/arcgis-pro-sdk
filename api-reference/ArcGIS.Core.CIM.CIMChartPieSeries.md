# CIMChartPieSeries

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartPieSeries.yml" sourcestartlinenumber="1">Provides access to members that control pie chart series.</p>


## Object Signature

```csharp
public class CIMChartPieSeries : CIMChartSeries, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMChartPieSeries()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartPieSeries.yml" sourcestartlinenumber="1">Provides access to members that control pie chart series.</p>


```csharp
public CIMChartPieSeries()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartPieSeries.yml" sourcestartlinenumber="1">Creates a deep copy of CIMChartPieSeries.</p>


```csharp
public CIMChartPieSeries Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartPieSeries.yml" sourcestartlinenumber="1">Reconstructs the CIMChartPieSeries with a specified state from a JSON encoding.</p>


```csharp
public static CIMChartPieSeries FromJson(string json, JsonDeserializationSettings settings = null)
```
### HolePercentage

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartPieSeries.yml" sourcestartlinenumber="1">Gets or sets the size of the hole in middle of the chart.</p>


```csharp
public double HolePercentage { get; set; }
```
### PercentageDecimalPlaces

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartPieSeries.yml" sourcestartlinenumber="1">Gets or sets the number of decimal places in the percentage values.</p>


```csharp
public int PercentageDecimalPlaces { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartPieSeries.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShowLabelPercentage

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartPieSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to show percentage value associated with a slice.</p>


```csharp
public bool ShowLabelPercentage { get; set; }
```
### ShowLabelValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartPieSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to show numeric value associated with a slice.</p>


```csharp
public bool ShowLabelValue { get; set; }
```
### SliceAggregationThreshold

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartPieSeries.yml" sourcestartlinenumber="1">Gets or sets the value indicating if slices with the size under a given percentage threshold are aggregated into a single slice.</p>


```csharp
public double SliceAggregationThreshold { get; set; }
```
### Slices

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartPieSeries.yml" sourcestartlinenumber="1">Gets or sets the array of slices.</p>


```csharp
public CIMChartPieSlice[] Slices { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartPieSeries.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMChartPieSeries and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartPieSeries.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


