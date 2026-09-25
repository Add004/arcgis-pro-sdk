# Geoprocessing

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.Geoprocessing.html">Geoprocessing</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.Geoprocessing.yml" sourcestartlinenumber="1">Geoprocessing helper class</p>


## Object Signature

```csharp
public static class Geoprocessing
```


## Members

### ExecuteToolAsync(string, IEnumerable&lt;string&gt;, IEnumerable&lt;KeyValuePair&lt;string, string&gt;&gt;, CancelableProgressor, GPExecuteToolFlags)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.Geoprocessing.yml" sourcestartlinenumber="1">Locks application and executes a geoprocessing tool.</p>


```csharp
public static Task<IGPResult> ExecuteToolAsync(string toolPath, IEnumerable<string> values, IEnumerable<KeyValuePair<string, string>> environments, CancelableProgressor progressor, GPExecuteToolFlags flags = GPExecuteToolFlags.Default)
```
### ExecuteToolAsync(string, IEnumerable&lt;string&gt;, IEnumerable&lt;KeyValuePair&lt;string, string&gt;&gt;, CancellationToken?, GPToolExecuteEventHandler, GPExecuteToolFlags)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.Geoprocessing.yml" sourcestartlinenumber="1">Executes a geoprocessing tool.</p>


```csharp
public static Task<IGPResult> ExecuteToolAsync(string toolPath, IEnumerable<string> values, IEnumerable<KeyValuePair<string, string>> environments = null, CancellationToken? cancelToken = null, GPToolExecuteEventHandler callback = null, GPExecuteToolFlags flags = GPExecuteToolFlags.Default)
```
### HistoryContainerKey

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.Geoprocessing.yml" sourcestartlinenumber="1">Gets the name of the History item container key</p>


```csharp
public const string HistoryContainerKey = "GPHistory"
```
### MakeEnvironmentArray(object, object, object, object, object, object, object, object, int?, object, int?, object, object, object, object, object, object, int?, bool?, bool?, bool?, bool?, bool?, bool?, object, object, object, object, object, double?, double?, object, double?, object, object, object, object, object, double?, object, int?, object, object, object, object, object, object, bool?, object, object, object, object, int?, string, string, object, bool?, bool?, object, object, bool?, bool?, bool?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.Geoprocessing.yml" sourcestartlinenumber="1">Helper function to create environment array, use named argument to set individual value. For more information regarding geoprocessing environments, please refer to <a href="https://pro.arcgis.com/en/pro-app/latest/tool-reference/environment-settings/an-overview-of-geoprocessing-environment-settings.htm">An overview of geoprocessing environment settings</a>.</p>


```csharp
public static IReadOnlyList<KeyValuePair<string, string>> MakeEnvironmentArray(object workspace = null, object packageWorkspace = null, object scratchFolder = null, object scratchGDB = null, object scratchWorkspace = null, object outputCoordinateSystem = null, object geographicTransformations = null, object extent = null, int? retryOnFailures = null, object parallelProcessingFactor = null, int? recycleProcessingWorkers = null, object cellAlignment = null, object cellSize = null, object cellSizeProjectionMethod = null, object mask = null, object snapRaster = null, object configKeyword = null, int? autoCommit = null, bool? maintainAttachments = null, bool? maintainSpatialIndex = null, bool? preserveGlobalIds = null, bool? transferGDBAttributeProperties = null, bool? qualifiedFieldNames = null, bool? transferDomains = null, object XYDomain = null, object XYResolution = null, object XYTolerance = null, object MDomain = null, object outputMFlag = null, double? MTolerance = null, double? MResolution = null, object ZDomain = null, double? outputZValue = null, object outputZFlag = null, object ZResolution = null, object ZTolerance = null, object randomGenerator = null, object cartographicCoordinateSystem = null, double? referenceScale = null, object cartographicPartitions = null, int? annotationTextStringFieldLength = null, object pyramid = null, object rasterStatistics = null, object compression = null, object tileSize = null, object resamplingMethod = null, object nodata = null, bool? terrainMemoryUsage = null, object tinSaveVersion = null, object coincidentPoints = null, object S100FeatureCatalogueFile = null, object processorType = null, int? gpuId = null, string processingServer = null, string processingServerUser = null, object processingServerPassword = null, bool? matchMultidimensionalVariable = null, bool? unionDimension = null, object baDataSource = null, object baNetworkSource = null, bool? baUseDetailedAggregation = null, bool? maintainCurveSegments = null, bool? overwriteoutput = null)
```
### MakeValueArray(params object[])

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.Geoprocessing.yml" sourcestartlinenumber="1">Creates a parameter value array from variable number of arguments. Use it in <xref href="ArcGIS.Desktop.Core.Geoprocessing.Geoprocessing.OpenToolDialog(System.String%2cSystem.Collections.Generic.IEnumerable%7bSystem.String%7d%2cSystem.Collections.Generic.IEnumerable%7bSystem.Collections.Generic.KeyValuePair%7bSystem.String%2cSystem.String%7d%7d%2cSystem.Boolean%2cArcGIS.Desktop.Core.Geoprocessing.GPToolExecuteEventHandler)" data-throw-if-not-resolved="false"></xref> and
<xref href="ArcGIS.Desktop.Core.Geoprocessing.Geoprocessing.ExecuteToolAsync(System.String%2cSystem.Collections.Generic.IEnumerable%7bSystem.String%7d%2cSystem.Collections.Generic.IEnumerable%7bSystem.Collections.Generic.KeyValuePair%7bSystem.String%2cSystem.String%7d%7d%2cArcGIS.Desktop.Framework.Threading.Tasks.CancelableProgressor%2cArcGIS.Desktop.Core.Geoprocessing.GPExecuteToolFlags)" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static IReadOnlyList<string> MakeValueArray(params object[] args)
```
### MakeValueString(object)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.Geoprocessing.yml" sourcestartlinenumber="1">Converts a .Net object to string.</p>


```csharp
public static string MakeValueString(object arg)
```
### OpenNotebook()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.Geoprocessing.yml" sourcestartlinenumber="1">Open the notebook</p>


```csharp
public static void OpenNotebook()
```
### OpenToolDialog(string, IEnumerable&lt;string&gt;, IEnumerable&lt;KeyValuePair&lt;string, string&gt;&gt;, bool, GPToolExecuteEventHandler)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.Geoprocessing.yml" sourcestartlinenumber="1">Activate Geoprocessing pane and open the tool dialog in the pane.</p>


```csharp
public static void OpenToolDialog(string toolPath, IEnumerable<string> values, IEnumerable<KeyValuePair<string, string>> environments = null, bool newSubPane = false, GPToolExecuteEventHandler callback = null)
```
### OpenToolDialogAsync(string, IEnumerable&lt;string&gt;, IEnumerable&lt;KeyValuePair&lt;string, string&gt;&gt;, GPToolExecuteEventHandler, GPExecuteToolFlags, GPToolDialogFlags, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.Geoprocessing.yml" sourcestartlinenumber="1">Activate Geoprocessing tool dialog.</p>


```csharp
public static Task<IGPResult> OpenToolDialogAsync(string toolPath, IEnumerable<string> values = null, IEnumerable<KeyValuePair<string, string>> environments = null, GPToolExecuteEventHandler callback = null, GPExecuteToolFlags executeFlags = GPExecuteToolFlags.Default, GPToolDialogFlags dialogFlags = GPToolDialogFlags.Default, string dialogTitle = null)
```
### ShowMessageBox(IEnumerable&lt;IGPMessage&gt;, string, GPMessageBoxStyle, string, string, ViewModelBase)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.Geoprocessing.yml" sourcestartlinenumber="1">Shows a messag box with Geoprocessing messages as formatted for the message box.</p>


```csharp
public static void ShowMessageBox(IEnumerable<IGPMessage> messages, string content_header, GPMessageBoxStyle style, string window_title = null, string icon_source = null, ViewModelBase parentViewModel = null)
```


