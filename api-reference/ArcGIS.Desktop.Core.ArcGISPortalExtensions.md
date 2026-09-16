# ArcGISPortalExtensions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Catalog.dll

<p sourcefile="api/ArcGIS.Desktop.Core.ArcGISPortalExtensions.yml" sourcestartlinenumber="1">Extension methods for the <xref href="ArcGIS.Desktop.Core.ArcGISPortal" data-throw-if-not-resolved="false"></xref> class.</p>


## Object Signature

```csharp
public static class ArcGISPortalExtensions
```


## Members

### GetBasemapsAsync(ArcGISPortal)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.ArcGISPortalExtensions.yml" sourcestartlinenumber="1">Gets the list of base maps that are configured for the given portal.</p>


```csharp
public static Task<IReadOnlyList<PortalItem>> GetBasemapsAsync(this ArcGISPortal portal)
```
### GetGroupsFromUserAsync(ArcGISPortal, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.ArcGISPortalExtensions.yml" sourcestartlinenumber="1">Gets the groups from the user's community information.</p>


```csharp
public static Task<IReadOnlyList<PortalGroup>> GetGroupsFromUserAsync(this ArcGISPortal portal, string username)
```
### GetPortalInfoAsync(ArcGISPortal)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.ArcGISPortalExtensions.yml" sourcestartlinenumber="1">Executes a self query on the specified portal to return its <xref href="ArcGIS.Desktop.Core.Portal.PortalInfo" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static Task<PortalInfo> GetPortalInfoAsync(this ArcGISPortal portal)
```
### GetUserContentAsync(ArcGISPortal, string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.ArcGISPortalExtensions.yml" sourcestartlinenumber="1">Gets the given username's content. Items are either in the home folder for the user, e.g.
/content/users/{username} or in a subfolder of the home folder with the given folder ID.
Multilevel folders are not supported.</p>


```csharp
public static Task<PortalUserContent> GetUserContentAsync(this ArcGISPortal portal, string username, string folderId = "")
```
### SearchForContentAsync(ArcGISPortal, PortalQueryParameters)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.ArcGISPortalExtensions.yml" sourcestartlinenumber="1">Searches for portal items from a query string.</p>


```csharp
public static Task<PortalQueryResultSet<PortalItem>> SearchForContentAsync(this ArcGISPortal portal, PortalQueryParameters queryParams)
```


