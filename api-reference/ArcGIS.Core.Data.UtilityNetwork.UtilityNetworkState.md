# UtilityNetworkState

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetworkState.yml" sourcestartlinenumber="1">Provides information about the current state of the utility network</p>


## Object Signature

```csharp
public sealed class UtilityNetworkState
```


## Members

### HasDirtyAreas

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetworkState.yml" sourcestartlinenumber="1">Returns whether the network topology of the utility network contains any dirty areas</p>


```csharp
public bool HasDirtyAreas { get; }
```
### HasErrors

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetworkState.yml" sourcestartlinenumber="1">Returns whether the network topology of the utility network has any errors.</p>


```csharp
public bool HasErrors { get; }
```
### IsNetworkTopologyEnabled

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetworkState.yml" sourcestartlinenumber="1">Returns whether the network topology of the utility network is enabled.</p>


```csharp
public bool IsNetworkTopologyEnabled { get; }
```
### LastConsistentMoment

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetworkState.yml" sourcestartlinenumber="1">Returns the <xref href="System.DateTime" data-throw-if-not-resolved="false"></xref> of the last time that the utility network was fully validated.</p>


```csharp
public DateTime LastConsistentMoment { get; }
```
### LastUpdateIsConnectedMoment

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetworkState.yml" sourcestartlinenumber="1">Returns the <xref href="System.DateTime" data-throw-if-not-resolved="false"></xref> of the last time that the Update Is Connected geoprocessing tool was run on the utility network.</p>


```csharp
public DateTime LastUpdateIsConnectedMoment { get; }
```


