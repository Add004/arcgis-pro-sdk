# TerrainLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.TerrainLayer.yml" sourcestartlinenumber="1">Represents a Terrain layer.</p>


## Object Signature

```csharp
public sealed class TerrainLayer : SurfaceLayer, IMetadataInfo, IMetadataSource
```


## Members

### CanInterpolateShape(Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TerrainLayer.yml" sourcestartlinenumber="1">Determines if values can be interpolated for the given geometry.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool CanInterpolateShape(Geometry geometry)
```
### GetTerrain()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TerrainLayer.yml" sourcestartlinenumber="1">Gets the terrain dataset associated with the layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Terrain GetTerrain()
```
### InterpolatePolygonToMultipatch(Polygon, int, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TerrainLayer.yml" sourcestartlinenumber="1">Creates a surface conforming multipatch by draping a polygon over the surface.
This method requires a 3D Analyst license.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Multipatch InterpolatePolygonToMultipatch(Polygon polygon, int maximumStripSize, double pyramidResolution)
```
### InterpolateShape(Geometry, SurfaceInterpolationMethod)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TerrainLayer.yml" sourcestartlinenumber="1">Interpolates Z values for a geometric shape from the surface layer.
This method requires a 3D Analyst license.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Geometry InterpolateShape(Geometry geometry, SurfaceInterpolationMethod interpolationMethod)
```
### InterpolateShape(Geometry, SurfaceInterpolationMethod, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TerrainLayer.yml" sourcestartlinenumber="1">Interpolates Z values for a geometric shape from the surface layer.
This method requires a 3D Analyst license.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Geometry InterpolateShape(Geometry geometry, SurfaceInterpolationMethod interpolationMethod, double stepSize, double pyramidResolution)
```
### InterpolateShapeVertices(Multipart, SurfaceInterpolationMethod, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TerrainLayer.yml" sourcestartlinenumber="1">Interpolates Z values for a geometric shape from the surface layer at it's vertices only.
This method requires a 3D Analyst license.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Geometry InterpolateShapeVertices(Multipart multipart, SurfaceInterpolationMethod interpolationMethod, double pyramidResolution)
```
### InterpolateZ(double, double, SurfaceInterpolationMethod)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TerrainLayer.yml" sourcestartlinenumber="1">Interpolates the z coordinate of the specified xy location from the surface layer.
This method requires a 3D Analyst license.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double InterpolateZ(double x, double y, SurfaceInterpolationMethod interpolationMethod)
```


