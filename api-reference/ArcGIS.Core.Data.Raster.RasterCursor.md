# RasterCursor

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Raster.html">Raster</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterCursor.yml" sourcestartlinenumber="1">Represents a cursor that provides optimized raster access.</p>


## Object Signature

```csharp
public sealed class RasterCursor : CoreObjectsBase, IDisposable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterCursor.yml" sourcestartlinenumber="1">The RasterCursor controls enumeration through the PixelBlocks in a Raster. It is useful for rasters
that are too large to be brought into memory at once.</p>


## Members

### Current

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterCursor.yml" sourcestartlinenumber="1">Gets the current <xref href="ArcGIS.Core.Data.Raster.PixelBlock" data-throw-if-not-resolved="false"></xref> of this <xref href="ArcGIS.Core.Data.Raster.RasterCursor" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public PixelBlock Current { get; }
```
### GetTopLeft()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterCursor.yml" sourcestartlinenumber="1">Gets the x and y offsets (in pixels) of the top left corner of the current <xref href="ArcGIS.Core.Data.Raster.PixelBlock" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Tuple<int, int> GetTopLeft()
```
### MoveNext()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterCursor.yml" sourcestartlinenumber="1">Advances to the next <xref href="ArcGIS.Core.Data.Raster.PixelBlock" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool MoveNext()
```
### Reset()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterCursor.yml" sourcestartlinenumber="1">Resets this <xref href="ArcGIS.Core.Data.Raster.RasterCursor" data-throw-if-not-resolved="false"></xref> to its original state, i.e. to the beginning of the raster it was created from.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Reset()
```


