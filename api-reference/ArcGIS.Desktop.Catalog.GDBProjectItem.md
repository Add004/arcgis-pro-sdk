# GDBProjectItem

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Catalog.html">Catalog</a>
- Assembly: ArcGIS.Desktop.Catalog.dll

<p sourcefile="api/ArcGIS.Desktop.Catalog.GDBProjectItem.yml" sourcestartlinenumber="1">Represents a database project item.</p>


## Object Signature

```csharp
public sealed class GDBProjectItem : ProjectItemInfoCrawl, IItemCrawlerSync, IProjectItem, IProjectMember, IProjectItemEdit, IProjectItemRename, IProjectItemSelected, IProgressItem
```

## Remarks

<p>
    A database project item is a file geodatabase, enterprise geodatabase, SQLite database, or
    a geopackage that has been added to the current project.
    </p>


## Members

### ContextMenuID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.GDBProjectItem.yml" sourcestartlinenumber="1">Gets the damlID for the context menu.</p>


```csharp
protected override string ContextMenuID { get; }
```
### ContextMenuID_ProjectItem

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.GDBProjectItem.yml" sourcestartlinenumber="1">Gets damlID menu for the project item's context menu.</p>


```csharp
protected override string ContextMenuID_ProjectItem { get; }
```
### FileSize

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.GDBProjectItem.yml" sourcestartlinenumber="1">Gets the item file size.</p>


```csharp
public override long FileSize { get; }
```
### GetDatastore()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Catalog.GDBProjectItem.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Datastore" data-throw-if-not-resolved="false"></xref> associated with the workspace corresponding to <xref href="ArcGIS.Desktop.Core.Item.Path" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Datastore GetDatastore()
```
### IsAttributedRelationship

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.GDBProjectItem.yml" sourcestartlinenumber="1">Unused interface property</p>


```csharp
public bool? IsAttributedRelationship { get; }
```
### IsCloudDataWarehouse

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.GDBProjectItem.yml" sourcestartlinenumber="1">Gets if the item is a cloud data warehouse.</p>


```csharp
public bool? IsCloudDataWarehouse { get; set; }
```
### IsGeodatabase

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.GDBProjectItem.yml" sourcestartlinenumber="1">Gets if the item is a geodatabase, if not it is a database where it contains unregistered tables.</p>


```csharp
public bool? IsGeodatabase { get; set; }
```
### IsMxNRelationship

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.GDBProjectItem.yml" sourcestartlinenumber="1">Unused interface property</p>


```csharp
public bool? IsMxNRelationship { get; }
```
### IsRegisteredWithGDB

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.GDBProjectItem.yml" sourcestartlinenumber="1">Unused interface property</p>


```csharp
public bool? IsRegisteredWithGDB { get; }
```
### ItemInfoValue

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.GDBProjectItem.yml" sourcestartlinenumber="1">Gets ItemInfoValue through interface</p>


```csharp
public ItemInfoValue ItemInfoValue { get; }
```
### OnCurrentRoot(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Catalog.GDBProjectItem.yml" sourcestartlinenumber="1">Called when the Item becomes the current root item in the Catalog View.</p>


```csharp
public override void OnCurrentRoot(bool isActivating)
```
### OnExpanded()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Catalog.GDBProjectItem.yml" sourcestartlinenumber="1">Called when the item is expanded.</p>


```csharp
public override Task OnExpanded()
```
### OnRemoveFromProject()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Catalog.GDBProjectItem.yml" sourcestartlinenumber="1">Called when the item is removed from the project.</p>


```csharp
public override void OnRemoveFromProject()
```
### SetIsCloudDataWarehouse()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Catalog.GDBProjectItem.yml" sourcestartlinenumber="1">Sets the project item to be a cloud data warehouse.</p>


```csharp
public Task SetIsCloudDataWarehouse()
```


