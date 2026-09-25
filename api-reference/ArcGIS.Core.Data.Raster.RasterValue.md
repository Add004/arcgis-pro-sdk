# RasterValue

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Raster.html">Raster</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterValue.yml" sourcestartlinenumber="1">Represents a raster value.</p>


## Object Signature

```csharp
public sealed class RasterValue : CoreObjectsBase, IDisposable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterValue.yml" sourcestartlinenumber="1">A RasterValue represents the value of a Raster field, similar to the value of a Geometry field. It allows you
to set a raster dataset and store it using storage properties.</p>


## Members

### RasterValue()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterValue.yml" sourcestartlinenumber="1">Default constructor</p>


```csharp
public RasterValue()
```
### GetRasterDataset()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterValue.yml" sourcestartlinenumber="1">Gets the raster dataset of this raster value.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RasterDataset GetRasterDataset()
```
### GetRasterStorageDef()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterValue.yml" sourcestartlinenumber="1">Gets the raster storage properties of this raster value.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RasterStorageDef GetRasterStorageDef()
```
### SetRasterDataset(RasterDataset)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterValue.yml" sourcestartlinenumber="1">Sets the raster dataset of this raster value.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetRasterDataset(RasterDataset rasterDataset)
```
### SetRasterStorageDef(RasterStorageDef)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterValue.yml" sourcestartlinenumber="1">Sets the raster storage properties of this raster value.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetRasterStorageDef(RasterStorageDef storageDef)
```


