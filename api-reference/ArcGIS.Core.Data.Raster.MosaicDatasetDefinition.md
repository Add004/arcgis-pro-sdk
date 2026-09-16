# MosaicDatasetDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Raster.html">Raster</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Raster.MosaicDatasetDefinition.yml" sourcestartlinenumber="1">Represents the properties of a <xref href="ArcGIS.Core.Data.Raster.MosaicDataset" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class MosaicDatasetDefinition : Definition, IDisposable
```


## Members

### DatasetType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Raster.MosaicDatasetDefinition.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.DatasetType" data-throw-if-not-resolved="false"></xref> of the mosaic dataset.</p>


```csharp
public override DatasetType DatasetType { get; }
```
### GetReferenced()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.MosaicDatasetDefinition.yml" sourcestartlinenumber="1">Gets a flag indicating whether the mosaic dataset is a referenced mosaic dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool GetReferenced()
```


