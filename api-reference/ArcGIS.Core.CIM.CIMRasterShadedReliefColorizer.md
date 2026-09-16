# CIMRasterShadedReliefColorizer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterShadedReliefColorizer.yml" sourcestartlinenumber="1">Represents a raster shaded relief colorizer.</p>


## Object Signature

```csharp
public class CIMRasterShadedReliefColorizer : CIMRasterColorizer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMRasterShadedReliefColorizer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterShadedReliefColorizer.yml" sourcestartlinenumber="1">Represents a raster shaded relief colorizer.</p>


```csharp
public CIMRasterShadedReliefColorizer()
```
### Altitude

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterShadedReliefColorizer.yml" sourcestartlinenumber="1">Gets or sets the Altitude. The value will be ignored if UseMapIlluminationProperties is set to true.</p>


```csharp
public double Altitude { get; set; }
```
### Azimuth

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterShadedReliefColorizer.yml" sourcestartlinenumber="1">Gets or sets the azimuth. The value will be ignored if UseMapIlluminationProperties is set to true.</p>


```csharp
public double Azimuth { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterShadedReliefColorizer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMRasterShadedReliefColorizer.</p>


```csharp
public CIMRasterShadedReliefColorizer Clone()
```
### ColorRamp

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterShadedReliefColorizer.yml" sourcestartlinenumber="1">Gets or sets the color ramp.</p>


```csharp
public CIMColorRamp ColorRamp { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterShadedReliefColorizer.yml" sourcestartlinenumber="1">Reconstructs the CIMRasterShadedReliefColorizer with a specified state from a JSON encoding.</p>


```csharp
public static CIMRasterShadedReliefColorizer FromJson(string json, JsonDeserializationSettings settings = null)
```
### HillShadeType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterShadedReliefColorizer.yml" sourcestartlinenumber="1">Gets or sets the hillshade type.</p>


```csharp
public ColorizerHillshadeType HillShadeType { get; set; }
```
### PixelSizeFactor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterShadedReliefColorizer.yml" sourcestartlinenumber="1">Gets or sets the pixel size factor.</p>


```csharp
public double PixelSizeFactor { get; set; }
```
### PixelSizePower

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterShadedReliefColorizer.yml" sourcestartlinenumber="1">Gets or sets the pixel size power.</p>


```csharp
public double PixelSizePower { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterShadedReliefColorizer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RemoveEdgeEffect

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterShadedReliefColorizer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to remove edge effect.</p>


```csharp
public bool RemoveEdgeEffect { get; set; }
```
### ScalingType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterShadedReliefColorizer.yml" sourcestartlinenumber="1">Gets or sets the scaling type.</p>


```csharp
public ColorizerScalingType ScalingType { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterShadedReliefColorizer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMRasterShadedReliefColorizer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseMapIlluminationProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterShadedReliefColorizer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to use map level illumination properties of altitude and azimuth.</p>


```csharp
public bool UseMapIlluminationProperties { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterShadedReliefColorizer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```
### ZFactor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterShadedReliefColorizer.yml" sourcestartlinenumber="1">Gets or sets a scaling factor used to convert the elevation values.</p>


```csharp
public double ZFactor { get; set; }
```


