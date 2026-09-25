# Tier

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Tier.yml" sourcestartlinenumber="1">Tiers demarcate a logical level within a network.  E.g., in an electric distribution network, there may be Subtransmission, MediumVoltage and LowVoltage tiers.</p>


## Object Signature

```csharp
public sealed class Tier
```


## Members

### DomainNetwork

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Tier.yml" sourcestartlinenumber="1">Gets the parent <xref href="ArcGIS.Core.Data.UtilityNetwork.Tier.DomainNetwork" data-throw-if-not-resolved="false"></xref> that contains this tier.</p>


```csharp
public DomainNetwork DomainNetwork { get; }
```
### GetDiagramTemplateNames()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Tier.yml" sourcestartlinenumber="1">Gets the default diagram template names for this tier.</p>


```csharp
public IReadOnlyList<string> GetDiagramTemplateNames()
```
### GetEditModeForUpdateSubnetwork(VersionSpecification)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Tier.yml" sourcestartlinenumber="1">Describes how update subnetwork uses eventing for a particular version type.</p>


```csharp
public EditMode GetEditModeForUpdateSubnetwork(VersionSpecification specification)
```
### GetTraceConfiguration()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Tier.yml" sourcestartlinenumber="1">The default <xref href="ArcGIS.Core.Data.UtilityNetwork.Trace.TraceConfiguration" data-throw-if-not-resolved="false"></xref> that defines subnetworks within this tier.</p>


```csharp
public TraceConfiguration GetTraceConfiguration()
```
### HasUpdateSubnetworkPolicy(UpdateSubnetworkPolicy)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Tier.yml" sourcestartlinenumber="1">Describes how update subnetwork promulgates subnetwork names to associated features.</p>


```csharp
public bool HasUpdateSubnetworkPolicy(UpdateSubnetworkPolicy policy)
```
### IsDisjointSubnetworkSupported

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Tier.yml" sourcestartlinenumber="1">Gets a value indicating whether disjoint subnetworks are supported in this tier.</p>


```csharp
public bool IsDisjointSubnetworkSupported { get; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Tier.yml" sourcestartlinenumber="1">Get the name of the tier.</p>


```csharp
public string Name { get; }
```
### Rank

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Tier.yml" sourcestartlinenumber="1">Gets the numeric rank of the tier.</p>


```csharp
public int Rank { get; }
```
### SubnetworkFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Tier.yml" sourcestartlinenumber="1">Gets the name of the subnetwork name field.</p>


```csharp
public string SubnetworkFieldName { get; }
```
### TierGroup

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Tier.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.UtilityNetwork.Tier.TierGroup" data-throw-if-not-resolved="false"></xref> this tier participates in.</p>


```csharp
public TierGroup TierGroup { get; }
```
### TopologyType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Tier.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.UtilityNetwork.TierTopologyType" data-throw-if-not-resolved="false"></xref> of the tier.</p>


```csharp
public TierTopologyType TopologyType { get; }
```
### ValidDevices

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Tier.yml" sourcestartlinenumber="1">Gets a list of valid <xref href="ArcGIS.Core.Data.UtilityNetwork.AssetType" data-throw-if-not-resolved="false"></xref> values for devices that can belong to this tier.</p>


```csharp
public IReadOnlyList<AssetType> ValidDevices { get; }
```
### ValidEdgeObjects

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Tier.yml" sourcestartlinenumber="1">Gets a list of valid <xref href="ArcGIS.Core.Data.UtilityNetwork.AssetType" data-throw-if-not-resolved="false"></xref> values for edge objects that can belong to this tier.</p>


```csharp
public IReadOnlyList<AssetType> ValidEdgeObjects { get; }
```
### ValidJunctionObjectSubnetworkControllers

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Tier.yml" sourcestartlinenumber="1">Gets a list of valid <xref href="ArcGIS.Core.Data.UtilityNetwork.AssetType" data-throw-if-not-resolved="false"></xref> values for junction object subnetwork controllers within this tier.</p>


```csharp
public IReadOnlyList<AssetType> ValidJunctionObjectSubnetworkControllers { get; }
```
### ValidJunctionObjects

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Tier.yml" sourcestartlinenumber="1">Gets a list of valid <xref href="ArcGIS.Core.Data.UtilityNetwork.AssetType" data-throw-if-not-resolved="false"></xref> values for junction objects that can belong to this tier.</p>


```csharp
public IReadOnlyList<AssetType> ValidJunctionObjects { get; }
```
### ValidJunctions

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Tier.yml" sourcestartlinenumber="1">Gets a list of valid <xref href="ArcGIS.Core.Data.UtilityNetwork.AssetType" data-throw-if-not-resolved="false"></xref> values for junctions that can belong to this tier.</p>


```csharp
public IReadOnlyList<AssetType> ValidJunctions { get; }
```
### ValidLines

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Tier.yml" sourcestartlinenumber="1">Gets a list of valid <xref href="ArcGIS.Core.Data.UtilityNetwork.AssetType" data-throw-if-not-resolved="false"></xref> values for lines that can belong to this tier.</p>


```csharp
public IReadOnlyList<AssetType> ValidLines { get; }
```
### ValidSubnetworkControllers

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Tier.yml" sourcestartlinenumber="1">Gets a list of valid <xref href="ArcGIS.Core.Data.UtilityNetwork.AssetType" data-throw-if-not-resolved="false"></xref> values for device subnetwork controllers within this tier.</p>


```csharp
public IReadOnlyList<AssetType> ValidSubnetworkControllers { get; }
```
### ValidSubnetworkLines

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Tier.yml" sourcestartlinenumber="1">Gets a list of <xref href="ArcGIS.Core.Data.UtilityNetwork.AssetType" data-throw-if-not-resolved="false"></xref> values for lines that are aggregated into the SubnetLine feature class.</p>


```csharp
public IReadOnlyList<AssetType> ValidSubnetworkLines { get; }
```


