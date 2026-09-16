# ProjectionTransformation

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.ProjectionTransformation.yml" sourcestartlinenumber="1">A projection transformation describes parameters used to project geometries from one spatial reference to another. Used in the <xref href="ArcGIS.Core.Geometry.GeometryEngine.ProjectEx(ArcGIS.Core.Geometry.Geometry%2cArcGIS.Core.Geometry.ProjectionTransformation)" data-throw-if-not-resolved="false"></xref> method.</p>


## Object Signature

```csharp
public sealed class ProjectionTransformation
```


## Members

### Create(SpatialReference, SpatialReference, Envelope)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.ProjectionTransformation.yml" sourcestartlinenumber="1">Creates a projection transformation from two spatial references and an extent of interest.
Automatically selects a geographic transformation for the projection.</p>


```csharp
public static ProjectionTransformation Create(SpatialReference inputSR, SpatialReference outputSR, Envelope extentOfInterest = null)
```
### CreateEx(SpatialReference, SpatialReference, DatumTransformation)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.ProjectionTransformation.yml" sourcestartlinenumber="1">Creates a projection transformation from two spatial references and the given datum transformation.</p>


```csharp
public static ProjectionTransformation CreateEx(SpatialReference inputSR, SpatialReference outputSR, DatumTransformation datumTransformation)
```
### CreateWithVertical(SpatialReference, SpatialReference, Envelope)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.ProjectionTransformation.yml" sourcestartlinenumber="1">Creates a projection transformation from two spatial references each having a vertical coordinate system,
and possibly an extent of interest. Automatically selects a hv (horizontal/vertical) datum transformation for the projection.</p>


```csharp
public static ProjectionTransformation CreateWithVertical(SpatialReference inputSR, SpatialReference outputSR, Envelope extentOfInterest = null)
```
### FindTransformations(SpatialReference, SpatialReference, Envelope, int, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.ProjectionTransformation.yml" sourcestartlinenumber="1">Gets the list of applicable transformations to use when projecting geometries from the input
spatial reference to the output spatial reference.</p>


```csharp
public static List<ProjectionTransformation> FindTransformations(SpatialReference inputSR, SpatialReference outputSR, Envelope extentOfInterest = null, int numResults = 1, bool vertical = false)
```
### GetInverse()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.ProjectionTransformation.yml" sourcestartlinenumber="1">Creates an inverse ProjectionTransformation instance. The inverse has swapped input and output spatial references and has an inverted CompositeGeographicTransformation.</p>


```csharp
public ProjectionTransformation GetInverse()
```
### InputSpatialReference

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.ProjectionTransformation.yml" sourcestartlinenumber="1">Gets the input spatial reference.</p>


```csharp
public SpatialReference InputSpatialReference { get; }
```
### OutputSpatialReference

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.ProjectionTransformation.yml" sourcestartlinenumber="1">Gets the output spatial reference.</p>


```csharp
public SpatialReference OutputSpatialReference { get; }
```
### Transformation

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.ProjectionTransformation.yml" sourcestartlinenumber="1">Gets the datum transformation. Can be null if transformation is not used.</p>


```csharp
public DatumTransformation Transformation { get; }
```


