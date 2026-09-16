# CIMPixelatedEffect

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMPixelatedEffect.yml" sourcestartlinenumber="1">Represents a visual effect for reshading the scene with a pixelated style.</p>


## Object Signature

```csharp
public class CIMPixelatedEffect : CIMVisualEffect, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMPixelatedEffect()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMPixelatedEffect.yml" sourcestartlinenumber="1">Represents a visual effect for reshading the scene with a pixelated style.</p>


```csharp
public CIMPixelatedEffect()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPixelatedEffect.yml" sourcestartlinenumber="1">Creates a deep copy of CIMPixelatedEffect.</p>


```csharp
public CIMPixelatedEffect Clone()
```
### ColorFactor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPixelatedEffect.yml" sourcestartlinenumber="1">Gets or sets the factor that exponentially influences the number of colors used in the color palette.</p>


```csharp
public int ColorFactor { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPixelatedEffect.yml" sourcestartlinenumber="1">Reconstructs the CIMPixelatedEffect with a specified state from a JSON encoding.</p>


```csharp
public static CIMPixelatedEffect FromJson(string json, JsonDeserializationSettings settings = null)
```
### PixelSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPixelatedEffect.yml" sourcestartlinenumber="1">Gets or sets the size of the effect's simulated pixels in points.</p>


```csharp
public double PixelSize { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPixelatedEffect.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPixelatedEffect.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMPixelatedEffect and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPixelatedEffect.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


