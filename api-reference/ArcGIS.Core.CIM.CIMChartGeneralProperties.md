# CIMChartGeneralProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartGeneralProperties.yml" sourcestartlinenumber="1">Provides access to members that control general chart properties.</p>


## Object Signature

```csharp
public class CIMChartGeneralProperties : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMChartGeneralProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartGeneralProperties.yml" sourcestartlinenumber="1">Provides access to members that control general chart properties.</p>


```csharp
public CIMChartGeneralProperties()
```
### BackgroundSymbolProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartGeneralProperties.yml" sourcestartlinenumber="1">Gets or sets the background fill symbol properties for the chart.</p>


```csharp
public CIMChartFillSymbolProperties BackgroundSymbolProperties { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartGeneralProperties.yml" sourcestartlinenumber="1">Creates a deep copy of CIMChartGeneralProperties.</p>


```csharp
public CIMChartGeneralProperties Clone()
```
### Footer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartGeneralProperties.yml" sourcestartlinenumber="1">Gets or sets the footer of the chart.</p>


```csharp
public string Footer { get; set; }
```
### FooterText

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartGeneralProperties.yml" sourcestartlinenumber="1">Gets or sets the footer symbol properties.</p>


```csharp
public CIMChartTextProperties FooterText { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartGeneralProperties.yml" sourcestartlinenumber="1">Reconstructs the CIMChartGeneralProperties with a specified state from a JSON encoding.</p>


```csharp
public static CIMChartGeneralProperties FromJson(string json, JsonDeserializationSettings settings = null)
```
### GridLineSymbolProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartGeneralProperties.yml" sourcestartlinenumber="1">Gets or sets the line symbol properties for horizontal grid lines.</p>


```csharp
public CIMChartLineSymbolProperties GridLineSymbolProperties { get; set; }
```
### PaletteColorRamp

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartGeneralProperties.yml" sourcestartlinenumber="1">Gets or sets the color ramp used to generate the palette colors.</p>


```csharp
public CIMColorRamp PaletteColorRamp { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartGeneralProperties.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShowFooter

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartGeneralProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the chart footer is visible.</p>


```csharp
public bool ShowFooter { get; set; }
```
### ShowSubTitle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartGeneralProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the chart subtitle is visible.</p>


```csharp
public bool ShowSubTitle { get; set; }
```
### ShowTitle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartGeneralProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the chart title is visible.</p>


```csharp
public bool ShowTitle { get; set; }
```
### SubTitle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartGeneralProperties.yml" sourcestartlinenumber="1">Gets or sets the subtitle of the chart.</p>


```csharp
public string SubTitle { get; set; }
```
### SubTitleText

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartGeneralProperties.yml" sourcestartlinenumber="1">Gets or sets the subtitle symbol properties.</p>


```csharp
public CIMChartTextProperties SubTitleText { get; set; }
```
### Theme

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartGeneralProperties.yml" sourcestartlinenumber="1">Gets or sets the theme of the chart.</p>


```csharp
public string Theme { get; set; }
```
### Title

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartGeneralProperties.yml" sourcestartlinenumber="1">Gets or sets the title of the chart.</p>


```csharp
public string Title { get; set; }
```
### TitleText

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartGeneralProperties.yml" sourcestartlinenumber="1">Gets or sets the title symbol properties.</p>


```csharp
public CIMChartTextProperties TitleText { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartGeneralProperties.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMChartGeneralProperties and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseAutomaticTitle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartGeneralProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the chart title is auto generated.</p>


```csharp
public bool UseAutomaticTitle { get; set; }
```
### VerticalGridLineSymbolProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartGeneralProperties.yml" sourcestartlinenumber="1">Gets or sets the line symbol properties for vertical grid lines.</p>


```csharp
public CIMChartLineSymbolProperties VerticalGridLineSymbolProperties { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartGeneralProperties.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


