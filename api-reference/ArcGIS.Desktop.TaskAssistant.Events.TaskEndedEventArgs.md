# TaskEndedEventArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.TaskAssistant.html">TaskAssistant</a>.<a class="xref" href="ArcGIS.Desktop.TaskAssistant.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.TaskAssistant.dll

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.Events.TaskEndedEventArgs.yml" sourcestartlinenumber="1">Represents information about a task ended event.</p>


## Object Signature

```csharp
public sealed class TaskEndedEventArgs : EventArgs
```


## Members

### Completed

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.Events.TaskEndedEventArgs.yml" sourcestartlinenumber="1">Gets if the task was completed.  If not completed, the task was canceled.</p>


```csharp
public bool Completed { get; }
```
### Duration

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.Events.TaskEndedEventArgs.yml" sourcestartlinenumber="1">Gets the total task execution time (not including idle time).</p>


```csharp
public double Duration { get; }
```
### EndTime

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.Events.TaskEndedEventArgs.yml" sourcestartlinenumber="1">Gets the task execution end time.</p>


```csharp
public DateTime EndTime { get; }
```
### ProjectName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.Events.TaskEndedEventArgs.yml" sourcestartlinenumber="1">Gets the name of the project the task was executed in.</p>


```csharp
public string ProjectName { get; }
```
### StartTime

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.Events.TaskEndedEventArgs.yml" sourcestartlinenumber="1">Gets the task execution start time.</p>


```csharp
public DateTime StartTime { get; }
```
### TaskGuid

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.Events.TaskEndedEventArgs.yml" sourcestartlinenumber="1">Gets the unique identifer of the task.</p>


```csharp
public Guid TaskGuid { get; }
```
### TaskItemGuid

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.Events.TaskEndedEventArgs.yml" sourcestartlinenumber="1">Gets the unique identifer of the task item.</p>


```csharp
public Guid TaskItemGuid { get; }
```
### TaskItemName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.Events.TaskEndedEventArgs.yml" sourcestartlinenumber="1">Gets the task item name.</p>


```csharp
public string TaskItemName { get; }
```
### TaskItemVersion

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.Events.TaskEndedEventArgs.yml" sourcestartlinenumber="1">Gets the task item version.</p>


```csharp
public string TaskItemVersion { get; }
```
### TaskName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.Events.TaskEndedEventArgs.yml" sourcestartlinenumber="1">Gets the task name.</p>


```csharp
public string TaskName { get; }
```
### UserID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.Events.TaskEndedEventArgs.yml" sourcestartlinenumber="1">Gets the UserID who executed the task.</p>


```csharp
public string UserID { get; }
```
### WMXJobID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.Events.TaskEndedEventArgs.yml" sourcestartlinenumber="1">Gets the JobID when the task is launched from WMX.</p>


```csharp
public int WMXJobID { get; }
```


