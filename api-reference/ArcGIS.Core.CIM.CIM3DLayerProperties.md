# CIM3DLayerProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIM3DLayerProperties.yml" sourcestartlinenumber="1">Represents 3D layer properties which contain properties used for 3D draw.</p>


## Object Signature

```csharp
public class CIM3DLayerProperties : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIM3DLayerProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIM3DLayerProperties.yml" sourcestartlinenumber="1">Creates a default CIM3DLayerProperties object.</p>


```csharp
public CIM3DLayerProperties()
```
### CastShadows

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIM3DLayerProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether shadows are enabled. If true, this layer's features contribute to shadows.</p>


```csharp
public bool CastShadows { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIM3DLayerProperties.yml" sourcestartlinenumber="1">Creates a deep copy of CIM3DLayerProperties.</p>


```csharp
public CIM3DLayerProperties Clone()
```
### DepthPriority

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIM3DLayerProperties.yml" sourcestartlinenumber="1">Gets or sets the depth priority of a 3D layer.</p>


```csharp
public int DepthPriority { get; set; }
```
### Enable2DSymbolPerspectiveScaling

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIM3DLayerProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether perspective scaling to screen-size is enabled for billboarded 2D symbols.</p>


```csharp
public bool Enable2DSymbolPerspectiveScaling { get; set; }
```
### ExaggerationMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIM3DLayerProperties.yml" sourcestartlinenumber="1">Gets or sets the layer's exaggeration mode.</p>


```csharp
public ExaggerationMode ExaggerationMode { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIM3DLayerProperties.yml" sourcestartlinenumber="1">Reconstructs the CIM3DLayerProperties with a specified state from a JSON encoding.</p>


```csharp
public static CIM3DLayerProperties FromJson(string json, JsonDeserializationSettings settings = null)
```
### IsLayerLit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIM3DLayerProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this layer is lit.</p>


```csharp
public bool IsLayerLit { get; set; }
```
### LayerFaceCulling

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIM3DLayerProperties.yml" sourcestartlinenumber="1">Gets or sets the layer's face culling setting.</p>


```csharp
public FaceCulling3D LayerFaceCulling { get; set; }
```
### Lighting

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIM3DLayerProperties.yml" sourcestartlinenumber="1">Gets or sets the layer's lighting setting.</p>


```csharp
public Lighting3D Lighting { get; set; }
```
### MaxDistance

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIM3DLayerProperties.yml" sourcestartlinenumber="1">Gets or sets the maximum distance at which objects in view are visible. Objects beyond this point don't get rendered.</p>


```csharp
public double MaxDistance { get; set; }
```
### MaxPreloadDistance

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIM3DLayerProperties.yml" sourcestartlinenumber="1">Gets or sets the maximum radius from the camera at which objects outside the view are loaded. Values are in Meters.</p>


```csharp
public double MaxPreloadDistance { get; set; }
```
### MinDistance

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIM3DLayerProperties.yml" sourcestartlinenumber="1">Gets or sets the minimum distance at which objects in view are visible. Objects closer than this don't get rendered.</p>


```csharp
public double MinDistance { get; set; }
```
### MinPreloadDistance

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIM3DLayerProperties.yml" sourcestartlinenumber="1">Gets or sets the minimum radius from the camera at which objects at which objects outside the view are loaded. Values are in Meters.</p>


```csharp
public double MinPreloadDistance { get; set; }
```
### OptimizeMarkerTransparency

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIM3DLayerProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether true alpha is quantized to fully opaque or transparent when false, actual values are used in marker drawing.</p>


```csharp
public bool OptimizeMarkerTransparency { get; set; }
```
### PreloadTextureCutoffHigh

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIM3DLayerProperties.yml" sourcestartlinenumber="1">Gets or sets the distance (in visible range) at which high resolution textures change to low resolution textures for objects outside the view. Range is 0 to 1.</p>


```csharp
public double PreloadTextureCutoffHigh { get; set; }
```
### PreloadTextureCutoffLow

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIM3DLayerProperties.yml" sourcestartlinenumber="1">Gets or sets the distance (in visible range) at which low resolution textures change to solid colors for objects outside the view. Range is 0 to 1.</p>


```csharp
public double PreloadTextureCutoffLow { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIM3DLayerProperties.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### TextureCutoffHigh

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIM3DLayerProperties.yml" sourcestartlinenumber="1">Gets or sets the distance (in visible range) at which high resolution textures change to low resolution textures. Range is 0 to 1.</p>


```csharp
public double TextureCutoffHigh { get; set; }
```
### TextureCutoffLow

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIM3DLayerProperties.yml" sourcestartlinenumber="1">Gets or sets the distance (in visible range) at which low resolution textures change to solid colors. Range is 0 to 1.</p>


```csharp
public double TextureCutoffLow { get; set; }
```
### TextureDownscalingFactor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIM3DLayerProperties.yml" sourcestartlinenumber="1">Gets or sets the downscaling factor. All textures for this layer are downscaled by this additional factor on loading.</p>


```csharp
public int TextureDownscalingFactor { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIM3DLayerProperties.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIM3DLayerProperties and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseCompressedTextures

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIM3DLayerProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether uncompressed textures are compressed using DXT5 at load time.</p>


```csharp
public bool UseCompressedTextures { get; set; }
```
### UseDepthWritingForTransparency

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIM3DLayerProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to use depth writing for transparency. This should be set to true if anomalies are seen in drawing order of transparent features in the same feature class.</p>


```csharp
public bool UseDepthWritingForTransparency { get; set; }
```
### VerticalExaggeration

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIM3DLayerProperties.yml" sourcestartlinenumber="1">Gets or sets the layer's vertical exaggeration.</p>


```csharp
public double VerticalExaggeration { get; set; }
```
### VerticalUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIM3DLayerProperties.yml" sourcestartlinenumber="1">Gets or sets the layer's vertical unit.</p>


```csharp
public Unit VerticalUnit { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIM3DLayerProperties.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


