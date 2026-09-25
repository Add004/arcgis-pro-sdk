# TierDefinition

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.TierDefinition.yml" sourcestartlinenumber="1">Returns the type of subnetworks suported in this domain network.</p>


## Object Signature

```csharp
public enum TierDefinition
```


## Members

### Hierarchical

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.TierDefinition.yml" sourcestartlinenumber="1">Subnetworks within this domain network are organized in a hierarchical fashion.  Features may belong to multiple tiers, organized in a hierarchical fashion.  These are typically used with pressure networks.</p>


```csharp
Hierarchical = 1
```
### None

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.TierDefinition.yml" sourcestartlinenumber="1">This domain network doesn't contain subnetworks.</p>


```csharp
None = 0
```
### Partitioned

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.TierDefinition.yml" sourcestartlinenumber="1">Subnetworks within this domain network are partitioned into different tiers.  Features belong to a single tier (except for subnetwork controllers, which span two tiers).  These are typically used with electrical networks.</p>


```csharp
Partitioned = 2
```


