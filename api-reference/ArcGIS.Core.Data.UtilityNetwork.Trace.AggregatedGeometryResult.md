# AggregatedGeometryResult

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.Trace.html">Trace</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.AggregatedGeometryResult.yml" sourcestartlinenumber="1">Represents the result of aggregated geometries (multi-point, polyline or polygon) from a trace output.</p>


## Object Signature

```csharp
public class AggregatedGeometryResult : Result
```


## Members

### Line

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.AggregatedGeometryResult.yml" sourcestartlinenumber="1">Returns an aggregated <xref href="ArcGIS.Core.Geometry.Polyline" data-throw-if-not-resolved="false"></xref> geometry.
This geometry is the union of all of the linear features returned by the trace.</p>


```csharp
public Geometry Line { get; }
```
### LineCore

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.AggregatedGeometryResult.yml" sourcestartlinenumber="1">Returns an aggregated <xref href="ArcGIS.Core.Geometry.Polyline" data-throw-if-not-resolved="false"></xref> geometry.
This geometry is the union of all of the linear features returned by the trace.</p>


```csharp
protected virtual Geometry LineCore { get; }
```
### Point

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.AggregatedGeometryResult.yml" sourcestartlinenumber="1">Returns an aggregated <xref href="ArcGIS.Core.Geometry.Multipoint" data-throw-if-not-resolved="false"></xref> geometry.
This geometry is the union of all of the point features returned by the trace.</p>


```csharp
public Geometry Point { get; }
```
### PointCore

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.AggregatedGeometryResult.yml" sourcestartlinenumber="1">Returns an aggregated <xref href="ArcGIS.Core.Geometry.Multipoint" data-throw-if-not-resolved="false"></xref> geometry.
This geometry is the union of all of the point features returned by the trace.</p>


```csharp
protected virtual Geometry PointCore { get; }
```
### Polygon

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.AggregatedGeometryResult.yml" sourcestartlinenumber="1">Returns an aggregated <xref href="ArcGIS.Core.Geometry.Polygon" data-throw-if-not-resolved="false"></xref> geometry.
This geometry is the union of all of the polygonal features returned by the trace.</p>


```csharp
public Geometry Polygon { get; }
```
### PolygonCore

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Trace.AggregatedGeometryResult.yml" sourcestartlinenumber="1">Returns an aggregated <xref href="ArcGIS.Core.Geometry.Polygon" data-throw-if-not-resolved="false"></xref> geometry.
This geometry is the union of all of the polygonal features returned by the trace.</p>


```csharp
protected virtual Geometry PolygonCore { get; }
```


