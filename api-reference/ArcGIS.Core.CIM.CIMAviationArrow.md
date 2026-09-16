# CIMAviationArrow

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationArrow.yml" sourcestartlinenumber="1">Represents an individual arrow in CIMAviationNorthArrow.</p>


## Object Signature

```csharp
public class CIMAviationArrow : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMAviationArrow()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationArrow.yml" sourcestartlinenumber="1">Represents an individual arrow in CIMAviationNorthArrow.</p>


```csharp
public CIMAviationArrow()
```
### ArrowLength

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationArrow.yml" sourcestartlinenumber="1">Gets or sets the line length for the arrow, internally units will always be of type points.</p>


```csharp
public double ArrowLength { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationArrow.yml" sourcestartlinenumber="1">Creates a deep copy of CIMAviationArrow.</p>


```csharp
public CIMAviationArrow Clone()
```
### DefaultPointSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationArrow.yml" sourcestartlinenumber="1">Gets or sets the default point symbol for the arrow.</p>


```csharp
public CIMSymbolReference DefaultPointSymbol { get; set; }
```
### EnableArrow

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationArrow.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the arrow is enabled.</p>


```csharp
public bool EnableArrow { get; set; }
```
### EnableLineIndicator

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationArrow.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the arrow's line indicator is enabled.</p>


```csharp
public bool EnableLineIndicator { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationArrow.yml" sourcestartlinenumber="1">Reconstructs the CIMAviationArrow with a specified state from a JSON encoding.</p>


```csharp
public static CIMAviationArrow FromJson(string json, JsonDeserializationSettings settings = null)
```
### LineIndicatorText

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationArrow.yml" sourcestartlinenumber="1">Gets or sets the text for the line indicator text symbol.</p>


```csharp
public string LineIndicatorText { get; set; }
```
### LineIndicatorTextSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationArrow.yml" sourcestartlinenumber="1">Gets or sets the indicator text symbol for the arrow.</p>


```csharp
public CIMSymbolReference LineIndicatorTextSymbol { get; set; }
```
### LineSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationArrow.yml" sourcestartlinenumber="1">Gets or sets the line symbol for the arrow.</p>


```csharp
public CIMSymbolReference LineSymbol { get; set; }
```
### NegativePointSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationArrow.yml" sourcestartlinenumber="1">Gets or sets the negative point symbol for the arrow.</p>


```csharp
public CIMSymbolReference NegativePointSymbol { get; set; }
```
### PositivePointSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationArrow.yml" sourcestartlinenumber="1">Gets or sets the positive point symbol for the arrow.</p>


```csharp
public CIMSymbolReference PositivePointSymbol { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationArrow.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationArrow.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMAviationArrow and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationArrow.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


