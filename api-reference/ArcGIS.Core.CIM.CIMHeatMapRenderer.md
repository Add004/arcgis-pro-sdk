# CIMHeatMapRenderer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMHeatMapRenderer.yml" sourcestartlinenumber="1">Represents a heat map renderer.
The heat map renderer draws point features as a continuous color gradient representing the density of the points.
The resulting density surface represents the physical proximity between points, optionally weighted by a specified
attribute value. The displayed raster surface is dynamic and updates if the source point features are edited.</p>


## Object Signature

```csharp
public class CIMHeatMapRenderer : CIMRenderer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMHeatMapRenderer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMHeatMapRenderer.yml" sourcestartlinenumber="1">Represents a heat map renderer.
The heat map renderer draws point features as a continuous color gradient representing the density of the points.
The resulting density surface represents the physical proximity between points, optionally weighted by a specified
attribute value. The displayed raster surface is dynamic and updates if the source point features are edited.</p>


```csharp
public CIMHeatMapRenderer()
```
### AutoAdjustPixelIntensity

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHeatMapRenderer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to update renderers pixel intensity range automatically. When set to True renderer's pixel intensity range will change based on the features with in the visible extent.</p>


```csharp
public bool AutoAdjustPixelIntensity { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHeatMapRenderer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMHeatMapRenderer.</p>


```csharp
public CIMHeatMapRenderer Clone()
```
### ColorScheme

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHeatMapRenderer.yml" sourcestartlinenumber="1">Gets or sets the color scheme of the heat map.
Controls how smooth the color gradient appears.
Must be either a continuous or multipart color ramp.
If no color scheme is specified, a default color ramp will be used.</p>


```csharp
public CIMColorRamp ColorScheme { get; set; }
```
### Field

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHeatMapRenderer.yml" sourcestartlinenumber="1">Gets or sets the name of the field denoting weighting values for each feature.
The field's value is the count or quantity to be spread across the landscape to create a continuous surface.
Values in the field may be integer or floating point.
The options for the field are listed below.
Specify the name of a numeric field in the feature table
Use &quot;&quot; if no item or special value will be used and each feature will be counted once.
Use Shape if input features contains Z.</p>


```csharp
public string Field { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHeatMapRenderer.yml" sourcestartlinenumber="1">Reconstructs the CIMHeatMapRenderer with a specified state from a JSON encoding.</p>


```csharp
public static CIMHeatMapRenderer FromJson(string json, JsonDeserializationSettings settings = null)
```
### Heading

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHeatMapRenderer.yml" sourcestartlinenumber="1">Gets or sets the legend heading.</p>


```csharp
public string Heading { get; set; }
```
### MaxLabel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHeatMapRenderer.yml" sourcestartlinenumber="1">Gets or sets the legend label for the maximum density value.</p>


```csharp
public string MaxLabel { get; set; }
```
### MaxPixelIntensity

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHeatMapRenderer.yml" sourcestartlinenumber="1">Gets or sets the maximum pixel intensity.</p>


```csharp
public double MaxPixelIntensity { get; set; }
```
### MaxPixelIntensityReferenceScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHeatMapRenderer.yml" sourcestartlinenumber="1">Gets or sets base scale at which the maximum pixel intensity should be used.
This value is used only when the auto adjust pixel intensity is set to false.</p>


```csharp
public double MaxPixelIntensityReferenceScale { get; set; }
```
### MinLabel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHeatMapRenderer.yml" sourcestartlinenumber="1">Gets or sets the legend label for the minimum density value.</p>


```csharp
public string MinLabel { get; set; }
```
### PixelIntensityStops

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHeatMapRenderer.yml" sourcestartlinenumber="1">Gets or sets the pixel intensity stops.</p>


```csharp
public double[] PixelIntensityStops { get; set; }
```
### Radius

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHeatMapRenderer.yml" sourcestartlinenumber="1">Gets or sets the radius which defines how far the heat spreads away from the points.
Specified and stored in Points and translates to Pixels at draw time.</p>


```csharp
[Obsolete("Radius is deprecated at 3.8. Use SearchRadius instead.")]
public int Radius { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHeatMapRenderer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ReferenceScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHeatMapRenderer.yml" sourcestartlinenumber="1">Gets or sets the scale at which the search radius (in screen units - points) is converted to map units.</p>


```csharp
public double ReferenceScale { get; set; }
```
### RendererQuality

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHeatMapRenderer.yml" sourcestartlinenumber="1">Gets or sets the renderer quality which controls the pixelation of the raster.
This is an arbitrary range that goes from Best (10) to Fastest (0).</p>


```csharp
public int RendererQuality { get; set; }
```
### SearchRadius

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHeatMapRenderer.yml" sourcestartlinenumber="1">Gets or sets the radius which defines how far the heat spreads away from the points.
Specified and stored in Points and translates to Pixels at draw time.</p>


```csharp
public double SearchRadius { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHeatMapRenderer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMHeatMapRenderer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHeatMapRenderer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


