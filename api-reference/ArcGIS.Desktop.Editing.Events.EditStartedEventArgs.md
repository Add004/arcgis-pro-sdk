# EditStartedEventArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditStartedEventArgs.yml" sourcestartlinenumber="1">Event Args for EditStartedEvent.</p>


## Object Signature

```csharp
public sealed class EditStartedEventArgs
```


## Members

### Guid

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditStartedEventArgs.yml" sourcestartlinenumber="1">Gets the guid that uniquely identifies the EditOperation.</p>


```csharp
public Guid Guid { get; }
```
### Operation

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditStartedEventArgs.yml" sourcestartlinenumber="1">Gets the EditOperation currently being executed.  Allows Event handler to make further edits.</p>


```csharp
public EditOperation Operation { get; }
```


