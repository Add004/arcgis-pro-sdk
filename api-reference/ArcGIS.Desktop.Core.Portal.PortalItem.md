# PortalItem

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.Portal.html">Portal</a>
- Assembly: ArcGIS.Desktop.Catalog.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalItem.yml" sourcestartlinenumber="1">Represents an item (a unit of content) in the portal.
An item may have associated binary or textual data which is available via
the GetDataAsync() method.</p>


## Object Signature

```csharp
public class PortalItem : OnlineItem
```


## Members

### PortalItem(ItemInfoValue)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalItem.yml" sourcestartlinenumber="1">For internal use only.</p>


```csharp
protected PortalItem(ItemInfoValue iiv)
```
### Access

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalItem.yml" sourcestartlinenumber="1">Gets the access level on the item.
<xref href="ArcGIS.Desktop.Core.Portal.PortalAccess.Private?text=Private" data-throw-if-not-resolved="false"></xref> is the default and only the item owner can access.
<xref href="ArcGIS.Desktop.Core.Portal.PortalAccess.Shared?text=Shared" data-throw-if-not-resolved="false"></xref> means the item is shared with a specific group.
<xref href="ArcGIS.Desktop.Core.Portal.PortalAccess.Organization?text=Organization" data-throw-if-not-resolved="false"></xref> restricts item access to members of your organization.
<xref href="ArcGIS.Desktop.Core.Portal.PortalAccess.Public?text=Public" data-throw-if-not-resolved="false"></xref> means any user can access the item.</p>


```csharp
public PortalAccess Access { get; }
```
### FolderID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalItem.yml" sourcestartlinenumber="1">Gets the folder id in which the owner has stored the item.</p>


```csharp
public string FolderID { get; }
```
### GetItemDataAsync(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalItem.yml" sourcestartlinenumber="1">Gets the item data. This resource is available only for the file and text item types.</p>


```csharp
public Task<bool> GetItemDataAsync(string fileName)
```
### ItemID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalItem.yml" sourcestartlinenumber="1">Gets the id of the item.</p>


```csharp
public string ItemID { get; }
```
### ItemKeywords

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalItem.yml" sourcestartlinenumber="1">Gets a list of keywords that further describes the type of this item.</p>


```csharp
public IReadOnlyList<string> ItemKeywords { get; }
```
### ItemTags

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalItem.yml" sourcestartlinenumber="1">Gets a list of user defined tags that are words or short phrases that describe the item.</p>


```csharp
public IReadOnlyList<string> ItemTags { get; }
```
### ItemUri

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalItem.yml" sourcestartlinenumber="1">Gets the uri of this portal item.</p>


```csharp
public Uri ItemUri { get; }
```
### LastModified

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalItem.yml" sourcestartlinenumber="1">Gets the date the item was modified.</p>


```csharp
public DateTime LastModified { get; }
```
### Owner

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalItem.yml" sourcestartlinenumber="1">Gets the username of the user who owns this item.</p>


```csharp
public string Owner { get; }
```
### PortalItemType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalItem.yml" sourcestartlinenumber="1">Gets the GIS content type of this item.</p>


```csharp
public PortalItemType PortalItemType { get; }
```
### ThumbnailUri

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalItem.yml" sourcestartlinenumber="1">Gets the URI associated with the thumbnail image for this item.</p>


```csharp
public Uri ThumbnailUri { get; }
```


