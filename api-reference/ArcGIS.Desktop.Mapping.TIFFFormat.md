# TIFFFormat

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.TIFFFormat.yml" sourcestartlinenumber="1">Represents a Tagged Image File Format (TIFF) object that can be used to export a
<xref href="ArcGIS.Desktop.Mapping.MapView?text=MapView" data-throw-if-not-resolved="false"></xref>, <xref href="ArcGIS.Desktop.Layouts.MapFrame?text=MapFrame" data-throw-if-not-resolved="false"></xref>, or a <xref href="ArcGIS.Desktop.Layouts.Layout?text=Layout" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class TIFFFormat : ExportFormat
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.TIFFFormat.yml" sourcestartlinenumber="1">TIFF files are the most versatile raster format. TIFFs can store pixel data at several bit depths and can be compressed with either lossy or
loss less compression techniques depending on file size and accuracy requirements. They are the best choice for importing into image editing applications across operating systems.
They cannot be natively viewed by a web browser. TIFFs exported from a Map or MapFrame also support georeferencing information in GeoTIFF tags or in a separate world file for use as raster data.</p>


## Members

### TIFFFormat()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.TIFFFormat.yml" sourcestartlinenumber="1">Initialize a new instance of TIFFFormat.</p>


```csharp
public TIFFFormat()
```
### ColorMode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TIFFFormat.yml" sourcestartlinenumber="1">Gets or sets the number of bits used to describe color.</p>


```csharp
public TIFFColorMode ColorMode { get; set; }
```
### GeoReferenceMapFrameName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TIFFFormat.yml" sourcestartlinenumber="1">Gets or sets the name of the map frame used to define the coordinate system for georeference information.</p>


```csharp
public string GeoReferenceMapFrameName { get; set; }
```
### HasColorProfile

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TIFFFormat.yml" sourcestartlinenumber="1">Gets or sets if a color profile is embedded.</p>


```csharp
public bool HasColorProfile { get; set; }
```
### HasGeoTiffTags

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TIFFFormat.yml" sourcestartlinenumber="1">Gets or sets if geoTIFF tags are included.
If set to true and a valid GeoReferenceMapFrameName is set, geoTIFF tags will be embedded in the resulting image
based on the map frame's coordinate system.</p>


```csharp
public bool HasGeoTiffTags { get; set; }
```
### HasTransparentBackground

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TIFFFormat.yml" sourcestartlinenumber="1">Gets or sets if the background will be transparent.</p>


```csharp
public bool HasTransparentBackground { get; set; }
```
### HasWorldFile

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TIFFFormat.yml" sourcestartlinenumber="1">Gets or sets if a georeferenced world file will be created.</p>


```csharp
public bool HasWorldFile { get; set; }
```
### ImageCompression

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TIFFFormat.yml" sourcestartlinenumber="1">Gets or sets the compression scheme.</p>


```csharp
public TIFFImageCompression ImageCompression { get; set; }
```
### ImageCompressionQuality

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TIFFFormat.yml" sourcestartlinenumber="1">This value (0–100) controls the amount of compression applied to the output image. With a JPEG image, quality is
adversely affected the more compression is applied. A higher quality (highest = 100) setting will produce sharper
images and larger file sizes. A lower quality setting will produce more image artifacts and smaller files.</p>


```csharp
public int ImageCompressionQuality { get; set; }
```
### Threshold

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TIFFFormat.yml" sourcestartlinenumber="1">Gets or sets the threshold value to indicate black and white color for the image intensities.</p>


```csharp
public int Threshold { get; set; }
```


