# CIMLASUniqueValueRenderer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASUniqueValueRenderer.yml" sourcestartlinenumber="1">Represents a LAS unique value renderer.</p>


## Object Signature

```csharp
public class CIMLASUniqueValueRenderer : CIMTinUniqueValueRenderer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMLASUniqueValueRenderer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASUniqueValueRenderer.yml" sourcestartlinenumber="1">Represents a LAS unique value renderer.</p>


```csharp
public CIMLASUniqueValueRenderer()
```
### Attribute

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASUniqueValueRenderer.yml" sourcestartlinenumber="1">Gets or sets the attribute index.</p>


```csharp
public int Attribute { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASUniqueValueRenderer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMLASUniqueValueRenderer.</p>


```csharp
public CIMLASUniqueValueRenderer Clone()
```
### ColorModulation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASUniqueValueRenderer.yml" sourcestartlinenumber="1">Gets or sets color modulation.</p>


```csharp
public CIMColorModulationInfo ColorModulation { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASUniqueValueRenderer.yml" sourcestartlinenumber="1">Reconstructs the CIMLASUniqueValueRenderer with a specified state from a JSON encoding.</p>


```csharp
public static CIMLASUniqueValueRenderer FromJson(string json, JsonDeserializationSettings settings = null)
```
### ModulateIntensity

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASUniqueValueRenderer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to modulate intensity.</p>


```csharp
public bool ModulateIntensity { get; set; }
```
### PointSplatter

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASUniqueValueRenderer.yml" sourcestartlinenumber="1">Gets or sets point splatter properties.</p>


```csharp
public CIMLASPointSplatter PointSplatter { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASUniqueValueRenderer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASUniqueValueRenderer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMLASUniqueValueRenderer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseSplat

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASUniqueValueRenderer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to use the splat technique.</p>


```csharp
public bool UseSplat { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASUniqueValueRenderer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


