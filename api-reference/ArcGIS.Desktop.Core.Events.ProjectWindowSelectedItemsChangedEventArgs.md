# ProjectWindowSelectedItemsChangedEventArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectWindowSelectedItemsChangedEventArgs.yml" sourcestartlinenumber="1">Event argument for the <xref href="ArcGIS.Desktop.Core.Events.ProjectWindowSelectedItemsChangedEvent" data-throw-if-not-resolved="false"></xref></p>


## Object Signature

```csharp
public class ProjectWindowSelectedItemsChangedEventArgs : EventArgs
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectWindowSelectedItemsChangedEventArgs.yml" sourcestartlinenumber="1">Access the <xref href="ArcGIS.Desktop.Core.Events.ProjectWindowSelectedItemsChangedEventArgs.IProjectWindow" data-throw-if-not-resolved="false"></xref> to get the selection change
for <i>that</i> window. There can be more than one project (view) pane open as well
as the Project dockpane (&quot;catalog&quot;). Each will have its own selection.</p>


## Members

### IProjectWindow

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectWindowSelectedItemsChangedEventArgs.yml" sourcestartlinenumber="1">Gets the IProjectWindow whose selection has changed</p>


```csharp
public IProjectWindow IProjectWindow { get; }
```
### WindowID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectWindowSelectedItemsChangedEventArgs.yml" sourcestartlinenumber="1">Gets the DAML id of the IProjectWindow</p>


```csharp
public string WindowID { get; }
```


