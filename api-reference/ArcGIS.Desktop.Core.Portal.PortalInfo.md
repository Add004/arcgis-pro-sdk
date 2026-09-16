# PortalInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.Portal.html">Portal</a>
- Assembly: ArcGIS.Desktop.Catalog.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalInfo.yml" sourcestartlinenumber="1">Includes information such as the name, logo, featured items and supported protocols (http vs https) for a portal.</p>


## Object Signature

```csharp
public sealed class PortalInfo
```

## Remarks

<pre><code sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalInfo.yml" sourcestartlinenumber="1">        If the user is not logged in or if the logged user doesn't belong to an organization, the information concerns 
        the &lt;b&gt;&lt;i&gt;default&lt;/i&gt;&lt;/b&gt; view of the portal. If the user is logged in or if the Url is an organization custom Url, 
        the information will be &lt;b&gt;&lt;i&gt;specific&lt;/i&gt;&lt;/b&gt; to the organization that the user belongs to.
</code></pre>
<p></p>
<pre><code sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalInfo.yml" sourcestartlinenumber="6">        The default view of the portal is dependent on the culture of the user which is obtained from the users profile.

        &lt;p&gt;
        You may get the current portal info by the ArcGISPortal.GetPortalInfoAsync (extension) method.
        &lt;/p&gt;
</code></pre>


## Members

### Access

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalInfo.yml" sourcestartlinenumber="1">Gets who can view your organization as an anonymous user.</p>


```csharp
public PortalAccess Access { get; }
```
### CanSearchPublic

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalInfo.yml" sourcestartlinenumber="1">Gets a value indicating if public items, groups, and users are included
in search queries on the portal. If the user is NOT signed on <b>true</b> (the default) is always returned.</p>


```csharp
public bool CanSearchPublic { get; }
```
### CanSharePublic

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalInfo.yml" sourcestartlinenumber="1">Gets if the organization allows or disallows a user to share groups or items publicly. If the
user is NOT signed on <b>true</b> (the default) is always returned.</p>


```csharp
public bool CanSharePublic { get; }
```
### Culture

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalInfo.yml" sourcestartlinenumber="1">Gets the locale information for the organization (for example, en, ru, fr, nl, zh-CN).</p>


```csharp
public string Culture { get; }
```
### CurrentVersion

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalInfo.yml" sourcestartlinenumber="1">Gets the current version of the portal.</p>


```csharp
public string CurrentVersion { get; }
```
### CustomBaseUrl

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalInfo.yml" sourcestartlinenumber="1">Gets the custom base URL for the organization.</p>


```csharp
public string CustomBaseUrl { get; }
```
### FeaturedGroups

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalInfo.yml" sourcestartlinenumber="1">Gets the featured groups for the organization. These are the groups that will be highlighted on the Groups page.</p>


```csharp
public IReadOnlyList<PortalFeaturedGroupInfo> FeaturedGroups { get; }
```
### GroupQueries

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalInfo.yml" sourcestartlinenumber="1">Gets a collection of queries identifying different portal content driven by different groups.</p>


```csharp
public IReadOnlyDictionary<string, string> GroupQueries { get; }
```
### IsPortal

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalInfo.yml" sourcestartlinenumber="1">Gets a value indicating whether the portal is on premises.</p>


```csharp
public bool IsPortal { get; }
```
### MaxTokenExpirationMinutes

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalInfo.yml" sourcestartlinenumber="1">Gets the maximum validity in minutes of tokens issued for users of the organization. If the
user is NOT signed on <b>-1</b> (the default) is always returned.</p>


```csharp
public int MaxTokenExpirationMinutes { get; }
```
### OrganizationDescription

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalInfo.yml" sourcestartlinenumber="1">Gets the description of the organization.
In the case of non-organizational users of ArcGIS Online or a multi-tenant portal, this will be null.</p>


```csharp
public string OrganizationDescription { get; }
```
### OrganizationId

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalInfo.yml" sourcestartlinenumber="1">Gets the id of the organization, if the user belongs to one.</p>


```csharp
public string OrganizationId { get; }
```
### OrganizationName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalInfo.yml" sourcestartlinenumber="1">Gets the name of the organization.
In the case of non-organizational users of ArcGIS Online or a multi-tenant portal, this will be null.</p>


```csharp
public string OrganizationName { get; }
```
### OrganizationRegion

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalInfo.yml" sourcestartlinenumber="1">Gets the region for the organization.</p>


```csharp
public string OrganizationRegion { get; }
```
### OrganizationSubdomain

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalInfo.yml" sourcestartlinenumber="1">Gets the prefix selected by the organization's administrator to be used with the CustomBaseURL.</p>


```csharp
public string OrganizationSubdomain { get; }
```
### Portal

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalInfo.yml" sourcestartlinenumber="1">Gets the ArcGIS portal.</p>


```csharp
public ArcGISPortal Portal { get; }
```
### PortalHostName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalInfo.yml" sourcestartlinenumber="1">Gets the portal host's URL.</p>


```csharp
public string PortalHostName { get; }
```
### PortalMode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalInfo.yml" sourcestartlinenumber="1">Gets the portal mode (singletenant, multitenant).</p>


```csharp
public PortalMode PortalMode { get; }
```
### PortalName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalInfo.yml" sourcestartlinenumber="1">Gets the name of the portal.</p>


```csharp
public string PortalName { get; }
```
### PortalThumbnail

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalInfo.yml" sourcestartlinenumber="1">Gets the portal thumbnail name. The PortalThumbnail can be empty.</p>


```csharp
public string PortalThumbnail { get; }
```
### PortalThumbnailUri

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalInfo.yml" sourcestartlinenumber="1">Gets the URI of the portal thumbnail.</p>


```csharp
public Uri PortalThumbnailUri { get; }
```
### RawJson

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalInfo.yml" sourcestartlinenumber="1">Gets the complete Json string returned from the portal self query.</p>


```csharp
public string RawJson { get; }
```
### UseVectorBasemaps

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalInfo.yml" sourcestartlinenumber="1">Gets if the organization is configured to use Esri vector base maps.</p>


```csharp
public bool UseVectorBasemaps { get; }
```


