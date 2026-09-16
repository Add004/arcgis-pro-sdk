# SegmentationTargetGroupProjectItem

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Catalog.html">Catalog</a>
- Assembly: ArcGIS.Desktop.Catalog.dll

<p sourcefile="api/ArcGIS.Desktop.Catalog.SegmentationTargetGroupProjectItem.yml" sourcestartlinenumber="1">Represents a segmentation target group project item.</p>


## Object Signature

```csharp
public sealed class SegmentationTargetGroupProjectItem : SegmentationProjectItem, IItemCrawlerSync, IProjectItem, IProjectMember, IProjectItemRename, IProjectItemEdit, IProjectMultiItem, IProjectItemSelected
```

## Remarks

<p>
    A segmentation target group project item is a segmentation target group that has been added to the current project. 
    </p>


## Members

### GroupSortOrderID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.SegmentationTargetGroupProjectItem.yml" sourcestartlinenumber="1">Gets the GroupSortOrderID.</p>


```csharp
public override int GroupSortOrderID { get; }
```
### InitDisplayType()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Catalog.SegmentationTargetGroupProjectItem.yml" sourcestartlinenumber="1">Initializes the display type.</p>


```csharp
protected override void InitDisplayType()
```
### ItemType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Catalog.SegmentationTargetGroupProjectItem.yml" sourcestartlinenumber="1">Gets the ItemType.</p>


```csharp
public override string ItemType { get; }
```


