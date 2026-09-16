# CIMWatercolorEffect

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMWatercolorEffect.yml" sourcestartlinenumber="1">Represents a visual effect for reshading the scene with a watercolor style.</p>


## Object Signature

```csharp
public class CIMWatercolorEffect : CIMVisualEffect, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMWatercolorEffect()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMWatercolorEffect.yml" sourcestartlinenumber="1">Represents a visual effect for reshading the scene with a watercolor style.</p>


```csharp
public CIMWatercolorEffect()
```
### BackgroundColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMWatercolorEffect.yml" sourcestartlinenumber="1">Gets or sets the background color.</p>


```csharp
public CIMColor BackgroundColor { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMWatercolorEffect.yml" sourcestartlinenumber="1">Creates a deep copy of CIMWatercolorEffect.</p>


```csharp
public CIMWatercolorEffect Clone()
```
### DrawMarginOutlines

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMWatercolorEffect.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to draw the outlines in the margin.</p>


```csharp
public bool DrawMarginOutlines { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMWatercolorEffect.yml" sourcestartlinenumber="1">Reconstructs the CIMWatercolorEffect with a specified state from a JSON encoding.</p>


```csharp
public static CIMWatercolorEffect FromJson(string json, JsonDeserializationSettings settings = null)
```
### MarginGradient

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMWatercolorEffect.yml" sourcestartlinenumber="1">Gets or sets the percentage (0-1) across the margin where the midpoint of the gradient is applied.</p>


```csharp
public double MarginGradient { get; set; }
```
### MarginWidth

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMWatercolorEffect.yml" sourcestartlinenumber="1">Gets or sets the width of the margin in percentage (0-1).</p>


```csharp
public double MarginWidth { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMWatercolorEffect.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMWatercolorEffect.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMWatercolorEffect and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMWatercolorEffect.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


