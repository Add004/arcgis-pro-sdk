# RasterImageryOptions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Gets and sets the application raster and imagery options.</p>


## Object Signature

```csharp
public class RasterImageryOptions
```


## Members

### DefaultBackgroundColor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Gets the application default raster background color.</p>


```csharp
public CIMColor DefaultBackgroundColor { get; }
```
### DefaultNoDataColor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Gets the application default raster NoData color.</p>


```csharp
public CIMColor DefaultNoDataColor { get; }
```
### Get3BandColor()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Get the three band composition.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public (int r, int g, int b) Get3BandColor()
```
### GetBackgroundColor()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Gets the raster background color.<br>
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMColor GetBackgroundColor()
```
### GetBackgroundValue()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Gets the RGB values used to indicate the background value.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public (double red, double green, double blue) GetBackgroundValue()
```
### GetClassifyColorRamp()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Gets the color ramp used for the classify symbology type.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMColorRamp GetClassifyColorRamp()
```
### GetClassifyColorRampName()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Gets the name of the color ramp used for the classify symbology type.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetClassifyColorRampName()
```
### GetClipPercentage()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Gets the minimum and maximum clip percentages.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public (double minValue, double maxValue) GetClipPercentage()
```
### GetCreateTiledTiff()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Gets if tiled TIFF files are to be created.<br>
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool GetCreateTiledTiff()
```
### GetDiscreteColorRamp()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Gets the color ramp used for the discrete symbology type.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMColorRamp GetDiscreteColorRamp()
```
### GetDiscreteColorRampName()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Gets the name of the color ramp used for the discrete symbology type.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetDiscreteColorRampName()
```
### GetDisplayBackground()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Gets if the background value of the raster dataset is to be displayed.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool GetDisplayBackground()
```
### GetEnableCustomColorSchemes()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Gets the setting that allows you to set custom color schemes.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool GetEnableCustomColorSchemes()
```
### GetEnableCustomRenderingDefaults()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Gets the setting that allows you to set custom rendering defaults.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool GetEnableCustomRenderingDefaults()
```
### GetGammaStretchValueBlue()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Gets the gamma stretch blue value.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double GetGammaStretchValueBlue()
```
### GetGammaStretchValueGreen()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Gets the gamma stretch green value.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double GetGammaStretchValueGreen()
```
### GetGammaStretchValueRed()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Gets the gamma stretch red value.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double GetGammaStretchValueRed()
```
### GetIsMosaicBoundaryVisible()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Gets if the boundary of the dataset is to be displayed in the map.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool GetIsMosaicBoundaryVisible()
```
### GetIsMosaicFootprintVisible()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Gets if the footprints of each raster within the dataset are to be displayed in the map.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool GetIsMosaicFootprintVisible()
```
### GetIsMosaicLayerExpanded()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Gets if a mosaic layer is to be expanded in the TOC.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool GetIsMosaicLayerExpanded()
```
### GetIsMosaicPreviewVisible()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Gets if the mosaic layer is to be shown in the map.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool GetIsMosaicPreviewVisible()
```
### GetIsMosaicSeamlinesVisible()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Gets if seamlines are to be displayed in the map.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool GetIsMosaicSeamlinesVisible()
```
### GetIsMultidimensionalDatasetTiledForTimeSeries()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Gets if a multidimensional dataset is to be tiled for pixel time series access.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool GetIsMultidimensionalDatasetTiledForTimeSeries()
```
### GetMSColor()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Gets the multispectral data band composition.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public (int r, int g, int b) GetMSColor()
```
### GetMaximumUniqueValues()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Gets the maximum number of values to display.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int GetMaximumUniqueValues()
```
### GetNoDataColor()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Gets the raster NoData color.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMColor GetNoDataColor()
```
### GetNumberOfStandardDeviation()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Gets the number of standard deviations.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double GetNumberOfStandardDeviation()
```
### GetProxyFileLocation()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Gets the proxy file location.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetProxyFileLocation()
```
### GetPyramidCompressionMethod()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Gets the compression type used when building the raster pyramids.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public PyramidCompressionType GetPyramidCompressionMethod()
```
### GetPyramidCompressionQuality()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Gets the pyramid compression quality used when pyramids are built with the <xref href="ArcGIS.Desktop.Core.PyramidCompressionType.JPEG" data-throw-if-not-resolved="false"></xref> or
<xref href="ArcGIS.Desktop.Core.PyramidCompressionType.JPEG_YCbCr" data-throw-if-not-resolved="false"></xref> compression methods.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int GetPyramidCompressionQuality()
```
### GetPyramidOption()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Gets the build pyramid option; that is how to handle raster dataset that do not have pyramids built.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public BuildPyramidOption GetPyramidOption()
```
### GetPyramidResampleMethod()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Gets the resanmpling method used when building pyramids.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public PyramidResamplingMode GetPyramidResampleMethod()
```
### GetResampleType()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Gets the resampling method.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RasterResamplingType GetResampleType()
```
### GetSkipFactorX()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Gets the X skip factor. That is the number of horizontal pixels between samples.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int GetSkipFactorX()
```
### GetSkipFactorY()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Gets the Y skip factor. That is the number of vertical pixels between samples.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int GetSkipFactorY()
```
### GetStatisticsOption()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Gets the calculate statistics option; that is how to handle raster datasets that do not have statistics calculated.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CalculateStatisticOption GetStatisticsOption()
```
### GetStretchType()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Gets the stretch type.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RasterStretchType GetStretchType()
```
### GetStretchedColorRamp()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Gets the color ramp used for the stretched symbology type.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMColorRamp GetStretchedColorRamp()
```
### GetStretchedColorRampName()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Gets the name of the color ramp used for the stretched symbology type.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetStretchedColorRampName()
```
### GetUniqueValueColorRamp()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Gets the color ramp used for the unique value symbology type.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMColorRamp GetUniqueValueColorRamp()
```
### GetUniqueValueColorRampName()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Gets the name of the color ramp used for the unique value symbology type.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetUniqueValueColorRampName()
```
### GetUseFirstPerspectiveImageryLayer()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Gets if the application will work in the perspective view when an appropriate layers is added to a map.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool GetUseFirstPerspectiveImageryLayer()
```
### GetUseImageServiceCache()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Gets the value indicating if an image service cache should be displayed rather than the image service (if it has a cache generated).
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool GetUseImageServiceCache()
```
### GetUseWavelengthInformation()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Gets the use band wavelength information setting.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool GetUseWavelengthInformation()
```
### GetUseWorldFile()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Gets if the raster dataset's native georeferencing should be overridden with the world file information.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool GetUseWorldFile()
```
### GetValidColorRampCategories()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Gets the set of color ramp categories that are valid for the raster settings.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<string> GetValidColorRampCategories()
```
### Set3BandColor(int, int, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Sets the three band composition.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Set3BandColor(int r, int g, int b)
```
### SetBackgroundColor(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Sets the raster background color.  Use <xref href="ArcGIS.Desktop.Core.RasterImageryOptions.SetDisplayBackground(System.Boolean)" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Desktop.Core.RasterImageryOptions.SetBackgroundValue(System.Double%2cSystem.Double%2cSystem.Double)" data-throw-if-not-resolved="false"></xref>
to display the background value.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetBackgroundColor(CIMColor backgroundColor)
```
### SetBackgroundValue(double, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Sets the RGB values for the background value.  Use <xref href="ArcGIS.Desktop.Core.RasterImageryOptions.SetDisplayBackground(System.Boolean)" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Desktop.Core.RasterImageryOptions.SetBackgroundColor(ArcGIS.Core.CIM.CIMColor)" data-throw-if-not-resolved="false"></xref>
to display the background value.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetBackgroundValue(double red, double green, double blue)
```
### SetClassifyColorRampName(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Sets the name of the color ramp used for the classify symbology type.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetClassifyColorRampName(string colorRamp)
```
### SetClipPercentage(double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Sets the minimum and maximum clip percentages.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetClipPercentage(double minValue, double maxValue)
```
### SetCreateTiledTiff(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Sets if tiled TIFF files are to be created.<br>
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetCreateTiledTiff(bool tiled)
```
### SetDiscreteColorRampName(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Sets the name of the color ramp used for the discrete symbology type.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDiscreteColorRampName(string colorRamp)
```
### SetDisplayBackground(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Sets if the background value of the raster dataset is to be displayed. Use <xref href="ArcGIS.Desktop.Core.RasterImageryOptions.SetBackgroundValue(System.Double%2cSystem.Double%2cSystem.Double)" data-throw-if-not-resolved="false"></xref>
and <xref href="ArcGIS.Desktop.Core.RasterImageryOptions.SetBackgroundColor(ArcGIS.Core.CIM.CIMColor)" data-throw-if-not-resolved="false"></xref> to define the background value and the color.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDisplayBackground(bool displayBackground)
```
### SetEnableCustomColorSchemes(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Sets the custom color scheme setting.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetEnableCustomColorSchemes(bool enableCustomColorSchemes)
```
### SetEnableCustomRenderingDefaults(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Sets the custom rendering setting.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetEnableCustomRenderingDefaults(bool enableCustomRendering)
```
### SetGammaStretchValueBlue(double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Sets the gamma stretch blue value.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetGammaStretchValueBlue(double value)
```
### SetGammaStretchValueGreen(double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Sets the gamma stretch green value.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetGammaStretchValueGreen(double value)
```
### SetGammaStretchValueRed(double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Sets the gamma stretch red value.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetGammaStretchValueRed(double value)
```
### SetIsMosaicBoundaryVisible(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Sets if the boundary of the dataset is to be displayed in the map.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetIsMosaicBoundaryVisible(bool isVisible)
```
### SetIsMosaicFootprintVisible(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Sets if the footprints of each raster within the dataset are to be displayed in the map.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetIsMosaicFootprintVisible(bool isVisible)
```
### SetIsMosaicLayerExpanded(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Sets if a mosaic layer is to be expanded in the TOC.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetIsMosaicLayerExpanded(bool isExpanded)
```
### SetIsMosaicPreviewVisible(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Sets if the mosaic layer is to be shown in the map. Set this to false to improve performance if it is not necessary to immediately
see your imagery or raster dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetIsMosaicPreviewVisible(bool isVisible)
```
### SetIsMosaicSeamlinesVisible(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Sets if seamlines are to be displayed in the map.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetIsMosaicSeamlinesVisible(bool isVisible)
```
### SetIsMultidimensionalDatasetTiledForTimeSeries(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Sets if a multidimensional dataset is to be tiled for pixel time series access.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetIsMultidimensionalDatasetTiledForTimeSeries(bool isTiled)
```
### SetMSColor(int, int, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Sets the multispectral data band composition.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetMSColor(int r, int g, int b)
```
### SetMaximumUniqueValues(int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Sets the maximum number of unique values to display.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetMaximumUniqueValues(int maximum)
```
### SetNoDataColor(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Sets the raster NoData color.<br>
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetNoDataColor(CIMColor noDataColor)
```
### SetNumberOfStandardDeviation(double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Sets the number of standard deviations.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetNumberOfStandardDeviation(double value)
```
### SetProxyFileLocation(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Sets the proxy file location.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetProxyFileLocation(string path)
```
### SetPyramidCompressionMethod(PyramidCompressionType)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Sets the compression type used when building the raster pyramids.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetPyramidCompressionMethod(PyramidCompressionType compressionType)
```
### SetPyramidCompressionQuality(int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Sets the pyramid compression quality.<br>
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetPyramidCompressionQuality(int value)
```
### SetPyramidOption(BuildPyramidOption)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Sets the build pyramid option for handling raster datasets that do not have pyramids built.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetPyramidOption(BuildPyramidOption option)
```
### SetPyramidResampleMethod(PyramidResamplingMode)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Sets the resampling method used when building pyramids.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetPyramidResampleMethod(PyramidResamplingMode resamplingMode)
```
### SetResampleType(RasterResamplingType)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Sets the resampling method.  Must be one of <xref href="ArcGIS.Core.CIM.RasterResamplingType.NearestNeighbor" data-throw-if-not-resolved="false"></xref>, <xref href="ArcGIS.Core.CIM.RasterResamplingType.BilinearInterpolation" data-throw-if-not-resolved="false"></xref>
or <xref href="ArcGIS.Core.CIM.RasterResamplingType.CubicConvolution" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetResampleType(RasterResamplingType resampleType)
```
### SetSkipFactorX(int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Sets the X skip factor. That is the number of horizontal pixels between samples.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetSkipFactorX(int skipfactorX)
```
### SetSkipFactorY(int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Sets the Y skip factor. That is the number of vertical pixels between samples.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetSkipFactorY(int skipfactorY)
```
### SetStatisticsOption(CalculateStatisticOption)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Sets the calculate statistics option; that is how to handle raster datasets that do not have statistics calculated.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetStatisticsOption(CalculateStatisticOption option)
```
### SetStretchType(RasterStretchType)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Sets the stretch type.  Must be one of <xref href="ArcGIS.Core.CIM.RasterStretchType.None" data-throw-if-not-resolved="false"></xref>, <xref href="ArcGIS.Core.CIM.RasterStretchType.StandardDeviations" data-throw-if-not-resolved="false"></xref>,
<xref href="ArcGIS.Core.CIM.RasterStretchType.MinimumMaximum" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Core.CIM.RasterStretchType.PercentMinimumMaximum" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetStretchType(RasterStretchType stretchType)
```
### SetStretchedColorRampName(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Sets the name of the color ramp used for the stretched symbology type.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetStretchedColorRampName(string colorRamp)
```
### SetUniqueValueColorRampName(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Sets the name of the color ramp used for the unique value symbology type.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetUniqueValueColorRampName(string colorRamp)
```
### SetUseFirstPerspectiveImageryLayer(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Sets if the application will work in the perspective view when an appropriate layers is added to a map.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetUseFirstPerspectiveImageryLayer(bool usePerspectiveView)
```
### SetUseImageServiceCache(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Sets the value indicating if an image service cache should be displayed rather than the image service (if it has a cache generated).
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetUseImageServiceCache(bool useCache)
```
### SetUseWavelengthInformation(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Sets the use band wavelength information setting.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetUseWavelengthInformation(bool useWaveLengthInformation)
```
### SetUseWorldFile(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.RasterImageryOptions.yml" sourcestartlinenumber="1">Sets if the raster dataset's native georeferencing should be overridden with the world file information.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetUseWorldFile(bool useWorldFile)
```


