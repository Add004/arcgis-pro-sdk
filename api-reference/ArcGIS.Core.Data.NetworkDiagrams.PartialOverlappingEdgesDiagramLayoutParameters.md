# PartialOverlappingEdgesDiagramLayoutParameters

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.NetworkDiagrams.html">NetworkDiagrams</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.PartialOverlappingEdgesDiagramLayoutParameters.yml" sourcestartlinenumber="1">Represents the Partial Overlapping Edges diagram layout parameters. This layout algorithm spaces out collinear edges or collinear portions of edges (edge segments) inside a given buffer zone.</p>


## Object Signature

```csharp
public sealed class PartialOverlappingEdgesDiagramLayoutParameters : DiagramLayoutParameters
```

## Remarks

<ul>
  <li>This layout algorithm detects sets of collinear edges or collinear portions of edges (edge segments) that can be considered as being inside a buffer zone of a given size.</li>
  <li>The edges or segments must be relatively close to each other—more or less parallel, overlap, or nearly overlap—and similar in length. 
    Segment buffer zones are then repositioned equally on the left and right sides, a proportional distance from the middle of the zone.</li>
  <li>The distance between each segment is equal to a given offset. If vertices exist along diagram edges, the global orientation of the segments is preserved as much as possible. 
    This is done so that, for example, a segment lying on the left side of another segment still ends up on the left side.</li>
</ul>


## Members

### BufferWidth

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.PartialOverlappingEdgesDiagramLayoutParameters.yml" sourcestartlinenumber="1">Width of the buffer zones in which to search for collinear edge segments.</p>


```csharp
public double BufferWidth { get; set; }
```
### Offset

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.PartialOverlappingEdgesDiagramLayoutParameters.yml" sourcestartlinenumber="1">Indicates the distance that will separate the detected edge segments.</p>


```csharp
public double Offset { get; set; }
```
### OptimizeEdges

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.PartialOverlappingEdgesDiagramLayoutParameters.yml" sourcestartlinenumber="1">Indicates if the segment placement order in each set of detected collinear segments are optimized to try to avoid crossing.</p>


```csharp
public bool OptimizeEdges { get; set; }
```


