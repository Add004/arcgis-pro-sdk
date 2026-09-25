# RasterDatasetDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Raster.html">Raster</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterDatasetDefinition.yml" sourcestartlinenumber="1">Represents the properties of a <xref href="ArcGIS.Core.Data.Raster.RasterDataset" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class RasterDatasetDefinition : Definition, IDisposable
```


## Members

### DatasetType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterDatasetDefinition.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.DatasetType" data-throw-if-not-resolved="false"></xref> of the raster dataset.</p>


```csharp
public override DatasetType DatasetType { get; }
```
### GetBandCount()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterDatasetDefinition.yml" sourcestartlinenumber="1">Gets the number of bands in the raster dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int GetBandCount()
```
### GetCompressionType()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterDatasetDefinition.yml" sourcestartlinenumber="1">Gets the compression type of this raster dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetCompressionType()
```
### GetExtent()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterDatasetDefinition.yml" sourcestartlinenumber="1">Gets the extent of the raster dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Envelope GetExtent()
```
### GetFormat()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterDatasetDefinition.yml" sourcestartlinenumber="1">Gets the format of the raster dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetFormat()
```
### GetSpatialReference()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterDatasetDefinition.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Geometry.SpatialReference" data-throw-if-not-resolved="false"></xref> of the raster dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SpatialReference GetSpatialReference()
```


