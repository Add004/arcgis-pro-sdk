# GPExecuteToolFlags

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.Geoprocessing.html">Geoprocessing</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.GPExecuteToolFlags.yml" sourcestartlinenumber="1">Flags to indicate what happens after a tool execution is complete. Use bitwise logic OR ('|') to combine two actions .</p>


## Object Signature

```csharp
[Flags]
public enum GPExecuteToolFlags
```


## Members

### AddOutputsToMap

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.GPExecuteToolFlags.yml" sourcestartlinenumber="1">Adds outputs to the current Map.</p>


```csharp
AddOutputsToMap = 1
```
### AddToHistory

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.GPExecuteToolFlags.yml" sourcestartlinenumber="1">Adds execution logs to geoprocessing project history.</p>


```csharp
AddToHistory = 2
```
### Default

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.GPExecuteToolFlags.yml" sourcestartlinenumber="1">Adds outputs to map and refreshes project items.</p>


```csharp
Default = AddOutputsToMap | RefreshProjectItems
```
### GPThread

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.GPExecuteToolFlags.yml" sourcestartlinenumber="1">Execute tool in GP thread</p>


```csharp
GPThread = 8
```
### InheritGPOptions

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.GPExecuteToolFlags.yml" sourcestartlinenumber="1">overrides AddOutputsToMap and AddToHistory by Geoprocessing Options settings</p>


```csharp
InheritGPOptions = 32
```
### None

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.GPExecuteToolFlags.yml" sourcestartlinenumber="1">No action is taken.</p>


```csharp
None = 0
```
### RefreshProjectItems

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.GPExecuteToolFlags.yml" sourcestartlinenumber="1">Refreshes project items.</p>


```csharp
RefreshProjectItems = 4
```


