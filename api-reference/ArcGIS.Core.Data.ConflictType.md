# ConflictType

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.ConflictType.yml" sourcestartlinenumber="1">Specifies the type of conflict in a row of a versioned feature class.</p>


## Object Signature

```csharp
public enum ConflictType
```


## Members

### DeleteUpdate

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.ConflictType.yml" sourcestartlinenumber="1">Row has been deleted in the source and updated in the difference.</p>


```csharp
DeleteUpdate = 5
```
### UpdateDelete

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.ConflictType.yml" sourcestartlinenumber="1">Row has been updated in the source and deleted in the difference.</p>


```csharp
UpdateDelete = 4
```
### UpdateUpdate

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.ConflictType.yml" sourcestartlinenumber="1">Row has been updated in both the source and difference.</p>


```csharp
UpdateUpdate = 3
```


