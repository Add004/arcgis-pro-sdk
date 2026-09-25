# PortalGroup

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.Portal.html">Portal</a>
- Assembly: ArcGIS.Desktop.Catalog.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalGroup.yml" sourcestartlinenumber="1">Represents a group within the portal (e.g., &quot;San Bernardino Fires&quot; ).</p>


## Object Signature

```csharp
public class PortalGroup : OnlineItem
```


## Members

### PortalGroup(ItemInfoValue)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalGroup.yml" sourcestartlinenumber="1">For internal use only.</p>


```csharp
protected PortalGroup(ItemInfoValue iiv)
```
### Access

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalGroup.yml" sourcestartlinenumber="1">Gets the access level on the group. Private is the default.
If Organization, only members of the organization can access the group. If Public, all users can access the group.</p>


```csharp
public PortalAccess Access { get; }
```
### GroupID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalGroup.yml" sourcestartlinenumber="1">Gets the id of the group.</p>


```csharp
public string GroupID { get; }
```
### Owner

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalGroup.yml" sourcestartlinenumber="1">Gets the username of the user who owns this item.</p>


```csharp
public string Owner { get; }
```
### PortalQuerySortField

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalGroup.yml" sourcestartlinenumber="1">Gets the sort field to use for this group.</p>


```csharp
public string PortalQuerySortField { get; }
```
### PortalQuerySortOrder

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalGroup.yml" sourcestartlinenumber="1">Gets the sort order to use for this group.</p>


```csharp
public PortalQuerySortOrder PortalQuerySortOrder { get; }
```
### ThumbnailUri

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalGroup.yml" sourcestartlinenumber="1">Gets the URI associated with the thumbnail image for this group.</p>


```csharp
public Uri ThumbnailUri { get; }
```


