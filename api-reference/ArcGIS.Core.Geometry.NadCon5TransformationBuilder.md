# NadCon5TransformationBuilder

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.NadCon5TransformationBuilder.yml" sourcestartlinenumber="1">A builder for creating a NadCon5 grid transformation.
A grid transformation is a type of geographic transformation that uses a grid dataset to perform the transformation.</p>


## Object Signature

```csharp
public sealed class NadCon5TransformationBuilder
```


## Members

### CreateNadCon5Transformation(string, string, SpatialReference, SpatialReference, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.NadCon5TransformationBuilder.yml" sourcestartlinenumber="1">Creates a NadCon5 grid transformation with the specified parameters.</p>


```csharp
public static GeographicTransformation CreateNadCon5Transformation(string name, string gridDatasetName, SpatialReference inputSpatialReference, SpatialReference outputSpatialReference, bool transformForward = true)
```


