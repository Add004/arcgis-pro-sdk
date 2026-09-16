# RasterLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.RasterLayer.yml" sourcestartlinenumber="1">Represents a raster layer.</p>


## Object Signature

```csharp
public sealed class RasterLayer : BasicRasterLayer, IMetadataInfo, IMetadataSource
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.RasterLayer.yml" sourcestartlinenumber="1">The raster layer is a representation of a file or geodatabase raster dataset. The raster layer is drawn based on the <xref href="ArcGIS.Core.CIM.CIMRasterColorizer" data-throw-if-not-resolved="false"></xref></p>


## Members

### CanGetLineOfSight(LineOfSightParams)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.RasterLayer.yml" sourcestartlinenumber="1">Determines whether a Line of Sight analysis can be calculated for the given set of parameters.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool CanGetLineOfSight(LineOfSightParams lineOfSightParams)
```
### CanInterpolateShape(Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.RasterLayer.yml" sourcestartlinenumber="1">Determines if values can be interpolated for the given geometry.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool CanInterpolateShape(Geometry geometry)
```
### CanSetTime(TimeParameters)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.RasterLayer.yml" sourcestartlinenumber="1">Gets if the mapMember supports time filtering and if the specified time parameters are valid.
This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public override bool CanSetTime(TimeParameters timeParams)
```
### DisplayExpressionInfo

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.RasterLayer.yml" sourcestartlinenumber="1">Gets the display expression info.</p>


```csharp
public CIMExpressionInfo DisplayExpressionInfo { get; }
```
### DisplayField

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.RasterLayer.yml" sourcestartlinenumber="1">Gets the name of the attribute field that is used to identify each row or feature.</p>


```csharp
public string DisplayField { get; }
```
### GetLineOfSight(LineOfSightParams)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.RasterLayer.yml" sourcestartlinenumber="1">Performs a line of sight analysis for an observer and target point on the surface.  Determines if the target point is visible from a given observer point.
This method requires a 3D Analyst license.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public LineOfSightResult GetLineOfSight(LineOfSightParams lineOfSightParams)
```
### GetSurfaceLength(Multipart)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.RasterLayer.yml" sourcestartlinenumber="1">Gets the 3D length of the multipart by interpolating heights from the surface and calculating the sum of 3D distances
between the vertices. Bilinear interpolation is used.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double GetSurfaceLength(Multipart multipart)
```
### GetSurfaceLength(Multipart, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.RasterLayer.yml" sourcestartlinenumber="1">Gets the 3D length of the multipart by interpolating heights from the surface and calculating the sum of 3D distances
between the vertices. Bilinear interpolation is used.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double GetSurfaceLength(Multipart multipart, double stepSize)
```
### GetSurfaceValues(MapPoint)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.RasterLayer.yml" sourcestartlinenumber="1">Gets elevation, slope and aspect values from the surface at the specified xy location.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SurfaceValues GetSurfaceValues(MapPoint point)
```
### InterpolateShape(Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.RasterLayer.yml" sourcestartlinenumber="1">Interpolates Z values for a geometric shape from the raster layer. Bilinear interpolation is used.
This method requires a 3D Analyst license.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Geometry InterpolateShape(Geometry geometry)
```
### InterpolateShape(Geometry, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.RasterLayer.yml" sourcestartlinenumber="1">Interpolates Z values for a geometric shape from the raster layer. Bilinear interpolation is used.
This method requires a 3D Analyst license.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Geometry InterpolateShape(Geometry geometry, double stepSize)
```
### InterpolateShapeVertices(Multipart)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.RasterLayer.yml" sourcestartlinenumber="1">Interpolates Z values for a geometric shape from the raster surface layer at it's vertices only. Bilinear interpolation is used.
This method requires a 3D Analyst license.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Geometry InterpolateShapeVertices(Multipart multipart)
```
### InterpolateZ(double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.RasterLayer.yml" sourcestartlinenumber="1">Interpolates the z coordinate of the specified location from the surface layer.  Bilinear interpolation is used.
This method requires a 3D Analyst license.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double InterpolateZ(double x, double y)
```
### IsEditable

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.RasterLayer.yml" sourcestartlinenumber="1">Gets whether a layer is editable.</p>


```csharp
public bool IsEditable { get; }
```
### SetDisplayExpressionInfo(CIMExpressionInfo)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.RasterLayer.yml" sourcestartlinenumber="1">Sets the display expression info with an arcade expression that will be used to identify features or rows. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDisplayExpressionInfo(CIMExpressionInfo displayExpressionInfo)
```
### SetDisplayField(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.RasterLayer.yml" sourcestartlinenumber="1">Sets the name of the attribute field that will be used to identify features or rows. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDisplayField(string displayField)
```


