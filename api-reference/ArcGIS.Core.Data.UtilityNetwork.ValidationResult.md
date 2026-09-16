# ValidationResult

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.ValidationResult.yml" sourcestartlinenumber="1">Provides information about the results of a call to <xref href="ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.ValidateNetworkTopology" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class ValidationResult
```


## Members

### GetDiscoveredSubnetworks()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.ValidationResult.yml" sourcestartlinenumber="1">Gets the discovered subnetworks during the <xref href="ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.ValidateNetworkTopology" data-throw-if-not-resolved="false"></xref> operation.</p>


```csharp
public IReadOnlyList<Subnetwork> GetDiscoveredSubnetworks()
```
### HasErrors

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.ValidationResult.yml" sourcestartlinenumber="1">Returns whether new errors were found in the network topology validation operation.</p>


```csharp
public bool HasErrors { get; }
```
### IsDiscoveredSubnetworksSupported

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.ValidationResult.yml" sourcestartlinenumber="1">Returns whether the utility network supports the capability to return the discovered subnetworks.</p>


```csharp
public bool IsDiscoveredSubnetworksSupported { get; }
```
### IsFullUpdate

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.ValidationResult.yml" sourcestartlinenumber="1">Returns whether the call to <xref href="ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.ValidateNetworkTopology" data-throw-if-not-resolved="false"></xref>() was executed on the entire network.</p>


```csharp
public bool IsFullUpdate { get; }
```
### UpdateLocalTime

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.ValidationResult.yml" sourcestartlinenumber="1">The <xref href="System.DateTime" data-throw-if-not-resolved="false"></xref> when the <xref href="ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.ValidateNetworkTopology" data-throw-if-not-resolved="false"></xref>() call took place, converted to the time zone of the ArcGIS Pro client machine.</p>


```csharp
public DateTime UpdateLocalTime { get; }
```


