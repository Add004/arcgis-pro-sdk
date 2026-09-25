# EPSFormat

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.EPSFormat.yml" sourcestartlinenumber="1">Represents an Encapsulated Postscript (EPS) object that can be used to export a
<xref href="ArcGIS.Desktop.Mapping.MapView?text=MapView" data-throw-if-not-resolved="false"></xref>, <xref href="ArcGIS.Desktop.Layouts.MapFrame?text=MapFrame" data-throw-if-not-resolved="false"></xref>, or a <xref href="ArcGIS.Desktop.Layouts.Layout?text=Layout" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class EPSFormat : ExportFormat
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.EPSFormat.yml" sourcestartlinenumber="1">EPS files use the PostScript page description language to describe vector and raster objects. PostScript is the publishing industry standard for high-end graphics files,
cartography, and printing. EPS files can be edited in many drawing applications or placed as a graphic in most page layout applications.
EPS files support embedding of fonts so that users who do not have Esri Fonts installed can still view the proper symbology.</p>


## Members

### EPSFormat()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.EPSFormat.yml" sourcestartlinenumber="1">Initialize a new instance of EPSFormat.</p>


```csharp
public EPSFormat()
```
### DoConvertCharacterMarkerSymbolsToPolygon

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.EPSFormat.yml" sourcestartlinenumber="1">Gets or sets a Boolean that controls the conversion of character marker symbols to polygon.</p>


```csharp
public bool DoConvertCharacterMarkerSymbolsToPolygon { get; set; }
```
### DoEmbedFonts

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.EPSFormat.yml" sourcestartlinenumber="1">Gets or sets a Boolean that controls the embedding of fonts in the export file.</p>


```csharp
public bool DoEmbedFonts { get; set; }
```
### DoFullRasterization

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.EPSFormat.yml" sourcestartlinenumber="1">Gets or sets a Boolean that controls the full rasterization in export file.</p>


```csharp
public bool DoFullRasterization { get; set; }
```
### ImageCompression

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.EPSFormat.yml" sourcestartlinenumber="1">Gets or sets the compression scheme used to compress image or raster data in the output file.</p>


```csharp
public ImageCompression ImageCompression { get; set; }
```
### ImageQuality

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.EPSFormat.yml" sourcestartlinenumber="1">Gets or sets the output image quality - the draw resolution of map layers that draw as rasters.</p>


```csharp
public ImageQuality ImageQuality { get; set; }
```


