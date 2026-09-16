# BasicRasterDataset

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Raster.html">Raster</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Raster.BasicRasterDataset.yml" sourcestartlinenumber="1">Represents a basic raster dataset from a specific <xref href="ArcGIS.Core.Data.Datastore" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public abstract class BasicRasterDataset : Dataset, IDisposable
```


## Members

### CreateDefaultRaster()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.BasicRasterDataset.yml" sourcestartlinenumber="1">Creates a <xref href="ArcGIS.Core.Data.Raster.Raster" data-throw-if-not-resolved="false"></xref> that has the same properties of this basic raster dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Raster CreateDefaultRaster()
```
### GetCompleteName()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.BasicRasterDataset.yml" sourcestartlinenumber="1">Gets the complete name of this raster dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetCompleteName()
```


