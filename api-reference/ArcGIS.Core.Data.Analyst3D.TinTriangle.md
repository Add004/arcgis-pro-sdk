# TinTriangle

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Analyst3D.html">Analyst3D</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinTriangle.yml" sourcestartlinenumber="1">A <xref href="ArcGIS.Core.Data.Analyst3D.TinTriangle" data-throw-if-not-resolved="false"></xref> is one of the three basic elements of a TIN.  Triangles are comprised of three <xref href="ArcGIS.Core.Data.Analyst3D.TinNode?text=TinNodes" data-throw-if-not-resolved="false"></xref> and
<xref href="ArcGIS.Core.Data.Analyst3D.TinEdge?text=TinEdges" data-throw-if-not-resolved="false"></xref>.  Nodes and edges are oriented in clockwise direction.</p>


## Object Signature

```csharp
public sealed class TinTriangle : TinElement, IDisposable
```


## Members

### Area

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinTriangle.yml" sourcestartlinenumber="1">Gets the area of this TIN triangle.  The area is in the units of the spatial reference of the TIN.
See <xref href="ArcGIS.Core.Data.Analyst3D.TinDatasetDefinition.GetSpatialReference" data-throw-if-not-resolved="false"></xref>
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double Area { get; }
```
### Area3D

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinTriangle.yml" sourcestartlinenumber="1">Gets the 3D area of this TIN triangle.  The area is in the units of the spatial reference of the TIN.
See <xref href="ArcGIS.Core.Data.Analyst3D.TinDatasetDefinition.GetSpatialReference" data-throw-if-not-resolved="false"></xref>. If the triangle has NaN z-values, then NaN is returned.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double Area3D { get; }
```
### Aspect

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinTriangle.yml" sourcestartlinenumber="1">Gets the aspect of this TIN triangle in radians.
The aspect is the compass direction of the steepest downhill slope of the triangle.
A value of 0 radians is due North, PI / 2 radians due East, PI radians due South, 3 * PI / 2 due West, etc.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double Aspect { get; }
```
### Edges

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinTriangle.yml" sourcestartlinenumber="1">Gets the edges of this TIN triangle.  The edges are ordered in a clockwise direction.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<TinEdge> Edges { get; }
```
### ElementType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinTriangle.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Analyst3D.TinElementType" data-throw-if-not-resolved="false"></xref> of this instance.  Always returns <xref href="ArcGIS.Core.Data.Analyst3D.TinElementType.Triangle" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public override TinElementType ElementType { get; }
```
### GetAdjacentTriangleIndices()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinTriangle.yml" sourcestartlinenumber="1">Gets the list of triangle indices adjacent to this TIN triangle.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<int> GetAdjacentTriangleIndices()
```
### GetAdjacentTriangles()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinTriangle.yml" sourcestartlinenumber="1">Gets the list of triangles adjacent to this TIN triangle.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<TinTriangle> GetAdjacentTriangles()
```
### GetCentroid()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinTriangle.yml" sourcestartlinenumber="1">Gets the centroid of this TIN triangle as determined by averaging the coordinates of its vertices.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public MapPoint GetCentroid()
```
### GetCircumCircle()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinTriangle.yml" sourcestartlinenumber="1">Gets the circle whose boundary passes through all three of the triangle's nodes.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public EllipticArcSegment GetCircumCircle()
```
### GetNormal()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinTriangle.yml" sourcestartlinenumber="1">Gets the vector normal to this TIN triangle.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Coordinate3D GetNormal()
```
### GetPointsBetweenZs(double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinTriangle.yml" sourcestartlinenumber="1">Gets the set of coordinates for this TIN triangle that falls within the specified Z values.
Use these coordinates to build a 3D polygonal definition for the area of the triangle that falls within the specified Z values.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<Coordinate3D> GetPointsBetweenZs(double minZ, double maxZ)
```
### GetUnitNormal()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinTriangle.yml" sourcestartlinenumber="1">Gets the vector normal to this TIN triangle, adjusted to a magnitude of one.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Coordinate3D GetUnitNormal()
```
### HasVoidZ

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinTriangle.yml" sourcestartlinenumber="1">Gets a value indicating if this TIN element has Z-less vertices. If the z-value of a vertex is NaN, then it is considered z-less.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public override bool HasVoidZ { get; }
```
### Intensity

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinTriangle.yml" sourcestartlinenumber="1">Gets the intensity (i.e. brightness value) of this TIN triangle.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double Intensity { get; }
```
### IsEmpty

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinTriangle.yml" sourcestartlinenumber="1">Gets a value indicating whether or not this element is empty.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public override bool IsEmpty { get; }
```
### IsInsideDataArea

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinTriangle.yml" sourcestartlinenumber="1">Gets if this element is within the interpolation zone or the data area of the TIN. See <xref href="ArcGIS.Core.Data.Analyst3D.TinDataset.GetDataArea" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public override bool IsInsideDataArea { get; }
```
### IsInsideExtent(Envelope)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinTriangle.yml" sourcestartlinenumber="1">Gets if this element is inside the specified extent.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public override bool IsInsideExtent(Envelope extent)
```
### Length

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinTriangle.yml" sourcestartlinenumber="1">Gets the length (i.e. perimeter) of this TIN triangle.  The length is in the units of the spatial reference of the TIN.
See <xref href="ArcGIS.Core.Data.Analyst3D.TinDatasetDefinition.GetSpatialReference" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public override double Length { get; }
```
### Length3D

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinTriangle.yml" sourcestartlinenumber="1">Gets the 3D length (i.e. perimeter) of this TIN triangle. The length is in the units of the spatial reference of the TIN.
See <xref href="ArcGIS.Core.Data.Analyst3D.TinDatasetDefinition.GetSpatialReference" data-throw-if-not-resolved="false"></xref>. If the triangle has NaN z-values, then NaN is returned.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double Length3D { get; }
```
### NodeCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinTriangle.yml" sourcestartlinenumber="1">Gets the node count of the element. Always returns 3.</p>


```csharp
public override int NodeCount { get; }
```
### Nodes

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinTriangle.yml" sourcestartlinenumber="1">Gets the nodes of this TIN triangle.  The nodes are ordered in a clockwise direction.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<TinNode> Nodes { get; }
```
### Slope

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinTriangle.yml" sourcestartlinenumber="1">Gets the slope of this TIN triangle in radians.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double Slope { get; }
```
### SlopePercent

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinTriangle.yml" sourcestartlinenumber="1">Gets the slope of this TIN triangle as a percent.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double SlopePercent { get; }
```
### TagValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinTriangle.yml" sourcestartlinenumber="1">Gets the tag value of this TIN triangle.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public override int TagValue { get; }
```
### ToPolygon()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinTriangle.yml" sourcestartlinenumber="1">Gets this TIN triangle as a <xref href="ArcGIS.Core.Geometry.Polygon" data-throw-if-not-resolved="false"></xref>.  The spatial reference of the returned polygon is set to the
spatial reference of the TIN.  See <xref href="ArcGIS.Core.Data.Analyst3D.TinDatasetDefinition.GetSpatialReference" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Polygon ToPolygon()
```


