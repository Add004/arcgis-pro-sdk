# ImageCompression

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.ImageCompression.yml" sourcestartlinenumber="1">Specifies the compression scheme used to compress image or raster data in the output file.</p>


## Object Signature

```csharp
public enum ImageCompression
```


## Members

### Adaptive

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.ImageCompression.yml" sourcestartlinenumber="1">JPEG and Deflate compression are combined, depending on the contents of the stream. This works well for most cases.</p>


```csharp
Adaptive = 5
```
### Deflate

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.ImageCompression.yml" sourcestartlinenumber="1">Lossless compression method that works well for most cases.</p>


```csharp
Deflate = 2
```
### JPEG

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.ImageCompression.yml" sourcestartlinenumber="1">Lossy compression method that works well for photographic-type images.</p>


```csharp
JPEG = 4
```
### JPEG2000

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.ImageCompression.yml" sourcestartlinenumber="1">Higher-quality compression with file sizes smaller than JPEG. This compression is lossless if set to quality 100.
JPEG2000 compression for EPS format is not supported.</p>


```csharp
JPEG2000 = 6
```
### LZW

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.ImageCompression.yml" sourcestartlinenumber="1">Lossless compression method using a code table.</p>


```csharp
LZW = 3
```
### None

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.ImageCompression.yml" sourcestartlinenumber="1">Compression is not applied.</p>


```csharp
None = 0
```
### RLE

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.ImageCompression.yml" sourcestartlinenumber="1">Run-length encoded compression, a lossless compression method that works well if there are large areas of the same color.</p>


```csharp
RLE = 1
```


