# CIMLASPointElevationRenderer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASPointElevationRenderer.yml" sourcestartlinenumber="1">Represents a LAS point elevation renderer.</p>


## Object Signature

```csharp
public class CIMLASPointElevationRenderer : CIMTinColorRampRenderer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMLASPointElevationRenderer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASPointElevationRenderer.yml" sourcestartlinenumber="1">Represents a LAS point elevation renderer.</p>


```csharp
public CIMLASPointElevationRenderer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASPointElevationRenderer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMLASPointElevationRenderer.</p>


```csharp
public CIMLASPointElevationRenderer Clone()
```
### ColorModulation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASPointElevationRenderer.yml" sourcestartlinenumber="1">Gets or sets color modulation.</p>


```csharp
public CIMColorModulationInfo ColorModulation { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASPointElevationRenderer.yml" sourcestartlinenumber="1">Reconstructs the CIMLASPointElevationRenderer with a specified state from a JSON encoding.</p>


```csharp
public static CIMLASPointElevationRenderer FromJson(string json, JsonDeserializationSettings settings = null)
```
### ModulateIntensity

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASPointElevationRenderer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to modulate intensity.</p>


```csharp
public bool ModulateIntensity { get; set; }
```
### PointSplatter

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASPointElevationRenderer.yml" sourcestartlinenumber="1">Gets or sets the point splatter properties.</p>


```csharp
public CIMLASPointSplatter PointSplatter { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASPointElevationRenderer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASPointElevationRenderer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMLASPointElevationRenderer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseSplat

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASPointElevationRenderer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to use the splat technique.</p>


```csharp
public bool UseSplat { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASPointElevationRenderer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


