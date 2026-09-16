# CIMChartGuide

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartGuide.yml" sourcestartlinenumber="1">Define the properties to define a chart guide.</p>


## Object Signature

```csharp
public class CIMChartGuide : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMChartGuide()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartGuide.yml" sourcestartlinenumber="1">Define the properties to define a chart guide.</p>


```csharp
public CIMChartGuide()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartGuide.yml" sourcestartlinenumber="1">Creates a deep copy of CIMChartGuide.</p>


```csharp
public CIMChartGuide Clone()
```
### FillSymbolProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartGuide.yml" sourcestartlinenumber="1">Gets or sets the symbol properties for the guide.</p>


```csharp
public CIMChartFillSymbolProperties FillSymbolProperties { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartGuide.yml" sourcestartlinenumber="1">Reconstructs the CIMChartGuide with a specified state from a JSON encoding.</p>


```csharp
public static CIMChartGuide FromJson(string json, JsonDeserializationSettings settings = null)
```
### GuideType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartGuide.yml" sourcestartlinenumber="1">Gets or sets the type of the guide.</p>


```csharp
public ChartGuideType GuideType { get; set; }
```
### GuideValueType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartGuide.yml" sourcestartlinenumber="1">Gets or sets the type of the coordinate value used in the guide.</p>


```csharp
public ChartValueType GuideValueType { get; set; }
```
### Label

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartGuide.yml" sourcestartlinenumber="1">Gets or sets the label for the guide.</p>


```csharp
public string Label { get; set; }
```
### LabelPosition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartGuide.yml" sourcestartlinenumber="1">Gets or sets the relative position of the label to the guide.</p>


```csharp
public ChartPosition LabelPosition { get; set; }
```
### LabelText

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartGuide.yml" sourcestartlinenumber="1">Gets or sets the text format for the guide label.</p>


```csharp
public CIMChartTextProperties LabelText { get; set; }
```
### MarkerSymbolProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartGuide.yml" sourcestartlinenumber="1">Gets or sets the marker symbol properties for the guide.</p>


```csharp
public CIMChartMarkerSymbolProperties MarkerSymbolProperties { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartGuide.yml" sourcestartlinenumber="1">Gets or sets the name / title for the guide.</p>


```csharp
public string Name { get; set; }
```
### Polyline

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartGuide.yml" sourcestartlinenumber="1">Gets or sets vertices of the polyline guide as an array of x and y coordinates in a row-major order.</p>


```csharp
public double[] Polyline { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartGuide.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### TimeFrom

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartGuide.yml" sourcestartlinenumber="1">Gets or sets the temporal coordinate of the from value for the guide. This value will be used when guide value type is set to temporal.</p>


```csharp
public TimeInstant TimeFrom { get; set; }
```
### TimeTo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartGuide.yml" sourcestartlinenumber="1">Gets or sets the temporal coordinate of the to value for the guide. This value will be used when guide value type is set to temporal.</p>


```csharp
public TimeInstant TimeTo { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartGuide.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMChartGuide and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### ValueFrom

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartGuide.yml" sourcestartlinenumber="1">Gets or sets the numeric coordinate of the from value for the guide. This value will be used when guide value type is set to numeric.</p>


```csharp
public double ValueFrom { get; set; }
```
### ValueFromField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartGuide.yml" sourcestartlinenumber="1">Gets or sets the field name for calculation of the numeric coordinate of the from value for the guide. This value will be used when guide value type is set to numeric.</p>


```csharp
public string ValueFromField { get; set; }
```
### ValueFromFieldAggregationType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartGuide.yml" sourcestartlinenumber="1">Gets or sets the aggregation type for calculation of the numeric coordinate of the from value for the guide. This value will be used when guide value type is set to numeric.</p>


```csharp
public ChartAggregationType ValueFromFieldAggregationType { get; set; }
```
### ValueTo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartGuide.yml" sourcestartlinenumber="1">Gets or sets the numeric coordinate of the to value for the guide. This value will be used when guide value type is set to numeric.</p>


```csharp
public double ValueTo { get; set; }
```
### Visible

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartGuide.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the guide is visible.</p>


```csharp
public bool Visible { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartGuide.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


