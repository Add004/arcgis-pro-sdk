# NTv2TransformationBuilder

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.NTv2TransformationBuilder.yml" sourcestartlinenumber="1">A builder for creating a NTv2 grid transformation.
A grid transformation is a type of geographic transformation that uses a grid dataset to perform the transformation.</p>


## Object Signature

```csharp
public sealed class NTv2TransformationBuilder
```


## Members

### CreateNTv2Transformation(string, string, SpatialReference, SpatialReference, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.NTv2TransformationBuilder.yml" sourcestartlinenumber="1">Creates a NTv2 grid transformation with the specified parameters.</p>


```csharp
public static GeographicTransformation CreateNTv2Transformation(string name, string gridDatasetName, SpatialReference inputSpatialReference, SpatialReference outputSpatialReference, bool transformForward = true)
```


