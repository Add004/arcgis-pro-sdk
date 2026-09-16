# PortalAccess

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.Portal.html">Portal</a>
- Assembly: ArcGIS.Desktop.Catalog.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalAccess.yml" sourcestartlinenumber="1">Indicates the level of access to a portal object: private, shared, organization, or public.</p>


## Object Signature

```csharp
[DataContract]
public enum PortalAccess
```


## Members

### Organization

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalAccess.yml" sourcestartlinenumber="1">Organization access.</p>


```csharp
[EnumMember(Value = "org")]
Organization = 0
```
### Private

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalAccess.yml" sourcestartlinenumber="1">Private access.</p>


```csharp
[EnumMember(Value = "private")]
Private = 1
```
### Public

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalAccess.yml" sourcestartlinenumber="1">Public access.</p>


```csharp
[EnumMember(Value = "public")]
Public = 2
```
### Shared

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalAccess.yml" sourcestartlinenumber="1">Shared access. Available only for items.</p>


```csharp
[EnumMember(Value = "shared")]
Shared = 3
```


