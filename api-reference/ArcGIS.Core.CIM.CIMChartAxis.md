# CIMChartAxis

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartAxis.yml" sourcestartlinenumber="1">Provides access to members that control chart axis properties.</p>


## Object Signature

```csharp
public class CIMChartAxis : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMChartAxis()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartAxis.yml" sourcestartlinenumber="1">Provides access to members that control chart axis properties.</p>


```csharp
public CIMChartAxis()
```
### AxisLineSymbolProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartAxis.yml" sourcestartlinenumber="1">Gets or sets the line symbol properties for axis.</p>


```csharp
public CIMChartLineSymbolProperties AxisLineSymbolProperties { get; set; }
```
### CalculateAutomaticMaximum

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartAxis.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the chart axis calculates its maximum.</p>


```csharp
public bool CalculateAutomaticMaximum { get; set; }
```
### CalculateAutomaticMinimum

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartAxis.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the chart axis calculates its minimum.</p>


```csharp
public bool CalculateAutomaticMinimum { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartAxis.yml" sourcestartlinenumber="1">Creates a deep copy of CIMChartAxis.</p>


```csharp
public CIMChartAxis Clone()
```
### DateTimeFormat

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartAxis.yml" sourcestartlinenumber="1">Gets or sets the format string for axis date/time labels.</p>


```csharp
public string DateTimeFormat { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartAxis.yml" sourcestartlinenumber="1">Reconstructs the CIMChartAxis with a specified state from a JSON encoding.</p>


```csharp
public static CIMChartAxis FromJson(string json, JsonDeserializationSettings settings = null)
```
### Guides

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartAxis.yml" sourcestartlinenumber="1">Gets or sets the array of guides.</p>


```csharp
public CIMChartGuide[] Guides { get; set; }
```
### Interval

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartAxis.yml" sourcestartlinenumber="1">Gets or sets the interval of the axis. The value should be positive.</p>


```csharp
public double Interval { get; set; }
```
### Inverted

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartAxis.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the chart axis is inverted.</p>


```csharp
public bool Inverted { get; set; }
```
### IsLogarithmic

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartAxis.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the chart axis has logarithmic scale.</p>


```csharp
public bool IsLogarithmic { get; set; }
```
### LabelAngle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartAxis.yml" sourcestartlinenumber="1">Gets or sets the rotation angle of the axis labels. The value range is from -90 to 90.</p>


```csharp
public double LabelAngle { get; set; }
```
### LabelCharacterLimit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartAxis.yml" sourcestartlinenumber="1">Gets or sets the character limit for axis labels.</p>


```csharp
public int LabelCharacterLimit { get; set; }
```
### LabelText

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartAxis.yml" sourcestartlinenumber="1">Gets or sets the label symbol properties.</p>


```csharp
public CIMChartTextProperties LabelText { get; set; }
```
### Maximum

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartAxis.yml" sourcestartlinenumber="1">Gets or sets the maximum of the axis.</p>


```csharp
public object Maximum { get; set; }
```
### Minimum

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartAxis.yml" sourcestartlinenumber="1">Gets or sets the minimum of the axis.</p>


```csharp
public object Minimum { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartAxis.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShowTitle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartAxis.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the axis title is visible.</p>


```csharp
public bool ShowTitle { get; set; }
```
### Title

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartAxis.yml" sourcestartlinenumber="1">Gets or sets the title of an axis.</p>


```csharp
public string Title { get; set; }
```
### TitleText

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartAxis.yml" sourcestartlinenumber="1">Gets or sets the title symbol properties.</p>


```csharp
public CIMChartTextProperties TitleText { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartAxis.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMChartAxis and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseAutomaticInterval

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartAxis.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the interval of the axis is auto calculated.</p>


```csharp
public bool UseAutomaticInterval { get; set; }
```
### UseAutomaticLabelAngle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartAxis.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the rotation angle of the axis labels is auto calculated.</p>


```csharp
public bool UseAutomaticLabelAngle { get; set; }
```
### UseAutomaticTitle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartAxis.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the axis title is auto generated.</p>


```csharp
public bool UseAutomaticTitle { get; set; }
```
### ValueFormat

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartAxis.yml" sourcestartlinenumber="1">Gets or sets the format string for axis value labels.</p>


```csharp
public string ValueFormat { get; set; }
```
### ValueNumberFormat

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartAxis.yml" sourcestartlinenumber="1">Gets or sets the number format of the axis labels. ValueNumberFormat takes precedence over ValueFormat when both are specified.</p>


```csharp
public CIMNumberFormat ValueNumberFormat { get; set; }
```
### Visible

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartAxis.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the chart axis is visible.</p>


```csharp
public bool Visible { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartAxis.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```
### ZoomEndPosition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartAxis.yml" sourcestartlinenumber="1">Gets or sets the relative end position for zoom/pan navigation. The value range is normalized between 0 and 1.</p>


```csharp
public double ZoomEndPosition { get; set; }
```
### ZoomStartPosition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartAxis.yml" sourcestartlinenumber="1">Gets or sets the relative start position for zoom/pan navigation. The value range is normalized between 0 and 1.</p>


```csharp
public double ZoomStartPosition { get; set; }
```


