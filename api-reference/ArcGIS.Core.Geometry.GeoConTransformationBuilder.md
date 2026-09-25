# GeoConTransformationBuilder

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.GeoConTransformationBuilder.yml" sourcestartlinenumber="1">A builder for creating a GeoCon grid transformation.
A grid transformation is a type of geographic transformation that uses a grid dataset to perform the transformation.</p>


## Object Signature

```csharp
public sealed class GeoConTransformationBuilder
```


## Members

### CreateGeoConTransformation(string, string, SpatialReference, SpatialReference, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeoConTransformationBuilder.yml" sourcestartlinenumber="1">Creates a GeoCon grid transformation with the specified parameters.</p>


```csharp
public static GeographicTransformation CreateGeoConTransformation(string name, string gridDatasetName, SpatialReference inputSpatialReference, SpatialReference outputSpatialReference, bool transformForward = true)
```


