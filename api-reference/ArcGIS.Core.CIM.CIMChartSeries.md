# CIMChartSeries

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSeries.yml" sourcestartlinenumber="1">Provides access to members that control chart series properties.</p>


## Object Signature

```csharp
public abstract class CIMChartSeries : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMChartSeries()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSeries.yml" sourcestartlinenumber="1">Provides access to members that control chart series properties.</p>


```csharp
protected CIMChartSeries()
```
### ColorType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSeries.yml" sourcestartlinenumber="1">Gets or sets the type of color for the series.</p>


```csharp
public ChartColorType ColorType { get; set; }
```
### DataLabelText

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSeries.yml" sourcestartlinenumber="1">Gets or sets the text style for the data label.</p>


```csharp
public CIMChartTextProperties DataLabelText { get; set; }
```
### FieldAggregation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSeries.yml" sourcestartlinenumber="1">Gets or sets the aggregate field values if series data has a group field.
Allowed values are count, sum, median, mean, and empty string.</p>


```csharp
public string[] FieldAggregation { get; set; }
```
### FieldExpressions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSeries.yml" sourcestartlinenumber="1">Gets or sets expression properties for chart series' fields.</p>


```csharp
public CIMExpressionInfo[] FieldExpressions { get; set; }
```
### Fields

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSeries.yml" sourcestartlinenumber="1">Gets or sets the data field names in the series. Optional depending on series type.</p>


```csharp
public string[] Fields { get; set; }
```
### GroupFields

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSeries.yml" sourcestartlinenumber="1">Gets or sets the group field names in the series.</p>


```csharp
public string[] GroupFields { get; set; }
```
### HorizontalAxis

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSeries.yml" sourcestartlinenumber="1">Gets or sets the index of horizontal axis.</p>


```csharp
public int HorizontalAxis { get; set; }
```
### Locations

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSeries.yml" sourcestartlinenumber="1">Gets or sets the locations for which data is to be plotted.</p>


```csharp
public CIMChartLocationDefinition[] Locations { get; set; }
```
### MultiSeries

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this series is a multi series.</p>


```csharp
public bool MultiSeries { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSeries.yml" sourcestartlinenumber="1">Gets or sets the name of the series shown in the legend.</p>


```csharp
public string Name { get; set; }
```
### OrderFields

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSeries.yml" sourcestartlinenumber="1">Gets or sets the sort field names in the series.</p>


```csharp
public string[] OrderFields { get; set; }
```
### OrderFieldsSortTypes

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSeries.yml" sourcestartlinenumber="1">Gets or sets the array of sort order types for fields in OrderFields property
Allowed values 0(Ascending), 1(Descending).</p>


```csharp
public int[] OrderFieldsSortTypes { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSeries.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShowLabels

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the series shows data labels.</p>


```csharp
public bool ShowLabels { get; set; }
```
### UniqueName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSeries.yml" sourcestartlinenumber="1">Gets or sets the default and unique name of the series.</p>


```csharp
public string UniqueName { get; set; }
```
### VerticalAxis

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSeries.yml" sourcestartlinenumber="1">Gets or sets the index of vertical axis.</p>


```csharp
public int VerticalAxis { get; set; }
```
### Visible

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the series is visible or not.</p>


```csharp
public bool Visible { get; set; }
```
### WhereClause

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSeries.yml" sourcestartlinenumber="1">Gets or sets the format string for series value labels.</p>


```csharp
public string WhereClause { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSeries.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


