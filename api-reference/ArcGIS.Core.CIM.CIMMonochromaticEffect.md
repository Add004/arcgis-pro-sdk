# CIMMonochromaticEffect

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMonochromaticEffect.yml" sourcestartlinenumber="1">Represents a visual effect for reshading the scene to monochromatic tones.</p>


## Object Signature

```csharp
public class CIMMonochromaticEffect : CIMVisualEffect, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMonochromaticEffect()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMonochromaticEffect.yml" sourcestartlinenumber="1">Represents a visual effect for reshading the scene to monochromatic tones.</p>


```csharp
public CIMMonochromaticEffect()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMonochromaticEffect.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMonochromaticEffect.</p>


```csharp
public CIMMonochromaticEffect Clone()
```
### Color

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMonochromaticEffect.yml" sourcestartlinenumber="1">Gets or sets the color of the effect.</p>


```csharp
public CIMColor Color { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMonochromaticEffect.yml" sourcestartlinenumber="1">Reconstructs the CIMMonochromaticEffect with a specified state from a JSON encoding.</p>


```csharp
public static CIMMonochromaticEffect FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMonochromaticEffect.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMonochromaticEffect.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMonochromaticEffect and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMonochromaticEffect.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


