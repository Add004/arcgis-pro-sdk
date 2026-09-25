# CIMPlaceNameIndex

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMPlaceNameIndex.yml" sourcestartlinenumber="1">Represents the place name index surround element.</p>


## Object Signature

```csharp
public class CIMPlaceNameIndex : CIMMapSurround, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMPlaceNameIndex()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMPlaceNameIndex.yml" sourcestartlinenumber="1">Represents the place name index surround element.</p>


```csharp
public CIMPlaceNameIndex()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPlaceNameIndex.yml" sourcestartlinenumber="1">Creates a deep copy of CIMPlaceNameIndex.</p>


```csharp
public CIMPlaceNameIndex Clone()
```
### ColumnGap

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPlaceNameIndex.yml" sourcestartlinenumber="1">Gets or sets the gap between frame columns. Units in points.</p>


```csharp
public double ColumnGap { get; set; }
```
### CustomGroupHeader

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPlaceNameIndex.yml" sourcestartlinenumber="1">Gets or sets the text value to use for custom group header.</p>


```csharp
public string CustomGroupHeader { get; set; }
```
### FittingStrategy

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPlaceNameIndex.yml" sourcestartlinenumber="1">Gets or sets the fitting strategy.</p>


```csharp
public PlaceNameFittingStrategy FittingStrategy { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPlaceNameIndex.yml" sourcestartlinenumber="1">Reconstructs the CIMPlaceNameIndex with a specified state from a JSON encoding.</p>


```csharp
public static CIMPlaceNameIndex FromJson(string json, JsonDeserializationSettings settings = null)
```
### GridLayer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPlaceNameIndex.yml" sourcestartlinenumber="1">Gets or sets the layer information for grid features.</p>


```csharp
public CIMPlaceNameLayerInfo GridLayer { get; set; }
```
### GridValueDelimiter

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPlaceNameIndex.yml" sourcestartlinenumber="1">Gets or sets the delimiter that is displayed between multiple grid values.</p>


```csharp
public StreetIndexDelimiter GridValueDelimiter { get; set; }
```
### GroupByExpression

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPlaceNameIndex.yml" sourcestartlinenumber="1">Gets or sets the arcade expression that controls what text will be displayed from groupby field.</p>


```csharp
public CIMExpressionInfo GroupByExpression { get; set; }
```
### GroupGap

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPlaceNameIndex.yml" sourcestartlinenumber="1">Gets or sets the spacing between group text and index text. Units in points.</p>


```csharp
public double GroupGap { get; set; }
```
### GroupTextSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPlaceNameIndex.yml" sourcestartlinenumber="1">Gets or sets the text symbol for a field that is grouped.</p>


```csharp
public CIMSymbolReference GroupTextSymbol { get; set; }
```
### HorizontalTextGap

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPlaceNameIndex.yml" sourcestartlinenumber="1">Gets or sets the horizontal gap around field values. Units in points.</p>


```csharp
public double HorizontalTextGap { get; set; }
```
### IndexDelimiter

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPlaceNameIndex.yml" sourcestartlinenumber="1">Gets or sets the delimiter that is displayed between the place name and grid value.</p>


```csharp
public StreetIndexDelimiter IndexDelimiter { get; set; }
```
### IndexDelimiterSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPlaceNameIndex.yml" sourcestartlinenumber="1">Gets or sets the symbol for the index delimiter.</p>


```csharp
public CIMSymbolReference IndexDelimiterSymbol { get; set; }
```
### MaxFontSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPlaceNameIndex.yml" sourcestartlinenumber="1">Gets or sets the maximum font size. Units in points.</p>


```csharp
public double MaxFontSize { get; set; }
```
### MinFontSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPlaceNameIndex.yml" sourcestartlinenumber="1">Gets or sets the minimum font size. Units in points.</p>


```csharp
public double MinFontSize { get; set; }
```
### PlaceNameLayer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPlaceNameIndex.yml" sourcestartlinenumber="1">Gets or sets the layer information for place name features.</p>


```csharp
public CIMPlaceNameLayerInfo PlaceNameLayer { get; set; }
```
### PlaceNameLayerSortFields

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPlaceNameIndex.yml" sourcestartlinenumber="1">Gets or sets the fields used from the place name layer for sorting.</p>


```csharp
public CIMTableField[] PlaceNameLayerSortFields { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPlaceNameIndex.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RightToLeft

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPlaceNameIndex.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether right to left orientation should be applied.</p>


```csharp
public bool RightToLeft { get; set; }
```
### RowGap

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPlaceNameIndex.yml" sourcestartlinenumber="1">Gets or sets the gap between rows. Units in points.</p>


```csharp
public double RowGap { get; set; }
```
### ShowGroupHeaders

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPlaceNameIndex.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to show/hide group headers.</p>


```csharp
public bool ShowGroupHeaders { get; set; }
```
### ShowTitle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPlaceNameIndex.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to show/hide the title.</p>


```csharp
public bool ShowTitle { get; set; }
```
### SpatialRelationship

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPlaceNameIndex.yml" sourcestartlinenumber="1">Gets or sets the spatial relationship between place name and grid features.</p>


```csharp
public esriSpatialRelEnum SpatialRelationship { get; set; }
```
### TitleText

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPlaceNameIndex.yml" sourcestartlinenumber="1">Gets or sets the text for the title of the element.</p>


```csharp
public string TitleText { get; set; }
```
### TitleTextSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPlaceNameIndex.yml" sourcestartlinenumber="1">Gets or sets the text symbol for title text.</p>


```csharp
public CIMSymbolReference TitleTextSymbol { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPlaceNameIndex.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMPlaceNameIndex and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### VerticalTextGap

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPlaceNameIndex.yml" sourcestartlinenumber="1">Gets or sets the vertical gap around field values. Units in points.</p>


```csharp
public double VerticalTextGap { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPlaceNameIndex.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


