# CompositeOperation

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Contracts.html">Contracts</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.CompositeOperation.yml" sourcestartlinenumber="1">Represents a list of Operation instances that are collectively applied.</p>


## Object Signature

```csharp
public sealed class CompositeOperation : Operation, IDisposable
```


## Members

### CompositeOperation(IEnumerable&lt;Operation&gt;, string, string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.CompositeOperation.yml" sourcestartlinenumber="1">Initializes a new CompositeOperation instance.</p>


```csharp
public CompositeOperation(IEnumerable<Operation> operations, string name = "", string category = "")
```
### CanRedo

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.CompositeOperation.yml" sourcestartlinenumber="1">Gets a boolean value indicating if an Operation permits Redo. Returns False if any Operation in any of its OperationManager instances returns False; otherwise, returns True.</p>


```csharp
public override bool CanRedo { get; }
```
### CanUndo

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.CompositeOperation.yml" sourcestartlinenumber="1">Gets a boolean value indicating if an Operation permits Undo. Returns False if any Operation in any of its OperationManager instances returns False; otherwise, returns True.</p>


```csharp
public override bool CanUndo { get; }
```
### Category

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.CompositeOperation.yml" sourcestartlinenumber="1">Gets the category the operation falls into.</p>


```csharp
public override string Category { get; }
```
### Dispose()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.CompositeOperation.yml" sourcestartlinenumber="1">Provides a mechanism for releasing unmanaged resources.</p>


```csharp
public override void Dispose()
```
### Do()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.CompositeOperation.yml" sourcestartlinenumber="1">Perform the operation synchronously.</p>


```csharp
protected override bool Do()
```
### DoAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.CompositeOperation.yml" sourcestartlinenumber="1">Perform the operation asynchronously.</p>


```csharp
protected override Task DoAsync()
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.CompositeOperation.yml" sourcestartlinenumber="1">Gets the name of the operation as it is to appear in the undo/redo lists.</p>


```csharp
public override string Name { get; }
```
### RedoAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.CompositeOperation.yml" sourcestartlinenumber="1">Redo the operation to redo the action from the <code>DoAsync</code> method.</p>


```csharp
protected override Task RedoAsync()
```
### UndoAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.CompositeOperation.yml" sourcestartlinenumber="1">Undo the operation to reset the action from the <code>DoAsync</code> method.</p>


```csharp
protected override Task UndoAsync()
```


