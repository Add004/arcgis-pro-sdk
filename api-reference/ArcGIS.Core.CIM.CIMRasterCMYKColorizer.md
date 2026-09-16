# CIMRasterCMYKColorizer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterCMYKColorizer.yml" sourcestartlinenumber="1">Represents a raster CMYK colorizer.</p>


## Object Signature

```csharp
public class CIMRasterCMYKColorizer : CIMRasterColorizer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMRasterCMYKColorizer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterCMYKColorizer.yml" sourcestartlinenumber="1">Represents a raster CMYK colorizer.</p>


```csharp
public CIMRasterCMYKColorizer()
```
### BackgroundColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterCMYKColorizer.yml" sourcestartlinenumber="1">Gets or sets the background color.</p>


```csharp
public CIMColor BackgroundColor { get; set; }
```
### BackgroundValueBlack

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterCMYKColorizer.yml" sourcestartlinenumber="1">Gets or sets the background value for black.</p>


```csharp
public double BackgroundValueBlack { get; set; }
```
### BackgroundValueCyan

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterCMYKColorizer.yml" sourcestartlinenumber="1">Gets or sets the background value for cyan.</p>


```csharp
public double BackgroundValueCyan { get; set; }
```
### BackgroundValueMagenta

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterCMYKColorizer.yml" sourcestartlinenumber="1">Gets or sets the background value for magenta.</p>


```csharp
public double BackgroundValueMagenta { get; set; }
```
### BackgroundValueYellow

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterCMYKColorizer.yml" sourcestartlinenumber="1">Gets or sets the background value for yellow.</p>


```csharp
public double BackgroundValueYellow { get; set; }
```
### BlackBandIndex

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterCMYKColorizer.yml" sourcestartlinenumber="1">Gets or sets the band index for black.</p>


```csharp
public int BlackBandIndex { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterCMYKColorizer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMRasterCMYKColorizer.</p>


```csharp
public CIMRasterCMYKColorizer Clone()
```
### CyanBandIndex

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterCMYKColorizer.yml" sourcestartlinenumber="1">Gets or sets the band index for cyan.</p>


```csharp
public int CyanBandIndex { get; set; }
```
### DisplayBackgroundValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterCMYKColorizer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to display the background value.</p>


```csharp
public bool DisplayBackgroundValue { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterCMYKColorizer.yml" sourcestartlinenumber="1">Reconstructs the CIMRasterCMYKColorizer with a specified state from a JSON encoding.</p>


```csharp
public static CIMRasterCMYKColorizer FromJson(string json, JsonDeserializationSettings settings = null)
```
### Invert

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterCMYKColorizer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not the stretch is inverted.</p>


```csharp
public bool Invert { get; set; }
```
### MagentaBandIndex

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterCMYKColorizer.yml" sourcestartlinenumber="1">Gets or sets the band index for magenta.</p>


```csharp
public int MagentaBandIndex { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterCMYKColorizer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SpecificationHistogramBlack

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterCMYKColorizer.yml" sourcestartlinenumber="1">Gets or sets the specification histogram for black.</p>


```csharp
public StatsHistogram SpecificationHistogramBlack { get; set; }
```
### SpecificationHistogramCyan

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterCMYKColorizer.yml" sourcestartlinenumber="1">Gets or sets the specification histogram for cyan.</p>


```csharp
public StatsHistogram SpecificationHistogramCyan { get; set; }
```
### SpecificationHistogramMagenta

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterCMYKColorizer.yml" sourcestartlinenumber="1">Gets or sets the specification histogram for magenta.</p>


```csharp
public StatsHistogram SpecificationHistogramMagenta { get; set; }
```
### SpecificationHistogramYellow

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterCMYKColorizer.yml" sourcestartlinenumber="1">Gets or sets the specification histogram for yellow.</p>


```csharp
public StatsHistogram SpecificationHistogramYellow { get; set; }
```
### StandardDeviationParam

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterCMYKColorizer.yml" sourcestartlinenumber="1">Gets or sets the standard deviation parameter for the stretch renderer.</p>


```csharp
public double StandardDeviationParam { get; set; }
```
### StretchStatsBlack

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterCMYKColorizer.yml" sourcestartlinenumber="1">Gets or sets the stretch histogram for black.</p>


```csharp
public StatsHistogram StretchStatsBlack { get; set; }
```
### StretchStatsCyan

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterCMYKColorizer.yml" sourcestartlinenumber="1">Gets or sets the stretch histogram for cyan.</p>


```csharp
public StatsHistogram StretchStatsCyan { get; set; }
```
### StretchStatsMagenta

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterCMYKColorizer.yml" sourcestartlinenumber="1">Gets or sets the stretch histogram for magenta.</p>


```csharp
public StatsHistogram StretchStatsMagenta { get; set; }
```
### StretchStatsType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterCMYKColorizer.yml" sourcestartlinenumber="1">Gets or sets the stretch statistics type.</p>


```csharp
public RasterStretchStatsType StretchStatsType { get; set; }
```
### StretchStatsYellow

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterCMYKColorizer.yml" sourcestartlinenumber="1">Gets or sets the stretch histogram for yellow.</p>


```csharp
public StatsHistogram StretchStatsYellow { get; set; }
```
### StretchType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterCMYKColorizer.yml" sourcestartlinenumber="1">Gets or sets the stretch type.</p>


```csharp
public RasterStretchType StretchType { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterCMYKColorizer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMRasterCMYKColorizer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseBlackMapping

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterCMYKColorizer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to use black mapping.</p>


```csharp
public bool UseBlackMapping { get; set; }
```
### UseCyanMapping

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterCMYKColorizer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to use cyan mapping.</p>


```csharp
public bool UseCyanMapping { get; set; }
```
### UseDefaultMapping

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterCMYKColorizer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to use default mapping.</p>


```csharp
public bool UseDefaultMapping { get; set; }
```
### UseMagentaMapping

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterCMYKColorizer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to use magenta mapping.</p>


```csharp
public bool UseMagentaMapping { get; set; }
```
### UseYellowMapping

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterCMYKColorizer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to use yellow mapping.</p>


```csharp
public bool UseYellowMapping { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterCMYKColorizer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```
### YellowBandIndex

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterCMYKColorizer.yml" sourcestartlinenumber="1">Gets or sets the band index for yellow.</p>


```csharp
public int YellowBandIndex { get; set; }
```


