# UtilityNetworkExtensions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>
- Assembly: ArcGIS.Desktop.Extensions.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetworkExtensions.yml" sourcestartlinenumber="1">This convenience API provides commonly-used UtilityNetwork-related extension methods for the <i>ArcGIS.Core.Data.UtilityNetwork</i> API.</p>


## Object Signature

```csharp
public static class UtilityNetworkExtensions
```


## Members

### DisableControllerInEditOperation(SubnetworkManager, Element)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetworkExtensions.yml" sourcestartlinenumber="1">Disables a feature corresponding to <code class="paramref">device</code> from being a <xref href="ArcGIS.Core.Data.UtilityNetwork.SubnetworkController" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void DisableControllerInEditOperation(this SubnetworkManager subnetworkManager, Element device)
```
### EnableControllerInEditOperation(SubnetworkManager, Tier, Element, string, string, string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetworkExtensions.yml" sourcestartlinenumber="1">Enables a feature corresponding to <code class="paramref">device</code> to be a <xref href="ArcGIS.Core.Data.UtilityNetwork.SubnetworkController" data-throw-if-not-resolved="false"></xref>
and adds it to an existing <xref href="ArcGIS.Core.Data.UtilityNetwork.Subnetwork" data-throw-if-not-resolved="false"></xref> corresponding to <code class="paramref">subnetworkName</code>.
If the specified subnetwork does not exist, a new one will be created.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static Subnetwork EnableControllerInEditOperation(this SubnetworkManager subnetworkManager, Tier tier, Element device, string subnetworkName, string controllerName, string description, string notes)
```
### ValidateNetworkTopologyInEditOperation(UtilityNetwork)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetworkExtensions.yml" sourcestartlinenumber="1">Validates the utility network topology in an edit operation. This method must be called on the MCT.
Use QueuedTask.Run.</p>


```csharp
public static ValidationResult ValidateNetworkTopologyInEditOperation(this UtilityNetwork utilityNetwork)
```
### ValidateNetworkTopologyInEditOperation(UtilityNetwork, Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetworkExtensions.yml" sourcestartlinenumber="1">Validates the utility network topology in an edit operation. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static ValidationResult ValidateNetworkTopologyInEditOperation(this UtilityNetwork utilityNetwork, Geometry extent)
```
### ValidateNetworkTopologyInEditOperation(UtilityNetwork, Geometry, ServiceSynchronizationType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetworkExtensions.yml" sourcestartlinenumber="1">Validates the utility network topology in an edit operation. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static ValidationResult ValidateNetworkTopologyInEditOperation(this UtilityNetwork utilityNetwork, Geometry extent, ServiceSynchronizationType serviceSynchronizationType)
```
### ValidateNetworkTopologyInEditOperation(UtilityNetwork, IEnumerable&lt;Selection&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetworkExtensions.yml" sourcestartlinenumber="1">Validates the utility network topology in an edit operation. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static ValidationResult ValidateNetworkTopologyInEditOperation(this UtilityNetwork utilityNetwork, IEnumerable<Selection> selections)
```
### ValidateNetworkTopologyInEditOperation(UtilityNetwork, IEnumerable&lt;Selection&gt;, ServiceSynchronizationType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetworkExtensions.yml" sourcestartlinenumber="1">Validates the utility network topology in an edit operation. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static ValidationResult ValidateNetworkTopologyInEditOperation(this UtilityNetwork utilityNetwork, IEnumerable<Selection> selections, ServiceSynchronizationType serviceSynchronizationType)
```


