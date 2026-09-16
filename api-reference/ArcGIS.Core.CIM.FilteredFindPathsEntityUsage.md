# FilteredFindPathsEntityUsage

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.FilteredFindPathsEntityUsage.yml" sourcestartlinenumber="1">Specifies how origin/destination entities are used in the filtered find paths algorithm.</p>


## Object Signature

```csharp
public enum FilteredFindPathsEntityUsage
```


## Members

### AllOriginsAllDestinations

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.FilteredFindPathsEntityUsage.yml" sourcestartlinenumber="1">The filtered find paths algorithm returns
one shortest path (if it exists) per origin entity and
one shortest path (if it exists) per destination entity.
When multiple entities are used, this option leads to longer computations.</p>


```csharp
AllOriginsAllDestinations = 3
```
### AllOriginsAnyDestination

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.FilteredFindPathsEntityUsage.yml" sourcestartlinenumber="1">The filtered find paths algorithm returns
one shortest path (if it exists) per origin entity and
the shortest paths for the destination entities that have the shortest shortest paths.
When multiple entities are used, this option leads to longer computations.</p>


```csharp
AllOriginsAnyDestination = 2
```
### AnyOriginAllDestinations

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.FilteredFindPathsEntityUsage.yml" sourcestartlinenumber="1">The filtered find paths algorithm returns
the shortest paths for the origin entities that have the shortest shortest paths and
one shortest path (if it exists) per destination entity.
When multiple entities are used, this option leads to longer computations.</p>


```csharp
AnyOriginAllDestinations = 1
```
### AnyOriginAnyDestination

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.FilteredFindPathsEntityUsage.yml" sourcestartlinenumber="1">The filtered find paths algorithm only returns
the shortest paths for the origin entities that have the shortest shortest paths and
the shortest paths for the destination entities that have the shortest shortest paths.
When multiple entities are used, this option leads to faster computations.</p>


```csharp
AnyOriginAnyDestination = 0
```
### EachPair

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.FilteredFindPathsEntityUsage.yml" sourcestartlinenumber="1">The filtered find paths algorithm returns
one shortest path (if it exists) per pair of origin and destination entity.
When multiple entities are used, this option leads to longer computations.
An error will be returned if strictly more than 10 origin entities are defined or
if strictly more than 10 destination entities are defined.</p>


```csharp
EachPair = 4
```


