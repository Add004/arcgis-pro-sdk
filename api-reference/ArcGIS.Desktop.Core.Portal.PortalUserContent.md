# PortalUserContent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.Portal.html">Portal</a>
- Assembly: ArcGIS.Desktop.Catalog.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalUserContent.yml" sourcestartlinenumber="1">Represents the content (folders and items) of a portal user.</p>


## Object Signature

```csharp
public sealed class PortalUserContent
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalUserContent.yml" sourcestartlinenumber="1">PortalUserContent is a snapshot of the content that is retrieved when the (given) portal
was queried.</p>


## Members

### PortalFolders

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalUserContent.yml" sourcestartlinenumber="1">Gets the collection of folders.</p>


```csharp
public IReadOnlyList<PortalFolder> PortalFolders { get; }
```
### PortalItems

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalUserContent.yml" sourcestartlinenumber="1">Gets the collection of portal items.</p>


```csharp
public IReadOnlyList<PortalItem> PortalItems { get; }
```


