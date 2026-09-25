# CombinePolicy

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.Telecom.html">Telecom</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CombinePolicy.yml" sourcestartlinenumber="1">Represents a combine policy that defines rules for combining network elements in a telecom domain network.</p>


## Object Signature

```csharp
public sealed class CombinePolicy
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CombinePolicy.yml" sourcestartlinenumber="1">Combine policies control how element attributes are handled when multiple elements are combined into a single element.</p>


## Members

### FieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CombinePolicy.yml" sourcestartlinenumber="1">The field name for the combine policy.</p>


```csharp
public string FieldName { get; }
```
### NetworkSource

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CombinePolicy.yml" sourcestartlinenumber="1">The network source that the combine policy applies to.</p>


```csharp
public NetworkSource NetworkSource { get; }
```
### Policy

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.CombinePolicy.yml" sourcestartlinenumber="1">The combine policy type.</p>


```csharp
public CombinePolicyType Policy { get; }
```


