# BMPFormat

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.BMPFormat.yml" sourcestartlinenumber="1">Represents a Microsoft Windows Bitmap (BMP) object that can be used to export a
<xref href="ArcGIS.Desktop.Mapping.MapView?text=MapView" data-throw-if-not-resolved="false"></xref>, <xref href="ArcGIS.Desktop.Layouts.MapFrame?text=MapFrame" data-throw-if-not-resolved="false"></xref>, or a <xref href="ArcGIS.Desktop.Layouts.Layout?text=Layout" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class BMPFormat : ExportFormat
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.BMPFormat.yml" sourcestartlinenumber="1">BMP files are simple, native Windows raster images. In general, BMPs are much larger than formats such as JPEG or PNG.
They do not scale as well as vector files and may appear blocky or jagged when increased in size.
BMPs can be generated with an accompanying world file for use as georeferenced raster data.</p>


## Members

### BMPFormat()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.BMPFormat.yml" sourcestartlinenumber="1">Initialize a new instance of BMPFormat.</p>


```csharp
public BMPFormat()
```
### ColorMode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.BMPFormat.yml" sourcestartlinenumber="1">Gets or sets the number of bits used to describe color for BMP.</p>


```csharp
public BMPColorMode ColorMode { get; set; }
```
### GeoReferenceMapFrameName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.BMPFormat.yml" sourcestartlinenumber="1">Gets or sets the name of the map frame used to define the coordinate system for georeference information.</p>


```csharp
public string GeoReferenceMapFrameName { get; set; }
```
### HasColorProfile

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.BMPFormat.yml" sourcestartlinenumber="1">Gets or sets if a color profile is embedded.</p>


```csharp
[Obsolete("Deprecated at 3.3")]
public bool HasColorProfile { get; set; }
```
### HasWorldFile

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.BMPFormat.yml" sourcestartlinenumber="1">Gets or sets if a georeferenced world file will be created.</p>


```csharp
public bool HasWorldFile { get; set; }
```
### Threshold

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.BMPFormat.yml" sourcestartlinenumber="1">Gets or sets the threshold value to indicate black and white color for the image intensities.</p>


```csharp
public int Threshold { get; set; }
```


