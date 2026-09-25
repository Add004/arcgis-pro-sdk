# TierGroup

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.TierGroup.yml" sourcestartlinenumber="1">Tier groups provide an extra level of organization for tiers.</p>
<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.TierGroup.yml" sourcestartlinenumber="3">For example, a gas network may be divided into two tier groups - Transmission and Distribution.
Each of these tier groups would contain a set of tiers specific to that group.  For example, Distribution Pressure and Distribution Isolation might be tiers within the
Distribution tier group.</p>


## Object Signature

```csharp
public sealed class TierGroup
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.TierGroup.yml" sourcestartlinenumber="1">Tier groups are only applicable to hierarchical networks.</p>


## Members

### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.TierGroup.yml" sourcestartlinenumber="1">The name of the tier group.</p>


```csharp
public string Name { get; }
```
### Tiers

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.TierGroup.yml" sourcestartlinenumber="1">Provides a list of <xref href="ArcGIS.Core.Data.UtilityNetwork.Tier" data-throw-if-not-resolved="false"></xref>s within this tier group.</p>


```csharp
public IReadOnlyList<Tier> Tiers { get; }
```


