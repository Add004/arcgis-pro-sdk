# CIMChartBoxPlotSeries

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBoxPlotSeries.yml" sourcestartlinenumber="1">Provides access to members that control box plot series.</p>


## Object Signature

```csharp
public class CIMChartBoxPlotSeries : CIMChartSeries, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMChartBoxPlotSeries()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBoxPlotSeries.yml" sourcestartlinenumber="1">Provides access to members that control box plot series.</p>


```csharp
public CIMChartBoxPlotSeries()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBoxPlotSeries.yml" sourcestartlinenumber="1">Creates a deep copy of CIMChartBoxPlotSeries.</p>


```csharp
public CIMChartBoxPlotSeries Clone()
```
### FillSymbolProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBoxPlotSeries.yml" sourcestartlinenumber="1">Gets or sets the properties of the box plot symbol.</p>


```csharp
public CIMChartFillSymbolProperties FillSymbolProperties { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBoxPlotSeries.yml" sourcestartlinenumber="1">Reconstructs the CIMChartBoxPlotSeries with a specified state from a JSON encoding.</p>


```csharp
public static CIMChartBoxPlotSeries FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBoxPlotSeries.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShowInnerPoints

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBoxPlotSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to show the box plot inner points.</p>


```csharp
public bool ShowInnerPoints { get; set; }
```
### ShowMean

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBoxPlotSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to show the box plot mean marker.</p>


```csharp
public bool ShowMean { get; set; }
```
### ShowOutliers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBoxPlotSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to show the box plot outliers.</p>


```csharp
public bool ShowOutliers { get; set; }
```
### SortedCategoryValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBoxPlotSeries.yml" sourcestartlinenumber="1">Gets or sets the array of sorted category values for custom sort.</p>


```csharp
public string[] SortedCategoryValues { get; set; }
```
### StandardizeValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBoxPlotSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to calculate standardized values for box plot.</p>


```csharp
public bool StandardizeValues { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBoxPlotSeries.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMChartBoxPlotSeries and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### VerticalOrientation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBoxPlotSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the box plot is vertically oriented.</p>


```csharp
public bool VerticalOrientation { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartBoxPlotSeries.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


