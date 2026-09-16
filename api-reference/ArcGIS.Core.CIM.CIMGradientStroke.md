# CIMGradientStroke

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGradientStroke.yml" sourcestartlinenumber="1">Represents a gradient stroke which draws linear geometry with a specified color scheme.</p>


## Object Signature

```csharp
public class CIMGradientStroke : CIMStroke, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGradientStroke()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGradientStroke.yml" sourcestartlinenumber="1">Represents a gradient stroke which draws linear geometry with a specified color scheme.</p>


```csharp
public CIMGradientStroke()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGradientStroke.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGradientStroke.</p>


```csharp
public CIMGradientStroke Clone()
```
### ColorRamp

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGradientStroke.yml" sourcestartlinenumber="1">Gets or sets the color scheme that is applied to the stroke.</p>


```csharp
public CIMColorRamp ColorRamp { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGradientStroke.yml" sourcestartlinenumber="1">Reconstructs the CIMGradientStroke with a specified state from a JSON encoding.</p>


```csharp
public static CIMGradientStroke FromJson(string json, JsonDeserializationSettings settings = null)
```
### GradientMethod

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGradientStroke.yml" sourcestartlinenumber="1">Gets or sets how the gradient is applied along the stroke.</p>


```csharp
public GradientStrokeMethod GradientMethod { get; set; }
```
### GradientSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGradientStroke.yml" sourcestartlinenumber="1">Gets or sets how much of the feature is covered by the color scheme. This is either a percentage of the total area which the color scheme spans or the number of page units from the starting point at which the gradient displays.</p>


```csharp
public double GradientSize { get; set; }
```
### GradientSizeUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGradientStroke.yml" sourcestartlinenumber="1">Gets or sets whether GradientSize is applied with an absolute distance or a relative percentage.</p>


```csharp
public SymbolUnits GradientSizeUnits { get; set; }
```
### GradientType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGradientStroke.yml" sourcestartlinenumber="1">Gets or sets whether the gradient is applied with discrete or continuous intervals.</p>


```csharp
public GradientStrokeType GradientType { get; set; }
```
### Interval

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGradientStroke.yml" sourcestartlinenumber="1">Gets or sets how many bands draw when the GradientType is set to Discrete.</p>


```csharp
public int Interval { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGradientStroke.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGradientStroke.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGradientStroke and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGradientStroke.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


