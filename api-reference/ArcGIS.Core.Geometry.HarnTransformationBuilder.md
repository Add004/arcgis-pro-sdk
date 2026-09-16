# HarnTransformationBuilder

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.HarnTransformationBuilder.yml" sourcestartlinenumber="1">A builder for creating a Harn grid transformation.
A grid transformation is a type of geographic transformation that uses a grid dataset to perform the transformation.</p>


## Object Signature

```csharp
public sealed class HarnTransformationBuilder
```


## Members

### CreateHarnTransformation(string, string, SpatialReference, SpatialReference, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.HarnTransformationBuilder.yml" sourcestartlinenumber="1">Creates a Harn grid transformation with the specified parameters.</p>


```csharp
public static GeographicTransformation CreateHarnTransformation(string name, string gridDatasetName, SpatialReference inputSpatialReference, SpatialReference outputSpatialReference, bool transformForward = true)
```


