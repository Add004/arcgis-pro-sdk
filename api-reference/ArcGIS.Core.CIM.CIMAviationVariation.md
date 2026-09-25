# CIMAviationVariation

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationVariation.yml" sourcestartlinenumber="1">Represents the properties for the variation text which is displayed in aviation north arrow.</p>


## Object Signature

```csharp
public class CIMAviationVariation : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMAviationVariation()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationVariation.yml" sourcestartlinenumber="1">Represents the properties for the variation text which is displayed in aviation north arrow.</p>


```csharp
public CIMAviationVariation()
```
### AlignVariationToLine

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationVariation.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to align text to line or display on side.</p>


```csharp
public bool AlignVariationToLine { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationVariation.yml" sourcestartlinenumber="1">Creates a deep copy of CIMAviationVariation.</p>


```csharp
public CIMAviationVariation Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationVariation.yml" sourcestartlinenumber="1">Reconstructs the CIMAviationVariation with a specified state from a JSON encoding.</p>


```csharp
public static CIMAviationVariation FromJson(string json, JsonDeserializationSettings settings = null)
```
### GridVariationIdentifier

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationVariation.yml" sourcestartlinenumber="1">Gets or sets the grid north identifier for the variation text.</p>


```csharp
public string GridVariationIdentifier { get; set; }
```
### MagneticVariationIdentifier

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationVariation.yml" sourcestartlinenumber="1">Gets or sets the magnetic north identifier for the variation text.</p>


```csharp
public string MagneticVariationIdentifier { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationVariation.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShowYear

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationVariation.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to show the variation year in the variation text.</p>


```csharp
public bool ShowYear { get; set; }
```
### ShowYearInParenthesis

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationVariation.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to show the variation year enclosed in parenthesis.</p>


```csharp
public bool ShowYearInParenthesis { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationVariation.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMAviationVariation and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### VariationTextOnLeft

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationVariation.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the variation text will be displayed on the left side of aviation north arrow, if false will display on the right side.</p>


```csharp
public bool VariationTextOnLeft { get; set; }
```
### VariationTextSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationVariation.yml" sourcestartlinenumber="1">Gets or sets the text symbol used for variation text in aviation north arrow.</p>


```csharp
public CIMSymbolReference VariationTextSymbol { get; set; }
```
### VariationYearSeparator

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationVariation.yml" sourcestartlinenumber="1">Gets or sets the string separator that goes between the variation text and the variation year.</p>


```csharp
public string VariationYearSeparator { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationVariation.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


