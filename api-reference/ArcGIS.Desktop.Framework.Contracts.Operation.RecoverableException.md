# Operation.RecoverableException

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Contracts.html">Contracts</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Operation.RecoverableException.yml" sourcestartlinenumber="1">The exception that a subclass should throw when it encounters a recoverable error condition and cannot execute.</p>


## Object Signature

```csharp
protected class Operation.RecoverableException : Exception, ISerializable
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Operation.RecoverableException.yml" sourcestartlinenumber="1">The framework handles this specific exception, and leaves the operation off the stack.
Meant to be called in DoAsync, UndoAsync, RedoAsync implementations. It is assumed that
the subclass handles the error appropriately and preserves application invariants.</p>


## Members

### RecoverableException()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Operation.RecoverableException.yml" sourcestartlinenumber="1">The exception that a subclass should throw when it encounters a recoverable error condition and cannot execute.</p>


```csharp
public RecoverableException()
```


