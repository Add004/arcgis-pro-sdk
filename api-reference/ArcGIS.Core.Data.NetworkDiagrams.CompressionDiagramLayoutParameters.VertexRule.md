# CompressionDiagramLayoutParameters.VertexRule

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.NetworkDiagrams.html">NetworkDiagrams</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.CompressionDiagramLayoutParameters.VertexRule.yml" sourcestartlinenumber="1">Determines how vertices along edges in the diagram must be processed.</p>


## Object Signature

```csharp
public enum CompressionDiagramLayoutParameters.VertexRule
```


## Members

### AllOuterVertices

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.CompressionDiagramLayoutParameters.VertexRule.yml" sourcestartlinenumber="1">All outer vertices are removed. Any edge vertices that are within the detected junctions' groups will be maintained, while edge vertices that are outside will be removed.
When there are containers in the diagram that have edges that intersect the container polygons, a vertex is added at the intersection of the edge and container polygon.</p>


```csharp
AllOuterVertices = 2
```
### AllOuterVerticesExceptTheFirstOne

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.CompressionDiagramLayoutParameters.VertexRule.yml" sourcestartlinenumber="1">All outer vertices except the first one are removed. Any edge vertices that are within the detected junctions' groups will be maintained, while edge vertices that are outside will be removed. When there are containers in the diagram that have edges
that intersect the container polygons, the first (or last) outside vertex is preserved on edges that intersect a container polygon. A vertex is automatically inserted at the intersection of the
edges and container polygons.</p>


```csharp
AllOuterVerticesExceptTheFirstOne = 3
```
### AllVertices

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.CompressionDiagramLayoutParameters.VertexRule.yml" sourcestartlinenumber="1">All vertices on all edges will be removed from the diagram</p>


```csharp
AllVertices = 1
```


