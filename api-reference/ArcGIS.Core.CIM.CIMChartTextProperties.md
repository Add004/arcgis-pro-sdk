# CIMChartTextProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTextProperties.yml" sourcestartlinenumber="1">Represents chart text properties.</p>


## Object Signature

```csharp
public class CIMChartTextProperties : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMChartTextProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTextProperties.yml" sourcestartlinenumber="1">Represents chart text properties.</p>


```csharp
public CIMChartTextProperties()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTextProperties.yml" sourcestartlinenumber="1">Creates a deep copy of CIMChartTextProperties.</p>


```csharp
public CIMChartTextProperties Clone()
```
### FontFamilyName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTextProperties.yml" sourcestartlinenumber="1">Gets or sets the font family name.</p>


```csharp
public string FontFamilyName { get; set; }
```
### FontFillColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTextProperties.yml" sourcestartlinenumber="1">Gets or sets the fill color for the font.</p>


```csharp
public CIMColor FontFillColor { get; set; }
```
### FontItalic

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTextProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the font style if it is italic or not.</p>


```csharp
public bool FontItalic { get; set; }
```
### FontOutlineColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTextProperties.yml" sourcestartlinenumber="1">Gets or sets the outline color for the font.</p>


```csharp
public CIMColor FontOutlineColor { get; set; }
```
### FontSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTextProperties.yml" sourcestartlinenumber="1">Gets or sets the font size in points.</p>


```csharp
public double FontSize { get; set; }
```
### FontWeight

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTextProperties.yml" sourcestartlinenumber="1">Gets or sets the font weight.</p>


```csharp
public ChartFontWeight FontWeight { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTextProperties.yml" sourcestartlinenumber="1">Reconstructs the CIMChartTextProperties with a specified state from a JSON encoding.</p>


```csharp
public static CIMChartTextProperties FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTextProperties.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### TextCase

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTextProperties.yml" sourcestartlinenumber="1">Gets or sets the text case.</p>


```csharp
public ChartTextCase TextCase { get; set; }
```
### TextOverline

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTextProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the text is drawn with an overline.</p>


```csharp
public bool TextOverline { get; set; }
```
### TextStrikethrough

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTextProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the text is drawn with a strikethrough.</p>


```csharp
public bool TextStrikethrough { get; set; }
```
### TextUnderline

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTextProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the text is drawn with an underline.</p>


```csharp
public bool TextUnderline { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTextProperties.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMChartTextProperties and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Visible

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTextProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the text is visible.</p>


```csharp
public bool Visible { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTextProperties.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


