# TinEdge

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Analyst3D.html">Analyst3D</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEdge.yml" sourcestartlinenumber="1">A <xref href="ArcGIS.Core.Data.Analyst3D.TinEdge" data-throw-if-not-resolved="false"></xref> is one of the three basic elements of a TIN.  Edges are comprised of two <xref href="ArcGIS.Core.Data.Analyst3D.TinNode?text=TinNodes" data-throw-if-not-resolved="false"></xref>.
Edges are oriented in clockwise order and are used to form <xref href="ArcGIS.Core.Data.Analyst3D.TinTriangle?text=triangles" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class TinEdge : TinElement, IDisposable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEdge.yml" sourcestartlinenumber="1">Edges may be hard, soft, or regular. Hard and soft edges are enforced in the triangulation.
When a TIN is used as a surface model, these usually represent breaklines. Regular edges are simply a consequence of
triangulation and don't have special meaning. The <xref href="ArcGIS.Core.Data.Analyst3D.TinEdgeType" data-throw-if-not-resolved="false"></xref> enumeration describes edge type.</p>


## Members

### Azimuth

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEdge.yml" sourcestartlinenumber="1">Gets the azimuth direction of this TIN edge in radians.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double Azimuth { get; }
```
### EdgeType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEdge.yml" sourcestartlinenumber="1">Gets the type of this TIN edge.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public TinEdgeType EdgeType { get; }
```
### ElementType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEdge.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Analyst3D.TinElementType" data-throw-if-not-resolved="false"></xref> of this instance.  Always returns <xref href="ArcGIS.Core.Data.Analyst3D.TinElementType.Edge" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public override TinElementType ElementType { get; }
```
### GetNeighbor()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEdge.yml" sourcestartlinenumber="1">Gets the corresponding edge of the triangle opposite to this TIN edge.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public TinEdge GetNeighbor()
```
### GetNextClockwiseEdge()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEdge.yml" sourcestartlinenumber="1">Gets the edge beginning at the &quot;toNode&quot; of this TIN edge.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public TinEdge GetNextClockwiseEdge()
```
### GetNextCounterClockwiseEdge()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEdge.yml" sourcestartlinenumber="1">Gets the edge terminating at the &quot;fromNode&quot; of this TIN edge.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public TinEdge GetNextCounterClockwiseEdge()
```
### GetNextEdgeInTriangle()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEdge.yml" sourcestartlinenumber="1">Gets the next edge in the triangle. The next edge is in the clockwise direction.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public TinEdge GetNextEdgeInTriangle()
```
### GetPreviousEdgeInTriangle()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEdge.yml" sourcestartlinenumber="1">Gets the previous edge in the triangle. The previous edge is counter-clockwise to this TIN edge.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public TinEdge GetPreviousEdgeInTriangle()
```
### HasVoidZ

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEdge.yml" sourcestartlinenumber="1">Gets a value indicating if this TIN element has Z-less vertices. If the z-value of a vertex is NaN, then it is considered z-less.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public override bool HasVoidZ { get; }
```
### IsEmpty

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEdge.yml" sourcestartlinenumber="1">Gets a value indicating whether or not this element is empty.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public override bool IsEmpty { get; }
```
### IsInsideDataArea

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEdge.yml" sourcestartlinenumber="1">Gets if this element is within the interpolation zone or the data area of the TIN. See <xref href="ArcGIS.Core.Data.Analyst3D.TinDataset.GetDataArea" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public override bool IsInsideDataArea { get; }
```
### IsInsideExtent(Envelope)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEdge.yml" sourcestartlinenumber="1">Gets if this element is inside the specified extent.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public override bool IsInsideExtent(Envelope extent)
```
### LeftTriangle

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEdge.yml" sourcestartlinenumber="1">Gets the triangle on the left (opposite) side of this TIN edge.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public TinTriangle LeftTriangle { get; }
```
### Length

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEdge.yml" sourcestartlinenumber="1">Gets the length of this TIN edge. The length is in the units of the spatial reference of the TIN.
See <xref href="ArcGIS.Core.Data.Analyst3D.TinDatasetDefinition.GetSpatialReference" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public override double Length { get; }
```
### Length3D

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEdge.yml" sourcestartlinenumber="1">Gets the 3D length of this TIN edge. The length is in the units of the spatial reference of the TIN.
See <xref href="ArcGIS.Core.Data.Analyst3D.TinDatasetDefinition.GetSpatialReference" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double Length3D { get; }
```
### NodeCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEdge.yml" sourcestartlinenumber="1">Gets the node count of the element. Always returns 2.</p>


```csharp
public override int NodeCount { get; }
```
### Nodes

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEdge.yml" sourcestartlinenumber="1">Gets the nodes of this TIN edge.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<TinNode> Nodes { get; }
```
### RightTriangle

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEdge.yml" sourcestartlinenumber="1">Gets the triangle on the right side of this TIN edge.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public TinTriangle RightTriangle { get; }
```
### TagValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEdge.yml" sourcestartlinenumber="1">Gets the tag value of this TIN edge.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public override int TagValue { get; }
```
### ToPolyline()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEdge.yml" sourcestartlinenumber="1">Gets this TIN edge as a <xref href="ArcGIS.Core.Geometry.Polyline" data-throw-if-not-resolved="false"></xref>.  The spatial reference of the returned polyline is set to the
spatial reference of the TIN.  See <xref href="ArcGIS.Core.Data.Analyst3D.TinDatasetDefinition.GetSpatialReference" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Polyline ToPolyline()
```


