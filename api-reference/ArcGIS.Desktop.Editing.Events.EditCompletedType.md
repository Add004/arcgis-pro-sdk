# EditCompletedType

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditCompletedType.yml" sourcestartlinenumber="1">Describes the type of an EditCompletedEvent.</p>


## Object Signature

```csharp
public enum EditCompletedType
```


## Members

### Discard

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditCompletedType.yml" sourcestartlinenumber="1">Indicates this EditCompletedEvent discards outstanding edits to the database.</p>


```csharp
Discard = 1
```
### Operation

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditCompletedType.yml" sourcestartlinenumber="1">Indicates this EditCompletedEvent has occured.</p>


```csharp
Operation = 2
```
### Post

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditCompletedType.yml" sourcestartlinenumber="1">Indicates this EditCompletedEvent was a post.</p>


```csharp
Post = 6
```
### Reconcile

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditCompletedType.yml" sourcestartlinenumber="1">Indicates this EditCompletedEvent has been reconciled.</p>


```csharp
Reconcile = 5
```
### Redo

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditCompletedType.yml" sourcestartlinenumber="1">Indicates this EditCompletedEvent has been redone.</p>


```csharp
Redo = 4
```
### Save

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditCompletedType.yml" sourcestartlinenumber="1">Indicates this EditCompletedEvant saves outstanding edits to the database.</p>


```csharp
Save = 0
```
### Undo

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditCompletedType.yml" sourcestartlinenumber="1">Indicates this EditCompletedEvent has been undone.</p>


```csharp
Undo = 3
```
### Unknown

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditCompletedType.yml" sourcestartlinenumber="1">Indicates this EditCompletedEvent was somthing else that should be interpreted as anything may have changed.</p>


```csharp
Unknown = 7
```


