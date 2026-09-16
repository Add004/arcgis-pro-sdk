# CIMHexMosaicEffect

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMHexMosaicEffect.yml" sourcestartlinenumber="1">Represents a visual effect for reshading the scene with a hexagonal mosaic texture.</p>


## Object Signature

```csharp
public class CIMHexMosaicEffect : CIMVisualEffect, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMHexMosaicEffect()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMHexMosaicEffect.yml" sourcestartlinenumber="1">Represents a visual effect for reshading the scene with a hexagonal mosaic texture.</p>


```csharp
public CIMHexMosaicEffect()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHexMosaicEffect.yml" sourcestartlinenumber="1">Creates a deep copy of CIMHexMosaicEffect.</p>


```csharp
public CIMHexMosaicEffect Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHexMosaicEffect.yml" sourcestartlinenumber="1">Reconstructs the CIMHexMosaicEffect with a specified state from a JSON encoding.</p>


```csharp
public static CIMHexMosaicEffect FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHexMosaicEffect.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Size

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHexMosaicEffect.yml" sourcestartlinenumber="1">Gets or sets the size of the hexagons measured in points.</p>


```csharp
public double Size { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHexMosaicEffect.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMHexMosaicEffect and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHexMosaicEffect.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


