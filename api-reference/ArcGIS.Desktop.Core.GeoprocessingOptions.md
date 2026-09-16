# GeoprocessingOptions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.GeoprocessingOptions.yml" sourcestartlinenumber="1">Gets and sets the available application geoprocessing options.</p>


## Object Signature

```csharp
public class GeoprocessingOptions
```


## Members

### AddOutputDatasetsToOpenMap

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.GeoprocessingOptions.yml" sourcestartlinenumber="1">Gets whether output datasets created by geoprocessing tools should be automatically
added to an open map.</p>


```csharp
public bool AddOutputDatasetsToOpenMap { get; }
```
### AddToTopOfMapContents

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.GeoprocessingOptions.yml" sourcestartlinenumber="1">Add output layers to the top of map contents.</p>


```csharp
public bool AddToTopOfMapContents { get; }
```
### AnalyzeScriptsAndModels

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.GeoprocessingOptions.yml" sourcestartlinenumber="1">Gets whether script and model tools are run through a compatibility-checking routine to ensure they can run successfully.</p>


```csharp
public bool AnalyzeScriptsAndModels { get; }
```
### AutoOpenMessagesWindow

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.GeoprocessingOptions.yml" sourcestartlinenumber="1">Gets whether the messages window will automatically be opened after running a tool in the Geoprocessing pane.</p>


```csharp
public bool AutoOpenMessagesWindow { get; }
```
### DisplayDisabledParameters

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.GeoprocessingOptions.yml" sourcestartlinenumber="1">Gets whether disabled tool parameters are displayed or hidden.  If displayed, they show as readonly.</p>


```csharp
public bool DisplayDisabledParameters { get; }
```
### DisplayShortedDataPaths

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.GeoprocessingOptions.yml" sourcestartlinenumber="1">Gets whether tool parameters that contain a dataset path display shortened names.</p>


```csharp
public bool DisplayShortedDataPaths { get; }
```
### EnableUndoOn

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.GeoprocessingOptions.yml" sourcestartlinenumber="1">Gets whether the &quot;Enable Undo&quot; button is on by default for tools that modify the input dataset.</p>


```csharp
public bool EnableUndoOn { get; }
```
### OverwriteExistingDatasets

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.GeoprocessingOptions.yml" sourcestartlinenumber="1">Gets whether geoprocessing tools can overwrite existing data, layers, or files when run.</p>


```csharp
public bool OverwriteExistingDatasets { get; }
```
### RemoveOverwrittenLayers

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.GeoprocessingOptions.yml" sourcestartlinenumber="1">Gets whether layers in a map are removed if their source
datasets are deleted by a geoprocessing tool that overwrites output.</p>


```csharp
public bool RemoveOverwrittenLayers { get; }
```
### SetAddOutputDatasetsToOpenMap(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.GeoprocessingOptions.yml" sourcestartlinenumber="1">Sets whether output datasets created by geoprocessing tools should be automatically
added to an open map. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetAddOutputDatasetsToOpenMap(bool addOutputDatasetsToOpenMap)
```
### SetAddToTopOfMapContents(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.GeoprocessingOptions.yml" sourcestartlinenumber="1">Set the add output layers to the top of map contents flag.</p>


```csharp
public void SetAddToTopOfMapContents(bool addToTopOfMapContents)
```
### SetAnalyzeScriptsAndModels(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.GeoprocessingOptions.yml" sourcestartlinenumber="1">Sets whether script and model tools are run through a compatibility-checking routine to ensure they can run successfully.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetAnalyzeScriptsAndModels(bool analyzeScriptsAndModels)
```
### SetAutoOpenMessagesWindow(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.GeoprocessingOptions.yml" sourcestartlinenumber="1">Sets whether the messages window will automatically be opened after running a tool in the Geoprocessing pane.<br>
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetAutoOpenMessagesWindow(bool autoOpenMessagesWindow)
```
### SetDisplayDisabledParameters(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.GeoprocessingOptions.yml" sourcestartlinenumber="1">Sets whether disabled tool parameters are displayed or hidden.  If displayed, they show as readonly.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDisplayDisabledParameters(bool displayDisabledParameters)
```
### SetDisplayShortedDataPaths(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.GeoprocessingOptions.yml" sourcestartlinenumber="1">Sets whether tool parameters that contain a dataset path display shortened names.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDisplayShortedDataPaths(bool displayShortedDataPaths)
```
### SetEnableUndoOn(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.GeoprocessingOptions.yml" sourcestartlinenumber="1">Sets whether the &quot;Enable Undo&quot; button is on by default for tools that modify the input dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetEnableUndoOn(bool enableUndoOn)
```
### SetOverwriteExistingDatasets(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.GeoprocessingOptions.yml" sourcestartlinenumber="1">Sets whether geoprocessing tools can overwrite existing data, layers, or files when run.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetOverwriteExistingDatasets(bool overwriteExistingDatasets)
```
### SetRemoveOverwrittenLayers(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.GeoprocessingOptions.yml" sourcestartlinenumber="1">Sets whether layers in a map are removed if their source
datasets are deleted by a geoprocessing tool that overwrites output.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetRemoveOverwrittenLayers(bool removeOverwrittenLayers)
```
### SetShowCommandSyntaxMessages(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.GeoprocessingOptions.yml" sourcestartlinenumber="1">Sets whether command syntax messages are displayed.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetShowCommandSyntaxMessages(bool showCommandSyntaxMessages)
```
### SetShowDiagnosticMessages(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.GeoprocessingOptions.yml" sourcestartlinenumber="1">Sets whether diagnostic messages are displayed.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetShowDiagnosticMessages(bool showDiagnosticMessages)
```
### SetShowNotificationOnToolCompletion(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.GeoprocessingOptions.yml" sourcestartlinenumber="1">Sets whether a notification is displayed when a geoprocessing tool completes.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetShowNotificationOnToolCompletion(bool showNotificationOnToolCompletion)
```
### SetShowProjectionTransformationMessages(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.GeoprocessingOptions.yml" sourcestartlinenumber="1">Sets whether projection transformation messages are displayed.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetShowProjectionTransformationMessages(bool showProjectionTransformationMessages)
```
### SetWriteGPOperationsToDataset(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.GeoprocessingOptions.yml" sourcestartlinenumber="1">Sets whether information about the tools being run is written to the tool's input and output dataset metadata.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetWriteGPOperationsToDataset(bool writeGPOperationsToDataset)
```
### SetWriteGPOperationsToHistory(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.GeoprocessingOptions.yml" sourcestartlinenumber="1">Sets whether the tools being run are added to the current project's geoprocessing history.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetWriteGPOperationsToHistory(bool writeGPOperationsToHistory)
```
### SetWriteGPOperationsToLog(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.GeoprocessingOptions.yml" sourcestartlinenumber="1">Sets whether information about the tools being run is written to an external log file.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetWriteGPOperationsToLog(bool writeGPOperationsToLog)
```
### ShowCommandSyntaxMessages

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.GeoprocessingOptions.yml" sourcestartlinenumber="1">Gets whether command syntax messages are displayed.</p>


```csharp
public bool ShowCommandSyntaxMessages { get; }
```
### ShowDiagnosticMessages

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.GeoprocessingOptions.yml" sourcestartlinenumber="1">Gets whether diagnostic messages are displayed.</p>


```csharp
public bool ShowDiagnosticMessages { get; }
```
### ShowNotificationOnToolCompletion

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.GeoprocessingOptions.yml" sourcestartlinenumber="1">Gets whether a notification is displayed when a geoprocessing tool completes.</p>


```csharp
public bool ShowNotificationOnToolCompletion { get; }
```
### ShowProjectionTransformationMessages

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.GeoprocessingOptions.yml" sourcestartlinenumber="1">Gets whether projection transformation messages are displayed.</p>


```csharp
public bool ShowProjectionTransformationMessages { get; }
```
### WriteGPOperationsToDataset

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.GeoprocessingOptions.yml" sourcestartlinenumber="1">Gets whether information about the tools being run is written to the tool's input and output dataset metadata.</p>


```csharp
public bool WriteGPOperationsToDataset { get; }
```
### WriteGPOperationsToHistory

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.GeoprocessingOptions.yml" sourcestartlinenumber="1">Gets whether the tools being run are added to the current project's geoprocessing history.</p>


```csharp
public bool WriteGPOperationsToHistory { get; }
```
### WriteGPOperationsToLog

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.GeoprocessingOptions.yml" sourcestartlinenumber="1">Gets whether information about the tools being run is written to an external log file.</p>


```csharp
public bool WriteGPOperationsToLog { get; }
```


