# TIFFImageCompression

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.TIFFImageCompression.yml" sourcestartlinenumber="1">Specifies the compression scheme used to compress image or raster data in the output file.</p>


## Object Signature

```csharp
public enum TIFFImageCompression
```


## Members

### Deflate

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.TIFFImageCompression.yml" sourcestartlinenumber="1">Lossless compression method that works well for most cases.</p>


```csharp
Deflate = 4
```
### JPEG

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.TIFFImageCompression.yml" sourcestartlinenumber="1">Lossy compression method that works well for photographic-type images.</p>


```csharp
JPEG = 2
```
### LZW

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.TIFFImageCompression.yml" sourcestartlinenumber="1">Lossless compression method using a code table.</p>


```csharp
LZW = 3
```
### None

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.TIFFImageCompression.yml" sourcestartlinenumber="1">Compression is not applied.</p>


```csharp
None = 0
```
### Packbits

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.TIFFImageCompression.yml" sourcestartlinenumber="1">Lossless compression method that works well if there are large areas of the same color.</p>


```csharp
Packbits = 1
```


