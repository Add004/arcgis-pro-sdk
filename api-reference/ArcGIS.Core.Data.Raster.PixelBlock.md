# PixelBlock

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Raster.html">Raster</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Raster.PixelBlock.yml" sourcestartlinenumber="1">Represents a container for pixel data that can be created using <xref href="ArcGIS.Core.Data.Raster.Raster.CreatePixelBlock(System.Int32%2cSystem.Int32)" data-throw-if-not-resolved="false"></xref></p>


## Object Signature

```csharp
public sealed class PixelBlock : CoreObjectsBase, IDisposable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.Raster.PixelBlock.yml" sourcestartlinenumber="1">The PixelBlock object is designed to handle generic pixel arrays from any raster data source. This means it must be able to handle single
and multiband data, as well as support different pixel types. To support multiple bands, or planes, of raster data,
the PixelBlock provides a separate array for each band (plane) in the raster.  You can get the pixel data from the pixel block,
modify the pixel values, and write the pixel block with the modified pixel values to a raster band. If the pixel block is
created from a Raster, the modified pixel block can be read using the <xref href="ArcGIS.Core.Data.Raster.Raster.Read(System.Int32%2cSystem.Int32%2cArcGIS.Core.Data.Raster.PixelBlock)" data-throw-if-not-resolved="false"></xref> method and written to
the raster dataset using the <xref href="ArcGIS.Core.Data.Raster.Raster.Write(System.Int32%2cSystem.Int32%2cArcGIS.Core.Data.Raster.PixelBlock)" data-throw-if-not-resolved="false"></xref> method.
For a small raster dataset, the size of the pixel block can be the size of the entire dataset, which can usually be held in memory at one time.
When working with large raster data, the best practice is to divide the raster into small pixel blocks and read and write these block by block
using the <xref href="ArcGIS.Core.Data.Raster.RasterCursor" data-throw-if-not-resolved="false"></xref> Object.</p>


## Members

### Clear(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.PixelBlock.yml" sourcestartlinenumber="1">Sets all values in the given plane to NoData.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Clear(int plane)
```
### GetBytesPerPixel()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.PixelBlock.yml" sourcestartlinenumber="1">Gets the number of bytes per pixel for this pixel block.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int GetBytesPerPixel()
```
### GetHeight()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.PixelBlock.yml" sourcestartlinenumber="1">Gets the height (number of rows) of this pixel block in pixels.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int GetHeight()
```
### GetNoDataMask(int, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.PixelBlock.yml" sourcestartlinenumber="1">Gets the NoData mask for the given plane from this pixel block.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Array GetNoDataMask(int plane, bool makeCopy)
```
### GetNoDataMaskValue(int, int, int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.PixelBlock.yml" sourcestartlinenumber="1">Gets the NoData mask value for the given plane, column and row from this pixel block.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public object GetNoDataMaskValue(int plane, int x, int y)
```
### GetPixelData(int, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.PixelBlock.yml" sourcestartlinenumber="1">Gets a 2-dimensional array of pixels from this pixel block based on the given plane.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Array GetPixelData(int plane, bool makeCopy)
```
### GetPixelType(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.PixelBlock.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Raster.RasterPixelType" data-throw-if-not-resolved="false"></xref> of this pixel block.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RasterPixelType GetPixelType(int plane)
```
### GetPlaneCount()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.PixelBlock.yml" sourcestartlinenumber="1">Gets the number of planes (bands) in this pixel block.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int GetPlaneCount()
```
### GetValue(int, int, int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.PixelBlock.yml" sourcestartlinenumber="1">Gets the pixel value for the given plane, column and row from this pixel block.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public object GetValue(int plane, int x, int y)
```
### GetWidth()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.PixelBlock.yml" sourcestartlinenumber="1">Gets the width (number of columns) of this pixel block in pixels.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int GetWidth()
```
### HasData()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.PixelBlock.yml" sourcestartlinenumber="1">Gets a value indicating whether this pixel block has any data pixels.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool HasData()
```
### HasNoData(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.PixelBlock.yml" sourcestartlinenumber="1">Gets a value indicating whether the given plane from this pixel block has any NoData pixels.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool HasNoData(int plane)
```
### SetNoDataMask(int, Array)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.PixelBlock.yml" sourcestartlinenumber="1">Sets the NoData mask for the given plane from this pixel block.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetNoDataMask(int plane, Array noData)
```
### SetPixelData(int, Array)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.PixelBlock.yml" sourcestartlinenumber="1">Sets an array of pixels to this pixel block based on the given plane.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetPixelData(int plane, Array data)
```


