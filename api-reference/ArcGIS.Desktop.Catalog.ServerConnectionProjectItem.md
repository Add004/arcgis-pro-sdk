# ServerConnectionProjectItem

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Catalog.html">Catalog</a>
- Assembly: ArcGIS.Desktop.Catalog.dll

<p sourcefile="api/ArcGIS.Desktop.Catalog.ServerConnectionProjectItem.yml" sourcestartlinenumber="1">Represents a server connection project item.</p>


## Object Signature

```csharp
public sealed class ServerConnectionProjectItem : ProjectItemInfoCrawl, IItemCrawlerSync, IProjectItem, IProjectMember, IProjectItemEdit, IProjectItemRename, IProjectMultiItem, IProjectItemSelected
```

## Remarks

<p>
    A server connection project item is a connection to an ArcGIS Server site, an OGC WMS service, or
    an OGC WMTS service that has been added to the current project. New server connections cannot be
    created, but an existing .ags, .wms, or .wmts file containing connection information can be added
    to a project.
    </p>


## Members

### GetInfo()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Catalog.ServerConnectionProjectItem.yml" sourcestartlinenumber="1">Gets the ProjectItemInfo for this project item.</p>


```csharp
public override ProjectItemInfo GetInfo()
```
### ServerConnection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.ServerConnectionProjectItem.yml" sourcestartlinenumber="1">Gets and sets the ServerConnection.</p>


```csharp
public CIMProjectServerConnection ServerConnection { get; set; }
```


