# ProjectClosingEventArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectClosingEventArgs.yml" sourcestartlinenumber="1">Represents the project on which the ProjectClosingEvent is operating</p>


## Object Signature

```csharp
public class ProjectClosingEventArgs : CancelEventArgs
```

## Remarks

<p>
    When the ProjectClosingEvent is fired, ProjectClosingEventArgs is returned to subscribers of the event
    </p>


## Members

### Project

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectClosingEventArgs.yml" sourcestartlinenumber="1">Gets the project associated with the event that was fired</p>


```csharp
public Project Project { get; }
```


