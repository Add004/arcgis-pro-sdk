# GIFFormat

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.GIFFormat.yml" sourcestartlinenumber="1">Represents an Graphic Interchange Format (GIF) object that can be used to export a
<xref href="ArcGIS.Desktop.Mapping.MapView?text=MapView" data-throw-if-not-resolved="false"></xref>, <xref href="ArcGIS.Desktop.Layouts.MapFrame?text=MapFrame" data-throw-if-not-resolved="false"></xref>, or a <xref href="ArcGIS.Desktop.Layouts.Layout?text=Layout" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class GIFFormat : ExportFormat
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.GIFFormat.yml" sourcestartlinenumber="1">GIF files are a legacy raster format for use on the web. GIFs cannot contain more than 256 colors (8-bits per pixel),
which along with optional lossless compression, makes them smaller than other file formats.</p>


## Members

### GIFFormat()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.GIFFormat.yml" sourcestartlinenumber="1">Initialize a new instance of GIFFormat.</p>


```csharp
public GIFFormat()
```
### ColorMode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.GIFFormat.yml" sourcestartlinenumber="1">Gets or sets the number of bits used to describe color for GIF.</p>


```csharp
public GIFColorMode ColorMode { get; set; }
```
### GeoReferenceMapFrameName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.GIFFormat.yml" sourcestartlinenumber="1">Gets or sets the name of the map frame used to define the coordinate system for georeference information</p>


```csharp
public string GeoReferenceMapFrameName { get; set; }
```
### HasWorldFile

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.GIFFormat.yml" sourcestartlinenumber="1">Gets or sets if a georeferenced world file will be created.</p>


```csharp
public bool HasWorldFile { get; set; }
```
### Threshold

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.GIFFormat.yml" sourcestartlinenumber="1">Gets or sets the threshold value to indicate black and white color for the image intensities.</p>


```csharp
public int Threshold { get; set; }
```


