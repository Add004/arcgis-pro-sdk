# CIMGlossaryTable

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGlossaryTable.yml" sourcestartlinenumber="1">Represents a glossary table for map product surround elements.</p>


## Object Signature

```csharp
public class CIMGlossaryTable : CIMMapProductSurround, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGlossaryTable()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGlossaryTable.yml" sourcestartlinenumber="1">Represents a glossary table for map product surround elements.</p>


```csharp
public CIMGlossaryTable()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGlossaryTable.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGlossaryTable.</p>


```csharp
public CIMGlossaryTable Clone()
```
### DelimiterCharacter

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGlossaryTable.yml" sourcestartlinenumber="1">Gets or sets the delimiter character that is displayed between columns.</p>


```csharp
public string DelimiterCharacter { get; set; }
```
### DelimiterTextSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGlossaryTable.yml" sourcestartlinenumber="1">Gets or sets the text symbol for the delimiter displayed between columns.</p>


```csharp
public CIMSymbolReference DelimiterTextSymbol { get; set; }
```
### Fields

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGlossaryTable.yml" sourcestartlinenumber="1">Gets or sets the fields displayed in the glossary table.</p>


```csharp
public CIMTableFrameField[] Fields { get; set; }
```
### FittingStrategy

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGlossaryTable.yml" sourcestartlinenumber="1">Gets or sets the fitting strategy.</p>


```csharp
public TableFrameFittingStrategy FittingStrategy { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGlossaryTable.yml" sourcestartlinenumber="1">Reconstructs the CIMGlossaryTable with a specified state from a JSON encoding.</p>


```csharp
public static CIMGlossaryTable FromJson(string json, JsonDeserializationSettings settings = null)
```
### HeadingGap

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGlossaryTable.yml" sourcestartlinenumber="1">Gets or sets the gap between column headings and rows. Values are in points.</p>


```csharp
public double HeadingGap { get; set; }
```
### HorizontalTextGap

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGlossaryTable.yml" sourcestartlinenumber="1">Gets or sets the horizontal gap around field values. Values are in points.</p>


```csharp
public double HorizontalTextGap { get; set; }
```
### MapMemberURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGlossaryTable.yml" sourcestartlinenumber="1">Gets or sets the URI to a Layer or Standalone table in the project.</p>


```csharp
public string MapMemberURI { get; set; }
```
### MinFontSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGlossaryTable.yml" sourcestartlinenumber="1">Gets or sets the limit when reducing font sizes. Values are in points.</p>


```csharp
public double MinFontSize { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGlossaryTable.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RightToLeft

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGlossaryTable.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether right to left orientation should be applied.</p>


```csharp
public bool RightToLeft { get; set; }
```
### RowGap

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGlossaryTable.yml" sourcestartlinenumber="1">Gets or sets the gap between rows. Values are in points.</p>


```csharp
public double RowGap { get; set; }
```
### Title

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGlossaryTable.yml" sourcestartlinenumber="1">Gets or sets the title of the element.</p>


```csharp
public string Title { get; set; }
```
### TitleGap

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGlossaryTable.yml" sourcestartlinenumber="1">Gets or sets the gap between title and column headings. Values are in points.</p>


```csharp
public double TitleGap { get; set; }
```
### TitleTextSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGlossaryTable.yml" sourcestartlinenumber="1">Gets or sets the text symbol for title text.</p>


```csharp
public CIMSymbolReference TitleTextSymbol { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGlossaryTable.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGlossaryTable and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### VerticalTextGap

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGlossaryTable.yml" sourcestartlinenumber="1">Gets or sets the vertical gap around field values. Values are in points.</p>


```csharp
public double VerticalTextGap { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGlossaryTable.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


