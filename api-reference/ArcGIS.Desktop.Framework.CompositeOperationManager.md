# CompositeOperationManager

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.CompositeOperationManager.yml" sourcestartlinenumber="1">A class that aggregates the operations of independent OperationManagers with its own and
optionally filters all operations of a specified category.</p>


## Object Signature

```csharp
public sealed class CompositeOperationManager : OperationManager
```


## Members

### CompositeOperationManager()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.CompositeOperationManager.yml" sourcestartlinenumber="1">Creates a new CompositeOperationManager instance.</p>


```csharp
public CompositeOperationManager()
```
### CompositeOperationManager(string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.CompositeOperationManager.yml" sourcestartlinenumber="1">Creates a new CompositeOperationManager instance that filters on the specified category.</p>


```csharp
public CompositeOperationManager(string filterCategory)
```
### AddOperationManager(OperationManager)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.CompositeOperationManager.yml" sourcestartlinenumber="1">Add another OperationManager to the composition.</p>


```csharp
public void AddOperationManager(OperationManager manager)
```
### ClearOperationManagers()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.CompositeOperationManager.yml" sourcestartlinenumber="1">Removes all OperationManager instances from the composition.</p>


```csharp
public void ClearOperationManagers()
```
### DoAsync(Operation)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.CompositeOperationManager.yml" sourcestartlinenumber="1">Performs the specified operation asynchronously and adds it to the undo stack.</p>


```csharp
public override Task DoAsync(Operation operation)
```
### FilterCategory

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.CompositeOperationManager.yml" sourcestartlinenumber="1">Gets a string identifying the category of operations to act on. For example, only undo 'Edit' operations in all the OperationManager objects.</p>


```csharp
public string FilterCategory { get; }
```
### RedoAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.CompositeOperationManager.yml" sourcestartlinenumber="1">Redo the top operation on the redo stack.</p>


```csharp
public override Task RedoAsync()
```
### RedoAsync(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.CompositeOperationManager.yml" sourcestartlinenumber="1">Redo all the operations in the redo stack that belong to the specified category.</p>


```csharp
public override Task RedoAsync(string category)
```
### RemoveOperationManager(OperationManager)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.CompositeOperationManager.yml" sourcestartlinenumber="1">Removes the specified OperationManager from the composition.</p>


```csharp
public void RemoveOperationManager(OperationManager manager)
```
### UndoAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.CompositeOperationManager.yml" sourcestartlinenumber="1">Rolls back the most recent operation to reset the last action performed with <xref href="ArcGIS.Desktop.Framework.Contracts.Operation.Do" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Desktop.Framework.Contracts.Operation.DoAsync" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public override Task UndoAsync()
```
### UndoAsync(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.CompositeOperationManager.yml" sourcestartlinenumber="1">Rolls back the most recent operation belonging to a specific category.</p>


```csharp
public override Task UndoAsync(string category)
```


