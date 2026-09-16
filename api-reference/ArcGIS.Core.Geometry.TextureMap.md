# TextureMap

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.TextureMap.yml" sourcestartlinenumber="1">A <xref href="ArcGIS.Core.Geometry.Texture" data-throw-if-not-resolved="false"></xref> class that contains a raster image.</p>


## Object Signature

```csharp
public abstract class TextureMap : Texture
```


## Members

### TextureMap()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.TextureMap.yml" sourcestartlinenumber="1">A <xref href="ArcGIS.Core.Geometry.Texture" data-throw-if-not-resolved="false"></xref> class that contains a raster image.</p>


```csharp
protected TextureMap()
```
### Buffer

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.TextureMap.yml" sourcestartlinenumber="1">Gets the buffer that contains the image.</p>


```csharp
public byte[] Buffer { get; }
```
### BytesPerPixel

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.TextureMap.yml" sourcestartlinenumber="1">Gets the bytes per pixel of the image.</p>


```csharp
public abstract byte BytesPerPixel { get; }
```
### ColumnCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.TextureMap.yml" sourcestartlinenumber="1">Gets the width of the image in pixels.</p>


```csharp
public abstract int ColumnCount { get; }
```
### RowCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.TextureMap.yml" sourcestartlinenumber="1">Gets the height of the image in pixels.</p>


```csharp
public virtual int RowCount { get; }
```


