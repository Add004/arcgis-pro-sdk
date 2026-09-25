# CIMChartLegend

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLegend.yml" sourcestartlinenumber="1">Provides access to members that control chart legend properties.</p>


## Object Signature

```csharp
public class CIMChartLegend : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMChartLegend()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLegend.yml" sourcestartlinenumber="1">Provides access to members that control chart legend properties.</p>


```csharp
public CIMChartLegend()
```
### Alignment

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLegend.yml" sourcestartlinenumber="1">Gets or sets the options in arranging the chart legend.</p>


```csharp
public ChartLegendAlignment Alignment { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLegend.yml" sourcestartlinenumber="1">Creates a deep copy of CIMChartLegend.</p>


```csharp
public CIMChartLegend Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLegend.yml" sourcestartlinenumber="1">Reconstructs the CIMChartLegend with a specified state from a JSON encoding.</p>


```csharp
public static CIMChartLegend FromJson(string json, JsonDeserializationSettings settings = null)
```
### LegendText

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLegend.yml" sourcestartlinenumber="1">Gets or sets the text symbol properties.</p>


```csharp
public CIMChartTextProperties LegendText { get; set; }
```
### LegendTitle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLegend.yml" sourcestartlinenumber="1">Gets or sets the text symbol properties for legend title.</p>


```csharp
public CIMChartTextProperties LegendTitle { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLegend.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShowTitle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLegend.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the legend title is visible.</p>


```csharp
public bool ShowTitle { get; set; }
```
### Title

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLegend.yml" sourcestartlinenumber="1">Gets or sets the title of the legend.</p>


```csharp
public string Title { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLegend.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMChartLegend and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### ValueFormat

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLegend.yml" sourcestartlinenumber="1">Gets or sets the format string for series value labels.</p>


```csharp
public string ValueFormat { get; set; }
```
### Visible

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLegend.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the chart legend is visible.</p>


```csharp
public bool Visible { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLegend.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


