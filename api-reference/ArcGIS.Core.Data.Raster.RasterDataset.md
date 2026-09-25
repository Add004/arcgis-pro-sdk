# RasterDataset

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Raster.html">Raster</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterDataset.yml" sourcestartlinenumber="1">Represents a raster dataset on disk or in a geodatabase.</p>


## Object Signature

```csharp
public class RasterDataset : BasicRasterDataset, IDisposable
```


## Members

### CreateFullRaster()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterDataset.yml" sourcestartlinenumber="1">Creates a <xref href="ArcGIS.Core.Data.Raster.Raster" data-throw-if-not-resolved="false"></xref> that has the same properties and all the bands in this raster dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Raster CreateFullRaster()
```
### CreateRaster(IEnumerable&lt;int&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterDataset.yml" sourcestartlinenumber="1">Creates a <xref href="ArcGIS.Core.Data.Raster.Raster" data-throw-if-not-resolved="false"></xref> that has the same properties and the given list of bands from this raster dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Raster CreateRaster(IEnumerable<int> bandIDs)
```
### GetBand(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterDataset.yml" sourcestartlinenumber="1">Gets a <xref href="ArcGIS.Core.Data.Raster.RasterBand" data-throw-if-not-resolved="false"></xref> from this raster dataset based on the band index.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RasterBand GetBand(int index)
```
### GetBandByName(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterDataset.yml" sourcestartlinenumber="1">Gets a <xref href="ArcGIS.Core.Data.Raster.RasterBand" data-throw-if-not-resolved="false"></xref> from this raster dataset based on the band name.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RasterBand GetBandByName(string name)
```
### GetBandCount()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterDataset.yml" sourcestartlinenumber="1">Gets the number of bands in this raster dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int GetBandCount()
```
### GetBandIndex(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterDataset.yml" sourcestartlinenumber="1">Gets the index for a band in this raster dataset based on the band name.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int GetBandIndex(string name)
```
### GetBandKeyProperty(int, string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterDataset.yml" sourcestartlinenumber="1">Gets a key property for a band in this raster dataset based on band index and key property name.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public object GetBandKeyProperty(int bandIndex, string name)
```
### GetDefinition()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterDataset.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Raster.RasterDatasetDefinition" data-throw-if-not-resolved="false"></xref> of this raster dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RasterDatasetDefinition GetDefinition()
```
### GetExtent()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterDataset.yml" sourcestartlinenumber="1">Gets the extent of this raster dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Envelope GetExtent()
```
### GetKeyProperty(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterDataset.yml" sourcestartlinenumber="1">Gets a key property of this raster dataset based on the key property name.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public object GetKeyProperty(string name)
```
### IsEmpty()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterDataset.yml" sourcestartlinenumber="1">Gets a value indicating whether this raster dataset is empty.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool IsEmpty()
```
### Type

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterDataset.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.DatasetType" data-throw-if-not-resolved="false"></xref> of this raster dataset.</p>


```csharp
public override DatasetType Type { get; }
```


