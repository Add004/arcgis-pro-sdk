# UtilityNetworkDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetworkDefinition.yml" sourcestartlinenumber="1">Represents the schema and properties of a utility network.</p>


## Object Signature

```csharp
public sealed class UtilityNetworkDefinition : Definition, IDisposable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetworkDefinition.yml" sourcestartlinenumber="1">UtilityNetworkDefinition objects can be obtained by calling <xref href="ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.GetDefinition" data-throw-if-not-resolved="false"></xref>.</p>


## Members

### DatasetType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetworkDefinition.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.DatasetType" data-throw-if-not-resolved="false"></xref>. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public override DatasetType DatasetType { get; }
```
### GetAssetGroupField()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetworkDefinition.yml" sourcestartlinenumber="1">Gets the name of the asset group field.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetAssetGroupField()
```
### GetAssetTypeField()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetworkDefinition.yml" sourcestartlinenumber="1">Gets the name of the asset type field.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetAssetTypeField()
```
### GetAssociationStatusField()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetworkDefinition.yml" sourcestartlinenumber="1">Gets the name of the association status field.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetAssociationStatusField()
```
### GetAvailableCategories()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetworkDefinition.yml" sourcestartlinenumber="1">Gets a list of all of the categories registered to the utility network.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<string> GetAvailableCategories()
```
### GetDomainNetwork(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetworkDefinition.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.UtilityNetwork.DomainNetwork" data-throw-if-not-resolved="false"></xref> with the specified name from this utility network. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public DomainNetwork GetDomainNetwork(string domainNetworkName)
```
### GetDomainNetworks()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetworkDefinition.yml" sourcestartlinenumber="1">Gets an IReadOnlyList of <xref href="ArcGIS.Core.Data.UtilityNetwork.DomainNetwork" data-throw-if-not-resolved="false"></xref> objects defined by this utility network. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<DomainNetwork> GetDomainNetworks()
```
### GetNetworkAttribute(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetworkDefinition.yml" sourcestartlinenumber="1">Gets a <xref href="ArcGIS.Core.Data.UtilityNetwork.NetworkAttribute" data-throw-if-not-resolved="false"></xref> object with the specified name.<br>
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public NetworkAttribute GetNetworkAttribute(string networkAttributeName)
```
### GetNetworkAttributes()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetworkDefinition.yml" sourcestartlinenumber="1">Gets a list of <xref href="ArcGIS.Core.Data.UtilityNetwork.NetworkAttribute" data-throw-if-not-resolved="false"></xref> definitions for this utility network. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<NetworkAttribute> GetNetworkAttributes()
```
### GetNetworkSource(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetworkDefinition.yml" sourcestartlinenumber="1">Gets a <xref href="ArcGIS.Core.Data.UtilityNetwork.NetworkSource" data-throw-if-not-resolved="false"></xref> object with the specified name.<br>
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public NetworkSource GetNetworkSource(string networkSourceName)
```
### GetNetworkSources()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetworkDefinition.yml" sourcestartlinenumber="1">Gets an IReadOnlyList of the <xref href="ArcGIS.Core.Data.UtilityNetwork.NetworkSource" data-throw-if-not-resolved="false"></xref> objects used by the network. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<NetworkSource> GetNetworkSources()
```
### GetRules()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetworkDefinition.yml" sourcestartlinenumber="1">Gets a list of <xref href="ArcGIS.Core.Data.UtilityNetwork.Rule" data-throw-if-not-resolved="false"></xref> definitions for the utility network. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<Rule> GetRules()
```
### GetSchemaVersion()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetworkDefinition.yml" sourcestartlinenumber="1">Gets the version number of the utility network schema. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetSchemaVersion()
```
### GetServiceTerritoryEnvelope()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetworkDefinition.yml" sourcestartlinenumber="1">Gets an <xref href="ArcGIS.Core.Geometry.Envelope" data-throw-if-not-resolved="false"></xref> representing the maximum extent of the data that has been stored in the <xref href="ArcGIS.Core.Data.UtilityNetwork" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Envelope GetServiceTerritoryEnvelope()
```
### GetTerminalConfigurations()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.UtilityNetworkDefinition.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.UtilityNetwork.TerminalConfiguration" data-throw-if-not-resolved="false"></xref> objects defined for this utility network. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<TerminalConfiguration> GetTerminalConfigurations()
```


