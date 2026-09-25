# RowChangedEventArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.RowChangedEventArgs.yml" sourcestartlinenumber="1">Provides information about the changes that were made by a row event.</p>


## Object Signature

```csharp
public sealed class RowChangedEventArgs
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.RowChangedEventArgs.yml" sourcestartlinenumber="1">Use the properties on this class to determine the type of row event and the row that was affected. The event could be either a create, change or delete.</p>


## Members

### CancelEdit()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.RowChangedEventArgs.yml" sourcestartlinenumber="1">Cancel the current EditOperation</p>


```csharp
public void CancelEdit()
```
### CancelEdit(Func&lt;Task&lt;bool&gt;&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.RowChangedEventArgs.yml" sourcestartlinenumber="1">Cancel the current EditOperation with a callback to execute code and possibly retry.</p>


```csharp
public void CancelEdit(Func<Task<bool>> callback)
```
### CancelEdit(string, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.RowChangedEventArgs.yml" sourcestartlinenumber="1">Cancel the current EditOperation with an option to override.</p>


```csharp
public void CancelEdit(string errorMessage, bool canOverride = false)
```
### EditType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.RowChangedEventArgs.yml" sourcestartlinenumber="1">Gets the edit type - was the row created, changed or deleted.</p>


```csharp
public EditType EditType { get; }
```
### Guid

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.RowChangedEventArgs.yml" sourcestartlinenumber="1">Gets the guid that uniquely identifies the EditOperation.</p>


```csharp
public Guid Guid { get; }
```
### Operation

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.RowChangedEventArgs.yml" sourcestartlinenumber="1">Gets the EditOperation currently being executed.  Allows Event handler to make further edits.</p>


```csharp
public EditOperation Operation { get; }
```
### Row

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.RowChangedEventArgs.yml" sourcestartlinenumber="1">Gets the Row that was modified.</p>


```csharp
public Row Row { get; }
```


