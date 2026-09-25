# CIMRandomHSVColorRamp

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMRandomHSVColorRamp.yml" sourcestartlinenumber="1">Represents a random HSV color ramp scheme.</p>


## Object Signature

```csharp
public class CIMRandomHSVColorRamp : CIMColorRamp, INotifyPropertyChanged, IXmlSerializable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.CIMRandomHSVColorRamp.yml" sourcestartlinenumber="1">A color ramp scheme where the colors are randomly selected within the set range of hue, saturation, and value values.</p>


## Members

### CIMRandomHSVColorRamp()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMRandomHSVColorRamp.yml" sourcestartlinenumber="1">Represents a random HSV color ramp scheme.</p>


```csharp
public CIMRandomHSVColorRamp()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRandomHSVColorRamp.yml" sourcestartlinenumber="1">Creates a deep copy of CIMRandomHSVColorRamp.</p>


```csharp
public CIMRandomHSVColorRamp Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRandomHSVColorRamp.yml" sourcestartlinenumber="1">Reconstructs the CIMRandomHSVColorRamp with a specified state from a JSON encoding.</p>


```csharp
public static CIMRandomHSVColorRamp FromJson(string json, JsonDeserializationSettings settings = null)
```
### MaxAlpha

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRandomHSVColorRamp.yml" sourcestartlinenumber="1">Gets or sets the maximum alpha or transparency for all of the colors. Can be a value between 0-100, where 0 is fully transparent.</p>


```csharp
public float MaxAlpha { get; set; }
```
### MaxH

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRandomHSVColorRamp.yml" sourcestartlinenumber="1">Gets or sets the hue at which the color ramp (also known as a color scheme) will end. Values can range from 0-360.</p>


```csharp
public float MaxH { get; set; }
```
### MaxS

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRandomHSVColorRamp.yml" sourcestartlinenumber="1">Gets or sets the maximum saturation possible for the colors within the color ramp (also known as a color scheme). Values can range between 0-100.</p>


```csharp
public float MaxS { get; set; }
```
### MaxV

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRandomHSVColorRamp.yml" sourcestartlinenumber="1">Gets or sets the maximum value possible for the colors within the color ramp (also known as a color scheme). Values can range between 0-100.</p>


```csharp
public float MaxV { get; set; }
```
### MinAlpha

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRandomHSVColorRamp.yml" sourcestartlinenumber="1">Gets or sets the minimum alpha or transparency for all of the colors. Can be a value between 0-100, where 0 is fully transparent.</p>


```csharp
public float MinAlpha { get; set; }
```
### MinH

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRandomHSVColorRamp.yml" sourcestartlinenumber="1">Gets or sets the hue from which the color ramp (also known as a color scheme) will start. Values can range from 0-360.</p>


```csharp
public float MinH { get; set; }
```
### MinS

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRandomHSVColorRamp.yml" sourcestartlinenumber="1">Gets or sets the minimum saturation possible for the colors within the color ramp (also known as a color scheme). Values can range between 0-100.</p>


```csharp
public float MinS { get; set; }
```
### MinV

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRandomHSVColorRamp.yml" sourcestartlinenumber="1">Gets or sets the minimum value possible for the colors within the ramp (also known as a scheme). Values can range between 0-100.</p>


```csharp
public float MinV { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRandomHSVColorRamp.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Seed

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRandomHSVColorRamp.yml" sourcestartlinenumber="1">Gets or sets the starting point for the random generation of the colors.</p>


```csharp
public int Seed { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRandomHSVColorRamp.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMRandomHSVColorRamp and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRandomHSVColorRamp.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


