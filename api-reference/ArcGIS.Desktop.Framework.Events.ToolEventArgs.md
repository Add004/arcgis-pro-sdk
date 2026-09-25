# ToolEventArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Events.ToolEventArgs.yml" sourcestartlinenumber="1">Provides data for the ActiveToolChangedEvent.</p>


## Object Signature

```csharp
public sealed class ToolEventArgs : EventArgs
```


## Members

### CurrentID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Events.ToolEventArgs.yml" sourcestartlinenumber="1">Gets the DAML ID of the newly activated tool.</p>


```csharp
public string CurrentID { get; }
```
### PreviousID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Events.ToolEventArgs.yml" sourcestartlinenumber="1">Gets the DAML ID of the previously active tool.</p>


```csharp
public string PreviousID { get; }
```


