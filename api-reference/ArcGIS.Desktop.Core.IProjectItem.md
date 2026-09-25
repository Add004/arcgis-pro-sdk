# IProjectItem

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.IProjectItem.yml" sourcestartlinenumber="1">Provides basic interface for <b>all</b> project items</p>


## Object Signature

```csharp
public interface IProjectItem
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Core.IProjectItem.yml" sourcestartlinenumber="1">Any class that is a type of project item must implement IProjectItem. These classes
also follow a convention that includes &quot;ProjectItem&quot; as part of their name</p>


## Members

### GetInfo()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.IProjectItem.yml" sourcestartlinenumber="1">Get the associated <xref href="ArcGIS.Desktop.Core.ProjectItemInfo" data-throw-if-not-resolved="false"></xref></p>


```csharp
ProjectItemInfo GetInfo()
```
### OnAddToProject()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.IProjectItem.yml" sourcestartlinenumber="1">Callback whenever a project item has been added to a project</p>


```csharp
void OnAddToProject()
```
### OnRemoveFromProject()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.IProjectItem.yml" sourcestartlinenumber="1">Callback whenever a project item is going to be removed from a project</p>


```csharp
void OnRemoveFromProject()
```


