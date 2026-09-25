# CIMScaleBar

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleBar.yml" sourcestartlinenumber="1">Represents a scale bar on a page layout.</p>


## Object Signature

```csharp
public abstract class CIMScaleBar : CIMMapSurround, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMScaleBar()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleBar.yml" sourcestartlinenumber="1">Represents a scale bar on a page layout.</p>


```csharp
protected CIMScaleBar()
```
### AlignToZeroPoint

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleBar.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the scale bar should align to zero.</p>


```csharp
public bool AlignToZeroPoint { get; set; }
```
### BarHeight

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleBar.yml" sourcestartlinenumber="1">Gets or sets the scale bar height.</p>


```csharp
public double BarHeight { get; set; }
```
### BarWidth

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleBar.yml" sourcestartlinenumber="1">Gets or sets the width of the scale bar.</p>


```csharp
public double BarWidth { get; set; }
```
### ComputeAtCenter

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleBar.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to compute the scale at map center.</p>


```csharp
public bool ComputeAtCenter { get; set; }
```
### DisplayFirstOutside

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleBar.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to display the first numeric value outside the bar.</p>


```csharp
public bool DisplayFirstOutside { get; set; }
```
### DisplayLastOutside

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleBar.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to display the last numeric value outside the bar.</p>


```csharp
public bool DisplayLastOutside { get; set; }
```
### Division

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleBar.yml" sourcestartlinenumber="1">Gets or sets the division value.</p>


```csharp
public double Division { get; set; }
```
### DivisionMarkHeight

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleBar.yml" sourcestartlinenumber="1">Gets or sets the division mark height value.</p>


```csharp
public double DivisionMarkHeight { get; set; }
```
### DivisionMarkSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleBar.yml" sourcestartlinenumber="1">Gets or sets the division mark line symbol.</p>


```csharp
public CIMSymbolReference DivisionMarkSymbol { get; set; }
```
### Divisions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleBar.yml" sourcestartlinenumber="1">Gets or sets the number of divisions.</p>


```csharp
public int Divisions { get; set; }
```
### DivisionsBeforeZero

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleBar.yml" sourcestartlinenumber="1">Gets or sets the number of divisions before zero.</p>


```csharp
public int DivisionsBeforeZero { get; set; }
```
### FittingStrategy

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleBar.yml" sourcestartlinenumber="1">Gets or sets the fitting strategy.</p>


```csharp
public ScaleBarFittingStrategy FittingStrategy { get; set; }
```
### LabelFrequency

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleBar.yml" sourcestartlinenumber="1">Gets or sets the label frequency.</p>


```csharp
public ScaleBarFrequency LabelFrequency { get; set; }
```
### LabelGap

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleBar.yml" sourcestartlinenumber="1">Gets or sets the label gap value.</p>


```csharp
public double LabelGap { get; set; }
```
### LabelPosition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleBar.yml" sourcestartlinenumber="1">Gets or sets the label position.</p>


```csharp
public ScaleBarVerticalPosition LabelPosition { get; set; }
```
### LabelSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleBar.yml" sourcestartlinenumber="1">Gets or sets label symbol.</p>


```csharp
public CIMSymbolReference LabelSymbol { get; set; }
```
### MarkFrequency

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleBar.yml" sourcestartlinenumber="1">Gets or sets the division mark frequency.</p>


```csharp
public ScaleBarFrequency MarkFrequency { get; set; }
```
### MarkPosition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleBar.yml" sourcestartlinenumber="1">Gets or sets the division mark position.</p>


```csharp
public ScaleBarVerticalPosition MarkPosition { get; set; }
```
### MidpointMarkHeight

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleBar.yml" sourcestartlinenumber="1">Gets or sets the midpoint mark height.</p>


```csharp
public double MidpointMarkHeight { get; set; }
```
### MidpointMarkSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleBar.yml" sourcestartlinenumber="1">Gets or sets the midpoint mark line symbol.</p>


```csharp
public CIMSymbolReference MidpointMarkSymbol { get; set; }
```
### NumberFormat

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleBar.yml" sourcestartlinenumber="1">Gets or sets the number format.</p>


```csharp
public CIMNumberFormat NumberFormat { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleBar.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SubdivisionMarkHeight

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleBar.yml" sourcestartlinenumber="1">Gets or sets the subdivision mark height.</p>


```csharp
public double SubdivisionMarkHeight { get; set; }
```
### SubdivisionMarkSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleBar.yml" sourcestartlinenumber="1">Gets or sets the subdivision mark line symbol.</p>


```csharp
public CIMSymbolReference SubdivisionMarkSymbol { get; set; }
```
### Subdivisions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleBar.yml" sourcestartlinenumber="1">Gets or sets the number of subdivisions.</p>


```csharp
public int Subdivisions { get; set; }
```
### UnitLabel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleBar.yml" sourcestartlinenumber="1">Gets or sets the unit label.</p>


```csharp
public string UnitLabel { get; set; }
```
### UnitLabelGap

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleBar.yml" sourcestartlinenumber="1">Gets or sets the unit label gap. Units set in points.</p>


```csharp
public double UnitLabelGap { get; set; }
```
### UnitLabelPosition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleBar.yml" sourcestartlinenumber="1">Gets or sets the unit label position.</p>


```csharp
public ScaleBarLabelPosition UnitLabelPosition { get; set; }
```
### UnitLabelSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleBar.yml" sourcestartlinenumber="1">Gets or sets the unit label symbol.</p>


```csharp
public CIMSymbolReference UnitLabelSymbol { get; set; }
```
### Units

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleBar.yml" sourcestartlinenumber="1">Gets or sets the units for the scale bar.</p>


```csharp
public Unit Units { get; set; }
```
### UseFractionCharacters

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleBar.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether fractional characters should be used.</p>


```csharp
public bool UseFractionCharacters { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleBar.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```
### ZeroPoint

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleBar.yml" sourcestartlinenumber="1">Gets or sets the zero location for the scale bar.</p>


```csharp
public MapPoint ZeroPoint { get; set; }
```


