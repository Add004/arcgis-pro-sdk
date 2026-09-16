# BusinessAnalystProjectItem

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Catalog.html">Catalog</a>
- Assembly: ArcGIS.Desktop.Catalog.dll

<p sourcefile="api/ArcGIS.Desktop.Catalog.BusinessAnalystProjectItem.yml" sourcestartlinenumber="1">Base class for file based business analyst project items.</p>


## Object Signature

```csharp
public abstract class BusinessAnalystProjectItem : ProjectItemInfoCrawl, IItemCrawlerSync, IProjectItem, IProjectMember, IProjectItemRename, IProjectItemEdit, IProjectMultiItem, IProjectItemSelected
```


## Members

### GetInfo()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Catalog.BusinessAnalystProjectItem.yml" sourcestartlinenumber="1">Gets the ProjectItemInfo for this project item.</p>


```csharp
public override ProjectItemInfo GetInfo()
```
### GroupSortOrderID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.BusinessAnalystProjectItem.yml" sourcestartlinenumber="1">Gets the GroupSortOrderID.</p>


```csharp
public abstract int GroupSortOrderID { get; }
```
### InitDisplayType()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Catalog.BusinessAnalystProjectItem.yml" sourcestartlinenumber="1">Initializes the display type.</p>


```csharp
protected abstract void InitDisplayType()
```
### ItemType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.BusinessAnalystProjectItem.yml" sourcestartlinenumber="1">Gets the ItemType.</p>


```csharp
public abstract string ItemType { get; }
```


