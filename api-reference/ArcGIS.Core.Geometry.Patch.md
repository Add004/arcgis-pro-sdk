# Patch

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.Patch.yml" sourcestartlinenumber="1">A class to create a patch for a <xref href="ArcGIS.Core.Geometry.Multipatch" data-throw-if-not-resolved="false"></xref>. Use <xref href="ArcGIS.Core.Geometry.MultipatchBuilderEx" data-throw-if-not-resolved="false"></xref> to construct a <xref href="ArcGIS.Core.Geometry.Multipatch" data-throw-if-not-resolved="false"></xref> from
patches.</p>


## Object Signature

```csharp
public sealed class Patch
```

## Remarks

<p>Each part in a multipatch is called a patch. A patch can be a triangle strip, triangle fan, a group of triangles, or a ring. 
    If the patch is a ring, it can be either the first ring of a polygon or another ring in the same polygon. The first ring means 
    that it was the first ring created for the polygon when the multipatch was constructed. It doesn't necessarily mean that it is an 
    outer ring and subsequent rings in the polygon are inner rings. The orientation of the ring determines if it is an outer or inner ring. 
    An outer ring is oriented clockwise.
    </p>
<p>
    A triangle strip is a continuous linked strip of 3-dimensional triangles such that every vertex after the first two completes a
    new triangle. A new triangle is always formed by connecting the new vertex with its two immediate predecessors. For example, 
    a triangle strip with six points has triangles defined by the point indices (0, 1, 2), (2, 1, 3), (2, 3, 4), (4, 3, 5).
    </p>
<p>
  <img src="images/ArcGIS.Core.Geometry/TriangleStrip.png" alt="Triangle Strip">
</p>
<p>
    A triangle fan is a continuous fan of 3-dimensional triangles such that the first point defines the origin. All triangles in the fan 
    share the origin as a common pivot point. Every vertex after the first two completes a triangle, and a new triangle is formed by 
    connecting the new vertex to its immediate predecessor and the origin. For example, a triangle fan with six points has triangles defined 
    by point indices (0, 1, 2), (0, 2, 3), (0, 3, 4), (0, 4, 5).
    </p>
<p>
  <img src="images/ArcGIS.Core.Geometry/TriangleFan.png" alt="Triangle Fan">
</p>
<p>
    A ring is a geometric element from which polygons are constructed, defined by an area bounded by one closed sequence of connected segments. 
    If the type of a patch is <xref href="ArcGIS.Core.Geometry.PatchType.FirstRing" data-throw-if-not-resolved="false"></xref>, then it was the first ring created when constructing the polygon. If the type of the 
    patch is <xref href="ArcGIS.Core.Geometry.PatchType.Ring" data-throw-if-not-resolved="false"></xref>, then it is part of the same polygon as the previous patch.
    </p>
<p>
  <img src="images/ArcGIS.Core.Geometry/Rings.png" alt="Rings">
</p>
<p>
    Triangles is a collection of 3-dimensional triangles such that each consecutive triplet of vertices defines a new triangle. The number of vertices 
    in patch of type PatchType.Triangles must be multiple of three. For example, a patch of type PatchType.Triangles with nine points has
    triangles defined by point indices (0, 1, 2), (3, 4, 5), (6, 7, 8).
    </p>
<p>
  <img src="images/ArcGIS.Core.Geometry/Triangles.png" alt="Triangles">
</p>


## Members

### Patch(Patch)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.Patch.yml" sourcestartlinenumber="1">Creates a deep copy of the <xref href="ArcGIS.Core.Geometry.Patch" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public Patch(Patch other)
```
### Patch(PatchType)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.Patch.yml" sourcestartlinenumber="1">Initializes an empty instance of the <xref href="ArcGIS.Core.Geometry.Patch" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public Patch(PatchType patchType)
```
### AddPoint(MapPoint)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Patch.yml" sourcestartlinenumber="1">Adds a point to the patch.</p>


```csharp
public void AddPoint(MapPoint point)
```
### Coords

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Patch.yml" sourcestartlinenumber="1">Gets or sets the IList of coordinates that define this patch.</p>


```csharp
public IList<Coordinate3D> Coords { get; set; }
```
### GetPoint(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Patch.yml" sourcestartlinenumber="1">Gets the point at the specified index.</p>


```csharp
public MapPoint GetPoint(int index)
```
### IDs

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Patch.yml" sourcestartlinenumber="1">Gets or sets the IList of ID-values.</p>


```csharp
public IList<int> IDs { get; set; }
```
### InsertPoint(int, MapPoint)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Patch.yml" sourcestartlinenumber="1">Inserts a point at the specified index.</p>


```csharp
public void InsertPoint(int index, MapPoint point)
```
### InsertPoints(int, IEnumerable&lt;MapPoint&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Patch.yml" sourcestartlinenumber="1">Inserts a range of points at the specified index.</p>


```csharp
public void InsertPoints(int index, IEnumerable<MapPoint> points)
```
### IsEqual(Patch)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Patch.yml" sourcestartlinenumber="1">Determines if this patch is equal to the other patch.</p>


```csharp
public bool IsEqual(Patch other)
```
### Material

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Patch.yml" sourcestartlinenumber="1">Gets or sets the material for this patch by reference.</p>


```csharp
public Material Material { get; set; }
```
### Ms

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Patch.yml" sourcestartlinenumber="1">Gets or sets the IList of M-values.</p>


```csharp
public IList<double> Ms { get; set; }
```
### Normals

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Patch.yml" sourcestartlinenumber="1">Gets or sets the IList of normals.</p>


```csharp
public IList<Coordinate3D> Normals { get; set; }
```
### PatchPriority

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Patch.yml" sourcestartlinenumber="1">Gets or sets a value representing the priority of this patch. The default value is zero.</p>


```csharp
public int PatchPriority { get; set; }
```
### PatchType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Patch.yml" sourcestartlinenumber="1">Gets or sets the patch type.</p>


```csharp
public PatchType PatchType { get; set; }
```
### RemovePoints(int, int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Patch.yml" sourcestartlinenumber="1">Removes a range of points.</p>


```csharp
public void RemovePoints(int fromIndex, int toIndex)
```
### SetPoint(int, MapPoint)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Patch.yml" sourcestartlinenumber="1">Sets a point at the specified index.</p>


```csharp
public void SetPoint(int index, MapPoint point)
```
### SynchronizeAttributeAwarenessWithBuilder(MultipatchBuilderEx)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Patch.yml" sourcestartlinenumber="1">Ensures this <xref href="ArcGIS.Core.Geometry.Patch" data-throw-if-not-resolved="false"></xref> has the same attributes as the input <xref href="ArcGIS.Core.Geometry.MultipatchBuilderEx" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public bool SynchronizeAttributeAwarenessWithBuilder(MultipatchBuilderEx multipatchBuilder)
```
### TextureCoords2D

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Patch.yml" sourcestartlinenumber="1">Gets or sets the IList of 2D texture coordinates.</p>


```csharp
public IList<Coordinate2D> TextureCoords2D { get; set; }
```


