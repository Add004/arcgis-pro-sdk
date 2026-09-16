# CIMRasterRGBColorizer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Represents a raster RGB colorizer.</p>


## Object Signature

```csharp
public class CIMRasterRGBColorizer : CIMRasterColorizer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMRasterRGBColorizer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Represents a raster RGB colorizer.</p>


```csharp
public CIMRasterRGBColorizer()
```
### AlphaBandIndex

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets the band to be represented in alpha.</p>


```csharp
public int AlphaBandIndex { get; set; }
```
### BackgroundColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets the background display color.</p>


```csharp
public CIMColor BackgroundColor { get; set; }
```
### BackgroundValueBlue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets the background blue value.</p>


```csharp
public double BackgroundValueBlue { get; set; }
```
### BackgroundValueGreen

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets the background green value.</p>


```csharp
public double BackgroundValueGreen { get; set; }
```
### BackgroundValueRed

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets the background red value.</p>


```csharp
public double BackgroundValueRed { get; set; }
```
### BlueBandIndex

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets the band to be represented in blue.</p>


```csharp
public int BlueBandIndex { get; set; }
```
### BlueLookup

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets the blue lookup values.</p>


```csharp
public int[] BlueLookup { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMRasterRGBColorizer.</p>


```csharp
public CIMRasterRGBColorizer Clone()
```
### CustomStretchMaxBlue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets the color stretch custom maximum value for blue.</p>


```csharp
public double CustomStretchMaxBlue { get; set; }
```
### CustomStretchMaxGreen

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets the color stretch custom maximum value for green.</p>


```csharp
public double CustomStretchMaxGreen { get; set; }
```
### CustomStretchMaxRed

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets the color stretch custom maximum value for red.</p>


```csharp
public double CustomStretchMaxRed { get; set; }
```
### CustomStretchMinBlue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets the color stretch custom minimum value for blue.</p>


```csharp
public double CustomStretchMinBlue { get; set; }
```
### CustomStretchMinGreen

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets the color stretch custom minimum value for green.</p>


```csharp
public double CustomStretchMinGreen { get; set; }
```
### CustomStretchMinRed

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets the color stretch custom minimum value for red.</p>


```csharp
public double CustomStretchMinRed { get; set; }
```
### DisplayBackgroundValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to display the background value.</p>


```csharp
public bool DisplayBackgroundValue { get; set; }
```
### ESRIStretchContrastB

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets the Esri stretch contrast value for blue.</p>


```csharp
public double ESRIStretchContrastB { get; set; }
```
### ESRIStretchContrastG

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets the Esri stretch contrast value for green.</p>


```csharp
public double ESRIStretchContrastG { get; set; }
```
### ESRIStretchContrastR

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets the Esri stretch contrast value for red.</p>


```csharp
public double ESRIStretchContrastR { get; set; }
```
### ESRIStretchMeanB

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets the Esri stretch mean value for blue.</p>


```csharp
public double ESRIStretchMeanB { get; set; }
```
### ESRIStretchMeanG

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets the Esri stretch mean value for green.</p>


```csharp
public double ESRIStretchMeanG { get; set; }
```
### ESRIStretchMeanR

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets the Esri stretch mean value for red.</p>


```csharp
public double ESRIStretchMeanR { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Reconstructs the CIMRasterRGBColorizer with a specified state from a JSON encoding.</p>


```csharp
public static CIMRasterRGBColorizer FromJson(string json, JsonDeserializationSettings settings = null)
```
### GammaB

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets the gamma value for blue.</p>


```csharp
public double GammaB { get; set; }
```
### GammaG

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets the gamma value for green.</p>


```csharp
public double GammaG { get; set; }
```
### GammaR

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets the gamma value for red.</p>


```csharp
public double GammaR { get; set; }
```
### GreenBandIndex

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets the band to be represented in green.</p>


```csharp
public int GreenBandIndex { get; set; }
```
### GreenLookup

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets the green lookup values.</p>


```csharp
public int[] GreenLookup { get; set; }
```
### Heading

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets the legend heading.</p>


```csharp
public string Heading { get; set; }
```
### HistogramEditInfoBlue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets the edit info defining the histogram customization for blue.</p>


```csharp
public CIMRasterHistogramEditInfo HistogramEditInfoBlue { get; set; }
```
### HistogramEditInfoGreen

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets the edit info defining the histogram customization for green.</p>


```csharp
public CIMRasterHistogramEditInfo HistogramEditInfoGreen { get; set; }
```
### HistogramEditInfoRed

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets the edit info defining the histogram customization for red.</p>


```csharp
public CIMRasterHistogramEditInfo HistogramEditInfoRed { get; set; }
```
### Invert

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not the stretch is inverted.</p>


```csharp
public bool Invert { get; set; }
```
### LumLookup

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets the lum lookup values.</p>


```csharp
public int[] LumLookup { get; set; }
```
### MaxPercent

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets the maximum percent.</p>


```csharp
public double MaxPercent { get; set; }
```
### MinPercent

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets the minimum percent.</p>


```csharp
public double MinPercent { get; set; }
```
### PansharpeningFilter

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets the pansharpening filter.</p>


```csharp
public CIMPansharpeningFilter PansharpeningFilter { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RedBandIndex

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets the band to be represented in red.</p>


```csharp
public int RedBandIndex { get; set; }
```
### RedLookup

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets the red lookup values.</p>


```csharp
public int[] RedLookup { get; set; }
```
### Saturation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets the saturation value.</p>


```csharp
public int Saturation { get; set; }
```
### Sharpening

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets the sharpening value.</p>


```csharp
public int Sharpening { get; set; }
```
### SpecificationHistogramBlue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets the specification histogram for blue.</p>


```csharp
public StatsHistogram SpecificationHistogramBlue { get; set; }
```
### SpecificationHistogramGreen

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets the specification histogram for green.</p>


```csharp
public StatsHistogram SpecificationHistogramGreen { get; set; }
```
### SpecificationHistogramRed

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets the specification histogram for red.</p>


```csharp
public StatsHistogram SpecificationHistogramRed { get; set; }
```
### StandardDeviationsParam

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets the standard deviations parameter.</p>


```csharp
public double StandardDeviationsParam { get; set; }
```
### StretchStatsBlue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets the stretch statistics for blue.</p>


```csharp
public StatsHistogram StretchStatsBlue { get; set; }
```
### StretchStatsGreen

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets the stretch statistics for green.</p>


```csharp
public StatsHistogram StretchStatsGreen { get; set; }
```
### StretchStatsRed

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets the stretch statistics for red.</p>


```csharp
public StatsHistogram StretchStatsRed { get; set; }
```
### StretchStatsType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets the stretch statistics type.</p>


```csharp
public RasterStretchStatsType StretchStatsType { get; set; }
```
### StretchType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets the stretch type.</p>


```csharp
public RasterStretchType StretchType { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMRasterRGBColorizer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseAlphaBand

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to use the alpha band.</p>


```csharp
public bool UseAlphaBand { get; set; }
```
### UseBlueBand

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to use the blue band.</p>


```csharp
public bool UseBlueBand { get; set; }
```
### UseCustomStretchMinMax

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to use custom stretch minimum and maximum.</p>


```csharp
public bool UseCustomStretchMinMax { get; set; }
```
### UseDefaultMapping

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to use default mapping.</p>


```csharp
public bool UseDefaultMapping { get; set; }
```
### UseGammaStretch

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to use gamma stretch.</p>


```csharp
public bool UseGammaStretch { get; set; }
```
### UseGreenBand

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to use the green band.</p>


```csharp
public bool UseGreenBand { get; set; }
```
### UseRedBand

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to use the red band.</p>


```csharp
public bool UseRedBand { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterRGBColorizer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


