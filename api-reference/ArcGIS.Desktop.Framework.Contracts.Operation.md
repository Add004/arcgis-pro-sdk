# Operation

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Contracts.html">Contracts</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Operation.yml" sourcestartlinenumber="1">Represents an action, or group of actions, that can be undone and redone. This is an abstract class.</p>


## Object Signature

```csharp
public abstract class Operation : IDisposable
```

## Remarks

<p>
    To participate in the undo/redo framework, an Operation must be created and added to the appropriate
    <xref href="ArcGIS.Desktop.Framework.OperationManager" data-throw-if-not-resolved="false"></xref>. There isn't one operation stack for the application, each <code>Pane</code> and
    <code>DockPane</code> decides how its operations are managed. For example, different maps have their own
    operation stack; changing the visibility of layers in one map will not be undoable if the focus switches to a different
    map. Although each Pane and DockPane are given the opportunity to provide their own <code>OperationManager</code>,
    they may elect to share the same one. For example, all map panes rely on an <code>OperationManager</code> managed
    by a <code>Map</code> object. This way, all the map panes for the same Map share the same OperationManager. In this
    case, changing the visibility of layers will show up in the undo/redo stack for all map panes showing this <code>Map</code>.
    </p>
<p>
    Operations can also be categorized so that operations belonging only to a specific category can be undone.
    For example, ArcGIS Pro has editing and mapping operations; if these operations are intermixed, users can 
    elect to just undo the editing operations and skip over the mapping operations. Categorized operations 
    must be mutually exclusive.
    </p>


## Members

### Operation()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Operation.yml" sourcestartlinenumber="1">Represents an action, or group of actions, that can be undone and redone. This is an abstract class.</p>


```csharp
protected Operation()
```
### CanRedo

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Operation.yml" sourcestartlinenumber="1">Gets a boolean indicating if the operation can be redone.</p>


```csharp
public virtual bool CanRedo { get; }
```
### CanUndo

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Operation.yml" sourcestartlinenumber="1">Gets a boolean indicating if the operation can be undone.</p>


```csharp
public virtual bool CanUndo { get; }
```
### Category

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Operation.yml" sourcestartlinenumber="1">Gets the category name.</p>


```csharp
public virtual string Category { get; }
```
### DirtiesProject

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Operation.yml" sourcestartlinenumber="1">Gets a boolean indicating if the operation should dirty the project.</p>


```csharp
public virtual bool DirtiesProject { get; }
```
### Dispose()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Operation.yml" sourcestartlinenumber="1">Provides a mechanism for releasing unmanaged resources.</p>


```csharp
public virtual void Dispose()
```
### Do()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Operation.yml" sourcestartlinenumber="1">Perform the operation synchronously.</p>


```csharp
protected virtual bool Do()
```
### DoAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Operation.yml" sourcestartlinenumber="1">Perform the operation asynchronously.</p>


```csharp
protected virtual Task DoAsync()
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Operation.yml" sourcestartlinenumber="1">Gets or sets a unique identifier for the Operation. Default value is -1.</p>


```csharp
public int ID { get; protected set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Operation.yml" sourcestartlinenumber="1">Gets the name of the operation as it is to appear in the undo/redo lists.</p>


```csharp
public abstract string Name { get; }
```
### RedoAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Operation.yml" sourcestartlinenumber="1">Restarts the <xref href="ArcGIS.Desktop.Framework.Contracts.Operation.Do" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Desktop.Framework.Contracts.Operation.DoAsync" data-throw-if-not-resolved="false"></xref> action.</p>


```csharp
protected abstract Task RedoAsync()
```
### SubCategory

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Operation.yml" sourcestartlinenumber="1">Gets the sub-category name.</p>


```csharp
public virtual string SubCategory { get; }
```
### UndoAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Operation.yml" sourcestartlinenumber="1">Undo the operation to reset the action from <xref href="ArcGIS.Desktop.Framework.Contracts.Operation.Do" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Desktop.Framework.Contracts.Operation.DoAsync" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
protected abstract Task UndoAsync()
```


