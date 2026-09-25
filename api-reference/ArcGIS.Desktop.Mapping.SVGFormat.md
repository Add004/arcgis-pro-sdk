# SVGFormat

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.SVGFormat.yml" sourcestartlinenumber="1">Represents a Scalable Vector Graphics (SVG) object that can be used to export a
<xref href="ArcGIS.Desktop.Mapping.MapView?text=MapView" data-throw-if-not-resolved="false"></xref>, <xref href="ArcGIS.Desktop.Layouts.MapFrame?text=MapFrame" data-throw-if-not-resolved="false"></xref>, or a <xref href="ArcGIS.Desktop.Layouts.Layout?text=Layout" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class SVGFormat : ExportFormat
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.SVGFormat.yml" sourcestartlinenumber="1">SVG is an XML-based file format that has been specifically designed for viewing on the Web.
SVG can contain both vector and raster information. This is a good choice for displaying maps on a web page because it is rescalable and more easily edited than raster files.
SVG has been gaining in popularity since the World Wide Web Consortium (W3C) selected it as their standard vector Web format.
Some Web browsers may require a plug-in to view SVG files; older browsers may not be able to view SVG files at all.</p>


## Members

### SVGFormat()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.SVGFormat.yml" sourcestartlinenumber="1">Initialize a new instance of SVGFormat.</p>


```csharp
public SVGFormat()
```
### DoCompressToSVGZ

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SVGFormat.yml" sourcestartlinenumber="1">Gets or sets a Boolean that controls if the document will be compressed.</p>


```csharp
public bool DoCompressToSVGZ { get; set; }
```
### DoConvertCharacterMarkerSymbolsToPolygon

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SVGFormat.yml" sourcestartlinenumber="1">Gets or sets a Boolean that controls the conversion of character marker symbols to polygon.</p>


```csharp
public bool DoConvertCharacterMarkerSymbolsToPolygon { get; set; }
```
### DoEmbedFonts

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SVGFormat.yml" sourcestartlinenumber="1">Gets or sets a Boolean that controls the embedding of fonts in the export file.</p>


```csharp
public bool DoEmbedFonts { get; set; }
```
### DoFullRasterization

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SVGFormat.yml" sourcestartlinenumber="1">Gets or sets a Boolean that controls the full rasterization in export file.</p>


```csharp
public bool DoFullRasterization { get; set; }
```
### DoRemoveThinLineArtifact

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SVGFormat.yml" sourcestartlinenumber="1">Gets or sets a Boolean to export raster content as a single tile.</p>


```csharp
public bool DoRemoveThinLineArtifact { get; set; }
```
### ImageQuality

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SVGFormat.yml" sourcestartlinenumber="1">Gets or sets the output image quality - the draw resolution of map layers that draw as rasters.</p>


```csharp
public ImageQuality ImageQuality { get; set; }
```
### IncludeNonVisibleMapLayers

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SVGFormat.yml" sourcestartlinenumber="1">Gets or sets if the output will have non-visible map layers.</p>


```csharp
public bool IncludeNonVisibleMapLayers { get; set; }
```
### ValidateOutputFilePath()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SVGFormat.yml" sourcestartlinenumber="1">Validates the output file path.</p>


```csharp
public override bool ValidateOutputFilePath()
```


