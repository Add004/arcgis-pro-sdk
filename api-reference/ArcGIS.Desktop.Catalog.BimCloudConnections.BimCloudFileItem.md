# BimCloudFileItem

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Catalog.html">Catalog</a>.<a class="xref" href="ArcGIS.Desktop.Catalog.BimCloudConnections.html">BimCloudConnections</a>
- Assembly: ArcGIS.Desktop.Catalog.dll

<p sourcefile="api/ArcGIS.Desktop.Catalog.BimCloudConnections.BimCloudFileItem.yml" sourcestartlinenumber="1">Represents a design file on a BIM Cloud datastore</p>


## Object Signature

```csharp
public abstract class BimCloudFileItem : ProjectItemInfoCrawl, IItemCrawlerSync, IProjectItem
```


## Members

### DownloadItem(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Catalog.BimCloudConnections.BimCloudFileItem.yml" sourcestartlinenumber="1">Download this item to the specified directory. The directory must already exist.
If a file of the same name already exists in the directory, it will be overwritten.</p>


```csharp
public abstract Item DownloadItem(string directoryPath)
```


