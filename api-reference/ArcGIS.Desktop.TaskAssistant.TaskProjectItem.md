# TaskProjectItem

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.TaskAssistant.html">TaskAssistant</a>
- Assembly: ArcGIS.Desktop.TaskAssistant.dll

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.TaskProjectItem.yml" sourcestartlinenumber="1">Represents a task project item.</p>


## Object Signature

```csharp
public sealed class TaskProjectItem : Item, IProjectItem, IProjectItemEdit, IProjectMultiItem, IProjectItemRename, IPortalProjectItem
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.TaskProjectItem.yml" sourcestartlinenumber="1">Task project items are stored within the project and are visible under the Tasks category in the Catalog pane.</p>


## Members

### CanRename

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.TaskProjectItem.yml" sourcestartlinenumber="1">Gets whether the project item can be renamed.</p>


```csharp
public bool CanRename { get; }
```
### GetTaskItemInfoAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.TaskProjectItem.yml" sourcestartlinenumber="1">Returns information about the task item.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Task<TaskItemInfo> GetTaskItemInfoAsync()
```
### IsOpen

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.TaskProjectItem.yml" sourcestartlinenumber="1">Gets the open flag of the task item (ie is the task item open in the Tasks pane).</p>


```csharp
public bool IsOpen { get; }
```
### PreviewRename(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.TaskProjectItem.yml" sourcestartlinenumber="1">PreviewRename is called first by the rename operation. The implemention should
set the <code sourcefile="api/ArcGIS.Desktop.TaskAssistant.TaskProjectItem.yml" sourcestartlinenumber="2">name</code> property of a new ItemInfoValue and return it.</p>


```csharp
public ItemInfoValue PreviewRename(string newName)
```
### PreviewRenameAsync(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.TaskProjectItem.yml" sourcestartlinenumber="1">PreviewRenameAsync is called first by the rename operation. The implemention
should set the <code sourcefile="api/ArcGIS.Desktop.TaskAssistant.TaskProjectItem.yml" sourcestartlinenumber="2">name</code> property of a new ItemInfoValue and return it.</p>


```csharp
public Task<ItemInfoValue> PreviewRenameAsync(string newName)
```
### Rename(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.TaskProjectItem.yml" sourcestartlinenumber="1">Renames the project item.  This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Rename(string newName)
```
### RenameAsync(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.TaskProjectItem.yml" sourcestartlinenumber="1">Renames the project item.</p>


```csharp
public Task RenameAsync(string newName)
```
### TaskItemGuid

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.TaskProjectItem.yml" sourcestartlinenumber="1">Gets the unique guid of the task item.</p>


```csharp
public Guid TaskItemGuid { get; }
```


