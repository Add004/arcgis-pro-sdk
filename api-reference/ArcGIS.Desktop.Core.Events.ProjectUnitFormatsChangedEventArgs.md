# ProjectUnitFormatsChangedEventArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectUnitFormatsChangedEventArgs.yml" sourcestartlinenumber="1">Event argument for the project units changed event.</p>


## Object Signature

```csharp
public class ProjectUnitFormatsChangedEventArgs : EventArgs
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectUnitFormatsChangedEventArgs.yml" sourcestartlinenumber="1">If any of the default project units are changed as part of
the event, the <xref href="ArcGIS.Desktop.Core.Events.ProjectUnitFormatsChangedEventArgs.DefaultsChangedHint" data-throw-if-not-resolved="false"></xref> identifies which ones
were changed (if any).</p>


## Members

### DefaultsChangedHint

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectUnitFormatsChangedEventArgs.yml" sourcestartlinenumber="1">Gets which project default unit formats were changed to different unit formats</p>


```csharp
public IEnumerable<UnitFormatType> DefaultsChangedHint { get; }
```


