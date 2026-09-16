# CIMDimensionStyle

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionStyle.yml" sourcestartlinenumber="1">Represents an dimension style which defines dimension appearance.</p>


## Object Signature

```csharp
public class CIMDimensionStyle : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMDimensionStyle()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionStyle.yml" sourcestartlinenumber="1">Represents an dimension style which defines dimension appearance.</p>


```csharp
public CIMDimensionStyle()
```
### Align

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionStyle.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the text should be aligned with the dimension line.</p>


```csharp
public bool Align { get; set; }
```
### BaselineHeight

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionStyle.yml" sourcestartlinenumber="1">Gets or sets the height of the construction for creating baseline dimensions with this style.</p>


```csharp
public double BaselineHeight { get; set; }
```
### BeginMarkerSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionStyle.yml" sourcestartlinenumber="1">Gets or sets the symbol used for the begin arrow.</p>


```csharp
public CIMPointSymbol BeginMarkerSymbol { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionStyle.yml" sourcestartlinenumber="1">Creates a deep copy of CIMDimensionStyle.</p>


```csharp
public CIMDimensionStyle Clone()
```
### ConvertUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionStyle.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the length of the dimension needs to be converted for display.</p>


```csharp
public bool ConvertUnits { get; set; }
```
### DimensionLineOption

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionStyle.yml" sourcestartlinenumber="1">Gets or sets the dimension line display of the style.</p>


```csharp
public DimensionPartOptions DimensionLineOption { get; set; }
```
### DimensionLineSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionStyle.yml" sourcestartlinenumber="1">Gets or sets the symbol used for the dimension line.</p>


```csharp
public CIMLineSymbol DimensionLineSymbol { get; set; }
```
### DisplayPrecision

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionStyle.yml" sourcestartlinenumber="1">Gets or sets the precision for the value displayed by the dimension text.</p>


```csharp
public int DisplayPrecision { get; set; }
```
### DisplayUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionStyle.yml" sourcestartlinenumber="1">Gets or sets the units the length of the dimension text is displayed in.</p>


```csharp
public Unit DisplayUnits { get; set; }
```
### DrawLineOnFit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionStyle.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether a dimension line should be drawn between the extension lines for an inward dimension.</p>


```csharp
public bool DrawLineOnFit { get; set; }
```
### EndMarkerSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionStyle.yml" sourcestartlinenumber="1">Gets or sets the symbol used for the end arrow.</p>


```csharp
public CIMPointSymbol EndMarkerSymbol { get; set; }
```
### Expression

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionStyle.yml" sourcestartlinenumber="1">Gets or sets the text expression for the style.</p>


```csharp
public string Expression { get; set; }
```
### ExpressionParserName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionStyle.yml" sourcestartlinenumber="1">Gets or sets the text expression parser for the text expression for the style.</p>


```csharp
public string ExpressionParserName { get; set; }
```
### ExpressionTitle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionStyle.yml" sourcestartlinenumber="1">Gets or sets the human readable text title that describes the dimension expression.</p>


```csharp
public string ExpressionTitle { get; set; }
```
### ExtendLineOnFit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionStyle.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the dimension line will be extended to underline the text on inward dimensions.</p>


```csharp
public bool ExtendLineOnFit { get; set; }
```
### ExtensionLineOffset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionStyle.yml" sourcestartlinenumber="1">Gets or sets the length of the extension line offset.</p>


```csharp
public double ExtensionLineOffset { get; set; }
```
### ExtensionLineOption

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionStyle.yml" sourcestartlinenumber="1">Gets or sets the extension line display options of the style.</p>


```csharp
public DimensionPartOptions ExtensionLineOption { get; set; }
```
### ExtensionLineOvershot

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionStyle.yml" sourcestartlinenumber="1">Gets or sets the length of the extension line overshot.</p>


```csharp
public double ExtensionLineOvershot { get; set; }
```
### ExtensionLineSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionStyle.yml" sourcestartlinenumber="1">Gets or sets the symbol used for extension lines.</p>


```csharp
public CIMLineSymbol ExtensionLineSymbol { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionStyle.yml" sourcestartlinenumber="1">Reconstructs the CIMDimensionStyle with a specified state from a JSON encoding.</p>


```csharp
public static CIMDimensionStyle FromJson(string json, JsonDeserializationSettings settings = null)
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionStyle.yml" sourcestartlinenumber="1">Gets or sets the ID of the style.</p>


```csharp
public int ID { get; set; }
```
### MarkerFit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionStyle.yml" sourcestartlinenumber="1">Gets or sets the arrow fit policy of the style.</p>


```csharp
public DimensionMarkerFit MarkerFit { get; set; }
```
### MarkerFitTolerance

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionStyle.yml" sourcestartlinenumber="1">Gets or sets the arrow fit tolerance of the style.</p>


```csharp
public double MarkerFitTolerance { get; set; }
```
### MarkerOption

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionStyle.yml" sourcestartlinenumber="1">Gets or sets the arrow display properties of the style.</p>


```csharp
public DimensionPartOptions MarkerOption { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionStyle.yml" sourcestartlinenumber="1">Gets or sets the name of the style.</p>


```csharp
public string Name { get; set; }
```
### Prefix

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionStyle.yml" sourcestartlinenumber="1">Gets or sets the prefix for the text expression for the style.</p>


```csharp
public string Prefix { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionStyle.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Suffix

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionStyle.yml" sourcestartlinenumber="1">Gets or sets the suffix for the text expression for the style.</p>


```csharp
public string Suffix { get; set; }
```
### TextFit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionStyle.yml" sourcestartlinenumber="1">Gets or sets the text fit policy for the style.</p>


```csharp
public DimensionTextFit TextFit { get; set; }
```
### TextOption

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionStyle.yml" sourcestartlinenumber="1">Gets or sets the text display option for the style.</p>


```csharp
public DimensionTextOption TextOption { get; set; }
```
### TextSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionStyle.yml" sourcestartlinenumber="1">Gets or sets the text symbol used for the text.</p>


```csharp
public CIMTextSymbol TextSymbol { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionStyle.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMDimensionStyle and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionStyle.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


