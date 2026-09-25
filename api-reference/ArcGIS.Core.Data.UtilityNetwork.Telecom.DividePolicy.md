# DividePolicy

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.Telecom.html">Telecom</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.DividePolicy.yml" sourcestartlinenumber="1">Represents a divide policy that defines rules for dividing network elements in a telecom domain network.</p>


## Object Signature

```csharp
public sealed class DividePolicy
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.DividePolicy.yml" sourcestartlinenumber="1">Divide policies control how element attributes are distributed when a single element is divided into multiple elements.</p>


## Members

### FieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.DividePolicy.yml" sourcestartlinenumber="1">The field name for the divide policy.</p>


```csharp
public string FieldName { get; }
```
### NetworkSource

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.DividePolicy.yml" sourcestartlinenumber="1">The network source that the divide policy applies to.</p>


```csharp
public NetworkSource NetworkSource { get; }
```
### Policy

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Telecom.DividePolicy.yml" sourcestartlinenumber="1">The divide policy type.</p>


```csharp
public DividePolicyType Policy { get; }
```


