# PNGFormat

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.PNGFormat.yml" sourcestartlinenumber="1">Represents a Portable Network Graphics (PNG) object that can be used to export a
<xref href="ArcGIS.Desktop.Mapping.MapView?text=MapView" data-throw-if-not-resolved="false"></xref>, <xref href="ArcGIS.Desktop.Layouts.MapFrame?text=MapFrame" data-throw-if-not-resolved="false"></xref>, or a <xref href="ArcGIS.Desktop.Layouts.Layout?text=Layout" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class PNGFormat : ExportFormat
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.PNGFormat.yml" sourcestartlinenumber="1">PNG is a versatile raster format that can display in web browsers and inserted into other documents.
It supports high-bit-depth color and uses a lossless compression. For maps, PNG is often the best raster format,
since the lossless compression keeps text and line work legible by preventing the compression artifacts that can occur in JPEG format.
PNGs can be generated with an accompanying world file for use as georeferenced raster data.</p>


## Members

### PNGFormat()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.PNGFormat.yml" sourcestartlinenumber="1">Initialize a new instance of PNGFormat.</p>


```csharp
public PNGFormat()
```
### ColorMode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PNGFormat.yml" sourcestartlinenumber="1">Gets or sets the number of bits used to describe color.</p>


```csharp
public PNGColorMode ColorMode { get; set; }
```
### GeoReferenceMapFrameName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PNGFormat.yml" sourcestartlinenumber="1">Gets or sets the name of the map frame used to define the coordinate system for georeference information</p>


```csharp
public string GeoReferenceMapFrameName { get; set; }
```
### HasColorProfile

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PNGFormat.yml" sourcestartlinenumber="1">Gets or sets if a color profile is embedded.</p>


```csharp
[Obsolete("Deprecated at 3.3")]
public bool HasColorProfile { get; set; }
```
### HasTransparentBackground

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PNGFormat.yml" sourcestartlinenumber="1">Gets or sets if the background will be transparent.</p>


```csharp
public bool HasTransparentBackground { get; set; }
```
### HasWorldFile

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PNGFormat.yml" sourcestartlinenumber="1">Gets or sets if a georeferenced world file will be created.</p>


```csharp
public bool HasWorldFile { get; set; }
```
### Threshold

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PNGFormat.yml" sourcestartlinenumber="1">Gets or sets the threshold value to indicate black and white color for the image intensities.</p>


```csharp
public int Threshold { get; set; }
```


