# esriNetworkForwardStarBacktrack

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.esriNetworkForwardStarBacktrack.yml" sourcestartlinenumber="1">Policy on when to return the from-edge in the network forward star adjacencies object.</p>


## Object Signature

```csharp
public enum esriNetworkForwardStarBacktrack
```


## Members

### esriNFSBAllowBacktrack

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.esriNetworkForwardStarBacktrack.yml" sourcestartlinenumber="1">Always return the from-edge in the network forward star adjacencies object.</p>


```csharp
esriNFSBAllowBacktrack = 1
```
### esriNFSBAtDeadEndsAndIntersections

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.esriNetworkForwardStarBacktrack.yml" sourcestartlinenumber="1">Return the from-edge in the network forward star adjacencies object only if it is the only edge that is adjacent to the query junction or the query junction has 3 or more adjacencies.</p>


```csharp
esriNFSBAtDeadEndsAndIntersections = 3
```
### esriNFSBAtDeadEndsOnly

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.esriNetworkForwardStarBacktrack.yml" sourcestartlinenumber="1">Return the from-edge in the network forward star adjacencies object only if it is the only edge that is adjacent to the query junction.</p>


```csharp
esriNFSBAtDeadEndsOnly = 2
```
### esriNFSBNoBacktrack

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.esriNetworkForwardStarBacktrack.yml" sourcestartlinenumber="1">Never return the from-edge in the network forward star adjacencies object.</p>


```csharp
esriNFSBNoBacktrack = 0
```


