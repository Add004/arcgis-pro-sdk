# DomainNetwork

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.DomainNetwork.yml" sourcestartlinenumber="1">The DomainNetwork class is used to represent a domain network inside a utility network.  A domain network typically represents an industry
domain such as 'Electric Distribution', 'Gas', or 'Water.'
DomainNetwork objects can be obtained by calling <xref href="ArcGIS.Core.Data.UtilityNetwork.UtilityNetworkDefinition.GetDomainNetworks" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class DomainNetwork
```


## Members

### Alias

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.DomainNetwork.yml" sourcestartlinenumber="1">Gets the alias name of the DomainNetwork.</p>


```csharp
public string Alias { get; }
```
### GetTier(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.DomainNetwork.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.UtilityNetwork.Tier" data-throw-if-not-resolved="false"></xref> object with the specified name.</p>


```csharp
public Tier GetTier(string tierName)
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.DomainNetwork.yml" sourcestartlinenumber="1">Gets a numeric ID for a DomainNetwork.</p>


```csharp
public int ID { get; }
```
### IsStructureNetwork

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.DomainNetwork.yml" sourcestartlinenumber="1">Returns whether this domain network represents a structure network.</p>


```csharp
public bool IsStructureNetwork { get; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.DomainNetwork.yml" sourcestartlinenumber="1">Gets the name of the DomainNetwork.</p>


```csharp
public string Name { get; }
```
### NetworkSources

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.DomainNetwork.yml" sourcestartlinenumber="1">Gets a list of all of the <xref href="ArcGIS.Core.Data.UtilityNetwork.NetworkSource" data-throw-if-not-resolved="false"></xref>s for this domain network.</p>


```csharp
public IReadOnlyList<NetworkSource> NetworkSources { get; }
```
### SubnetworkControllerType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.DomainNetwork.yml" sourcestartlinenumber="1">Returns the type of subnetwork controller supported in this domain network.</p>


```csharp
public SubnetworkControllerType SubnetworkControllerType { get; }
```
### TierDefinition

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.DomainNetwork.yml" sourcestartlinenumber="1">Returns the type of subnetworks supported in this domain network.</p>


```csharp
public TierDefinition TierDefinition { get; }
```
### TierGroups

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.DomainNetwork.yml" sourcestartlinenumber="1">Gets a list of all of the <xref href="ArcGIS.Core.Data.UtilityNetwork.TierGroup" data-throw-if-not-resolved="false"></xref>s for this domain network.</p>


```csharp
public IReadOnlyList<TierGroup> TierGroups { get; }
```
### Tiers

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.DomainNetwork.yml" sourcestartlinenumber="1">Gets a list of <xref href="ArcGIS.Core.Data.UtilityNetwork.Tier" data-throw-if-not-resolved="false"></xref> objects within this domain network.</p>


```csharp
public IReadOnlyList<Tier> Tiers { get; }
```


