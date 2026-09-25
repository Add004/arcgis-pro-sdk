# Item

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Represents an item that is available to be used in the current project</p>


## Object Signature

```csharp
public class Item : PropertyChangedBase, IMetadata
```

## Remarks

<p>
    An item is a dataset, feature class, table, service, tool, file, folder, and so on that can be used 
    in the current project. For example, an item could be an ArcMap document returned by a search that you want 
    to import to the current project. An item could also be available from the active portal
    </p>


## Members

### Item()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Default constructor</p>


```csharp
protected Item()
```
### Item(ItemInfoValue)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Constructor that takes an <xref href="ArcGIS.Desktop.Core.Item.ItemInfoValue" data-throw-if-not-resolved="false"></xref></p>


```csharp
protected Item(ItemInfoValue iiv)
```
### Item(string, string, string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Constructor that takes a name, catalog path, and container type for an item</p>


```csharp
protected Item(string name, string path, string type)
```
### AccessConstraints

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets documented limitations with respect to using the item.
Derived from Use Limitations defined in the item's metadata.</p>


```csharp
public string AccessConstraints { get; }
```
### AddRangeToChildren(IEnumerable&lt;Item&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Adds the collection of items to the item's child collection</p>


```csharp
protected void AddRangeToChildren(IEnumerable<Item> items, bool bBrowsingFilesMode = false)
```
### Alias

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets and sets the alias of the item. The setter for this property changes the value for this application session, but will not result
in the new value being persisted for the next session even if changes to the project are saved. If the new value needs to be saved
with other project changes, use the <xref href="ArcGIS.Desktop.Core.Item.SetAlias(System.String)" data-throw-if-not-resolved="false"></xref> method.</p>


```csharp
public string Alias { get; set; }
```
### BlockFromCache

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets whether to block from the cache</p>


```csharp
protected virtual bool BlockFromCache { get; }
```
### CanEdit()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Indicates if metadata is editable for the item.  This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool CanEdit()
```
### Category

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets the category for this item</p>


```csharp
protected virtual string Category { get; }
```
### ClearChildren()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Removes all items from the item's child collection</p>


```csharp
protected void ClearChildren()
```
### ContainerType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets and sets the container type for this item</p>


```csharp
protected string ContainerType { get; set; }
```
### ContextMenuID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets and sets the context menu id for the item</p>


```csharp
protected virtual string ContextMenuID { get; set; }
```
### CopyMetadataFromItem(Item)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Copy metadata from Item. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void CopyMetadataFromItem(Item sourceItem)
```
### CreatedTime

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets the item creation time</p>


```csharp
protected virtual string CreatedTime { get; set; }
```
### Credits

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets information that gives credit to the producer or provider of the item.
Derived from Credits defined in the item's metadata.</p>


```csharp
public string Credits { get; }
```
### DataLastModifiedTime

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets and sets the last modified time for this item</p>


```csharp
protected virtual string DataLastModifiedTime { get; set; }
```
### DeleteMetadataContent(MDDeleteContentOption)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Delete certain content from  the metadata of the current item. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void DeleteMetadataContent(MDDeleteContentOption deleteOption)
```
### Description

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets and sets a description of the item.
Derived from the Description or Abstract defined in the item's metadata.</p>


```csharp
public string Description { get; protected set; }
```
### DisplayType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets and sets the display type string</p>


```csharp
protected virtual string DisplayType { get; set; }
```
### Equals(object)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Determines if the given object is identical to this object.</p>


```csharp
public override bool Equals(object obj)
```
### ExportMetadata(string, MDImportExportOption, MDExportRemovalOption)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Export metadata. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void ExportMetadata(string outputFilePath, MDImportExportOption exportType, MDExportRemovalOption removalOption)
```
### ExportMetadata(string, MDImportExportOption, MDExportRemovalOption, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Export metadata. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void ExportMetadata(string outputFilePath, MDImportExportOption exportType, MDExportRemovalOption removalOption, string styleSheetPath)
```
### FileSize

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets the item file size</p>


```csharp
public virtual long FileSize { get; }
```
### GetChildren()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets the children of this item</p>


```csharp
protected Item[] GetChildren()
```
### GetContainerType()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets the container type</p>


```csharp
protected virtual string GetContainerType()
```
### GetHashCode()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets a hash code associated with this item.</p>


```csharp
public override int GetHashCode()
```
### GetItems()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Browses the contents of an item.
Returns a snapshot collection of of the item's children.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IEnumerable<Item> GetItems()
```
### GetRepairPath()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets the repair path</p>


```csharp
protected virtual string GetRepairPath()
```
### GetXml()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets the item’s metadata XML document as a string.<br>
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetXml()
```
### GroupSortOrder

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets and sets the group sort order for the item.</p>


```csharp
protected int GroupSortOrder { get; set; }
```
### Guid

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets a unique identifier for the item</p>


```csharp
public string Guid { get; protected set; }
```
### HasChild(Item)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Check if the item contains the specified child item in its child collection</p>


```csharp
protected bool HasChild(Item item)
```
### HasChildren

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Checks whether the item has child items in its child item collection</p>


```csharp
protected bool HasChildren { get; }
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets a unique identifier associated with each portal item</p>


```csharp
public string ID { get; protected set; }
```
### ImportMetadata(string, MDImportExportOption)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Import metadata. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void ImportMetadata(string catalogPathOrMDUri, MDImportExportOption importType)
```
### ImportMetadata(string, MDImportExportOption, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Import metadata. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void ImportMetadata(string catalogPathOrMDUri, MDImportExportOption importType, string styleSheetPath)
```
### InsertChild(int, Item)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Insert the child item into the item's child collection at the specified index</p>


```csharp
protected void InsertChild(int index, Item item)
```
### IsContainer

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets if the item contains other items</p>


```csharp
public virtual bool IsContainer { get; }
```
### IsDefault

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets if the item has been set as a default for this project</p>


```csharp
public bool IsDefault { get; protected set; }
```
### IsInvalid

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets if the item is invalid</p>


```csharp
public bool IsInvalid { get; protected set; }
```
### IsInvalidReason

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Get the reason that the item is invalid</p>


```csharp
public ItemIsInvalidReasonEnum IsInvalidReason { get; set; }
```
### IsMainThreadRequired

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Returns whether the Item must be refreshed on the MCT within the
lambda of a QueuedTask.Run.</p>


```csharp
public bool IsMainThreadRequired { get; }
```
### IsSearchable

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets whether the item is searchable. Default is true</p>


```csharp
protected virtual bool IsSearchable { get; }
```
### ItemCategories

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets a list of the item categories in which the item participates</p>


```csharp
public List<ItemCategory> ItemCategories { get; }
```
### Key

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets the associated key for this item</p>


```csharp
protected virtual string Key { get; }
```
### MaxScale

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets the maximum map scale at which the item should draw</p>


```csharp
public double MaxScale { get; }
```
### MinScale

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets the minimum map scale at which the item should draw</p>


```csharp
public double MinScale { get; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets and sets the name of the item</p>


```csharp
public virtual string Name { get; protected set; }
```
### OnCurrentRoot(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Called when the Item becomes the current root item in the Catalog View.</p>


```csharp
public virtual void OnCurrentRoot(bool isActivating)
```
### OnExpanded()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Override to implement any custom logic when your item is expanded</p>


```csharp
public virtual Task OnExpanded()
```
### OnFolderRename(string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Callback when an item's parent folder is being renamed</p>


```csharp
protected virtual void OnFolderRename(string oldValue, string newValue)
```
### Path

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets the path used to access the item</p>


```csharp
public virtual string Path { get; protected set; }
```
### PhysicalPath

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets and sets the location where the item is stored</p>


```csharp
public string PhysicalPath { get; protected set; }
```
### Refresh()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Refreshes the collection of children. Use <xref href="ArcGIS.Desktop.Core.Item.IsMainThreadRequired" data-throw-if-not-resolved="false"></xref> to determine
the correct thread for performing a refresh.</p>


```csharp
public void Refresh()
```
### RemoveChild(Item)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Remove the specified item from the item's child collection</p>


```csharp
protected bool RemoveChild(Item item)
```
### RemoveRangeFromChildren(IEnumerable&lt;Item&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Remove the collection of items from the item's child collection</p>


```csharp
protected void RemoveRangeFromChildren(IEnumerable<Item> items)
```
### Repair(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Repair the path</p>


```csharp
public virtual bool Repair(string newPath)
```
### SaveMetadataAsHTML(string, MDSaveAsHTMLOption)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Save the metadata of the current item as HTML. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SaveMetadataAsHTML(string outputFilePath, MDSaveAsHTMLOption outputType)
```
### SaveMetadataAsUsingCustomXSLT(string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Save the metadata of the current item using customized XSLT. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SaveMetadataAsUsingCustomXSLT(string customXSLTFilePath, string outputFilePath)
```
### SaveMetadataAsXML(string, MDSaveAsXMLOption)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Save the metadata of the current item as XML. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SaveMetadataAsXML(string outputFilePath, MDSaveAsXMLOption outputType)
```
### SearchItem(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Search</p>


```csharp
public bool SearchItem(string searchString)
```
### SetAlias(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Changes the alias value on the given item. This method will return false if the item is not a folder connection.</p>


```csharp
public bool SetAlias(string newAlias)
```
### SetXml(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Sets the item’s metadata to the XML document provided as a string. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetXml(string xml)
```
### SortOrder

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets and sets the project item sort order for the item.</p>


```csharp
protected ProjectItemSortOrder SortOrder { get; set; }
```
### SourceModifiedTime

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets and sets the time when the item's source item was last modified</p>


```csharp
public TimeInstant SourceModifiedTime { get; protected set; }
```
### SourceUri

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets and sets a Uri that identifies the source item from which the item was created in the project</p>


```csharp
public string SourceUri { get; protected set; }
```
### Summary

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets and sets a summary describing the purpose of the item.
Derived from the Summary or Purpose defined in the item's metadata.</p>


```csharp
public string Summary { get; set; }
```
### SupportsCategories

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets whether the item supports categories. The default is false</p>


```csharp
protected virtual bool SupportsCategories { get; }
```
### SupportsDateType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets whether the item supports a date. The default is true</p>


```csharp
protected virtual bool SupportsDateType { get; }
```
### SupportsOwner

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets whether the item supports an owner. The default is false</p>


```csharp
protected virtual bool SupportsOwner { get; }
```
### Synchronize()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Updates metadata with the current properties of the item. Metadata is created for the item if it doesn't already exist.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string Synchronize()
```
### Tags

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets and sets a comma-separated list of tags that describe the item.
Derived from Tags defined in the item's metdata.</p>


```csharp
public string Tags { get; protected set; }
```
### ThumbnailPath

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets and sets a path to a thumbnail that describes and helps to identify the item.
Derived from the Thumbnail that is extracted from the item's metadata.</p>


```csharp
public string ThumbnailPath { get; protected set; }
```
### Title

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets and sets a descriptive title for the item.
Derived from the Title in the item's metadata.</p>


```csharp
public string Title { get; protected set; }
```
### ToString()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Override the default ToString() method.</p>


```csharp
public override string ToString()
```
### Type

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets a localized string indicating the item's type, for example, shapefile</p>


```csharp
public string Type { get; protected set; }
```
### TypeID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets the type identifier that indicates what icon, context menu, and operations the item should have</p>


```csharp
public string TypeID { get; }
```
### TypeKeywords

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets keywords associated with the item's type that support finding the item with a search</p>


```csharp
public string TypeKeywords { get; }
```
### UnlinkPortalItem()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Derived classes can override this method</p>


```csharp
protected virtual Task UnlinkPortalItem()
```
### UpgradeMetadata(MDUpgradeOption)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Upgrade the metadata of the current item. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void UpgradeMetadata(MDUpgradeOption upgradeOption)
```
### Url

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets a URL that can be used to access the item</p>


```csharp
public string Url { get; protected set; }
```
### XMax

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets the maximum value along the x-axis for the item's minimum bounding rectangle</p>


```csharp
public double XMax { get; }
```
### XMin

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets the minimum value along the x-axis for the item's minimum bounding rectangle</p>


```csharp
public double XMin { get; }
```
### YMax

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets the maximum value along the y-axis for the item's minimum bounding rectangle</p>


```csharp
public double YMax { get; }
```
### YMin

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Item.yml" sourcestartlinenumber="1">Gets the minimum value along the y-axis for the item's minimum bounding rectangle</p>


```csharp
public double YMin { get; }
```


