# TaskItemInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.TaskAssistant.html">TaskAssistant</a>
- Assembly: ArcGIS.Desktop.TaskAssistant.dll

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.TaskItemInfo.yml" sourcestartlinenumber="1">Represents summary information about a task item.</p>


## Object Signature

```csharp
public sealed class TaskItemInfo
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.TaskItemInfo.yml" sourcestartlinenumber="1">Use the <xref href="ArcGIS.Desktop.TaskAssistant.TaskAssistantFactory.GetTaskItemInfoAsync(System.String)" data-throw-if-not-resolved="false"></xref> API call to obtain information about a task item.</p>


## Members

### Description

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.TaskItemInfo.yml" sourcestartlinenumber="1">Gets the description of the task item.</p>


```csharp
public string Description { get; }
```
### GetTasks()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.TaskItemInfo.yml" sourcestartlinenumber="1">Gets the tasks of the task item.</p>


```csharp
public IEnumerable<TaskInfo> GetTasks()
```
### Guid

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.TaskItemInfo.yml" sourcestartlinenumber="1">Gets the unique guid of the task item.</p>


```csharp
public Guid Guid { get; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.TaskItemInfo.yml" sourcestartlinenumber="1">Gets the name of the task item.</p>


```csharp
public string Name { get; }
```


