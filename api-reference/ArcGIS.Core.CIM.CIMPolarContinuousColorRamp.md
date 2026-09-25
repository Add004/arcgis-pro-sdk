# CIMPolarContinuousColorRamp

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMPolarContinuousColorRamp.yml" sourcestartlinenumber="1">Represents a polar continuous color ramp scheme.</p>


## Object Signature

```csharp
public class CIMPolarContinuousColorRamp : CIMContinuousColorRamp, INotifyPropertyChanged, IXmlSerializable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.CIMPolarContinuousColorRamp.yml" sourcestartlinenumber="1">A color ramp scheme that has a polar transition between two colors. This scheme uses the HSV algorithm which uses a path around the color wheel to transition the hue, saturation, and value of the beginning color to the hue, saturation, and value of the ending color.</p>


## Members

### CIMPolarContinuousColorRamp()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMPolarContinuousColorRamp.yml" sourcestartlinenumber="1">Represents a polar continuous color ramp scheme.</p>


```csharp
public CIMPolarContinuousColorRamp()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPolarContinuousColorRamp.yml" sourcestartlinenumber="1">Creates a deep copy of CIMPolarContinuousColorRamp.</p>


```csharp
public CIMPolarContinuousColorRamp Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPolarContinuousColorRamp.yml" sourcestartlinenumber="1">Reconstructs the CIMPolarContinuousColorRamp with a specified state from a JSON encoding.</p>


```csharp
public static CIMPolarContinuousColorRamp FromJson(string json, JsonDeserializationSettings settings = null)
```
### InterpolationSpace

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPolarContinuousColorRamp.yml" sourcestartlinenumber="1">Gets or sets the color space in which the polar interpolation occurs. HSV, HLS, and LAB are the only supported color space types.</p>


```csharp
public ColorSpaceType InterpolationSpace { get; set; }
```
### PolarDirection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPolarContinuousColorRamp.yml" sourcestartlinenumber="1">Gets or sets the direction of the polar progression for the path from the beginning hue to the ending hue.</p>


```csharp
public PolarDirection PolarDirection { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPolarContinuousColorRamp.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPolarContinuousColorRamp.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMPolarContinuousColorRamp and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPolarContinuousColorRamp.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


