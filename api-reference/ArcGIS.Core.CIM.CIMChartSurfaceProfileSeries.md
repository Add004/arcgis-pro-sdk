# CIMChartSurfaceProfileSeries

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSurfaceProfileSeries.yml" sourcestartlinenumber="1">Represents a surface profile chart series.</p>


## Object Signature

```csharp
public class CIMChartSurfaceProfileSeries : CIMChartSeries, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMChartSurfaceProfileSeries()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSurfaceProfileSeries.yml" sourcestartlinenumber="1">Represents a surface profile chart series.</p>


```csharp
public CIMChartSurfaceProfileSeries()
```
### Bands

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSurfaceProfileSeries.yml" sourcestartlinenumber="1">Gets or sets the bands to be used from the input to draw the profile.</p>


```csharp
public CIMChartSurfaceProfileBand[] Bands { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSurfaceProfileSeries.yml" sourcestartlinenumber="1">Creates a deep copy of CIMChartSurfaceProfileSeries.</p>


```csharp
public CIMChartSurfaceProfileSeries Clone()
```
### Dimension

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSurfaceProfileSeries.yml" sourcestartlinenumber="1">Gets or sets the name of the dimension for which the values are to be plotted.</p>


```csharp
public string Dimension { get; set; }
```
### DimensionValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSurfaceProfileSeries.yml" sourcestartlinenumber="1">Gets or sets the dimension values to be used from a multidimensional input to draw the profile.</p>


```csharp
public CIMChartSurfaceProfileDimensionValues DimensionValues { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSurfaceProfileSeries.yml" sourcestartlinenumber="1">Reconstructs the CIMChartSurfaceProfileSeries with a specified state from a JSON encoding.</p>


```csharp
public static CIMChartSurfaceProfileSeries FromJson(string json, JsonDeserializationSettings settings = null)
```
### HorizontalUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSurfaceProfileSeries.yml" sourcestartlinenumber="1">Gets or sets the unit of measure to be used for the axis.</p>


```csharp
public Unit HorizontalUnit { get; set; }
```
### Layers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSurfaceProfileSeries.yml" sourcestartlinenumber="1">Gets or sets the layers to be used as additional inputs for the profile.</p>


```csharp
public CIMChartSurfaceProfileLayer[] Layers { get; set; }
```
### PlotType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSurfaceProfileSeries.yml" sourcestartlinenumber="1">Gets or sets the type of plot for this chart.</p>


```csharp
public ChartSurfaceProfilePlotType PlotType { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSurfaceProfileSeries.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SampleDistance

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSurfaceProfileSeries.yml" sourcestartlinenumber="1">Gets or sets the sample distance for the profile.</p>


```csharp
public double SampleDistance { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSurfaceProfileSeries.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMChartSurfaceProfileSeries and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Variable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSurfaceProfileSeries.yml" sourcestartlinenumber="1">Gets or sets the name of the variable for which the values are to be plotted.</p>


```csharp
public string Variable { get; set; }
```
### VerticalScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSurfaceProfileSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating the scale value for the axis.</p>


```csharp
public double VerticalScale { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartSurfaceProfileSeries.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


