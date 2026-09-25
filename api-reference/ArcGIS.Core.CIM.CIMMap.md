# CIMMap

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Represents a map or scene.</p>


## Object Signature

```csharp
public class CIMMap : CIMDefinition, INotifyPropertyChanged, IXmlSerializable
```

## Remarks

<p>
    A map is a container of geographic information. There are different kinds of geographic information within a map: imagery, terrain, and different kinds of vector data. The information in a map is organized into layers. A map contains an ordered list of layers, and draws each layer on top of its preceding layers. In 3D layers may be drawn in Z order and not layer order.
    </p>
<p>
    A map has a single spatial reference system. Each of its layers can be stored natively in different spatial reference systems. If a layer has a different spatial reference system than a map it is displayed in, the map reprojects the data to its spatial reference system before drawing it.
    </p>
<p>
    A map can dynamically place labels for its features. It finds optimal label locations for each map extent to maximize typographic clarity and to avoid overlaps.
    </p>


## Members

### CIMMap()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Represents a map or scene.</p>


```csharp
public CIMMap()
```
### AnimationActiveTrackName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the name of the currently active animation track.</p>


```csharp
public string AnimationActiveTrackName { get; set; }
```
### AnimationViewTracks

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the collection of view tracks in the animation.</p>


```csharp
public CIMViewTrack[] AnimationViewTracks { get; set; }
```
### Attribution

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the attribution text that will appear on the map when it is drawn.</p>


```csharp
public string Attribution { get; set; }
```
### AutoFillFeatureCache

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether auto fill mode is enabled or disabled for a map.</p>


```csharp
public bool AutoFillFeatureCache { get; set; }
```
### BackgroundColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the background color.</p>


```csharp
public CIMColor BackgroundColor { get; set; }
```
### Bookmarks

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the bookmarks.</p>


```csharp
public CIMBookmark[] Bookmarks { get; set; }
```
### CMYKColorProfile

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the name of the CMYK color profile for a map.</p>


```csharp
public string CMYKColorProfile { get; set; }
```
### ClipToFullExtent

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to clip to full extent.</p>


```csharp
public bool ClipToFullExtent { get; set; }
```
### ClippingAreaBorderSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the border symbol used for displaying the clipping area.</p>


```csharp
public CIMSymbolReference ClippingAreaBorderSymbol { get; set; }
```
### ClippingMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the clipping mode for a map.</p>


```csharp
public ClippingMode ClippingMode { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMap.</p>


```csharp
public CIMMap Clone()
```
### ColorModel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the color model for a map.</p>


```csharp
public ColorModel ColorModel { get; set; }
```
### CustomClippingShapeURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the URI of the custom clipping shape used when the clipping mode is set to CustomShape.</p>


```csharp
public string CustomClippingShapeURI { get; set; }
```
### CustomElevationSurfaceLayers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the URIs of the custom elevation surface layers in the map.</p>


```csharp
public string[] CustomElevationSurfaceLayers { get; set; }
```
### CustomFullExtent

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the custom full extent as a polygon.</p>


```csharp
public Polygon CustomFullExtent { get; set; }
```
### CustomProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the custom properties of the map. Custom properties are limited to key / value pairs of strings and developers are fully responsible for stored content.</p>


```csharp
public CIMStringMap[] CustomProperties { get; set; }
```
### DatumTransforms

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the set of geographic transformations used by the map for spatial references that do not have vertical coordinate system.</p>


```csharp
public CIMDatumTransform[] DatumTransforms { get; set; }
```
### DefaultCamera

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the default camera.</p>


```csharp
public CIMViewCamera DefaultCamera { get; set; }
```
### DefaultCameraEffect

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the camera effect that new views of this scene are opened with.</p>


```csharp
public CIMCameraEffect DefaultCameraEffect { get; set; }
```
### DefaultColorVisionDeficiencyMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the color vision deficiency mode that new views of this map or scene are opened with.</p>


```csharp
public ColorVisionDeficiencyType DefaultColorVisionDeficiencyMode { get; set; }
```
### DefaultExtent

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the extent shown when you open new views of the map. The application automatically updates this property whenever you save a project with an active map view.</p>


```csharp
public Envelope DefaultExtent { get; set; }
```
### DefaultFieldOfView

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the default field-of-view in degrees (value must be between 35 and 70).
Only used when the scene is in Perspective draw mode.</p>


```csharp
public double DefaultFieldOfView { get; set; }
```
### DefaultGlobeTransparency

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the transparency of the spheroid's combined terrain mesh and draped content.</p>


```csharp
public double DefaultGlobeTransparency { get; set; }
```
### DefaultPostprocessingEffects

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the post-processing effects that new views of this scene are opened with.</p>


```csharp
public CIMPostprocessingEffect[] DefaultPostprocessingEffects { get; set; }
```
### DefaultRotation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the default rotation.</p>


```csharp
public double DefaultRotation { get; set; }
```
### DefaultScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the scale used when you open new views of the map. When set, the application automatically applies this property after DefaultExtent to ensure the view is at the correct scale.</p>


```csharp
public double DefaultScale { get; set; }
```
### DefaultViewingMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the viewing mode that new views of this map are opened with.</p>


```csharp
public MapViewingMode DefaultViewingMode { get; set; }
```
### DefaultVisualEffect

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the visual effect that new views of this scene are opened with.</p>


```csharp
public CIMVisualEffect DefaultVisualEffect { get; set; }
```
### Description

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the long description of the map.</p>


```csharp
public string Description { get; set; }
```
### EditingElevation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the editing elevation mode.</p>


```csharp
public CIMEditingElevation EditingElevation { get; set; }
```
### EditingTemplateCollection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the collection of editing templates for a map.</p>


```csharp
public CIMEditingTemplateCollection EditingTemplateCollection { get; set; }
```
### ElevationDisplayUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the WKID of the elevation display unit used by the map.</p>


```csharp
public int ElevationDisplayUnit { get; set; }
```
### EnableNavigationBelowGround

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or to enable navigation below the ground.</p>


```csharp
public bool EnableNavigationBelowGround { get; set; }
```
### EnableWraparound

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or to enable wraparound when the coordinate system supports it.</p>


```csharp
public bool EnableWraparound { get; set; }
```
### FieldMappings

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the collection of field mappings for a map.</p>


```csharp
public CIMFieldMapping[] FieldMappings { get; set; }
```
### FloorAwareMapProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the floor-aware properties of the map.</p>


```csharp
public CIMFloorAwareMapProperties FloorAwareMapProperties { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Reconstructs the CIMMap with a specified state from a JSON encoding.</p>


```csharp
public static CIMMap FromJson(string json, JsonDeserializationSettings settings = null)
```
### GeneralPlacementProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the general label placement properties for dynamic labels in the map.</p>


```csharp
public CIMGeneralPlacementProperties GeneralPlacementProperties { get; set; }
```
### GeotriggerProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the geotrigger properties of the map.</p>


```csharp
public CIMMapGeotriggerProperties GeotriggerProperties { get; set; }
```
### GroundElevationSurfaceLayer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the URI of the ground elevation surface layer in the map.</p>


```csharp
public string GroundElevationSurfaceLayer { get; set; }
```
### GroundToGridCorrection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the Ground To Grid Correction properties.</p>


```csharp
public CIMGroundToGridCorrection GroundToGridCorrection { get; set; }
```
### HVDatumTransforms

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the set of geographic transformations used by the map for spatial references with vertical coordinate system.</p>


```csharp
public CompositeHVDatumTransformation[] HVDatumTransforms { get; set; }
```
### IPSAwareMapProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the IPS-aware properties of the map.</p>


```csharp
public CIMIPSAwareMapProperties IPSAwareMapProperties { get; set; }
```
### Illumination

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the illumination properties.</p>


```csharp
public CIMIlluminationProperties Illumination { get; set; }
```
### IncludeMaximumInScaleRanges

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to draw up to and including the maximum scale in scale ranges.</p>


```csharp
public bool IncludeMaximumInScaleRanges { get; set; }
```
### KnowledgeGraphLinkChartProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the Knowledge Graph Link Chart properties of this map.
This property is only applicable if the MapType is LinkChart.</p>


```csharp
public CIMKnowledgeGraphLinkChartProperties KnowledgeGraphLinkChartProperties { get; set; }
```
### Layers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the layers as an array of layer repository paths.</p>


```csharp
public string[] Layers { get; set; }
```
### LayersExcludedFromClipping

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the layers to be excluded from clipping. The layers are defined as an array of layer repository paths.</p>


```csharp
public string[] LayersExcludedFromClipping { get; set; }
```
### LinkCharts

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the link charts as an array of link chart repository paths.</p>


```csharp
public string[] LinkCharts { get; set; }
```
### LocationDisplayUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the WKID of the location display unit used by the map.</p>


```csharp
public int LocationDisplayUnit { get; set; }
```
### Locators

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the locators as an ordered array.</p>


```csharp
public CIMLocator[] Locators { get; set; }
```
### MapContexts

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets an array string values used to provide a hint for the intended context for the map.</p>


```csharp
public string[] MapContexts { get; set; }
```
### MapType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the map type.</p>


```csharp
public MapType MapType { get; set; }
```
### NearPlaneClipDistance

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the near plane clip distance in meters for a scene. This property applies to only local and global viewing modes.</p>


```csharp
public double NearPlaneClipDistance { get; set; }
```
### NearPlaneClipDistanceMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the near plane clipping mode for a scene. This property applies to only local and global viewing modes.</p>


```csharp
public ClipDistanceMode NearPlaneClipDistanceMode { get; set; }
```
### RGBColorProfile

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the name of the RGB color profile for a map.</p>


```csharp
public string RGBColorProfile { get; set; }
```
### RangeSliderSettings

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the range slider settings.</p>


```csharp
public CIMSliderSettings RangeSliderSettings { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ReferenceScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the map reference scale.</p>


```csharp
public double ReferenceScale { get; set; }
```
### ScaleDisplayFormat

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the display mode for the map's Scales in the user interface.</p>


```csharp
public ScaleDisplayFormat ScaleDisplayFormat { get; set; }
```
### ScaleFormat

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the scale format describing the formatting of the scale value.</p>


```csharp
public CIMScaleFormat ScaleFormat { get; set; }
```
### Scales

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets an array of CIMScale objects, describing the full list of named scales for the map.</p>


```csharp
public CIMScale[] Scales { get; set; }
```
### SimulateOverprint

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to simulate overprint for a map.</p>


```csharp
public bool SimulateOverprint { get; set; }
```
### SnapToScales

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to snap only to the map's list of named scales when zooming.</p>


```csharp
public bool SnapToScales { get; set; }
```
### SnappingProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the snapping properties of the map.</p>


```csharp
public CIMSnappingProperties SnappingProperties { get; set; }
```
### SpatialReference

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the map's spatial reference.</p>


```csharp
public SpatialReference SpatialReference { get; set; }
```
### StandaloneTables

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the standalone tables as an array of table repository paths.</p>


```csharp
public string[] StandaloneTables { get; set; }
```
### StandaloneVideos

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the standalone videos as an array of video repository paths.</p>


```csharp
public string[] StandaloneVideos { get; set; }
```
### StereoProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the stereo properties.</p>


```csharp
public CIMMapStereoProperties StereoProperties { get; set; }
```
### SurfaceColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the color of the default spheroid.</p>


```csharp
public CIMColor SurfaceColor { get; set; }
```
### SurfacesExcludedFromClipping

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the surfaces to be excluded from clipping. The surfaces are defined as an array of surface IDs.</p>


```csharp
public string[] SurfacesExcludedFromClipping { get; set; }
```
### TimeDisplay

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the time display properties.</p>


```csharp
public CIMMapTimeDisplay TimeDisplay { get; set; }
```
### TimeSliderSettings

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the time slider settings.</p>


```csharp
public CIMSliderSettings TimeSliderSettings { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMap and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseMasking

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether masking established on all layers in the map is turned on or off.</p>


```csharp
public bool UseMasking { get; set; }
```
### UseServiceLayerIDs

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to allow the use of unique numeric IDs on layers that will be used when publishing services.</p>


```csharp
public bool UseServiceLayerIDs { get; set; }
```
### WeatherEffect

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Gets or sets the weather effect.</p>


```csharp
public CIMWeatherEffect WeatherEffect { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMap.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


