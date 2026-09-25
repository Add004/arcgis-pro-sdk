# JPEGTexture

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.JPEGTexture.yml" sourcestartlinenumber="1">A <xref href="ArcGIS.Core.Geometry.TextureMap" data-throw-if-not-resolved="false"></xref> that contains a Jpeg image. Wrap a JPEGTexture within a <xref href="ArcGIS.Core.Geometry.TextureResource" data-throw-if-not-resolved="false"></xref> for use with a <xref href="ArcGIS.Core.Geometry.BasicMaterial" data-throw-if-not-resolved="false"></xref>
when defining a <xref href="ArcGIS.Core.Geometry.Multipatch" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class JPEGTexture : TextureMap
```


## Members

### JPEGTexture(JPEGTexture)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.JPEGTexture.yml" sourcestartlinenumber="1">Constructs a new JPEGTexture from the given JPEG texture.</p>


```csharp
public JPEGTexture(JPEGTexture other)
```
### JPEGTexture(byte[])

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.JPEGTexture.yml" sourcestartlinenumber="1">Initializes a new instance of the <xref href="ArcGIS.Core.Geometry.JPEGTexture" data-throw-if-not-resolved="false"></xref> class from the given buffer.</p>


```csharp
public JPEGTexture(byte[] buffer)
```
### BytesPerPixel

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.JPEGTexture.yml" sourcestartlinenumber="1">Gets the bytes per pixel of the image.</p>


```csharp
public override byte BytesPerPixel { get; }
```
### ColumnCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.JPEGTexture.yml" sourcestartlinenumber="1">Gets the width of the image in pixels.</p>


```csharp
public override int ColumnCount { get; }
```
### IsEqual(Texture)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.JPEGTexture.yml" sourcestartlinenumber="1">Determines if this texture is equal to the other texture.</p>


```csharp
public override bool IsEqual(Texture texture)
```
### RowCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.JPEGTexture.yml" sourcestartlinenumber="1">Gets the height of the image in pixels.</p>


```csharp
public override int RowCount { get; }
```


