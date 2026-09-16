# ContingencyValidationResult

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.ContingencyValidationResult.yml" sourcestartlinenumber="1">Provides information about valid and invalid contingency constraints.</p>


## Object Signature

```csharp
public sealed class ContingencyValidationResult
```


## Members

### Matches

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.ContingencyValidationResult.yml" sourcestartlinenumber="1">Gets the list of matched contingency constraints.</p>


```csharp
public IReadOnlyList<Contingency> Matches { get; }
```
### Violations

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.ContingencyValidationResult.yml" sourcestartlinenumber="1">Gets the list of violated contingency constraints.</p>


```csharp
public IReadOnlyList<ContingencyViolation> Violations { get; }
```


