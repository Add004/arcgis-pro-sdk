# SelectedProjectChangedEventArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.Controls.html">Controls</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.SelectedProjectChangedEventArgs.yml" sourcestartlinenumber="1">Passed as the event parameter in the SelectedProjectChanged event for the
RecentProjectsControl.</p>


## Object Signature

```csharp
public sealed class SelectedProjectChangedEventArgs : EventArgs
```


## Members

### ProjectPath

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.SelectedProjectChangedEventArgs.yml" sourcestartlinenumber="1">Gets the project path.  The can be either a path to a local project or the fully qualified url to a portal project item.</p>


```csharp
public string ProjectPath { get; }
```


