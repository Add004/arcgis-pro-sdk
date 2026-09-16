# GPToolDialogFlags

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.Geoprocessing.html">Geoprocessing</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.GPToolDialogFlags.yml" sourcestartlinenumber="1">GP Tool Dialog style flags</p>


## Object Signature

```csharp
[Flags]
public enum GPToolDialogFlags
```


## Members

### Default

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.GPToolDialogFlags.yml" sourcestartlinenumber="1">Open tool in the Geoprocessing pane and show Parameters|Environments tabs.</p>


```csharp
Default = GPPane | ShowEnvironment
```
### Floating

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.GPToolDialogFlags.yml" sourcestartlinenumber="1">Open tool in a floating stand-alone window.</p>


```csharp
Floating = 4
```
### FloatingAddApplyButton

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.GPToolDialogFlags.yml" sourcestartlinenumber="1">Floating standalone window has Apply button that keeps window open after run</p>


```csharp
FloatingAddApplyButton = 12
```
### GPPane

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.GPToolDialogFlags.yml" sourcestartlinenumber="1">Open tool in the Geoprocessing pane, re-using existing dialog.</p>


```csharp
GPPane = 1
```
### GPPaneNewSubPane

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.GPToolDialogFlags.yml" sourcestartlinenumber="1">Open tool in the Geoprocessing pane, adding a new sub pane if needed.</p>


```csharp
GPPaneNewSubPane = 3
```
### ShowEnvironment

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.GPToolDialogFlags.yml" sourcestartlinenumber="1">Show Parameters|Enviroments tabs.</p>


```csharp
ShowEnvironment = 16
```


