# ProximityResult

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.ProximityResult.yml" sourcestartlinenumber="1">Result from a GeometryEngine proximity operation such as <xref href="ArcGIS.Core.Geometry.GeometryEngine.NearestPoint(ArcGIS.Core.Geometry.Geometry%2cArcGIS.Core.Geometry.MapPoint)" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Core.Geometry.GeometryEngine.NearestVertex(ArcGIS.Core.Geometry.Geometry%2cArcGIS.Core.Geometry.MapPoint)" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class ProximityResult
```


## Members

### Distance

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.ProximityResult.yml" sourcestartlinenumber="1">Gets the distance between the input query point and the nearest point found.</p>


```csharp
public double Distance { get; }
```
### IsRightSide

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.ProximityResult.yml" sourcestartlinenumber="1">Is the point rightSide or leftSide? Only relevant if calling <xref href="ArcGIS.Core.Geometry.GeometryEngine.NearestPoint(ArcGIS.Core.Geometry.Geometry%2cArcGIS.Core.Geometry.MapPoint)" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public bool IsRightSide { get; }
```
### PartIndex

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.ProximityResult.yml" sourcestartlinenumber="1">Gets the index of the part in which the point was found.</p>


```csharp
public int PartIndex { get; }
```
### Point

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.ProximityResult.yml" sourcestartlinenumber="1">Gets the point found.</p>


```csharp
public MapPoint Point { get; }
```
### PointIndex

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.ProximityResult.yml" sourcestartlinenumber="1">Gets the index of the point that was found.
Only relevant if calling <xref href="ArcGIS.Core.Geometry.GeometryEngine.NearestVertex(ArcGIS.Core.Geometry.Geometry%2cArcGIS.Core.Geometry.MapPoint)" data-throw-if-not-resolved="false"></xref>, otherwise point index is null.</p>


```csharp
public int? PointIndex { get; }
```
### SegmentIndex

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.ProximityResult.yml" sourcestartlinenumber="1">Gets the segment index of the segment containing the nearest point. The segment index is relative to the part index.
For example, if PartIndex = 2 and SegmentIndex = 0, it means segment 0 in part 2.
Only relevant if calling <xref href="ArcGIS.Core.Geometry.GeometryEngine.NearestPoint(ArcGIS.Core.Geometry.Geometry%2cArcGIS.Core.Geometry.MapPoint)" data-throw-if-not-resolved="false"></xref>, otherwise segment index is null.</p>


```csharp
public int? SegmentIndex { get; }
```


