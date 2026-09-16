# ReshapeEdgesDiagramLayoutParameters.Operation

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.NetworkDiagrams.html">NetworkDiagrams</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.ReshapeEdgesDiagramLayoutParameters.Operation.yml" sourcestartlinenumber="1">The type of reshape operation.</p>


## Object Signature

```csharp
public enum ReshapeEdgesDiagramLayoutParameters.Operation
```


## Members

### MarkCrossingEdges

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.ReshapeEdgesDiagramLayoutParameters.Operation.yml" sourcestartlinenumber="1">Mark crossing edges operation. Inserts circle arcs along diagram edges to mark the crossing with other edges.</p>


```csharp
MarkCrossingEdges = 5
```
### ReduceVerticesByAngle

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.ReshapeEdgesDiagramLayoutParameters.Operation.yml" sourcestartlinenumber="1">Reduce vertices by angle operation. Removes some or all vertices displayed along diagram edges according to the angle that separates the segments incident to those vertices.</p>


```csharp
ReduceVerticesByAngle = 4
```
### RemoveVertices

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.ReshapeEdgesDiagramLayoutParameters.Operation.yml" sourcestartlinenumber="1">Remove vertices operation. Removes all vertices along any edges in the diagram.</p>


```csharp
RemoveVertices = 2
```
### SeparateOverlappingEdges

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.ReshapeEdgesDiagramLayoutParameters.Operation.yml" sourcestartlinenumber="1">Separate overlapping edges operation. Separates edges that connect the same origin and extremity junctions when they are overlapping.</p>


```csharp
SeparateOverlappingEdges = 3
```
### SquareEdges

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.ReshapeEdgesDiagramLayoutParameters.Operation.yml" sourcestartlinenumber="1">Square edges operation. Inserts vertices along diagram edges so these edges are displayed with right angles.</p>


```csharp
SquareEdges = 1
```


