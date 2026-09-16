# PatchType

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.PatchType.yml" sourcestartlinenumber="1">Describes the type of the patch.</p>


## Object Signature

```csharp
public enum PatchType
```

## Remarks

<p>Each part in a multipatch is called a patch. A patch can be a triangle strip, triangle fan, a group of triangles, or a ring. 
    If the patch is a ring, it can be either the first ring of a polygon or another ring in the same polygon. The first ring means 
    that it was the first ring created for the polygon when the multipatch was constructed. It doesn't necessarily mean that it is an 
    outer ring and subsequent rings in the polygon are inner rings.
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
    If the type of a patch is PatchType.FirstRing, then it was the first ring created when constructing the polygon. If the type of the 
    patch is PatchType.Ring, then it is part of the same polygon as the previous patch.
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

### FirstRing

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.PatchType.yml" sourcestartlinenumber="1">The first ring created when constructing the polygon.</p>


```csharp
FirstRing = 4
```
### Ring

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.PatchType.yml" sourcestartlinenumber="1">A ring of the same polygon as the previous patch.</p>


```csharp
Ring = 5
```
### TriangleFan

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.PatchType.yml" sourcestartlinenumber="1">A continuous fan of 3-dimensional triangles such that the first point defines the origin.</p>


```csharp
TriangleFan = 1
```
### TriangleStrip

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.PatchType.yml" sourcestartlinenumber="1">A continuous linked strip of 3-dimensional triangles.</p>


```csharp
TriangleStrip = 0
```
### Triangles

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.PatchType.yml" sourcestartlinenumber="1">A collection of 3-dimensional triangles.</p>


```csharp
Triangles = 6
```


