# CIMHalftoneEffect

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMHalftoneEffect.yml" sourcestartlinenumber="1">Represents a visual effect for reshading the scene with halftone.</p>


## Object Signature

```csharp
public class CIMHalftoneEffect : CIMVisualEffect, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMHalftoneEffect()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMHalftoneEffect.yml" sourcestartlinenumber="1">Represents a visual effect for reshading the scene with halftone.</p>


```csharp
public CIMHalftoneEffect()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHalftoneEffect.yml" sourcestartlinenumber="1">Creates a deep copy of CIMHalftoneEffect.</p>


```csharp
public CIMHalftoneEffect Clone()
```
### DotSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHalftoneEffect.yml" sourcestartlinenumber="1">Gets or sets the maximum size of the halftone dots in points.</p>


```csharp
public double DotSize { get; set; }
```
### DotStrength

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHalftoneEffect.yml" sourcestartlinenumber="1">Gets or sets the strength of the halftone dots.</p>


```csharp
public double DotStrength { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHalftoneEffect.yml" sourcestartlinenumber="1">Reconstructs the CIMHalftoneEffect with a specified state from a JSON encoding.</p>


```csharp
public static CIMHalftoneEffect FromJson(string json, JsonDeserializationSettings settings = null)
```
### InvertTone

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHalftoneEffect.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to use white halftone dots.</p>


```csharp
public bool InvertTone { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHalftoneEffect.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHalftoneEffect.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMHalftoneEffect and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHalftoneEffect.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


