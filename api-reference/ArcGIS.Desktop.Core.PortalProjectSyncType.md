# PortalProjectSyncType

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.PortalProjectSyncType.yml" sourcestartlinenumber="1">Sets flow direction when merging portal projects</p>


## Object Signature

```csharp
public enum PortalProjectSyncType
```

## Remarks

<p>
    When a project is saved to portal, or a portal project is saved as another portal project, or  
    a local cached project is getting updates from portal, the PortalProjectSyncType is used to
    specify the flow direction of the synchronization.
    </p>


## Members

### ForcePull

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.PortalProjectSyncType.yml" sourcestartlinenumber="1">New local items are deleted. New remote items are pulled. Conflicts are automatically resolved to pull from the portal.</p>


```csharp
ForcePull = 3
```
### ForcePullIgnoreLock

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.PortalProjectSyncType.yml" sourcestartlinenumber="1">New local items are deleted. New remote items are pulled. Conflicts are automatically resolved to pull from the portal and the lock will be ignored.</p>


```csharp
ForcePullIgnoreLock = 4
```
### ForcePush

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.PortalProjectSyncType.yml" sourcestartlinenumber="1">Portal items are overwritten with local items. Conflicts are automatically resolved to push to the portal.</p>


```csharp
ForcePush = 1
```
### Pull

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.PortalProjectSyncType.yml" sourcestartlinenumber="1">New remote items are pulled from portal and new local items are pushed to portal. Conflicts are automatically resolved to pull from the portal.</p>


```csharp
Pull = 2
```
### Push

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.PortalProjectSyncType.yml" sourcestartlinenumber="1">New remote items are pulled from portal and new local items are pushed to portal. Conflicts are automatically resolved to push to the portal.</p>


```csharp
Push = 0
```


