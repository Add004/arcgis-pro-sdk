# ProjectHomeFolderChangedEventArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectHomeFolderChangedEventArgs.yml" sourcestartlinenumber="1">Represents old and new values of the current project's home folder.</p>


## Object Signature

```csharp
public class ProjectHomeFolderChangedEventArgs : CancelEventArgs
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectHomeFolderChangedEventArgs.yml" sourcestartlinenumber="1">When the home folder value changes after initialization, ProjectHomeFolderChangedEventArgs is returned to the subscribers.</p>


## Members

### ProjectHomeFolderChangedEventArgs(string, string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectHomeFolderChangedEventArgs.yml" sourcestartlinenumber="1">Default constructor</p>


```csharp
public ProjectHomeFolderChangedEventArgs(string oldValue, string newValue)
```
### NewValue

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectHomeFolderChangedEventArgs.yml" sourcestartlinenumber="1">The new (current) value of the current project's home folder property</p>


```csharp
public string NewValue { get; }
```
### OldValue

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectHomeFolderChangedEventArgs.yml" sourcestartlinenumber="1">The previous value of the current project's home folder property</p>


```csharp
public string OldValue { get; }
```


