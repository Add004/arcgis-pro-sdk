# ProjectEventArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectEventArgs.yml" sourcestartlinenumber="1">Represents the project on which an event operates, and an enumeration indicating how the
project was opened and created, if appropriate</p>


## Object Signature

```csharp
public class ProjectEventArgs : EventArgs
```

## Remarks

<p>
    When events are fired indicating that a project operation is occurring or has occurred,  
    ProjectEventArgs is returned to subscribers of the events.
    </p>


## Members

### ProjectEventArgs(Project)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectEventArgs.yml" sourcestartlinenumber="1">Creates ProjectEventArgs to pass the project to an event handler.</p>


```csharp
public ProjectEventArgs(Project Project)
```
### AllowProjectModification

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectEventArgs.yml" sourcestartlinenumber="1">Gets whether the project should allow event handlers to modify project and make project dirty</p>


```csharp
public bool AllowProjectModification { get; set; }
```
### IsSaveAs

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectEventArgs.yml" sourcestartlinenumber="1">Gets whether the project is saving in a saveAs scenario</p>


```csharp
public bool IsSaveAs { get; set; }
```
### IsSavingBackup

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectEventArgs.yml" sourcestartlinenumber="1">Gets whether the project is saving a backup</p>


```csharp
public bool IsSavingBackup { get; }
```
### Project

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectEventArgs.yml" sourcestartlinenumber="1">Gets the project associated with the event that was fired</p>


```csharp
public Project Project { get; }
```
### ProjectOpenMode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectEventArgs.yml" sourcestartlinenumber="1">Gets the enumeration associated with the event indicating how the project was opened</p>


```csharp
public ProjectOpenMode ProjectOpenMode { get; }
```
### ProjectPath

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectEventArgs.yml" sourcestartlinenumber="1">Gets the SaveAsPath</p>


```csharp
public string ProjectPath { get; }
```
### ProjectUrl

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectEventArgs.yml" sourcestartlinenumber="1">The Url if it is portal project</p>


```csharp
public string ProjectUrl { get; set; }
```


