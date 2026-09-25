# CIMGradientFill

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGradientFill.yml" sourcestartlinenumber="1">Represents a gradient fill which fills polygonal geometry with a specified color scheme.</p>


## Object Signature

```csharp
public class CIMGradientFill : CIMFill, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGradientFill()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGradientFill.yml" sourcestartlinenumber="1">Represents a gradient fill which fills polygonal geometry with a specified color scheme.</p>


```csharp
public CIMGradientFill()
```
### Angle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGradientFill.yml" sourcestartlinenumber="1">Gets or sets the angle of the gradient when the GradientMethod is set to Linear or Rectangular.</p>


```csharp
public double Angle { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGradientFill.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGradientFill.</p>


```csharp
public CIMGradientFill Clone()
```
### ColorRamp

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGradientFill.yml" sourcestartlinenumber="1">Gets or sets the color scheme that is applied to the fill.</p>


```csharp
public CIMColorRamp ColorRamp { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGradientFill.yml" sourcestartlinenumber="1">Reconstructs the CIMGradientFill with a specified state from a JSON encoding.</p>


```csharp
public static CIMGradientFill FromJson(string json, JsonDeserializationSettings settings = null)
```
### GradientMethod

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGradientFill.yml" sourcestartlinenumber="1">Gets or sets a value which specifies how the gradient is applied within the fill.</p>


```csharp
public GradientFillMethod GradientMethod { get; set; }
```
### GradientSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGradientFill.yml" sourcestartlinenumber="1">Gets or sets a value which determines how much of the feature is covered by the color scheme. This is either a percentage of the total area which the color scheme spans or the number of page units from the starting point at which the gradient displays.</p>


```csharp
public double GradientSize { get; set; }
```
### GradientSizeUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGradientFill.yml" sourcestartlinenumber="1">Gets or sets a value which specifies whether GradientSize is applied with an absolute distance or a relative percentage.</p>


```csharp
public SymbolUnits GradientSizeUnits { get; set; }
```
### GradientType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGradientFill.yml" sourcestartlinenumber="1">Gets or sets a value which specifies if the gradient is applied with discrete intervals or if it is continuous.</p>


```csharp
public GradientStrokeType GradientType { get; set; }
```
### Interval

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGradientFill.yml" sourcestartlinenumber="1">Gets or sets how many bands draw when the GradientType is set to Discrete.</p>


```csharp
public int Interval { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGradientFill.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGradientFill.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGradientFill and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGradientFill.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


