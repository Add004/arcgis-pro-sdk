# SurfaceInterpolationMethod

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.SurfaceInterpolationMethod.yml" sourcestartlinenumber="1">Interpolation method used for elevation calculations.  See <xref href="ArcGIS.Desktop.Mapping.TinLayer.InterpolateShape(ArcGIS.Core.Geometry.Geometry%2cArcGIS.Desktop.Mapping.SurfaceInterpolationMethod)" data-throw-if-not-resolved="false"></xref>
and <xref href="ArcGIS.Desktop.Mapping.TinLayer.GetSurfaceLength(ArcGIS.Core.Geometry.Multipart%2cArcGIS.Desktop.Mapping.SurfaceInterpolationMethod)" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Desktop.Mapping.TerrainLayer.InterpolateShape(ArcGIS.Core.Geometry.Geometry%2cArcGIS.Desktop.Mapping.SurfaceInterpolationMethod)" data-throw-if-not-resolved="false"></xref>
and <xref href="ArcGIS.Desktop.Mapping.TerrainLayer.InterpolateShapeVertices(ArcGIS.Core.Geometry.Multipart%2cArcGIS.Desktop.Mapping.SurfaceInterpolationMethod%2cSystem.Double)" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public enum SurfaceInterpolationMethod
```


## Members

### Linear

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.SurfaceInterpolationMethod.yml" sourcestartlinenumber="1">Linear interpolation.  The default.</p>


```csharp
Linear = 0
```
### NaturalNeighbor

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.SurfaceInterpolationMethod.yml" sourcestartlinenumber="1">Natural neighbor interpolation.</p>


```csharp
NaturalNeighbor = 1
```
### NaturalNeighborInverseDistanceWeight

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.SurfaceInterpolationMethod.yml" sourcestartlinenumber="1">Inverse Distance Weight based on natural neighbors.</p>


```csharp
NaturalNeighborInverseDistanceWeight = 6
```
### NaturalNeighborZAverage

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.SurfaceInterpolationMethod.yml" sourcestartlinenumber="1">Z closest to the average of all natural neighbor nodes.</p>


```csharp
NaturalNeighborZAverage = 4
```
### NaturalNeighborZMax

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.SurfaceInterpolationMethod.yml" sourcestartlinenumber="1">Maximum Z of all natural neighbor nodes.</p>


```csharp
NaturalNeighborZMax = 3
```
### NaturalNeighborZMin

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.SurfaceInterpolationMethod.yml" sourcestartlinenumber="1">Minimum Z of all natural neighbor nodes.</p>


```csharp
NaturalNeighborZMin = 2
```
### NaturalNeighborZNearest

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.SurfaceInterpolationMethod.yml" sourcestartlinenumber="1">Z value of the nearest node.</p>


```csharp
NaturalNeighborZNearest = 5
```


