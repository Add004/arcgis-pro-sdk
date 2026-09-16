# SubnetworkManager

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.SubnetworkManager.yml" sourcestartlinenumber="1">The SubnetworkManager is a class that contains a collection of subnetwork management routines.</p>


## Object Signature

```csharp
public sealed class SubnetworkManager : CoreObjectsBase, IDisposable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.SubnetworkManager.yml" sourcestartlinenumber="1">The SubnetworkManager object is obtained by calling <xref href="ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.GetSubnetworkManager" data-throw-if-not-resolved="false"></xref>.</p>


## Members

### DisableController(Element)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.SubnetworkManager.yml" sourcestartlinenumber="1">Disables a feature corresponding to <code class="paramref">device</code> from being a <xref href="ArcGIS.Core.Data.UtilityNetwork.SubnetworkController" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void DisableController(Element device)
```
### EnableController(Tier, Element, string, string, string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.SubnetworkManager.yml" sourcestartlinenumber="1">Enables a feature corresponding to <code class="paramref">device</code> to be a <xref href="ArcGIS.Core.Data.UtilityNetwork.SubnetworkController" data-throw-if-not-resolved="false"></xref>
and adds it to an existing <xref href="ArcGIS.Core.Data.UtilityNetwork.Subnetwork" data-throw-if-not-resolved="false"></xref> corresponding to <code class="paramref">subnetworkName</code>.
If the specified subnetwork does not exist, a new one will be created.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Subnetwork EnableController(Tier tier, Element device, string subnetworkName, string controllerName, string description, string notes)
```
### GetSubnetwork(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.SubnetworkManager.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.UtilityNetwork.Subnetwork" data-throw-if-not-resolved="false"></xref> specified by <code class="paramref">name</code>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Subnetwork GetSubnetwork(string name)
```
### GetSubnetworks(Tier, SubnetworkStates)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.SubnetworkManager.yml" sourcestartlinenumber="1">Gets the list of <xref href="ArcGIS.Core.Data.UtilityNetwork.Subnetwork" data-throw-if-not-resolved="false"></xref> in the <xref href="ArcGIS.Core.Data.UtilityNetwork.Tier" data-throw-if-not-resolved="false"></xref>
specified by <code class="paramref">tier</code> whose <xref href="ArcGIS.Core.Data.UtilityNetwork.SubnetworkStates" data-throw-if-not-resolved="false"></xref> are in <code class="paramref">subnetworkStates</code>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<Subnetwork> GetSubnetworks(Tier tier, SubnetworkStates subnetworkStates)
```
### UpdateAllSubnetworks(Tier, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.SubnetworkManager.yml" sourcestartlinenumber="1">Updates all the subnetworks that are part of the <code class="paramref">tier</code> in a utility network.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void UpdateAllSubnetworks(Tier tier, bool continueOnFailure)
```


