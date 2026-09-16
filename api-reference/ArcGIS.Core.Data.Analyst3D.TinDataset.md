# TinDataset

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Analyst3D.html">Analyst3D</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinDataset.yml" sourcestartlinenumber="1">Represents a TIN dataset.</p>


## Object Signature

```csharp
public sealed class TinDataset : Dataset, IDisposable
```


## Members

### GetDataArea()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinDataset.yml" sourcestartlinenumber="1">Gets the data area of the TIN as a Z-aware polygon.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Polygon GetDataArea()
```
### GetDataEdgeCount()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinDataset.yml" sourcestartlinenumber="1">Gets the number of data edges in this TIN.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int GetDataEdgeCount()
```
### GetDataNodeCount()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinDataset.yml" sourcestartlinenumber="1">Gets the number of data nodes in this TIN.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int GetDataNodeCount()
```
### GetDataTriangleCount()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinDataset.yml" sourcestartlinenumber="1">Gets the number of data triangles in this TIN.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int GetDataTriangleCount()
```
### GetDefinition()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinDataset.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Analyst3D.TinDatasetDefinition" data-throw-if-not-resolved="false"></xref> of this TIN dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public TinDatasetDefinition GetDefinition()
```
### GetEdgeByIndex(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinDataset.yml" sourcestartlinenumber="1">Gets the edge specified by the index.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public TinEdge GetEdgeByIndex(int index)
```
### GetEdgeCount()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinDataset.yml" sourcestartlinenumber="1">Gets the total number of edges in this TIN.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int GetEdgeCount()
```
### GetExtent()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinDataset.yml" sourcestartlinenumber="1">Gets an <xref href="ArcGIS.Core.Geometry.Envelope" data-throw-if-not-resolved="false"></xref> representing the maximum extent of the data that has been stored in the <xref href="ArcGIS.Core.Data.Analyst3D.TinDataset" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Envelope GetExtent()
```
### GetFullExtent()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinDataset.yml" sourcestartlinenumber="1">Gets the full 2D-extent of the user-supplied data in the TIN including NODATA nodes.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Envelope GetFullExtent()
```
### GetIsEmpty()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinDataset.yml" sourcestartlinenumber="1">Gets if the TIN is empty.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool GetIsEmpty()
```
### GetNaturalNeighbors(MapPoint)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinDataset.yml" sourcestartlinenumber="1">Gets the set of nodes that are the natural neighbors of the specified point.
The natural neighbors of a point are the nodes it would connect with to form triangles if it were inserted in the triangulation.
They are the closest surrounding nodes in all directions.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<TinNode> GetNaturalNeighbors(MapPoint point)
```
### GetNearestEdge(MapPoint)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinDataset.yml" sourcestartlinenumber="1">Gets the nearest edge to the specified point.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public TinEdge GetNearestEdge(MapPoint point)
```
### GetNearestNode(MapPoint)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinDataset.yml" sourcestartlinenumber="1">Gets the nearest node to the specified point.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public TinNode GetNearestNode(MapPoint point)
```
### GetNodeByIndex(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinDataset.yml" sourcestartlinenumber="1">Gets the node specified by the index.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public TinNode GetNodeByIndex(int index)
```
### GetNodeCount()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinDataset.yml" sourcestartlinenumber="1">Gets the total number of nodes in this TIN.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int GetNodeCount()
```
### GetOutsideEdgeCount()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinDataset.yml" sourcestartlinenumber="1">Gets the number of outside edges in this TIN.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int GetOutsideEdgeCount()
```
### GetOutsideNodeCount()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinDataset.yml" sourcestartlinenumber="1">Gets the number of outside nodes in this TIN.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int GetOutsideNodeCount()
```
### GetOutsideTriangleCount()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinDataset.yml" sourcestartlinenumber="1">Gets the number of outside triangles in this TIN.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int GetOutsideTriangleCount()
```
### GetSuperNodeExtent()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinDataset.yml" sourcestartlinenumber="1">Gets the full extent of the TIN based on the super nodes.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Envelope GetSuperNodeExtent()
```
### GetTriangleByIndex(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinDataset.yml" sourcestartlinenumber="1">Gets the triangle specified by the index.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public TinTriangle GetTriangleByIndex(int index)
```
### GetTriangleByPoint(MapPoint)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinDataset.yml" sourcestartlinenumber="1">Gets the triangle at the specified point.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public TinTriangle GetTriangleByPoint(MapPoint point)
```
### GetTriangleCount()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinDataset.yml" sourcestartlinenumber="1">Gets the total number of triangles in this TIN.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int GetTriangleCount()
```
### GetTriangleNeighborhood(MapPoint)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinDataset.yml" sourcestartlinenumber="1">Gets all triangles whose circumscribed circle contains the specified point.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<TinTriangle> GetTriangleNeighborhood(MapPoint point)
```
### GetVersion()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinDataset.yml" sourcestartlinenumber="1">Gets the version of this TIN.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public TinVersion GetVersion()
```
### GetZFactor()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinDataset.yml" sourcestartlinenumber="1">Gets the Z unit conversion factor for this TIN.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double GetZFactor()
```
### HasEdgeTags()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinDataset.yml" sourcestartlinenumber="1">Gets if any edges have tags in this TIN.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool HasEdgeTags()
```
### HasHardEdges()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinDataset.yml" sourcestartlinenumber="1">Gets if there are any hard edges in this TIN. Hard and soft edges are enforced in the triangulation.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool HasHardEdges()
```
### HasNodeTags()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinDataset.yml" sourcestartlinenumber="1">Gets if any nodes have tags in this TIN.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool HasNodeTags()
```
### HasSoftEdges()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinDataset.yml" sourcestartlinenumber="1">Gets if there are any soft edges in this TIN. Hard and soft edges are enforced in the triangulation.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool HasSoftEdges()
```
### HasTriangleTags()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinDataset.yml" sourcestartlinenumber="1">Gets if any triangles have tags in this TIN.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool HasTriangleTags()
```
### SearchEdges(TinEdgeFilter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinDataset.yml" sourcestartlinenumber="1">Retrieves the edges in the TIN that satisfy the criteria set in the <code class="paramref">filter</code>.
If no filter is set, all single edges that intersect the data extent will be retrieved.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public TinEdgeCursor SearchEdges(TinEdgeFilter filter)
```
### SearchNodes(TinNodeFilter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinDataset.yml" sourcestartlinenumber="1">Retrieves the nodes in the TIN that satisfy the criteria set in the <code class="paramref">filter</code>.
If no filter is set, all nodes that intersect the data extent will be retrieved.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public TinNodeCursor SearchNodes(TinNodeFilter filter)
```
### SearchTriangles(TinTriangleFilter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinDataset.yml" sourcestartlinenumber="1">Retrieves the triangles in the TIN that satisfy the criteria set in the <code class="paramref">filter</code>.
If no filter is set, all triangles that intersect the data extent will be retrieved.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public TinTriangleCursor SearchTriangles(TinTriangleFilter filter)
```
### Type

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinDataset.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.DatasetType" data-throw-if-not-resolved="false"></xref> of this TIN dataset.  Returns <xref href="ArcGIS.Core.Data.DatasetType.Tin" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public override DatasetType Type { get; }
```
### UsesConstrainedDelaunay()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinDataset.yml" sourcestartlinenumber="1">Gets if the TIN is defined using the Constrained Delaunay triangulation technique.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool UsesConstrainedDelaunay()
```


