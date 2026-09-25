# SubnetworkUpdateOptions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.SubnetworkUpdateOptions.yml" sourcestartlinenumber="1">Represents a mechanism to update a <xref href="ArcGIS.Core.Data.UtilityNetwork.Subnetwork" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class SubnetworkUpdateOptions
```


## Members

### SubnetworkUpdateOptions()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.SubnetworkUpdateOptions.yml" sourcestartlinenumber="1">Initializes a new instance of the <code>SubnetworkUpdateOptions</code> class to update a <xref href="ArcGIS.Core.Data.UtilityNetwork.Subnetwork" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public SubnetworkUpdateOptions()
```
### ForceUpdate

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.SubnetworkUpdateOptions.yml" sourcestartlinenumber="1">Specifies whether the subnetwork update operation can run against subnetworks that are not marked as dirty. The default is false which means the subnetwork update operation will return an error if the subnetwork is not marked as dirty.</p>


```csharp
public bool ForceUpdate { get; set; }
```
### ServiceSynchronizationType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.SubnetworkUpdateOptions.yml" sourcestartlinenumber="1">Specifies whether the subnetwork update operation is executed synchronously or asynchronously. The default is Synchronous.</p>


```csharp
public ServiceSynchronizationType ServiceSynchronizationType { get; set; }
```
### TraceConfiguration

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.SubnetworkUpdateOptions.yml" sourcestartlinenumber="1">Specifies the trace configuration used for the subnetwork update operation.</p>


```csharp
public TraceConfiguration TraceConfiguration { get; set; }
```


