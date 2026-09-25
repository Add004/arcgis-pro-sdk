# ProjectExtender

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Core.ProjectExtender.yml" sourcestartlinenumber="1">Contains extension methods to extend <xref href="ArcGIS.Desktop.Core.Project" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public static class ProjectExtender
```


## Members

### GetBookmarks(Project)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.ProjectExtender.yml" sourcestartlinenumber="1">Returns the project's collection of bookmarks. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static ReadOnlyObservableCollection<Bookmark> GetBookmarks(this Project project)
```


