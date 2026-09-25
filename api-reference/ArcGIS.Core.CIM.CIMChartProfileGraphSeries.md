# CIMChartProfileGraphSeries

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartProfileGraphSeries.yml" sourcestartlinenumber="1">Provides access to members that control profile graph series.</p>


## Object Signature

```csharp
public class CIMChartProfileGraphSeries : CIMChartSeries, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMChartProfileGraphSeries()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartProfileGraphSeries.yml" sourcestartlinenumber="1">Provides access to members that control profile graph series.</p>


```csharp
public CIMChartProfileGraphSeries()
```
### Chain

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartProfileGraphSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to chain lines together from end to end if their endpoints coincide.</p>


```csharp
public bool Chain { get; set; }
```
### ChainingTolerance

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartProfileGraphSeries.yml" sourcestartlinenumber="1">Gets or sets a threshold value determining whether line endpoints coincide in XY.</p>


```csharp
public double ChainingTolerance { get; set; }
```
### ChainingToleranceZ

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartProfileGraphSeries.yml" sourcestartlinenumber="1">Gets or sets a threshold value determining whether line endpoints coincide in Z.</p>


```csharp
public double ChainingToleranceZ { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartProfileGraphSeries.yml" sourcestartlinenumber="1">Creates a deep copy of CIMChartProfileGraphSeries.</p>


```csharp
public CIMChartProfileGraphSeries Clone()
```
### FlipDirection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartProfileGraphSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to flip the direction in which lines and chains are graphed.</p>


```csharp
public bool FlipDirection { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartProfileGraphSeries.yml" sourcestartlinenumber="1">Reconstructs the CIMChartProfileGraphSeries with a specified state from a JSON encoding.</p>


```csharp
public static CIMChartProfileGraphSeries FromJson(string json, JsonDeserializationSettings settings = null)
```
### HorizontalUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartProfileGraphSeries.yml" sourcestartlinenumber="1">Gets or sets the unit of measure to be used for horizontal distance. The default value is layer's spatial reference XY unit.</p>


```csharp
public Unit HorizontalUnit { get; set; }
```
### LineSeriesType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartProfileGraphSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating which line type to use in the graph.</p>


```csharp
public ProfileGraphLineSeriesType LineSeriesType { get; set; }
```
### LineSymbolProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartProfileGraphSeries.yml" sourcestartlinenumber="1">Gets or sets the line symbol properties of the profile graph series.</p>


```csharp
public CIMChartLineSymbolProperties LineSymbolProperties { get; set; }
```
### MarkerSymbolProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartProfileGraphSeries.yml" sourcestartlinenumber="1">Gets or sets the marker symbol properties of the profile graph series.</p>


```csharp
public CIMChartMarkerSymbolProperties MarkerSymbolProperties { get; set; }
```
### ProfileGraphFields

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartProfileGraphSeries.yml" sourcestartlinenumber="1">Gets or sets the field names in the series. It contains three values (DirectionPreference, ChainingGrouping, and ChainBounds).</p>


```csharp
public string[] ProfileGraphFields { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartProfileGraphSeries.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShowLoSConnectingLine

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartProfileGraphSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to draw a line connecting points from Line Of Sight output.</p>


```csharp
public bool ShowLoSConnectingLine { get; set; }
```
### ShowLoSPoints

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartProfileGraphSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to draw points from Line Of Sight output.</p>


```csharp
public bool ShowLoSPoints { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartProfileGraphSeries.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMChartProfileGraphSeries and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TrackCursor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartProfileGraphSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether in the map/scene to dynamically display cursor movement in the chart.</p>


```csharp
public bool TrackCursor { get; set; }
```
### VariableInYAxis1

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartProfileGraphSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating which variable to display in the first Y axis.</p>


```csharp
public ProfileGraphVariableInYAxis VariableInYAxis1 { get; set; }
```
### VerticalExaggeration

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartProfileGraphSeries.yml" sourcestartlinenumber="1">Gets or sets a value by which to exaggerate the vertical axis relative to the horizontal axis.</p>


```csharp
public double VerticalExaggeration { get; set; }
```
### VerticalUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartProfileGraphSeries.yml" sourcestartlinenumber="1">Gets or sets the unit of measure to be used for elevation. The default value is the layer's vertical coordinate system's Z unit, if there is one.</p>


```csharp
public Unit VerticalUnit { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartProfileGraphSeries.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


