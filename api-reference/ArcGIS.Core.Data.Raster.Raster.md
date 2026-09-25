# Raster

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Raster.html">Raster</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Raster.Raster.yml" sourcestartlinenumber="1">Represents an in-memory raster that can perform resampling and reprojection.</p>


## Object Signature

```csharp
public sealed class Raster : CoreObjectsBase, IDisposable
```

## Remarks

<p>The Raster object is a transient representation of raster data that can perform resampling and reprojection. It can 
    be modified without affecting the source data. This allows the raster to represent what you want, as you may 
    specify a projection, extent, and cell size into which the input data will be transformed. This makes the raster 
    quite useful for performing display or analysis in a coordinate system different from that which is stored in 
    the raster dataset. 
    Because of the transient nature of the raster, any modifications that are made to this object will be lost when 
    the object is released. The modified Raster can be persisted to another raster dataset on disk or in a 
    geodatabase using the <xref href="ArcGIS.Core.Data.Raster.Raster.SaveAs(System.String%2cArcGIS.Core.Data.Datastore%2cSystem.String%2cArcGIS.Core.Data.Raster.RasterStorageDef)" data-throw-if-not-resolved="false"></xref> method.
    A Raster is most easily understood as a vehicle to provide resampling, projection, and data type conversion 
    from one or more raster bands to a desired output coordinate system.</p>
<p>A Raster can be obtained in the following ways:</p>
<ol><li>From a <xref href="ArcGIS.Desktop.Mapping.RasterLayer" data-throw-if-not-resolved="false"></xref> using <xref href="ArcGIS.Desktop.Mapping.BasicRasterLayer.GetRaster" data-throw-if-not-resolved="false"></xref> method.</li><li>From a <xref href="ArcGIS.Core.Data.Raster.RasterDataset" data-throw-if-not-resolved="false"></xref> using either <xref href="ArcGIS.Core.Data.Raster.RasterDataset.CreateRaster(System.Collections.Generic.IEnumerable%7bSystem.Int32%7d)" data-throw-if-not-resolved="false"></xref>, <xref href="ArcGIS.Core.Data.Raster.RasterDataset.CreateFullRaster" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Core.Data.Raster.BasicRasterDataset.CreateDefaultRaster" data-throw-if-not-resolved="false"></xref> methods.</li><li>From a <xref href="ArcGIS.Core.Data.Raster.RasterBand" data-throw-if-not-resolved="false"></xref> using the <xref href="ArcGIS.Core.Data.Raster.BasicRasterDataset.CreateDefaultRaster" data-throw-if-not-resolved="false"></xref> method.</li></ol>


## Members

### CanEdit()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.Raster.yml" sourcestartlinenumber="1">Gets a value indicating whether this raster can be edited.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool CanEdit()
```
### CanSaveAs(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.Raster.yml" sourcestartlinenumber="1">Gets a value indicating whether this raster can be saved to the given format.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool CanSaveAs(string format)
```
### CreateCursor(int, int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.Raster.yml" sourcestartlinenumber="1">Create a <xref href="ArcGIS.Core.Data.Raster.RasterCursor" data-throw-if-not-resolved="false"></xref> for optimized access to raster pixels.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RasterCursor CreateCursor(int blockWidth, int blockHeight)
```
### CreatePixelBlock(int, int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.Raster.yml" sourcestartlinenumber="1">Create a <xref href="ArcGIS.Core.Data.Raster.PixelBlock" data-throw-if-not-resolved="false"></xref> of the given width and height.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public PixelBlock CreatePixelBlock(int width, int height)
```
### Erase(int, int, PixelBlock)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.Raster.yml" sourcestartlinenumber="1">Erase a <xref href="ArcGIS.Core.Data.Raster.PixelBlock" data-throw-if-not-resolved="false"></xref> from this raster starting at a given top-left corner.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Erase(int topLeftCornerX, int topLeftCornerY, PixelBlock pixelBlock)
```
### GetAttributeTable()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.Raster.yml" sourcestartlinenumber="1">Gets the attribute table of this raster.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Table GetAttributeTable()
```
### GetBand(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.Raster.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Raster.RasterBand" data-throw-if-not-resolved="false"></xref> from this raster based on the band index.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RasterBand GetBand(int index)
```
### GetBandByName(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.Raster.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Raster.RasterBand" data-throw-if-not-resolved="false"></xref> from this raster based on the band name.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RasterBand GetBandByName(string name)
```
### GetBandCount()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.Raster.yml" sourcestartlinenumber="1">Gets the number of bands in this raster.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int GetBandCount()
```
### GetBandKeyProperty(int, string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.Raster.yml" sourcestartlinenumber="1">Gets a key property for a band in this raster based on band index and key property name.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public object GetBandKeyProperty(int bandIndex, string name)
```
### GetColormap()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.Raster.yml" sourcestartlinenumber="1">Gets the colormap of this raster.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RasterColormap GetColormap()
```
### GetExtent()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.Raster.yml" sourcestartlinenumber="1">Gets the extent of this raster.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Envelope GetExtent()
```
### GetHeight()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.Raster.yml" sourcestartlinenumber="1">Gets the height (number of rows) of this raster.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int GetHeight()
```
### GetKeyProperty(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.Raster.yml" sourcestartlinenumber="1">Gets the key property of the raster based on the key property name.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public object GetKeyProperty(string name)
```
### GetMeanCellSize()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.Raster.yml" sourcestartlinenumber="1">Gets the mean cell size of this raster.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Tuple<double, double> GetMeanCellSize()
```
### GetNoDataValue()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.Raster.yml" sourcestartlinenumber="1">Gets the NoData value of this raster.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public object GetNoDataValue()
```
### GetPixelType()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.Raster.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Raster.RasterPixelType" data-throw-if-not-resolved="false"></xref> of this raster.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RasterPixelType GetPixelType()
```
### GetPixelValue(int, int, int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.Raster.yml" sourcestartlinenumber="1">Gets the pixel value for the given band, row and column from this raster.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public object GetPixelValue(int band, int column, int row)
```
### GetRasterDataset()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.Raster.yml" sourcestartlinenumber="1">Gets the parent raster dataset of this raster.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public BasicRasterDataset GetRasterDataset()
```
### GetResamplingHint()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.Raster.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Raster.RasterResamplingHint" data-throw-if-not-resolved="false"></xref> for this raster.</p>


```csharp
public RasterResamplingHint GetResamplingHint()
```
### GetResamplingType()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.Raster.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.CIM.RasterResamplingType" data-throw-if-not-resolved="false"></xref> for this raster.</p>


```csharp
public RasterResamplingType GetResamplingType()
```
### GetSpatialReference()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.Raster.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Geometry.SpatialReference" data-throw-if-not-resolved="false"></xref> of this raster.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SpatialReference GetSpatialReference()
```
### GetWidth()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.Raster.yml" sourcestartlinenumber="1">Gets the width (number of columns) of this raster.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int GetWidth()
```
### IsInteger()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.Raster.yml" sourcestartlinenumber="1">Gets a flag indicating whether the data in this raster is integer data.</p>


```csharp
public bool IsInteger()
```
### MapToPixel(double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.Raster.yml" sourcestartlinenumber="1">Converts a location in map space (X and Y) to pixel space (Column and Row).
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Tuple<int, int> MapToPixel(double x, double y)
```
### PixelToMap(int, int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.Raster.yml" sourcestartlinenumber="1">Converts a location in pixel space (Column and Row) to map space (X and Y).
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Tuple<double, double> PixelToMap(int column, int row)
```
### Read(int, int, PixelBlock)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.Raster.yml" sourcestartlinenumber="1">Read a <xref href="ArcGIS.Core.Data.Raster.PixelBlock" data-throw-if-not-resolved="false"></xref> starting from the top-left corner.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Read(int topLeftCornerX, int topLeftCornerY, PixelBlock pixelBlock)
```
### Refresh()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.Raster.yml" sourcestartlinenumber="1">Refreshes the properties of the <xref href="ArcGIS.Core.Data.Raster.RasterDataset" data-throw-if-not-resolved="false"></xref> associated with this raster with any changes.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Refresh()
```
### SaveAs(string, Datastore, string, RasterStorageDef)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.Raster.yml" sourcestartlinenumber="1">Create a new persisted <xref href="ArcGIS.Core.Data.Raster.RasterDataset" data-throw-if-not-resolved="false"></xref> with the
given name and format in the given <xref href="ArcGIS.Core.Data.Datastore" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RasterDataset SaveAs(string name, Datastore datastore, string format, RasterStorageDef storageDef = null)
```
### SetExtent(Envelope)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.Raster.yml" sourcestartlinenumber="1">Sets the extent of this raster.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetExtent(Envelope extent)
```
### SetHeight(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.Raster.yml" sourcestartlinenumber="1">Sets the height (number of rows) of this raster.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetHeight(int height)
```
### SetNoDataValue(object)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.Raster.yml" sourcestartlinenumber="1">Sets the NoData value of this raster.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetNoDataValue(object value)
```
### SetPixelType(RasterPixelType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.Raster.yml" sourcestartlinenumber="1">Sets the <xref href="ArcGIS.Core.Data.Raster.RasterPixelType" data-throw-if-not-resolved="false"></xref> of this raster.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetPixelType(RasterPixelType type)
```
### SetResamplingHint(RasterResamplingHint)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.Raster.yml" sourcestartlinenumber="1">Sets the <xref href="ArcGIS.Core.Data.Raster.RasterResamplingHint" data-throw-if-not-resolved="false"></xref> for this raster.</p>


```csharp
public void SetResamplingHint(RasterResamplingHint hint)
```
### SetResamplingType(RasterResamplingType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.Raster.yml" sourcestartlinenumber="1">Sets the <xref href="ArcGIS.Core.CIM.RasterResamplingType" data-throw-if-not-resolved="false"></xref> for this raster.</p>


```csharp
public void SetResamplingType(RasterResamplingType type)
```
### SetSpatialReference(SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.Raster.yml" sourcestartlinenumber="1">Sets the <xref href="ArcGIS.Core.Geometry.SpatialReference" data-throw-if-not-resolved="false"></xref> of this raster.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetSpatialReference(SpatialReference spatialRef)
```
### SetWidth(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.Raster.yml" sourcestartlinenumber="1">Sets the width (number of columns) of this raster.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetWidth(int width)
```
### Write(int, int, PixelBlock)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.Raster.yml" sourcestartlinenumber="1">Write a <xref href="ArcGIS.Core.Data.Raster.PixelBlock" data-throw-if-not-resolved="false"></xref> to this raster starting from the top-left corner.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Write(int topLeftCornerX, int topLeftCornerY, PixelBlock pixelBlock)
```


