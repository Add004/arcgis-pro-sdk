# UncompressedTexture

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.UncompressedTexture.yml" sourcestartlinenumber="1">A <xref href="ArcGIS.Core.Geometry.TextureMap" data-throw-if-not-resolved="false"></xref> that contains a raw uncompressed raster image.  Wrap an UncompressedTexture within a <xref href="ArcGIS.Core.Geometry.TextureResource" data-throw-if-not-resolved="false"></xref> for use with
a <xref href="ArcGIS.Core.Geometry.BasicMaterial" data-throw-if-not-resolved="false"></xref> when defining a <xref href="ArcGIS.Core.Geometry.Multipatch" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class UncompressedTexture : TextureMap
```


## Members

### UncompressedTexture(UncompressedTexture)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.UncompressedTexture.yml" sourcestartlinenumber="1">Creates a deep copy of the <xref href="ArcGIS.Core.Geometry.UncompressedTexture" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public UncompressedTexture(UncompressedTexture other)
```
### UncompressedTexture(byte[], int, int, byte)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.UncompressedTexture.yml" sourcestartlinenumber="1">Initializes a new instance of the <xref href="ArcGIS.Core.Geometry.UncompressedTexture" data-throw-if-not-resolved="false"></xref> class from given data.</p>


```csharp
public UncompressedTexture(byte[] buffer, int columns, int rows, byte bpp)
```
### BytesPerPixel

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.UncompressedTexture.yml" sourcestartlinenumber="1">Gets the bytes per pixel of the image.</p>


```csharp
public override byte BytesPerPixel { get; }
```
### ColumnCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.UncompressedTexture.yml" sourcestartlinenumber="1">Gets the width of the image in pixels.</p>


```csharp
public override int ColumnCount { get; }
```
### IsEqual(Texture)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.UncompressedTexture.yml" sourcestartlinenumber="1">Determines if this texture is equal to the other texture.</p>


```csharp
public override bool IsEqual(Texture other)
```
### RowCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.UncompressedTexture.yml" sourcestartlinenumber="1">Gets the height of the image in pixels.</p>


```csharp
public override int RowCount { get; }
```


