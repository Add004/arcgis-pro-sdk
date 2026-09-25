# AssetGroup

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.AssetGroup.yml" sourcestartlinenumber="1">The AssetGroup class provides information about Asset Groups within the utility network.  In the core geodatabase, they are implemented as subtypes.</p>


## Object Signature

```csharp
public sealed class AssetGroup : CoreObjectsBase, IDisposable
```


## Members

### Code

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.AssetGroup.yml" sourcestartlinenumber="1">Gets the ID of the AssetGroup.  This corresponds to the subtype code.</p>


```csharp
public int Code { get; }
```
### GetAssetType(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.AssetGroup.yml" sourcestartlinenumber="1">Gets an <xref href="ArcGIS.Core.Data.UtilityNetwork.AssetType" data-throw-if-not-resolved="false"></xref> object with the specified name.<br>
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public AssetType GetAssetType(string assetTypeName)
```
### GetAssetTypes()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.AssetGroup.yml" sourcestartlinenumber="1">Gets a list of AssetTypes for this Asset Group.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<AssetType> GetAssetTypes()
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.AssetGroup.yml" sourcestartlinenumber="1">Gets the name of the AssetGroup.</p>


```csharp
public string Name { get; }
```
### NetworkSource

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.AssetGroup.yml" sourcestartlinenumber="1">Gets the parent <xref href="ArcGIS.Core.Data.UtilityNetwork.NetworkSource" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public NetworkSource NetworkSource { get; }
```


