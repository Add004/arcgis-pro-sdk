# EMFFormat

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.EMFFormat.yml" sourcestartlinenumber="1">Represents an Enhanced Metafile Format (EMF) object that can be used to export a
<xref href="ArcGIS.Desktop.Mapping.MapView?text=MapView" data-throw-if-not-resolved="false"></xref>, <xref href="ArcGIS.Desktop.Layouts.MapFrame?text=MapFrame" data-throw-if-not-resolved="false"></xref>, or a <xref href="ArcGIS.Desktop.Layouts.Layout?text=Layout" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class EMFFormat : ExportFormat
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.EMFFormat.yml" sourcestartlinenumber="1">EMF files are native Windows graphics files that can contain a mixture of vector and raster data.
They are useful for embedding in Windows documents because the vector portions of the EMF can be resized without loss of quality.
However, since EMF does not support font embedding and is exclusively a Windows format, it is not commonly used as an interchange format between users.</p>


## Members

### EMFFormat()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.EMFFormat.yml" sourcestartlinenumber="1">Initialize a new instance of EMFFormat.</p>


```csharp
public EMFFormat()
```
### DoConvertCharacterMarkerSymbolsToPolygon

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.EMFFormat.yml" sourcestartlinenumber="1">Gets or sets a Boolean that controls the conversion of character marker symbols to polygon.</p>


```csharp
public bool DoConvertCharacterMarkerSymbolsToPolygon { get; set; }
```
### DoFullRasterization

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.EMFFormat.yml" sourcestartlinenumber="1">Gets or sets a Boolean that controls the full rasterization in export file.</p>


```csharp
public bool DoFullRasterization { get; set; }
```
### ImageQuality

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.EMFFormat.yml" sourcestartlinenumber="1">Gets or sets the output image quality - the draw resolution of map layers that draw as rasters.</p>


```csharp
public ImageQuality ImageQuality { get; set; }
```


