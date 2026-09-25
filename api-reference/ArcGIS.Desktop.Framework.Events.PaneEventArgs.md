# PaneEventArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Events.PaneEventArgs.yml" sourcestartlinenumber="1">Represents the current change in pane state.</p>


## Object Signature

```csharp
public sealed class PaneEventArgs : EventArgs
```


## Members

### IncomingPane

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Events.PaneEventArgs.yml" sourcestartlinenumber="1">Gets the pane being activated.</p>


```csharp
public Pane IncomingPane { get; }
```
### OutgoingPane

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Events.PaneEventArgs.yml" sourcestartlinenumber="1">Gets the pane being deactivated.</p>


```csharp
public Pane OutgoingPane { get; }
```


