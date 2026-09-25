# FolderConnectionProjectItem

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Catalog.html">Catalog</a>
- Assembly: ArcGIS.Desktop.Catalog.dll

<p sourcefile="api/ArcGIS.Desktop.Catalog.FolderConnectionProjectItem.yml" sourcestartlinenumber="1">Represents a folder connection project item.</p>


## Object Signature

```csharp
public class FolderConnectionProjectItem : ProjectItemInfoCrawl, IItemCrawlerSync, IProjectItem, IProjectMember, IProjectItemEdit, IProjectItemRename, IProjectItemSelected, IProgressItem, ISearchableItem
```

## Remarks

<p>
    A folder connection project item is a folder that has been added to the current project.
    The folder connection is a project item. The sub-folders and other items that can be accessed
    using the folder connection are items, not project items.
    </p>


## Members

### OnExpanded()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Catalog.FolderConnectionProjectItem.yml" sourcestartlinenumber="1">Called when the item is expanded.</p>


```csharp
public override Task OnExpanded()
```
### RequiresMainThread

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.FolderConnectionProjectItem.yml" sourcestartlinenumber="1">Is the Main Thread required?  Always returns false.</p>


```csharp
public bool RequiresMainThread { get; }
```
### Search(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Catalog.FolderConnectionProjectItem.yml" sourcestartlinenumber="1">Performs the search using the specified string.</p>


```csharp
public IEnumerable<Item> Search(string searchString)
```


