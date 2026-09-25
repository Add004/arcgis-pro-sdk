# GPExecuteToolEventArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Events.GPExecuteToolEventArgs.yml" sourcestartlinenumber="1">Event argument for the <xref href="ArcGIS.Desktop.Core.Events.GPExecuteToolEvent" data-throw-if-not-resolved="false"></xref></p>


## Object Signature

```csharp
public class GPExecuteToolEventArgs : EventArgs
```


## Members

### GPExecuteToolEventArgs()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.Events.GPExecuteToolEventArgs.yml" sourcestartlinenumber="1">Event argument for the <xref href="ArcGIS.Desktop.Core.Events.GPExecuteToolEvent" data-throw-if-not-resolved="false"></xref></p>


```csharp
public GPExecuteToolEventArgs()
```
### GPResult

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Events.GPExecuteToolEventArgs.yml" sourcestartlinenumber="1">Gets the associated IGPResult</p>


```csharp
public IGPResult GPResult { get; init; }
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Events.GPExecuteToolEventArgs.yml" sourcestartlinenumber="1">unique execute ID</p>


```csharp
public string ID { get; init; }
```
### IsStarting

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Events.GPExecuteToolEventArgs.yml" sourcestartlinenumber="1">Gets whether the execution of the tool is starting</p>


```csharp
public bool IsStarting { get; init; }
```
### Path

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Events.GPExecuteToolEventArgs.yml" sourcestartlinenumber="1">Gets the associated GPTool path</p>


```csharp
public string Path { get; init; }
```


