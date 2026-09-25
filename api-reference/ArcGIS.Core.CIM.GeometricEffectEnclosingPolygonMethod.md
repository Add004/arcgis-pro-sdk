# GeometricEffectEnclosingPolygonMethod

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectEnclosingPolygonMethod.yml" sourcestartlinenumber="1">Geometric effect enclosing polygon methods.</p>


## Object Signature

```csharp
public enum GeometricEffectEnclosingPolygonMethod
```


## Members

### ClosePath

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectEnclosingPolygonMethod.yml" sourcestartlinenumber="1">ClosePath - for polygon input, it generates a polygon that matches the geometry of a polygon feature. For line input, it generates a polygon that connects both ends of the line to each other.</p>


```csharp
ClosePath = 0
```
### ConvexHull

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectEnclosingPolygonMethod.yml" sourcestartlinenumber="1">ConvexHull - for polygon input, it generates a polygon with a minimum number of sides to surround the feature. For line input, it generates a polygon that approximates the shape of the line.</p>


```csharp
ConvexHull = 1
```
### RectangularBox

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.GeometricEffectEnclosingPolygonMethod.yml" sourcestartlinenumber="1">RectangularBox - generates a polygon equal to the spatial envelope of the feature.</p>


```csharp
RectangularBox = 2
```


