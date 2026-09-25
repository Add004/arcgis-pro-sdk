# RasterStorageDef

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Raster.html">Raster</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterStorageDef.yml" sourcestartlinenumber="1">Represents the parameters to control raster storage properties.</p>


## Object Signature

```csharp
public sealed class RasterStorageDef : CoreObjectsBase, IDisposable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterStorageDef.yml" sourcestartlinenumber="1">The RasterStorageDef instructs the database to store the raster dataset in certain way,
for example using a certain tile size, cell size, origin, compression, and pyramid option.
Only cell size and origin are applicable for Personal and File geodatabases.</p>


## Members

### RasterStorageDef()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterStorageDef.yml" sourcestartlinenumber="1">Default constructor</p>


```csharp
public RasterStorageDef()
```
### GetCellSize()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterStorageDef.yml" sourcestartlinenumber="1">Gets the cell size of the raster to be stored from this raster storage definition.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Tuple<double, double> GetCellSize()
```
### GetCompressionQuality()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterStorageDef.yml" sourcestartlinenumber="1">Gets the compression quality of the raster to be stored from this raster storage definition.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int GetCompressionQuality()
```
### GetCompressionType()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterStorageDef.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Raster.RasterCompressionType" data-throw-if-not-resolved="false"></xref> of the raster to be stored from this raster storage definition.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RasterCompressionType GetCompressionType()
```
### GetOrigin()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterStorageDef.yml" sourcestartlinenumber="1">Gets the origin of the enterprise geodatabase raster to be stored from this raster storage definition.</p>


```csharp
public MapPoint GetOrigin()
```
### GetPyramidLevel()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterStorageDef.yml" sourcestartlinenumber="1">Gets the number of pyramid levels to be built from this raster storage definition.</p>


```csharp
public int GetPyramidLevel()
```
### GetPyramidResampleType()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterStorageDef.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.CIM.RasterResamplingType" data-throw-if-not-resolved="false"></xref> to use to build pyramids from this raster storage definition.</p>


```csharp
public RasterResamplingType GetPyramidResampleType()
```
### GetTileHeight()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterStorageDef.yml" sourcestartlinenumber="1">Gets the tile height of the raster to be stored from this raster storage definition.</p>


```csharp
public int GetTileHeight()
```
### GetTileWidth()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterStorageDef.yml" sourcestartlinenumber="1">Gets the tile width of the raster to be stored from this raster storage definition.</p>


```csharp
public int GetTileWidth()
```
### SetCellSize(double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterStorageDef.yml" sourcestartlinenumber="1">Sets the cell size of the raster to be stored on this raster storage definition.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetCellSize(double x, double y)
```
### SetCompressionQuality(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterStorageDef.yml" sourcestartlinenumber="1">Sets the compression quality of the raster to be stored on this raster storage definition.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetCompressionQuality(int quality)
```
### SetCompressionType(RasterCompressionType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterStorageDef.yml" sourcestartlinenumber="1">Sets the <xref href="ArcGIS.Core.Data.Raster.RasterCompressionType" data-throw-if-not-resolved="false"></xref> of the raster to be stored on this raster storage definition.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetCompressionType(RasterCompressionType compression)
```
### SetOrigin(MapPoint)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterStorageDef.yml" sourcestartlinenumber="1">Sets the origin of the enterprise geodatabase raster to be stored on this raster storage definition.</p>


```csharp
public void SetOrigin(MapPoint origin)
```
### SetPyramidLevel(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterStorageDef.yml" sourcestartlinenumber="1">Sets the number of pyramid levels to be built on this raster storage definition.</p>


```csharp
public void SetPyramidLevel(int level)
```
### SetPyramidResampleType(RasterResamplingType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterStorageDef.yml" sourcestartlinenumber="1">Sets the <xref href="ArcGIS.Core.CIM.RasterResamplingType" data-throw-if-not-resolved="false"></xref> to use to build pyramids on this raster storage definition.</p>


```csharp
public void SetPyramidResampleType(RasterResamplingType resampling)
```
### SetTileHeight(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterStorageDef.yml" sourcestartlinenumber="1">Sets the tile height of the raster to be stored on this raster storage definition.</p>


```csharp
public void SetTileHeight(int height)
```
### SetTileWidth(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterStorageDef.yml" sourcestartlinenumber="1">Sets the tile width of the raster to be stored on this raster storage definition.</p>


```csharp
public void SetTileWidth(int width)
```


