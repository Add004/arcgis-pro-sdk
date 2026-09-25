# GeometryDimensionType

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryDimensionType.yml" sourcestartlinenumber="1">Describes the dimensionality of the geometry object. Use with <xref href="ArcGIS.Core.Geometry.GeometryEngine.Intersection(ArcGIS.Core.Geometry.Geometry%2cArcGIS.Core.Geometry.Geometry%2cArcGIS.Core.Geometry.GeometryDimensionType)" data-throw-if-not-resolved="false"></xref> .</p>


## Object Signature

```csharp
public enum GeometryDimensionType
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryDimensionType.yml" sourcestartlinenumber="1">A <xref href="ArcGIS.Core.Geometry.MapPoint" data-throw-if-not-resolved="false"></xref> and a <xref href="ArcGIS.Core.Geometry.Multipoint" data-throw-if-not-resolved="false"></xref> are zero dimensional.
A <xref href="ArcGIS.Core.Geometry.Polyline" data-throw-if-not-resolved="false"></xref> is one dimensional.
A <xref href="ArcGIS.Core.Geometry.Polygon" data-throw-if-not-resolved="false"></xref>, and an <xref href="ArcGIS.Core.Geometry.Envelope" data-throw-if-not-resolved="false"></xref> are two dimensional.
A <xref href="ArcGIS.Core.Geometry.Multipatch" data-throw-if-not-resolved="false"></xref> is three dimensional.
Note if Geometry.HasZ = true, meaning that it is Z-Aware, the dimensionality of the geometry is not affected.</p>


## Members

### EsriGeometry0Dimension

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryDimensionType.yml" sourcestartlinenumber="1">Zero dimension (point or multipoint).</p>


```csharp
EsriGeometry0Dimension = 1
```
### EsriGeometry1Dimension

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryDimensionType.yml" sourcestartlinenumber="1">One dimension (polyline).</p>


```csharp
EsriGeometry1Dimension = 2
```
### EsriGeometry2Dimension

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryDimensionType.yml" sourcestartlinenumber="1">Two dimension (polygon or envelope).</p>


```csharp
EsriGeometry2Dimension = 4
```
### EsriGeometry3Dimension

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryDimensionType.yml" sourcestartlinenumber="1">Three dimension (multipatch).</p>


```csharp
EsriGeometry3Dimension = 6
```
### EsriGeometryUnknownDimension

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryDimensionType.yml" sourcestartlinenumber="1">Dimension is unknown.</p>


```csharp
EsriGeometryUnknownDimension = -1
```


