# SimplifyType

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.SimplifyType.yml" sourcestartlinenumber="1">Options for use with the <xref href="ArcGIS.Core.Geometry.GeometryEngine.SimplifyPolyline(ArcGIS.Core.Geometry.Polyline%2cArcGIS.Core.Geometry.SimplifyType%2cSystem.Boolean)" data-throw-if-not-resolved="false"></xref> functions.</p>


## Object Signature

```csharp
public enum SimplifyType
```


## Members

### Network

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.SimplifyType.yml" sourcestartlinenumber="1">Removes zero length segments (zero in 2 dimensions), merges parts at endpoints that only connect to each other, re-orients
segments that are pointing against the prevailing orientation for a part. Creates new parts for discontiguous segments or segments with different
attributes. For a pair of segments in a part that share an endpoint such that one segment has NaN attributes and the other has non-NaN attributes,
assign the non-NaN attributes of one to the corresponding NaN slots of the other. Equivalent to IPolyline SimplifyNetwork.</p>


```csharp
Network = 0
```
### Nonplanar

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.SimplifyType.yml" sourcestartlinenumber="1">Nonplanar: Removes zero length segments (zero in 2 dimensions), re-orients segments that are pointing against the prevailing orientation for a part.
Creates new parts for non-contiguous segments or segments with different attributes. For a pair of segments in a part that share an endpoint
such that one segment has NaN attributes and the other has non-NaN attributes, assign the non-NaN attributes of one to the corresponding NaN
slots of the other. This method is similar to <b>Network</b>, except parts are <b>not</b> merged where an end point is shared.
Equivalent to IPolyline6 SimplifyNonPlanar.</p>


```csharp
Nonplanar = 2
```
### Planar

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.SimplifyType.yml" sourcestartlinenumber="1">Force planar simplification on to a polyline that is M-Aware. If a polyline is m-aware, planar
simplification will not attempt to detect self-intersections, overlaps, etc. Equivalent to IPolyline4 SimplifyEx(planarSimplify=true).</p>


```csharp
Planar = 1
```


