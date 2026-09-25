# CIMIlluminationProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMIlluminationProperties.yml" sourcestartlinenumber="1">Represents illumination properties.</p>


## Object Signature

```csharp
public class CIMIlluminationProperties : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMIlluminationProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMIlluminationProperties.yml" sourcestartlinenumber="1">Represents illumination properties.</p>


```csharp
public CIMIlluminationProperties()
```
### AmbientLight

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIlluminationProperties.yml" sourcestartlinenumber="1">Gets or sets the ambient light value.</p>


```csharp
public double AmbientLight { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMIlluminationProperties.yml" sourcestartlinenumber="1">Creates a deep copy of CIMIlluminationProperties.</p>


```csharp
public CIMIlluminationProperties Clone()
```
### DateTime

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIlluminationProperties.yml" sourcestartlinenumber="1">Gets or sets the time instant.</p>


```csharp
public TimeInstant DateTime { get; set; }
```
### EnableAmbientOcclusion

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIlluminationProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to enable ambient occlusion for a scene or map.</p>


```csharp
public bool EnableAmbientOcclusion { get; set; }
```
### EnableEyeDomeLighting

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIlluminationProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to enable eye-dome lighting for a scene or map.</p>


```csharp
public bool EnableEyeDomeLighting { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMIlluminationProperties.yml" sourcestartlinenumber="1">Reconstructs the CIMIlluminationProperties with a specified state from a JSON encoding.</p>


```csharp
public static CIMIlluminationProperties FromJson(string json, JsonDeserializationSettings settings = null)
```
### IlluminationSource

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIlluminationProperties.yml" sourcestartlinenumber="1">Gets or sets the illumination source.</p>


```csharp
public IlluminationSource IlluminationSource { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMIlluminationProperties.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShowAtmosphericEffects

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIlluminationProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to show atmospheric effects.</p>


```csharp
public bool ShowAtmosphericEffects { get; set; }
```
### ShowShadows3D

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIlluminationProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to show shadows in 3D.</p>


```csharp
public bool ShowShadows3D { get; set; }
```
### ShowStars

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIlluminationProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to show the stars and the atmospheric halo for a global scene.</p>


```csharp
public bool ShowStars { get; set; }
```
### SunAltitude

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIlluminationProperties.yml" sourcestartlinenumber="1">Gets or sets the sun altitude.</p>


```csharp
public double SunAltitude { get; set; }
```
### SunAzimuth

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIlluminationProperties.yml" sourcestartlinenumber="1">Gets or sets the sun azimuth.</p>


```csharp
public double SunAzimuth { get; set; }
```
### SunPositionX

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIlluminationProperties.yml" sourcestartlinenumber="1">Gets or sets the sun position X.</p>


```csharp
public double SunPositionX { get; set; }
```
### SunPositionY

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIlluminationProperties.yml" sourcestartlinenumber="1">Gets or sets the sun position Y.</p>


```csharp
public double SunPositionY { get; set; }
```
### SunPositionZ

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIlluminationProperties.yml" sourcestartlinenumber="1">Gets or sets the sun position Z.</p>


```csharp
public double SunPositionZ { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMIlluminationProperties.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMIlluminationProperties and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMIlluminationProperties.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


