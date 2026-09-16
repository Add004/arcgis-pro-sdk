# TinLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinLayer.yml" sourcestartlinenumber="1">Represents a TIN layer.</p>


## Object Signature

```csharp
public sealed class TinLayer : SurfaceLayer, IMetadataInfo, IMetadataSource
```


## Members

### CanInterpolateShape(Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinLayer.yml" sourcestartlinenumber="1">Determines if values can be interpolated for the given geometry.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool CanInterpolateShape(Geometry geometry)
```
### GetSurfaceLength(Multipart, SurfaceInterpolationMethod)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinLayer.yml" sourcestartlinenumber="1">Gets the 3D length of the multipart by interpolating heights from the surface and calculating the sum of 3D distances
between the vertices.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double GetSurfaceLength(Multipart multipart, SurfaceInterpolationMethod interpolationMethod)
```
### GetSurfaceLength(Multipart, SurfaceInterpolationMethod, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinLayer.yml" sourcestartlinenumber="1">Gets the 3D length of the multipart by interpolating heights from the surface and calculating the sum of 3D distances
between the vertices.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double GetSurfaceLength(Multipart multipart, SurfaceInterpolationMethod interpolationMethod, double stepSize, double profileWeedTolerance)
```
### GetSurfaceValues(MapPoint)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinLayer.yml" sourcestartlinenumber="1">Gets elevation, slope and aspect values from the surface at the specified xy location.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SurfaceValues GetSurfaceValues(MapPoint point)
```
### GetTinDataset()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinLayer.yml" sourcestartlinenumber="1">Gets the TIN dataset associated with the layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public TinDataset GetTinDataset()
```
### InterpolatePolygonToMultipatch(Polygon, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinLayer.yml" sourcestartlinenumber="1">Creates a surface conforming multipatch by draping a polygon over the surface.
This method requires a 3D Analyst license.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Multipatch InterpolatePolygonToMultipatch(Polygon polygon, int maximumStripSize)
```
### InterpolateShape(Geometry, SurfaceInterpolationMethod)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinLayer.yml" sourcestartlinenumber="1">Interpolates Z values for a geometric shape from the surface layer.
This method requires a 3D Analyst license.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Geometry InterpolateShape(Geometry geometry, SurfaceInterpolationMethod interpolationMethod)
```
### InterpolateShape(Geometry, SurfaceInterpolationMethod, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinLayer.yml" sourcestartlinenumber="1">Interpolates Z values for a geometric shape from the surface layer.
This method requires a 3D Analyst license.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Geometry InterpolateShape(Geometry geometry, SurfaceInterpolationMethod interpolationMethod, double stepSize, double profileWeedTolerance)
```
### InterpolateShapeVertices(Multipart, SurfaceInterpolationMethod)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinLayer.yml" sourcestartlinenumber="1">Interpolates Z values for a geometric shape from the surface layer at it's vertices only.
This method requires a 3D Analyst license.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Geometry InterpolateShapeVertices(Multipart multipart, SurfaceInterpolationMethod interpolationMethod)
```
### InterpolateZ(double, double, SurfaceInterpolationMethod)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinLayer.yml" sourcestartlinenumber="1">Interpolates the z coordinate of the specified (x,y) location from the surface layer.
This method requires a 3D Analyst license.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double InterpolateZ(double x, double y, SurfaceInterpolationMethod interpolationMethod)
```
### SearchEdges(TinEdgeFilter)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinLayer.yml" sourcestartlinenumber="1">Retrieves the edges in the TIN that satisfy the criteria set in the <code class="paramref">filter</code>.
If no filter is set, all edges will be retrieved.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public TinEdgeCursor SearchEdges(TinEdgeFilter filter)
```
### SearchNodes(TinNodeFilter)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinLayer.yml" sourcestartlinenumber="1">Retrieves the nodes in the TIN that satisfy the criteria set in the <code class="paramref">filter</code>.
If no filter is set, all nodes will be retrieved.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public TinNodeCursor SearchNodes(TinNodeFilter filter)
```
### SearchTriangles(TinTriangleFilter)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TinLayer.yml" sourcestartlinenumber="1">Retrieves the triangles in the TIN that satisfy the criteria set in the <code class="paramref">filter</code>.
If no filter is set, all triangles will be retrieved.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public TinTriangleCursor SearchTriangles(TinTriangleFilter filter)
```


