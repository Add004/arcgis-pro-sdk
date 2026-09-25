# CIMPieChartMarker

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMPieChartMarker.yml" sourcestartlinenumber="1">Represents a pie chart marker which is a marker that draws numeric values arranged in a circle.</p>


## Object Signature

```csharp
public class CIMPieChartMarker : CIMChartMarker, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMPieChartMarker()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMPieChartMarker.yml" sourcestartlinenumber="1">Represents a pie chart marker which is a marker that draws numeric values arranged in a circle.</p>


```csharp
public CIMPieChartMarker()
```
### AggregateSliceLabel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPieChartMarker.yml" sourcestartlinenumber="1">Gets or sets the label shown in the legend for the aggregate slice.</p>


```csharp
public string AggregateSliceLabel { get; set; }
```
### AggregateSliceSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPieChartMarker.yml" sourcestartlinenumber="1">Gets or sets the polygon symbol used to draw the aggregate slice.</p>


```csharp
public CIMPolygonSymbol AggregateSliceSymbol { get; set; }
```
### AggregateSmallSlices

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPieChartMarker.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to aggregate small pie slices.</p>


```csharp
public bool AggregateSmallSlices { get; set; }
```
### Clockwise

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPieChartMarker.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the orientation of the wedges of the pie chart are clockwise or counterclockwise.</p>


```csharp
public bool Clockwise { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPieChartMarker.yml" sourcestartlinenumber="1">Creates a deep copy of CIMPieChartMarker.</p>


```csharp
public CIMPieChartMarker Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPieChartMarker.yml" sourcestartlinenumber="1">Reconstructs the CIMPieChartMarker with a specified state from a JSON encoding.</p>


```csharp
public static CIMPieChartMarker FromJson(string json, JsonDeserializationSettings settings = null)
```
### InvalidValuesLabel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPieChartMarker.yml" sourcestartlinenumber="1">Gets or sets the label shown in the legend for features with invalid values.</p>


```csharp
public string InvalidValuesLabel { get; set; }
```
### InvalidValuesSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPieChartMarker.yml" sourcestartlinenumber="1">Gets or sets the polygon symbol used to draw features with invalid values.</p>


```csharp
public CIMPolygonSymbol InvalidValuesSymbol { get; set; }
```
### OutlineSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPieChartMarker.yml" sourcestartlinenumber="1">Gets or sets the line symbol that is applied to outline of the whole pie chart.</p>


```csharp
public CIMLineSymbol OutlineSymbol { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPieChartMarker.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShowInvalidValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPieChartMarker.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to show a pie symbol for features with invalid values.</p>


```csharp
public bool ShowInvalidValues { get; set; }
```
### ShowOutline

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPieChartMarker.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to show the outline symbol.</p>


```csharp
public bool ShowOutline { get; set; }
```
### SliceAggregationThreshold

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPieChartMarker.yml" sourcestartlinenumber="1">Gets or sets the aggregation threshold.</p>


```csharp
public double SliceAggregationThreshold { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPieChartMarker.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMPieChartMarker and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPieChartMarker.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


