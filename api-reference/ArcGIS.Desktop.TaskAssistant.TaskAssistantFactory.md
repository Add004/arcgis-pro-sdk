# TaskAssistantFactory

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.TaskAssistant.html">TaskAssistant</a>
- Assembly: ArcGIS.Desktop.TaskAssistant.dll

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.TaskAssistantFactory.yml" sourcestartlinenumber="1">Represents the Tasks factory. Provides the ability to open, close or export task items.</p>


## Object Signature

```csharp
public sealed class TaskAssistantFactory
```


## Members

### CanImportTaskFile(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.TaskAssistantFactory.yml" sourcestartlinenumber="1">Determines if an ArcGIS Pro .esriTasks file can be imported to the current project.</p>


```csharp
public bool CanImportTaskFile(string taskFile)
```
### CanOpenTaskFile(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.TaskAssistantFactory.yml" sourcestartlinenumber="1">Determines if the task file can be opened.</p>


```csharp
public bool CanOpenTaskFile(string taskFile)
```
### CloseTaskItemAsync(Guid)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.TaskAssistantFactory.yml" sourcestartlinenumber="1">Closes and unloads a specified task item from the Tasks pane.  Also removes the task item from the project.</p>


```csharp
public Task CloseTaskItemAsync(Guid taskItemGuid)
```
### ExportTaskItemAsync(Guid, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.TaskAssistantFactory.yml" sourcestartlinenumber="1">Exports the specified task item to an ArcGIS Pro .esriTasks file at the defined location.</p>


```csharp
public Task<string> ExportTaskItemAsync(Guid taskItemGuid, string path)
```
### GetTaskItemInfoAsync(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.TaskAssistantFactory.yml" sourcestartlinenumber="1">Gets information about the task item stored in an ArcGIS Pro .esriTasks file.</p>


```csharp
public Task<TaskItemInfo> GetTaskItemInfoAsync(string taskFile)
```
### ImportTaskFileAsync(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.TaskAssistantFactory.yml" sourcestartlinenumber="1">Imports an ArcGIS Pro .esriTasks file.  The file is added to the current project.</p>


```csharp
public Task<Guid> ImportTaskFileAsync(string taskFile)
```
### Instance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.TaskAssistantFactory.yml" sourcestartlinenumber="1">Gets the singleton instance for TaskAssistantFactory</p>


```csharp
public static TaskAssistantFactory Instance { get; }
```
### IsTaskFileValid(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.TaskAssistantFactory.yml" sourcestartlinenumber="1">Gets if the specified task file is valid.</p>


```csharp
public bool IsTaskFileValid(string taskFile)
```
### OpenTaskFileAsync(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.TaskAssistantFactory.yml" sourcestartlinenumber="1">Opens an ArcGIS Pro .esriTasks file.  The file is added to the current project and loaded into the Tasks pane.</p>


```csharp
public Task<Guid> OpenTaskFileAsync(string taskFile)
```
### OpenTaskFileAsync(string, Guid)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.TaskAssistantFactory.yml" sourcestartlinenumber="1">Opens an ArcGIS Pro .esriTasks file.  The file is added to the current project and loaded into the Tasks pane.  Use the <code class="paramref">taskGuid</code> parameter
to specify a particular task in the task file to be opened. Use the <xref href="ArcGIS.Desktop.TaskAssistant.TaskAssistantFactory.GetTaskItemInfoAsync(System.String)" data-throw-if-not-resolved="false"></xref> API call to obtain information about the tasks and their identifiers within the
task file.</p>


```csharp
public Task<Guid> OpenTaskFileAsync(string taskFile, Guid taskGuid)
```
### OpenTaskItemAsync(Guid)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.TaskAssistantFactory.yml" sourcestartlinenumber="1">Opens an ArcGIS Pro task item.  The item is loaded into the Tasks pane.</p>


```csharp
public Task<Guid> OpenTaskItemAsync(Guid taskItemGuid)
```
### OpenTaskItemAsync(Guid, Guid)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.TaskAssistantFactory.yml" sourcestartlinenumber="1">Opens an ArcGIS Pro task item.  The item is loaded into the Tasks pane.  Use the <code class="paramref">taskGuid</code> parameter
to specify a particular task in the task item to be opened. Use the <xref href="ArcGIS.Desktop.TaskAssistant.TaskProjectItem.GetTaskItemInfoAsync" data-throw-if-not-resolved="false"></xref> method to obtain information about the
tasks within a task item.</p>


```csharp
public Task<Guid> OpenTaskItemAsync(Guid taskItemGuid, Guid taskGuid)
```


