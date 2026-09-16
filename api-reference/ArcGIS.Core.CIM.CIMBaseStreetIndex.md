# CIMBaseStreetIndex

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseStreetIndex.yml" sourcestartlinenumber="1">Represents the base class for index feature surround elements.</p>


## Object Signature

```csharp
public abstract class CIMBaseStreetIndex : CIMMapSurround, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMBaseStreetIndex()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseStreetIndex.yml" sourcestartlinenumber="1">Represents the base class for index feature surround elements.</p>


```csharp
protected CIMBaseStreetIndex()
```
### Columns

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseStreetIndex.yml" sourcestartlinenumber="1">Gets or sets the number of columns allowed to display.</p>


```csharp
public int Columns { get; set; }
```
### Fields

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseStreetIndex.yml" sourcestartlinenumber="1">Gets or sets the fields displayed in the street index.</p>


```csharp
public CIMTableField[] Fields { get; set; }
```
### FittingStrategy

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseStreetIndex.yml" sourcestartlinenumber="1">Gets or sets the fitting strategy.</p>


```csharp
public TableFrameFittingStrategy FittingStrategy { get; set; }
```
### GroupGap

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseStreetIndex.yml" sourcestartlinenumber="1">Gets or sets the spacing between group and headers.</p>


```csharp
public double GroupGap { get; set; }
```
### GroupTextSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseStreetIndex.yml" sourcestartlinenumber="1">Gets or sets the text symbol for a field that is grouped.</p>


```csharp
public CIMSymbolReference GroupTextSymbol { get; set; }
```
### HeaderGap

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseStreetIndex.yml" sourcestartlinenumber="1">Gets or sets the spacing between headers and data.</p>


```csharp
public double HeaderGap { get; set; }
```
### HeaderTextSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseStreetIndex.yml" sourcestartlinenumber="1">Gets or sets the text symbol for header text.</p>


```csharp
public CIMSymbolReference HeaderTextSymbol { get; set; }
```
### IndexDelimiter

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseStreetIndex.yml" sourcestartlinenumber="1">Gets or sets the delimiter that is displayed between columns.</p>


```csharp
public StreetIndexDelimiter IndexDelimiter { get; set; }
```
### LayerURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseStreetIndex.yml" sourcestartlinenumber="1">Gets or sets the path to the layer containing the features to be indexed.</p>


```csharp
public string LayerURI { get; set; }
```
### MinFontSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseStreetIndex.yml" sourcestartlinenumber="1">Gets or sets the minimum font size. Units in points.</p>


```csharp
public double MinFontSize { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseStreetIndex.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### TextSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseStreetIndex.yml" sourcestartlinenumber="1">Gets or sets the text symbol for the features.</p>


```csharp
public CIMSymbolReference TextSymbol { get; set; }
```
### TitleText

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseStreetIndex.yml" sourcestartlinenumber="1">Gets or sets the title of the element.</p>


```csharp
public string TitleText { get; set; }
```
### TitleTextSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseStreetIndex.yml" sourcestartlinenumber="1">Gets or sets the text symbol for title text.</p>


```csharp
public CIMSymbolReference TitleTextSymbol { get; set; }
```
### WrapMethod

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseStreetIndex.yml" sourcestartlinenumber="1">Gets or sets how the data should wrap across multiple columns.</p>


```csharp
public StreetIndexWrapMethod WrapMethod { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBaseStreetIndex.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


