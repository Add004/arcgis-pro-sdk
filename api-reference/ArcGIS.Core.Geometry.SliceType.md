# SliceType

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.SliceType.yml" sourcestartlinenumber="1">Options for use with the <xref href="ArcGIS.Core.Geometry.GeometryEngine.SlicePolygonIntoEqualParts(ArcGIS.Core.Geometry.Polygon%2cSystem.Int32%2cSystem.Double%2cArcGIS.Core.Geometry.SliceType)" data-throw-if-not-resolved="false"></xref> method.</p>


## Object Signature

```csharp
public enum SliceType
```


## Members

### Blocks

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.SliceType.yml" sourcestartlinenumber="1">Slice into equal area blocks, not necessarily strips.
The slicing is done recursively, each time slicing the polygon into two parts along the larger dimension (height or width).</p>


```csharp
Blocks = 2
```
### Strips

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.SliceType.yml" sourcestartlinenumber="1">Slice into strips.</p>


```csharp
Strips = 1
```


