# NearestNeighbor

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.Trace.html">Trace</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.NearestNeighbor.yml" sourcestartlinenumber="1">The NearestNeighbor class encapsulates all of the criteria for defining a nearest neighbor filter.</p>


## Object Signature

```csharp
public sealed class NearestNeighbor
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.NearestNeighbor.yml" sourcestartlinenumber="1">Nearest neighbor filters allow you to return the next <i>N</i> rows, where the &quot;distance&quot; to those rows is calculated by a network attribute.</p>


## Members

### NearestNeighbor(NetworkAttribute, int, IEnumerable&lt;AssetType&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.NearestNeighbor.yml" sourcestartlinenumber="1">Creates a new instance of the NearestNeighbor class, defined by asset types.</p>


```csharp
public NearestNeighbor(NetworkAttribute costNetworkAttribute, int count, IEnumerable<AssetType> nearestAssetTypes)
```
### NearestNeighbor(NetworkAttribute, int, IEnumerable&lt;string&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.NearestNeighbor.yml" sourcestartlinenumber="1">Creates a new instance of the NearestNeighbor class, defined by categories.</p>


```csharp
public NearestNeighbor(NetworkAttribute costNetworkAttribute, int count, IEnumerable<string> nearestCategories)
```
### NearestNeighbor(NetworkAttribute, int, IEnumerable&lt;string&gt;, IEnumerable&lt;AssetType&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.NearestNeighbor.yml" sourcestartlinenumber="1">Creates a new instance of the NearestNeighbor class, defined by both categories and asset types.</p>


```csharp
public NearestNeighbor(NetworkAttribute costNetworkAttribute, int count, IEnumerable<string> nearestCategories, IEnumerable<AssetType> nearestAssetTypes)
```
### CostNetworkAttribute

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.NearestNeighbor.yml" sourcestartlinenumber="1">The <xref href="ArcGIS.Core.Data.UtilityNetwork.NetworkAttribute" data-throw-if-not-resolved="false"></xref> used to determine the definition of &quot;nearest.&quot;</p>


```csharp
public NetworkAttribute CostNetworkAttribute { get; }
```
### Count

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.NearestNeighbor.yml" sourcestartlinenumber="1">The number of nearest rows to return.</p>


```csharp
public int Count { get; }
```
### NearestAssetTypes

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.NearestNeighbor.yml" sourcestartlinenumber="1">The <xref href="ArcGIS.Core.Data.UtilityNetwork.AssetType" data-throw-if-not-resolved="false"></xref> objects that are used to define rows to return.</p>


```csharp
public IReadOnlyList<AssetType> NearestAssetTypes { get; }
```
### NearestCategories

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.NearestNeighbor.yml" sourcestartlinenumber="1">The Category strings that are used to define rows to return.</p>


```csharp
public IReadOnlyList<string> NearestCategories { get; }
```


