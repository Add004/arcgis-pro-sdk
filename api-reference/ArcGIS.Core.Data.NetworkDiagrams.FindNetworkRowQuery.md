# FindNetworkRowQuery

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.NetworkDiagrams.html">NetworkDiagrams</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.FindNetworkRowQuery.yml" sourcestartlinenumber="1">Represents a find network row query. This query is used to obtain utility network rows from a set of diagram feature ids.</p>


## Object Signature

```csharp
public sealed class FindNetworkRowQuery
```


## Members

### FindNetworkRowQuery()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.FindNetworkRowQuery.yml" sourcestartlinenumber="1">Initializes a new instance of the FindNetworkRowQuery class.</p>


```csharp
public FindNetworkRowQuery()
```
### AddAggregations

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.FindNetworkRowQuery.yml" sourcestartlinenumber="1">Indicates whether aggregated diagram features are processed or not.</p>


```csharp
public bool AddAggregations { get; set; }
```
### DiagramFeatureGlobalIDs

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.FindNetworkRowQuery.yml" sourcestartlinenumber="1">A list of diagram feature global IDs.</p>


```csharp
public IReadOnlyList<Guid> DiagramFeatureGlobalIDs { get; set; }
```


