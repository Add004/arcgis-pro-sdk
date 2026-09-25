# OperationManager

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.OperationManager.yml" sourcestartlinenumber="1">A collection of operations that users can undo and redo.</p>


## Object Signature

```csharp
public class OperationManager
```

## Remarks

<p>
    In general, undo operations are organized per <xref href="ArcGIS.Desktop.Framework.Contracts.Pane" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Desktop.Framework.Contracts.DockPane" data-throw-if-not-resolved="false"></xref>. 
    In other words, each Pane and DockPane manages its own operation stack. For example, operations added
    to map A are not visible to map B. The active window (Pane or DockPane) becomes the active OperationManager. 
    When a window becomes active, its OperationManager is requested and connected to the undo/redo user interface.
    </p>
<p>
    Panes and DockPanes may however elect to share OperationManagers. For example, two Panes that are showing the same map
    will have the same OperationManager.
    </p>


## Members

### OperationManager()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.OperationManager.yml" sourcestartlinenumber="1">Initializes a new instance of the OperationManager class.</p>


```csharp
public OperationManager()
```
### AddRedoOperation(Operation)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.OperationManager.yml" sourcestartlinenumber="1">Add the specified operation to the redo stack.</p>


```csharp
public void AddRedoOperation(Operation operation)
```
### AddUndoOperation(Operation)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.OperationManager.yml" sourcestartlinenumber="1">Add the specified operation to the undo stack.</p>


```csharp
public void AddUndoOperation(Operation operation)
```
### CanRedo

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.OperationManager.yml" sourcestartlinenumber="1">Gets a boolean value after checking if the first operation can be redone.</p>


```csharp
public bool CanRedo { get; }
```
### CanUndo

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.OperationManager.yml" sourcestartlinenumber="1">Gets a boolean value after checking if the first operation can be undone.</p>


```csharp
public bool CanUndo { get; }
```
### ClearRedoCategory(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.OperationManager.yml" sourcestartlinenumber="1">Removes all operations belonging to the specified category from redo stack.</p>


```csharp
public void ClearRedoCategory(string category)
```
### ClearRedoSubCategory(string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.OperationManager.yml" sourcestartlinenumber="1">Removes all operations belonging to the specified category from redo stack.</p>


```csharp
public void ClearRedoSubCategory(string category, string subCategory)
```
### ClearUndoCategory(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.OperationManager.yml" sourcestartlinenumber="1">Removes all operations belonging to the specified category from undo stack.</p>


```csharp
public void ClearUndoCategory(string category)
```
### ClearUndoSubCategory(string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.OperationManager.yml" sourcestartlinenumber="1">Removes all operations belonging to the specified category and sub category from undo stack.</p>


```csharp
public void ClearUndoSubCategory(string category, string subCategory)
```
### CreateCompositeOperation(Action, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.OperationManager.yml" sourcestartlinenumber="1">Groups existing operations into a single composite operation. This method must be called on the primary worker thread. Use QueuedTask.Run.</p>


```csharp
public void CreateCompositeOperation(Action action, string name)
```
### Decrement()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.OperationManager.yml" sourcestartlinenumber="1">Decreases the operation count without reforming an operation. This API supports the Framework infrastructure and is not intended to be used directly from your code.</p>


```csharp
public static void Decrement()
```
### Do(Operation)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.OperationManager.yml" sourcestartlinenumber="1">Performs the specified operation synchronously and adds it to the undo stack.</p>


```csharp
public virtual bool Do(Operation operation)
```
### DoAsync(Operation)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.OperationManager.yml" sourcestartlinenumber="1">Performs the specified operation asynchronously and adds it to the undo stack.</p>


```csharp
public virtual Task DoAsync(Operation operation)
```
### FindRedoOperations(Func&lt;Operation, bool&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.OperationManager.yml" sourcestartlinenumber="1">Returns all the operations from the redo stack that match the conditions defined by the specified predicate.</p>


```csharp
public List<Operation> FindRedoOperations(Func<Operation, bool> predicate)
```
### FindUndoOperations(Func&lt;Operation, bool&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.OperationManager.yml" sourcestartlinenumber="1">Returns all the operations from the undo stack that match the conditions defined by the specified predicate.</p>


```csharp
public List<Operation> FindUndoOperations(Func<Operation, bool> predicate)
```
### Increment()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.OperationManager.yml" sourcestartlinenumber="1">Increases the operation count without performing an operation. This API supports the Framework infrastructure and is not intended to be used directly from your code.</p>


```csharp
public static void Increment()
```
### PeekRedo(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.OperationManager.yml" sourcestartlinenumber="1">Return the topmost operation of the given category in the native redo stack.</p>


```csharp
public Operation PeekRedo(string category = "")
```
### PeekUndo(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.OperationManager.yml" sourcestartlinenumber="1">Return the topmost operation of the given category in the native undo stack.</p>


```csharp
public Operation PeekUndo(string category = "")
```
### RedoAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.OperationManager.yml" sourcestartlinenumber="1">Redo the top operation on the redo stack.</p>


```csharp
public virtual Task RedoAsync()
```
### RedoAsync(int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.OperationManager.yml" sourcestartlinenumber="1">Redo the specified number of operations in the redo stack.</p>


```csharp
public Task RedoAsync(int count)
```
### RedoAsync(int, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.OperationManager.yml" sourcestartlinenumber="1">The number and category of operations to redo.</p>


```csharp
public Task RedoAsync(int count, string category)
```
### RedoAsync(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.OperationManager.yml" sourcestartlinenumber="1">Redo all the operations in the redo stack that belong to the specified category.</p>


```csharp
public virtual Task RedoAsync(string category)
```
### RemoveRedoOperation(Operation)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.OperationManager.yml" sourcestartlinenumber="1">Removes the specified operation from the redo stack.</p>


```csharp
public void RemoveRedoOperation(Operation operation)
```
### RemoveUndoOperation(Operation)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.OperationManager.yml" sourcestartlinenumber="1">Removes the specified operation from the undo stack.</p>


```csharp
public void RemoveUndoOperation(Operation operation)
```
### RunningOperation

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.OperationManager.yml" sourcestartlinenumber="1">The Operation that is currently running. Automatically set and cleared by the system as operations are executed.</p>


```csharp
public Operation RunningOperation { get; }
```
### UndoAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.OperationManager.yml" sourcestartlinenumber="1">Rolls back the most recent operation to reset the last action performed with <xref href="ArcGIS.Desktop.Framework.Contracts.Operation.Do" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Desktop.Framework.Contracts.Operation.DoAsync" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public virtual Task UndoAsync()
```
### UndoAsync(int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.OperationManager.yml" sourcestartlinenumber="1">Rolls back the specified number of operations off the top of the undo stack.</p>


```csharp
public Task UndoAsync(int count)
```
### UndoAsync(int, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.OperationManager.yml" sourcestartlinenumber="1">Rolls back the specified number of operations belonging to the specified category.</p>


```csharp
public Task UndoAsync(int count, string category)
```
### UndoAsync(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.OperationManager.yml" sourcestartlinenumber="1">Rolls back the most recent operation belonging to a specific category.</p>


```csharp
public virtual Task UndoAsync(string category)
```


