# ConflictDetectionType

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.ConflictDetectionType.yml" sourcestartlinenumber="1">Specifies how conflicts are defined.</p>


## Object Signature

```csharp
public enum ConflictDetectionType
```


## Members

### ByColumn

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.ConflictDetectionType.yml" sourcestartlinenumber="1">Conflicts are only detected if the same attribute is updated in the source and target versions.</p>


```csharp
ByColumn = 1
```
### ByRow

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.ConflictDetectionType.yml" sourcestartlinenumber="1">Conflicts are detected if the same row is edited in the source and target versions.</p>


```csharp
ByRow = 0
```


