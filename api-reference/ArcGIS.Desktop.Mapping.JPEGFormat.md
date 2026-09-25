# JPEGFormat

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.JPEGFormat.yml" sourcestartlinenumber="1">Represents a Joint Photographic Experts Group (JPEG) format object that can be used to export a
<xref href="ArcGIS.Desktop.Mapping.MapView?text=MapView" data-throw-if-not-resolved="false"></xref>, <xref href="ArcGIS.Desktop.Layouts.MapFrame?text=MapFrame" data-throw-if-not-resolved="false"></xref>, or a <xref href="ArcGIS.Desktop.Layouts.Layout?text=Layout" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class JPEGFormat : ExportFormat
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.JPEGFormat.yml" sourcestartlinenumber="1">JPEG files are compressed image files. They support 24-bit color and are a popular choice for use on the web because a JPEG file size is often substantially
smaller than many other image formats. However, the JPEG compression algorithm is lossy and is not recommended for many map images, as line drawings, and text
or icon graphics become blurred by compression artifacts. Therefore, PNG is usually a superior format for map images. JPEGs can be generated with an accompanying
world file for use as georeferenced raster data.</p>


## Members

### JPEGFormat()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.JPEGFormat.yml" sourcestartlinenumber="1">Initialize a new instance of JPEGFormat.</p>


```csharp
public JPEGFormat()
```
### ColorMode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.JPEGFormat.yml" sourcestartlinenumber="1">Gets or sets the number of bits used to describe color for JPEG.</p>


```csharp
public JPEGColorMode ColorMode { get; set; }
```
### GeoReferenceMapFrameName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.JPEGFormat.yml" sourcestartlinenumber="1">Gets or sets the name of the map frame used to define the coordinate system for georeference information</p>


```csharp
public string GeoReferenceMapFrameName { get; set; }
```
### HasColorProfile

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.JPEGFormat.yml" sourcestartlinenumber="1">Gets or sets if a color profile is embedded.</p>


```csharp
[Obsolete("Deprecated at 3.3")]
public bool HasColorProfile { get; set; }
```
### HasWorldFile

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.JPEGFormat.yml" sourcestartlinenumber="1">Gets or sets if a georeferenced world file will be created.</p>


```csharp
public bool HasWorldFile { get; set; }
```
### ImageCompressionQuality

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.JPEGFormat.yml" sourcestartlinenumber="1">This value (0–100) controls the amount of compression applied to the output image. With a JPEG image, quality is
adversely affected the more compression is applied. A higher quality (highest = 100) setting will produce sharper
images and larger file sizes. A lower quality setting will produce more image artifacts and smaller files.</p>


```csharp
public int ImageCompressionQuality { get; set; }
```


