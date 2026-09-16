# MapProjectItem

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapProjectItem.yml" sourcestartlinenumber="1">Represents a map project item.</p>


## Object Signature

```csharp
public sealed class MapProjectItem : ProjectItemInfoCrawl, IProjectItemEdit, IProjectItemRename, ISearchableItem, IPortalProjectItem, IDisposable
```


## Members

### CanOpenView()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapProjectItem.yml" sourcestartlinenumber="1">Gets whether the view can be opened.</p>


```csharp
protected override bool CanOpenView()
```
### ContextMenuOpenView(MapViewingMode)

- Kind: method


```csharp
public void ContextMenuOpenView(MapViewingMode viewMode)
```
### CreateMapProjectItem(string, string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapProjectItem.yml" sourcestartlinenumber="1">Create a map project item with the given name and path.</p>


```csharp
public static MapProjectItem CreateMapProjectItem(string name, string path, string data)
```
### Dispose()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapProjectItem.yml" sourcestartlinenumber="1">Dispose the project item</p>


```csharp
public void Dispose()
```
### GetMap()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapProjectItem.yml" sourcestartlinenumber="1">Returns a <xref href="ArcGIS.Desktop.Mapping.Map?text=map" data-throw-if-not-resolved="false"></xref> by loading it first if necessary.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Map GetMap()
```
### MapType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapProjectItem.yml" sourcestartlinenumber="1">Gets the map type.</p>


```csharp
public MapType MapType { get; }
```
### OnFolderRename(string, string)

- Kind: method


```csharp
protected override void OnFolderRename(string oldValue, string newValue)
```
### OnRemoveFromProject()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapProjectItem.yml" sourcestartlinenumber="1">Call back whenever a project item is going to be removed from a project</p>


```csharp
public override void OnRemoveFromProject()
```
### OpenMapPaneAsync(MapViewingMode)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapProjectItem.yml" sourcestartlinenumber="1">Opens a map pane for the map project item</p>


```csharp
public Task<IMapPane> OpenMapPaneAsync(MapViewingMode flag = 0)
```
### RefreshChildrenAsync()

- Kind: method


```csharp
public Task RefreshChildrenAsync()
```
### Search(string)

- Kind: method


```csharp
public IEnumerable<Item> Search(string searchString)
```
### Thumbnail

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapProjectItem.yml" sourcestartlinenumber="1">Gets the thumbnail image source</p>


```csharp
public ImageSource Thumbnail { get; }
```
### ViewingMode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapProjectItem.yml" sourcestartlinenumber="1">Gets the map viewing mode.</p>


```csharp
public MapViewingMode ViewingMode { get; }
```


