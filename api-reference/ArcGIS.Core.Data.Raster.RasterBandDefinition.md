# RasterBandDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Raster.html">Raster</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterBandDefinition.yml" sourcestartlinenumber="1">Represents the properties of a <xref href="ArcGIS.Core.Data.Raster.RasterBand" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class RasterBandDefinition : Definition, IDisposable
```


## Members

### DatasetType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterBandDefinition.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.DatasetType" data-throw-if-not-resolved="false"></xref> of the raster band.</p>


```csharp
public override DatasetType DatasetType { get; }
```
### GetExtent()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterBandDefinition.yml" sourcestartlinenumber="1">Gets the extent of the raster band.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Envelope GetExtent()
```
### GetHeight()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterBandDefinition.yml" sourcestartlinenumber="1">Gets the height (number of rows) of the raster band.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int GetHeight()
```
### GetMeanCellSize()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterBandDefinition.yml" sourcestartlinenumber="1">Gets the mean cell size of the raster band.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Tuple<double, double> GetMeanCellSize()
```
### GetNoDataValue()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterBandDefinition.yml" sourcestartlinenumber="1">Gets the NoData value of the raster band.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public object GetNoDataValue()
```
### GetPixelType()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterBandDefinition.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Raster.RasterPixelType" data-throw-if-not-resolved="false"></xref> of the raster band.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RasterPixelType GetPixelType()
```
### GetSpatialReference()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterBandDefinition.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Geometry.SpatialReference" data-throw-if-not-resolved="false"></xref> of the raster band.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SpatialReference GetSpatialReference()
```
### GetWidth()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterBandDefinition.yml" sourcestartlinenumber="1">Gets the width (number of columns) of the raster band.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int GetWidth()
```
### IsInteger()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterBandDefinition.yml" sourcestartlinenumber="1">Gets a flag indicating whether the data in the raster band is integer data.</p>


```csharp
public bool IsInteger()
```


