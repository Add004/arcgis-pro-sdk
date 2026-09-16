# PyramidCompressionType

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.PyramidCompressionType.yml" sourcestartlinenumber="1">Defines the compression type used when building raster pyramids.  See <xref href="ArcGIS.Desktop.Core.RasterImageryOptions.GetPyramidCompressionMethod" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public enum PyramidCompressionType
```


## Members

### Default

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.PyramidCompressionType.yml" sourcestartlinenumber="1">Default. If the source data is compressed using a wavelet compression, it builds pyramids with the JPEG compression type; otherwise, LZ77 is used.</p>


```csharp
Default = 4
```
### JPEG

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.PyramidCompressionType.yml" sourcestartlinenumber="1">JPEG.</p>


```csharp
JPEG = 2
```
### JPEG_YCbCr

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.PyramidCompressionType.yml" sourcestartlinenumber="1">JPEG_YCbCr. A lossy compression using the luma (Y) and chroma (Cb and Cr) color space components.</p>


```csharp
JPEG_YCbCr = 11
```
### LZ77

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.PyramidCompressionType.yml" sourcestartlinenumber="1">LZ77.</p>


```csharp
LZ77 = 1
```
### None

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.PyramidCompressionType.yml" sourcestartlinenumber="1">No compression.</p>


```csharp
None = 0
```


