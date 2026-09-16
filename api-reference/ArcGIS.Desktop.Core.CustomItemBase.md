# CustomItemBase

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.CustomItemBase.yml" sourcestartlinenumber="1">Base class for deriving custom items. Custom items are shown in the Catalog View and Pane</p>


## Object Signature

```csharp
public abstract class CustomItemBase : Item, IMetadata
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Core.CustomItemBase.yml" sourcestartlinenumber="1">Custom items that have a physical file representation on disk should registered
their file extension within the Config.daml so that they can be browsed within
Folder collection in Catalog. Registration is within the <b>esri_customItems</b> category
and should include the fileExtension of your custom item and keywords that can be used in
the Catalog search. Note: The Pro SDK template for custom items will automatically generate a set of Config.daml
entries for you.<br>
Custom items that can contain child items should set <b>IsContainer</b>=<b>true</b>.
The custom item <xref href="ArcGIS.Desktop.Core.CustomItemBase.Fetch" data-throw-if-not-resolved="false"></xref> method is called when the
item is first expanded in the Catalog to allow custom items to retrieve their child
items</p>


## Members

### CustomItemBase()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.CustomItemBase.yml" sourcestartlinenumber="1">Default constructor</p>


```csharp
public CustomItemBase()
```
### CustomItemBase(ItemInfoValue)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.CustomItemBase.yml" sourcestartlinenumber="1">This is the primary constructor called by Catalog and Pro internals when
creating custom items</p>


```csharp
public CustomItemBase(ItemInfoValue itemInfoValue)
```
### CustomItemBase(string, string, string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.CustomItemBase.yml" sourcestartlinenumber="1">This constructor is provided for use by 3rd parties implementing a custom item. It is not called by Catalog.</p>


```csharp
public CustomItemBase(string name, string catalogPath, string typeID)
```
### CustomItemBase(string, string, string, string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.CustomItemBase.yml" sourcestartlinenumber="1">This constructor is provided for use by 3rd parties implementing a custom item. It is not called by Catalog.</p>


```csharp
public CustomItemBase(string name, string catalogPath, string typeID, string containerType)
```
### CanDelete()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.CustomItemBase.yml" sourcestartlinenumber="1">Gets whether your item can be deleted. The default is <b>false</b></p>


```csharp
public virtual bool CanDelete()
```
### CanRename

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.CustomItemBase.yml" sourcestartlinenumber="1">Gets whether the item can be renamed. The default is <b>true</b></p>


```csharp
protected virtual bool CanRename { get; }
```
### Delete()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.CustomItemBase.yml" sourcestartlinenumber="1">Override to implement any custom logic for delete of your item.</p>


```csharp
public virtual void Delete()
```
### Fetch()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.CustomItemBase.yml" sourcestartlinenumber="1">Custom items that are containers should implement fetch to populate their
child items when they are expanded for the first time in Catalog.</p>


```csharp
public virtual void Fetch()
```
### LargeImage

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.CustomItemBase.yml" sourcestartlinenumber="1">Gets the large image. Override to provide a custom large image</p>


```csharp
public virtual ImageSource LargeImage { get; }
```
### OnRename(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.CustomItemBase.yml" sourcestartlinenumber="1">Override to implement any custom logic for rename of your item</p>


```csharp
protected virtual bool OnRename(string newName)
```
### RenameAsync(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.CustomItemBase.yml" sourcestartlinenumber="1">Rename the custom item</p>


```csharp
public Task<bool> RenameAsync(string newName)
```
### Selected()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.CustomItemBase.yml" sourcestartlinenumber="1">Override to implement any custom logic for select of your item</p>


```csharp
public virtual void Selected()
```
### SmallImage

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.CustomItemBase.yml" sourcestartlinenumber="1">Gets the small image. Override to provide a custom small image</p>


```csharp
public virtual Task<ImageSource> SmallImage { get; }
```
### UnlinkPortalItem()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.CustomItemBase.yml" sourcestartlinenumber="1">Used by catalog for internal purposes</p>


```csharp
protected override sealed Task UnlinkPortalItem()
```
### Unselected()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.CustomItemBase.yml" sourcestartlinenumber="1">Override to implement any custom logic for unselection of your item</p>


```csharp
public virtual void Unselected()
```


