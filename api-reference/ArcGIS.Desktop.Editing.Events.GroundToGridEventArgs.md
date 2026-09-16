# GroundToGridEventArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.GroundToGridEventArgs.yml" sourcestartlinenumber="1">Event parameters for <xref href="ArcGIS.Desktop.Editing.Events.GroundToGridEvent" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class GroundToGridEventArgs : EventArgs
```


## Members

### Map

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.GroundToGridEventArgs.yml" sourcestartlinenumber="1">Gets the map associated with this event.</p>


```csharp
public Map Map { get; }
```
### PropertyName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.GroundToGridEventArgs.yml" sourcestartlinenumber="1">Gets the name of the Ground to Grid property that changed.
If null then more than one property was changed at the same time.</p>


```csharp
public string PropertyName { get; }
```


