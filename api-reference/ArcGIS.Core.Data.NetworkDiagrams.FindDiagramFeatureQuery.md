# FindDiagramFeatureQuery

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.NetworkDiagrams.html">NetworkDiagrams</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.FindDiagramFeatureQuery.yml" sourcestartlinenumber="1">Represents a find diagram feature query.  This query is used to obtain diagram features from a set of utility network row ids.</p>


## Object Signature

```csharp
public sealed class FindDiagramFeatureQuery
```


## Members

### FindDiagramFeatureQuery()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.FindDiagramFeatureQuery.yml" sourcestartlinenumber="1">Initializes a new instance of the FindDiagramFeatureQuery class.</p>


```csharp
public FindDiagramFeatureQuery()
```
### AddAggregations

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.FindDiagramFeatureQuery.yml" sourcestartlinenumber="1">Indicates whether aggregated diagram features are included.</p>


```csharp
public bool AddAggregations { get; set; }
```
### AddConnectivityAssociations

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.FindDiagramFeatureQuery.yml" sourcestartlinenumber="1">Indicates whether connectivity associations are included.</p>


```csharp
public bool AddConnectivityAssociations { get; set; }
```
### AddStructuralAttachments

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.FindDiagramFeatureQuery.yml" sourcestartlinenumber="1">Indicates whether structural attachments are included.</p>


```csharp
public bool AddStructuralAttachments { get; set; }
```
### NetworkRowGlobalIDs

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.FindDiagramFeatureQuery.yml" sourcestartlinenumber="1">A list of network row global IDs.</p>


```csharp
public IReadOnlyList<Guid> NetworkRowGlobalIDs { get; set; }
```


