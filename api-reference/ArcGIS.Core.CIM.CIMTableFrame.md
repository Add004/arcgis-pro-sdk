# CIMTableFrame

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableFrame.yml" sourcestartlinenumber="1">Layout element used to display tabular data.</p>


## Object Signature

```csharp
public class CIMTableFrame : CIMMapSurround, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMTableFrame()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableFrame.yml" sourcestartlinenumber="1">Layout element used to display tabular data.</p>


```csharp
public CIMTableFrame()
```
### Alternate1RowBackgroundCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableFrame.yml" sourcestartlinenumber="1">Gets or sets the alternate 1 row background count. Show even row background for this many rows before alternating.</p>


```csharp
public int Alternate1RowBackgroundCount { get; set; }
```
### Alternate1RowBackgroundSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableFrame.yml" sourcestartlinenumber="1">Gets or sets the second alternating data record background symbol.</p>


```csharp
public CIMSymbolReference Alternate1RowBackgroundSymbol { get; set; }
```
### Alternate2RowBackgroundCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableFrame.yml" sourcestartlinenumber="1">Gets or sets the alternate 2 row background count. Show odd row background for this many rows before alternating.</p>


```csharp
public int Alternate2RowBackgroundCount { get; set; }
```
### Alternate2RowBackgroundSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableFrame.yml" sourcestartlinenumber="1">Gets or sets the first alternating data record background symbol.</p>


```csharp
public CIMSymbolReference Alternate2RowBackgroundSymbol { get; set; }
```
### BalanceColumns

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableFrame.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to balance the columns of the table.</p>


```csharp
public bool BalanceColumns { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableFrame.yml" sourcestartlinenumber="1">Creates a deep copy of CIMTableFrame.</p>


```csharp
public CIMTableFrame Clone()
```
### ColumnBorderSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableFrame.yml" sourcestartlinenumber="1">Gets or sets the column border symbol.</p>


```csharp
public CIMSymbolReference ColumnBorderSymbol { get; set; }
```
### ColumnGap

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableFrame.yml" sourcestartlinenumber="1">Gets or sets the gap between table columns.</p>


```csharp
public double ColumnGap { get; set; }
```
### Columns

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableFrame.yml" sourcestartlinenumber="1">Gets or sets the number of columns.</p>


```csharp
public int Columns { get; set; }
```
### CustomWhereClause

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableFrame.yml" sourcestartlinenumber="1">Gets or sets the custom where clause. Show rows that match custom where clause when FillingStrategy is set to esriCIMTableFrameFillingStrategy_CustomWhereClause.</p>


```csharp
public string CustomWhereClause { get; set; }
```
### DefaultTableFrameField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableFrame.yml" sourcestartlinenumber="1">Gets or sets the default table frame field used when creating new table frames.</p>


```csharp
public CIMTableFrameField DefaultTableFrameField { get; set; }
```
### FieldGap

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableFrame.yml" sourcestartlinenumber="1">Gets or sets the gap between fields.</p>


```csharp
public double FieldGap { get; set; }
```
### Fields

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableFrame.yml" sourcestartlinenumber="1">Gets or sets the fields displayed by the table frame.</p>


```csharp
public CIMTableFrameField[] Fields { get; set; }
```
### FillingStrategy

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableFrame.yml" sourcestartlinenumber="1">Gets or sets the strategy used to query records.</p>


```csharp
public TableFrameFillingStrategy FillingStrategy { get; set; }
```
### FittingStrategy

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableFrame.yml" sourcestartlinenumber="1">Gets or sets the strategy used to query records.</p>


```csharp
public TableFrameFittingStrategy FittingStrategy { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableFrame.yml" sourcestartlinenumber="1">Reconstructs the CIMTableFrame with a specified state from a JSON encoding.</p>


```csharp
public static CIMTableFrame FromJson(string json, JsonDeserializationSettings settings = null)
```
### HeadingBackgroundSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableFrame.yml" sourcestartlinenumber="1">Gets or sets the field name/alias background symbol.</p>


```csharp
public CIMSymbolReference HeadingBackgroundSymbol { get; set; }
```
### HeadingBorderSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableFrame.yml" sourcestartlinenumber="1">Gets or sets the field name/alias border symbol.</p>


```csharp
public CIMSymbolReference HeadingBorderSymbol { get; set; }
```
### HeadingGap

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableFrame.yml" sourcestartlinenumber="1">Gets or sets the gap between field names and rows.</p>


```csharp
public double HeadingGap { get; set; }
```
### HeadingLineSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableFrame.yml" sourcestartlinenumber="1">Gets or sets the field name/alias underline symbol.</p>


```csharp
public CIMSymbolReference HeadingLineSymbol { get; set; }
```
### HorizontalTextGap

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableFrame.yml" sourcestartlinenumber="1">Gets or sets the horizontal gap around field values.</p>


```csharp
public double HorizontalTextGap { get; set; }
```
### MapMemberURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableFrame.yml" sourcestartlinenumber="1">Gets or sets the layer or standalone table that defines the data to display.</p>


```csharp
public string MapMemberURI { get; set; }
```
### MinFontSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableFrame.yml" sourcestartlinenumber="1">Gets or sets the limit when reducing font sizes. Values is in points.</p>


```csharp
public double MinFontSize { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableFrame.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RowBorderSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableFrame.yml" sourcestartlinenumber="1">Gets or sets the border symbol for row sections: data records, summary statistics, and statistics totals.</p>


```csharp
public CIMSymbolReference RowBorderSymbol { get; set; }
```
### RowGap

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableFrame.yml" sourcestartlinenumber="1">Gets or sets the gap between rows.</p>


```csharp
public double RowGap { get; set; }
```
### RowLimit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableFrame.yml" sourcestartlinenumber="1">Gets or sets the maximum number of rows the table frame will show. 0 Indicates &quot;no limit&quot;.</p>


```csharp
public int RowLimit { get; set; }
```
### ShowHeadings

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableFrame.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to show the headings.</p>


```csharp
public bool ShowHeadings { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableFrame.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMTableFrame and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### VerticalTextGap

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableFrame.yml" sourcestartlinenumber="1">Gets or sets the vertical gap around field values.</p>


```csharp
public double VerticalTextGap { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableFrame.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


