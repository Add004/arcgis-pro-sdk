# MosaicDataset

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Raster.html">Raster</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Raster.MosaicDataset.yml" sourcestartlinenumber="1">Represents a mosaic dataset on disk or in a geodatabase.</p>


## Object Signature

```csharp
public sealed class MosaicDataset : FunctionRasterDataset, IDisposable
```


## Members

### GetBoundary()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.MosaicDataset.yml" sourcestartlinenumber="1">Gets the Boundary table of this mosaic dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public FeatureClass GetBoundary()
```
### GetCatalog()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.MosaicDataset.yml" sourcestartlinenumber="1">Gets the Catalog (Footprint) table of this mosaic dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public FeatureClass GetCatalog()
```
### GetDefinition()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.MosaicDataset.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Raster.MosaicDatasetDefinition" data-throw-if-not-resolved="false"></xref> of this mosaic dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public MosaicDatasetDefinition GetDefinition()
```
### GetSeamline()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.MosaicDataset.yml" sourcestartlinenumber="1">Gets the Seamline table of this mosaic dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public FeatureClass GetSeamline()
```
### GetStereoTable()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.MosaicDataset.yml" sourcestartlinenumber="1">Gets the Stereo table of this mosaic dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public FeatureClass GetStereoTable()
```
### Type

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Raster.MosaicDataset.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.DatasetType" data-throw-if-not-resolved="false"></xref> of this mosaic dataset.</p>


```csharp
public override DatasetType Type { get; }
```


