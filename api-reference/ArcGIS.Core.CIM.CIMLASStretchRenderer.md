# CIMLASStretchRenderer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchRenderer.yml" sourcestartlinenumber="1">Represents a LAS stretch renderer.</p>


## Object Signature

```csharp
public class CIMLASStretchRenderer : CIMTerrainAttributeRenderer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMLASStretchRenderer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchRenderer.yml" sourcestartlinenumber="1">Represents a LAS stretch renderer.</p>


```csharp
public CIMLASStretchRenderer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchRenderer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMLASStretchRenderer.</p>


```csharp
public CIMLASStretchRenderer Clone()
```
### ColorModulation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchRenderer.yml" sourcestartlinenumber="1">Gets or sets color modulation.</p>


```csharp
public CIMColorModulationInfo ColorModulation { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchRenderer.yml" sourcestartlinenumber="1">Reconstructs the CIMLASStretchRenderer with a specified state from a JSON encoding.</p>


```csharp
public static CIMLASStretchRenderer FromJson(string json, JsonDeserializationSettings settings = null)
```
### Heading

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchRenderer.yml" sourcestartlinenumber="1">Gets or sets the heading.</p>


```csharp
public string Heading { get; set; }
```
### ModulationInput

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchRenderer.yml" sourcestartlinenumber="1">Gets or sets the modulation input.</p>


```csharp
public CIMLASStretchInput ModulationInput { get; set; }
```
### ModulationWeight

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchRenderer.yml" sourcestartlinenumber="1">Gets or sets the modulation weight.</p>


```csharp
public double ModulationWeight { get; set; }
```
### PointSplatter

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchRenderer.yml" sourcestartlinenumber="1">Gets or sets the point splatter.</p>


```csharp
public CIMLASPointSplatter PointSplatter { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchRenderer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### StretchDrawingType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchRenderer.yml" sourcestartlinenumber="1">Gets or sets the stretch drawing type.</p>


```csharp
public LASStretchDrawingType StretchDrawingType { get; set; }
```
### StretchSourceInput

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchRenderer.yml" sourcestartlinenumber="1">Gets or sets the stretch source input.</p>


```csharp
public CIMLASStretchInput StretchSourceInput { get; set; }
```
### TintSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchRenderer.yml" sourcestartlinenumber="1">Gets or sets the tint symbol.</p>


```csharp
public CIMSymbolReference TintSymbol { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchRenderer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMLASStretchRenderer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseModulation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchRenderer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to use modulation.</p>


```csharp
public bool UseModulation { get; set; }
```
### UseSplat

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchRenderer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to use the splat technique.</p>


```csharp
public bool UseSplat { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchRenderer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


