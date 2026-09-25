# CIMOutlineEffect

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMOutlineEffect.yml" sourcestartlinenumber="1">Represents a visual effect for reshading the scene with outlines.</p>


## Object Signature

```csharp
public class CIMOutlineEffect : CIMVisualEffect, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMOutlineEffect()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMOutlineEffect.yml" sourcestartlinenumber="1">Represents a visual effect for reshading the scene with outlines.</p>


```csharp
public CIMOutlineEffect()
```
### BackgroundColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMOutlineEffect.yml" sourcestartlinenumber="1">Gets or sets the effect's background color.</p>


```csharp
public CIMColor BackgroundColor { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMOutlineEffect.yml" sourcestartlinenumber="1">Creates a deep copy of CIMOutlineEffect.</p>


```csharp
public CIMOutlineEffect Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMOutlineEffect.yml" sourcestartlinenumber="1">Reconstructs the CIMOutlineEffect with a specified state from a JSON encoding.</p>


```csharp
public static CIMOutlineEffect FromJson(string json, JsonDeserializationSettings settings = null)
```
### OutlineColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMOutlineEffect.yml" sourcestartlinenumber="1">Gets or sets the effect's outline color.</p>


```csharp
public CIMColor OutlineColor { get; set; }
```
### OutlineStrength

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMOutlineEffect.yml" sourcestartlinenumber="1">Gets or sets the outline strength which influences the outline weight and the threshold used for edge detection.</p>


```csharp
public double OutlineStrength { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMOutlineEffect.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMOutlineEffect.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMOutlineEffect and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMOutlineEffect.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


