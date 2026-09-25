# CIMRasterStretchColorizer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterStretchColorizer.yml" sourcestartlinenumber="1">Represents a raster stretch colorizer.</p>


## Object Signature

```csharp
public class CIMRasterStretchColorizer : CIMRasterColorizer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMRasterStretchColorizer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterStretchColorizer.yml" sourcestartlinenumber="1">Represents a raster stretch colorizer.</p>


```csharp
public CIMRasterStretchColorizer()
```
### BackgroundColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterStretchColorizer.yml" sourcestartlinenumber="1">Gets or sets the background color.</p>


```csharp
public CIMColor BackgroundColor { get; set; }
```
### BackgroundValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterStretchColorizer.yml" sourcestartlinenumber="1">Gets or sets the background value.</p>


```csharp
public double BackgroundValue { get; set; }
```
### BandIndex

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterStretchColorizer.yml" sourcestartlinenumber="1">Gets or sets the band index of the band being stretched.</p>


```csharp
public int BandIndex { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterStretchColorizer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMRasterStretchColorizer.</p>


```csharp
public CIMRasterStretchColorizer Clone()
```
### ColorRamp

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterStretchColorizer.yml" sourcestartlinenumber="1">Gets or sets the color ramp.</p>


```csharp
public CIMColorRamp ColorRamp { get; set; }
```
### ColorScheme

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterStretchColorizer.yml" sourcestartlinenumber="1">Gets or sets the color ramp scheme name.</p>


```csharp
public string ColorScheme { get; set; }
```
### CustomStretchMax

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterStretchColorizer.yml" sourcestartlinenumber="1">Gets or sets the color stretch custom max.</p>


```csharp
public double CustomStretchMax { get; set; }
```
### CustomStretchMin

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterStretchColorizer.yml" sourcestartlinenumber="1">Gets or sets the color stretch custom min.</p>


```csharp
public double CustomStretchMin { get; set; }
```
### DisplayBackgroundValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterStretchColorizer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to display the background.</p>


```csharp
public bool DisplayBackgroundValue { get; set; }
```
### ESRIStretchContrast

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterStretchColorizer.yml" sourcestartlinenumber="1">Gets or sets the Esri stretch contrast parameter.</p>


```csharp
public double ESRIStretchContrast { get; set; }
```
### ESRIStretchMean

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterStretchColorizer.yml" sourcestartlinenumber="1">Gets or sets the Esri stretch mean parameter.</p>


```csharp
public double ESRIStretchMean { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterStretchColorizer.yml" sourcestartlinenumber="1">Reconstructs the CIMRasterStretchColorizer with a specified state from a JSON encoding.</p>


```csharp
public static CIMRasterStretchColorizer FromJson(string json, JsonDeserializationSettings settings = null)
```
### GammaValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterStretchColorizer.yml" sourcestartlinenumber="1">Gets or sets the gamma value.</p>


```csharp
public double GammaValue { get; set; }
```
### Heading

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterStretchColorizer.yml" sourcestartlinenumber="1">Gets or sets the legend heading.</p>


```csharp
public string Heading { get; set; }
```
### HistogramEditInfo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterStretchColorizer.yml" sourcestartlinenumber="1">Gets or sets the edit info defining the raster histogram customization.</p>


```csharp
public CIMRasterHistogramEditInfo HistogramEditInfo { get; set; }
```
### Invert

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterStretchColorizer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to invert the stretch.</p>


```csharp
public bool Invert { get; set; }
```
### Lookup

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterStretchColorizer.yml" sourcestartlinenumber="1">Gets or sets a long array of lookup values.</p>


```csharp
public int[] Lookup { get; set; }
```
### MaxPercent

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterStretchColorizer.yml" sourcestartlinenumber="1">Gets or sets the maximum percent.</p>


```csharp
public double MaxPercent { get; set; }
```
### MinPercent

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterStretchColorizer.yml" sourcestartlinenumber="1">Gets or sets the minimum percent.</p>


```csharp
public double MinPercent { get; set; }
```
### NumberFormat

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterStretchColorizer.yml" sourcestartlinenumber="1">Gets or sets the number format applied to the display of values.</p>


```csharp
public CIMNumberFormat NumberFormat { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterStretchColorizer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Sharpening

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterStretchColorizer.yml" sourcestartlinenumber="1">Gets or sets the sharpening value.</p>


```csharp
public int Sharpening { get; set; }
```
### SpecificationHistogram

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterStretchColorizer.yml" sourcestartlinenumber="1">Gets or sets the statistics for histogram specification stretch.</p>


```csharp
public StatsHistogram SpecificationHistogram { get; set; }
```
### StandardDeviationParam

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterStretchColorizer.yml" sourcestartlinenumber="1">Gets or sets the standard deviation parameter value.</p>


```csharp
public double StandardDeviationParam { get; set; }
```
### StatsType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterStretchColorizer.yml" sourcestartlinenumber="1">Gets or sets the type of raster stretch statistics.</p>


```csharp
public RasterStretchStatsType StatsType { get; set; }
```
### StretchClasses

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterStretchColorizer.yml" sourcestartlinenumber="1">Gets or sets the raster stretch classes.</p>


```csharp
public CIMRasterStretchClass[] StretchClasses { get; set; }
```
### StretchStats

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterStretchColorizer.yml" sourcestartlinenumber="1">Gets or sets the raster stretch statistics.</p>


```csharp
public StatsHistogram StretchStats { get; set; }
```
### StretchType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterStretchColorizer.yml" sourcestartlinenumber="1">Gets or sets the raster stretch type.</p>


```csharp
public RasterStretchType StretchType { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterStretchColorizer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMRasterStretchColorizer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseAdvancedLabeling

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterStretchColorizer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to use advanced labeling.</p>


```csharp
public bool UseAdvancedLabeling { get; set; }
```
### UseCustomStretchMinMax

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterStretchColorizer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to use custom stretch minimum and maximum.</p>


```csharp
public bool UseCustomStretchMinMax { get; set; }
```
### UseGammaStretch

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterStretchColorizer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to use gamma stretch.</p>


```csharp
public bool UseGammaStretch { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterStretchColorizer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


