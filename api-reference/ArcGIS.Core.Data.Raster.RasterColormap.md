# RasterColormap

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Raster.html">Raster</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterColormap.yml" sourcestartlinenumber="1">Represents a raster colormap.</p>


## Object Signature

```csharp
public sealed class RasterColormap : CoreObjectsBase, IDisposable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterColormap.yml" sourcestartlinenumber="1">A color map is a set of values that are associated with colors. Color maps are used to
display a single-band raster consistently with the same colors. Each pixel value is
associated with a color. The color values are stored as an array of integers, each integer
representing a color (OLE color). To convert the OLE color value into a <xref href="System.Drawing.Color" data-throw-if-not-resolved="false"></xref>
to acces the rgb values, use the <xref href="System.Drawing.ColorTranslator.FromOle(System.Int32)" data-throw-if-not-resolved="false"></xref> method.
Color maps are capable of supporting any bit depth, except FLOAT. They can also support
positive and negative values, and the color maps can contain missing color mapped values.
When displaying a dataset with a color colormap containing missing value, the pixels with
that value will not be displayed.</p>


## Members

### GetColors()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterColormap.yml" sourcestartlinenumber="1">Gets the color values from this colormap.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int[] GetColors()
```
### GetValues()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Raster.RasterColormap.yml" sourcestartlinenumber="1">Gets the pixel values from this colormap.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int[] GetValues()
```


