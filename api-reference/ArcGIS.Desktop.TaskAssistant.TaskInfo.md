# TaskInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.TaskAssistant.html">TaskAssistant</a>
- Assembly: ArcGIS.Desktop.TaskAssistant.dll

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.TaskInfo.yml" sourcestartlinenumber="1">Represents summary information about a task.</p>


## Object Signature

```csharp
public sealed class TaskInfo
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.TaskInfo.yml" sourcestartlinenumber="1">Use the <xref href="ArcGIS.Desktop.TaskAssistant.TaskAssistantFactory.GetTaskItemInfoAsync(System.String)" data-throw-if-not-resolved="false"></xref> API call to obtain information about a task item and its tasks.</p>


## Members

### GroupPath

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.TaskInfo.yml" sourcestartlinenumber="1">Gets the path of the task in the task item.</p>


```csharp
public string GroupPath { get; }
```
### Guid

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.TaskInfo.yml" sourcestartlinenumber="1">Gets the unique guid of the task.</p>


```csharp
public Guid Guid { get; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.TaskInfo.yml" sourcestartlinenumber="1">Gets the name of the task.</p>


```csharp
public string Name { get; }
```


