# CIMAviationVerticalScaleProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationVerticalScaleProperties.yml" sourcestartlinenumber="1">Represents a set of scale properties for aviation-specific Vertical Scale Bar, such as a feet scale or meter scale properties.</p>


## Object Signature

```csharp
public class CIMAviationVerticalScaleProperties : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMAviationVerticalScaleProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationVerticalScaleProperties.yml" sourcestartlinenumber="1">Represents a set of scale properties for aviation-specific Vertical Scale Bar, such as a feet scale or meter scale properties.</p>


```csharp
public CIMAviationVerticalScaleProperties()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationVerticalScaleProperties.yml" sourcestartlinenumber="1">Creates a deep copy of CIMAviationVerticalScaleProperties.</p>


```csharp
public CIMAviationVerticalScaleProperties Clone()
```
### DivisionLineLength

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationVerticalScaleProperties.yml" sourcestartlinenumber="1">Gets or sets the division line length for the scale bar. The units are in points.</p>


```csharp
public double DivisionLineLength { get; set; }
```
### DivisionMarkSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationVerticalScaleProperties.yml" sourcestartlinenumber="1">Gets or sets the line symbol for the divisions.</p>


```csharp
public CIMSymbolReference DivisionMarkSymbol { get; set; }
```
### Divisions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationVerticalScaleProperties.yml" sourcestartlinenumber="1">Gets or sets the division count for the scale.</p>


```csharp
public int Divisions { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationVerticalScaleProperties.yml" sourcestartlinenumber="1">Reconstructs the CIMAviationVerticalScaleProperties with a specified state from a JSON encoding.</p>


```csharp
public static CIMAviationVerticalScaleProperties FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationVerticalScaleProperties.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ScaleBarHeight

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationVerticalScaleProperties.yml" sourcestartlinenumber="1">Gets or sets the height for the scale bar.</p>


```csharp
public double ScaleBarHeight { get; set; }
```
### ScaleTextSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationVerticalScaleProperties.yml" sourcestartlinenumber="1">Gets or sets the text symbol for the scale values.</p>


```csharp
public CIMSymbolReference ScaleTextSymbol { get; set; }
```
### ScaleUnitText

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationVerticalScaleProperties.yml" sourcestartlinenumber="1">Gets or sets the string value for the scale unit text.</p>


```csharp
public string ScaleUnitText { get; set; }
```
### SubdivisionLineLength

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationVerticalScaleProperties.yml" sourcestartlinenumber="1">Gets or sets the subdivision line length for the scale bar. The units are in points.</p>


```csharp
public double SubdivisionLineLength { get; set; }
```
### SubdivisionMarkSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationVerticalScaleProperties.yml" sourcestartlinenumber="1">Gets or sets the line symbol for the subdivisions.</p>


```csharp
public CIMSymbolReference SubdivisionMarkSymbol { get; set; }
```
### Subdivisions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationVerticalScaleProperties.yml" sourcestartlinenumber="1">Gets or sets the subdivision count for the scale.</p>


```csharp
public int Subdivisions { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationVerticalScaleProperties.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMAviationVerticalScaleProperties and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UnitTextSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationVerticalScaleProperties.yml" sourcestartlinenumber="1">Gets or sets the text symbol used for the scale unit.</p>


```csharp
public CIMSymbolReference UnitTextSymbol { get; set; }
```
### Visible

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationVerticalScaleProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to show this scale, if false no graphics will be shown.</p>


```csharp
public bool Visible { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationVerticalScaleProperties.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


