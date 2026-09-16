# TinNode

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Analyst3D.html">Analyst3D</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinNode.yml" sourcestartlinenumber="1">A <xref href="ArcGIS.Core.Data.Analyst3D.TinNode" data-throw-if-not-resolved="false"></xref> is one of the three basic elements of a TIN.  Nodes store X, Y and Z values and optional tag values.</p>


## Object Signature

```csharp
public sealed class TinNode : TinElement, IDisposable
```


## Members

### Coordinate2D

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinNode.yml" sourcestartlinenumber="1">Gets a <xref href="ArcGIS.Core.Geometry.Coordinate2D" data-throw-if-not-resolved="false"></xref> structure with the X and Y values.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Coordinate2D Coordinate2D { get; }
```
### Coordinate3D

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinNode.yml" sourcestartlinenumber="1">Gets a <xref href="ArcGIS.Core.Geometry.Coordinate3D" data-throw-if-not-resolved="false"></xref> structure with the X, Y, and Z values.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Coordinate3D Coordinate3D { get; }
```
### ElementType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinNode.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Analyst3D.TinElementType" data-throw-if-not-resolved="false"></xref> of this instance.  Always returns <xref href="ArcGIS.Core.Data.Analyst3D.TinElementType.Node" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public override TinElementType ElementType { get; }
```
### GetAdjacentNodeIndices()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinNode.yml" sourcestartlinenumber="1">Gets all the node indices that are next to this node; that is that are connected to this node by TIN edges.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<int> GetAdjacentNodeIndices()
```
### GetAdjacentNodes()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinNode.yml" sourcestartlinenumber="1">Gets all the nodes that are next to this node; that is that are connected to this node by TIN edges.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<TinNode> GetAdjacentNodes()
```
### GetDegree(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinNode.yml" sourcestartlinenumber="1">Gets the degree of this TIN node.  The degree of a node is the number of edges that are connected to it.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int GetDegree(bool enforceEdgesOnly)
```
### GetIncidentEdgeIndices()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinNode.yml" sourcestartlinenumber="1">Gets all the edge indices that share this node as their &quot;from&quot; node.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<int> GetIncidentEdgeIndices()
```
### GetIncidentEdges()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinNode.yml" sourcestartlinenumber="1">Gets all the edges that share this node as their &quot;from&quot; node.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<TinEdge> GetIncidentEdges()
```
### GetIncidentTriangleIndices()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinNode.yml" sourcestartlinenumber="1">Gets all the triangle indices which reference this node.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<int> GetIncidentTriangleIndices()
```
### GetIncidentTriangles()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinNode.yml" sourcestartlinenumber="1">Gets all the triangles which reference this node.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<TinTriangle> GetIncidentTriangles()
```
### GetVoronoiRegion(Polygon)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinNode.yml" sourcestartlinenumber="1">Gets the Voronoi polygon region for this node.  The Voronoi region (also known as Thiessen or proximal polygon) encloses an area that is closer to the
source node than to any other node in the triangulation.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Polygon GetVoronoiRegion(Polygon clipPolygon = null)
```
### HasVoidZ

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinNode.yml" sourcestartlinenumber="1">Gets a value indicating if this TIN node has Z-less vertices. If the z-value of a vertex is NaN, then it is considered z-less.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public override bool HasVoidZ { get; }
```
### IsEmpty

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinNode.yml" sourcestartlinenumber="1">Gets a value indicating whether or not this element is empty.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public override bool IsEmpty { get; }
```
### IsInsideDataArea

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinNode.yml" sourcestartlinenumber="1">Gets if this element is within the interpolation zone or the data area of the TIN.  See <xref href="ArcGIS.Core.Data.Analyst3D.TinDataset.GetDataArea" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public override bool IsInsideDataArea { get; }
```
### IsInsideExtent(Envelope)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinNode.yml" sourcestartlinenumber="1">Gets if this element is inside the specified extent.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public override bool IsInsideExtent(Envelope extent)
```
### IsOnDomainBoundary

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinNode.yml" sourcestartlinenumber="1">Gets if this node is on the TIN domain boundary. That is, if it is on the boundary of the interpolation zone or data area.
See <xref href="ArcGIS.Core.Data.Analyst3D.TinDataset.GetDataArea" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool IsOnDomainBoundary { get; }
```
### NodeCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinNode.yml" sourcestartlinenumber="1">Gets the node count of the element. Always returns 1.</p>


```csharp
public override int NodeCount { get; }
```
### Source

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinNode.yml" sourcestartlinenumber="1">Gets the source of this TIN node.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public TinNodeSourceType Source { get; }
```
### TagValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinNode.yml" sourcestartlinenumber="1">Gets the tag value of this TIN node.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public override int TagValue { get; }
```
### ToMapPoint()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinNode.yml" sourcestartlinenumber="1">Gets a <xref href="ArcGIS.Core.Geometry.MapPoint" data-throw-if-not-resolved="false"></xref> with the X, Y and Z values. The spatial reference of the returned point is set to the
spatial reference of the TIN.  See <xref href="ArcGIS.Core.Data.Analyst3D.TinDatasetDefinition.GetSpatialReference" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public MapPoint ToMapPoint()
```


