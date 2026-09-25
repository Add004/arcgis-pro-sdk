# AIXFormat

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.AIXFormat.yml" sourcestartlinenumber="1">Represents a Portable Document Format (AIX) object that can be used to export a
<xref href="ArcGIS.Desktop.Mapping.MapView?text=MapView" data-throw-if-not-resolved="false"></xref>, <xref href="ArcGIS.Desktop.Layouts.MapFrame?text=MapFrame" data-throw-if-not-resolved="false"></xref>, or a <xref href="ArcGIS.Desktop.Layouts.Layout?text=Layout" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class AIXFormat : ExportFormat
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.AIXFormat.yml" sourcestartlinenumber="1">AIX files are designed to be consistently viewable and printable across different platforms.
They are commonly used for distributing documents on the Web and are becoming a standard interchange format for content delivery.
AIXs are editable in many graphics applications and can retain annotation, labeling, and attribute data for map layers.
AIX exports from support embedding of fonts and thus can display symbology correctly even if the user does not have Esri fonts installed.</p>


## Members

### AIXFormat()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.AIXFormat.yml" sourcestartlinenumber="1">Initialize a new instance of AIXFormat.</p>


```csharp
public AIXFormat()
```
### DoCompressVectorGraphics

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.AIXFormat.yml" sourcestartlinenumber="1">Gets or sets a Boolean that controls compression of vector and text portions of the output file. Image compression is defined separately.</p>


```csharp
public bool DoCompressVectorGraphics { get; set; }
```
### DoConvertCharacterMarkerSymbolsToPolygon

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.AIXFormat.yml" sourcestartlinenumber="1">Gets or sets a Boolean that controls the conversion of character marker symbols to polygon.</p>


```csharp
public bool DoConvertCharacterMarkerSymbolsToPolygon { get; set; }
```
### DoEmbedFonts

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.AIXFormat.yml" sourcestartlinenumber="1">Gets or sets a Boolean that controls the embedding of fonts in the export file.</p>


```csharp
public bool DoEmbedFonts { get; set; }
```
### HasColorProfile

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.AIXFormat.yml" sourcestartlinenumber="1">Gets or sets if a color profile is embedded.</p>


```csharp
public bool HasColorProfile { get; set; }
```
### HasLayoutBackground

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.AIXFormat.yml" sourcestartlinenumber="1">Gets or sets if the output will have white background.</p>


```csharp
public bool HasLayoutBackground { get; set; }
```
### ImageCompression

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.AIXFormat.yml" sourcestartlinenumber="1">Gets or sets the compression scheme used to compress image or raster data in the output file.</p>


```csharp
public ImageCompression ImageCompression { get; set; }
```
### ImageCompressionQuality

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.AIXFormat.yml" sourcestartlinenumber="1">This value (0–100) controls the amount of compression applied to the output image. With a JPEG image, quality is
adversely affected the more compression is applied. A higher quality (highest = 100) setting will produce sharper
images and larger file sizes. A lower quality setting will produce more image artifacts and smaller files.</p>


```csharp
public int ImageCompressionQuality { get; set; }
```
### ImageQuality

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.AIXFormat.yml" sourcestartlinenumber="1">Gets or sets the output image quality - the draw resolution of map layers that draw as rasters.</p>


```csharp
public ImageQuality ImageQuality { get; set; }
```
### IncludeNonVisibleMapLayers

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.AIXFormat.yml" sourcestartlinenumber="1">Gets or sets if the output will have non-visible map layers.</p>


```csharp
public bool IncludeNonVisibleMapLayers { get; set; }
```


