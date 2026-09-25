# EditCompletingEventArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditCompletingEventArgs.yml" sourcestartlinenumber="1">This event is fired just before committing an edit.</p>


## Object Signature

```csharp
public sealed class EditCompletingEventArgs
```


## Members

### CancelEdit()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditCompletingEventArgs.yml" sourcestartlinenumber="1">Cancel the current EditOperation.</p>


```csharp
public void CancelEdit()
```
### CancelEdit(Func&lt;Task&lt;bool&gt;&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditCompletingEventArgs.yml" sourcestartlinenumber="1">Cancel the current EditOperation with a callback to execute code and possibly retry.</p>


```csharp
public void CancelEdit(Func<Task<bool>> callback)
```
### CancelEdit(string, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditCompletingEventArgs.yml" sourcestartlinenumber="1">Cancel the current EditOperation with an option to override.</p>


```csharp
public void CancelEdit(string errorMessage, bool canOverride = false)
```
### Guid

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditCompletingEventArgs.yml" sourcestartlinenumber="1">Gets the guid that uniquely identifies the EditOperation.</p>


```csharp
public Guid Guid { get; }
```
### Operation

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditCompletingEventArgs.yml" sourcestartlinenumber="1">Gets the EditOperation currently being executed.  Allows Event handler to make further edits.</p>


```csharp
public EditOperation Operation { get; }
```


