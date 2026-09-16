# TaskStartedEventArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.TaskAssistant.html">TaskAssistant</a>.<a class="xref" href="ArcGIS.Desktop.TaskAssistant.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.TaskAssistant.dll

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.Events.TaskStartedEventArgs.yml" sourcestartlinenumber="1">Represents information about a task started event.</p>


## Object Signature

```csharp
public sealed class TaskStartedEventArgs : EventArgs
```


## Members

### ProjectName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.Events.TaskStartedEventArgs.yml" sourcestartlinenumber="1">Gets the name of the project the task was started in.</p>


```csharp
public string ProjectName { get; }
```
### StartTime

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.Events.TaskStartedEventArgs.yml" sourcestartlinenumber="1">Gets the task execution start time.</p>


```csharp
public DateTime StartTime { get; }
```
### TaskGuid

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.Events.TaskStartedEventArgs.yml" sourcestartlinenumber="1">Gets the unique identifer of the task.</p>


```csharp
public Guid TaskGuid { get; }
```
### TaskItemGuid

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.Events.TaskStartedEventArgs.yml" sourcestartlinenumber="1">Gets the unique identifer of the task item.</p>


```csharp
public Guid TaskItemGuid { get; }
```
### TaskItemName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.Events.TaskStartedEventArgs.yml" sourcestartlinenumber="1">Gets the task item name.</p>


```csharp
public string TaskItemName { get; }
```
### TaskItemVersion

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.Events.TaskStartedEventArgs.yml" sourcestartlinenumber="1">Gets the task item version.</p>


```csharp
public string TaskItemVersion { get; }
```
### TaskName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.Events.TaskStartedEventArgs.yml" sourcestartlinenumber="1">Gets the task name.</p>


```csharp
public string TaskName { get; }
```
### UserID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.Events.TaskStartedEventArgs.yml" sourcestartlinenumber="1">Gets the ID of the user who started the task.</p>


```csharp
public string UserID { get; }
```
### WMXJobID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.Events.TaskStartedEventArgs.yml" sourcestartlinenumber="1">Gets the JobID when the task is launched from WMX.</p>


```csharp
public int WMXJobID { get; }
```


