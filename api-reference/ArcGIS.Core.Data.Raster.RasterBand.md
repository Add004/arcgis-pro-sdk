# RasterBand

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Raster.html">Raster</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterBand.yml" sourcestartlinenumber="1">Represents a single band of a <xref href="ArcGIS.Core.Data.Raster.RasterDataset" data-throw-if-not-resolved="false"></xref></p>


## Object Signature

```csharp
public sealed class RasterBand : BasicRasterDataset, IDisposable
```


## Members

### GetAttributeTable()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterBand.yml" sourcestartlinenumber="1">Gets the attribute table of this raster band.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Table GetAttributeTable()
```
### GetColormap()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterBand.yml" sourcestartlinenumber="1">Gets the colormap of this raster band.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RasterColormap GetColormap()
```
### GetDefinition()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterBand.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Raster.RasterBandDefinition" data-throw-if-not-resolved="false"></xref> of this raster band.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RasterBandDefinition GetDefinition()
```
### GetExtent()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterBand.yml" sourcestartlinenumber="1">Gets the extent of this raster band.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Envelope GetExtent()
```
### HasAttributeTable()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterBand.yml" sourcestartlinenumber="1">Gets a value indicating whether this raster band has an attribute table.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool HasAttributeTable()
```
### HasColormap()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterBand.yml" sourcestartlinenumber="1">Gets a value indicating whether this raster band has a colormap.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool HasColormap()
```
### Type

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterBand.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.DatasetType" data-throw-if-not-resolved="false"></xref> of this raster band.</p>


```csharp
public override DatasetType Type { get; }
```


