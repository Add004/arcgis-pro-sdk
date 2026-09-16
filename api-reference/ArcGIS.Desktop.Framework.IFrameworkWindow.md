# IFrameworkWindow

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.IFrameworkWindow.yml" sourcestartlinenumber="1">Identifies framework windows (panes and dock panes) that support operations and activation.</p>


## Object Signature

```csharp
public interface IFrameworkWindow
```


## Members

### Activate()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.IFrameworkWindow.yml" sourcestartlinenumber="1">Make this window the active window.</p>


```csharp
void Activate()
```
### OperationManager

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.IFrameworkWindow.yml" sourcestartlinenumber="1">A collection of operations that users can undo and redo.</p>


```csharp
OperationManager OperationManager { get; }
```


