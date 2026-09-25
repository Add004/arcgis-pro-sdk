# WktExportFlags

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.WktExportFlags.yml" sourcestartlinenumber="1">Specifies the flags that control the behavior of the <xref href="ArcGIS.Core.Geometry.GeometryEngine.ExportToWKT(ArcGIS.Core.Geometry.WktExportFlags%2cArcGIS.Core.Geometry.Geometry)" data-throw-if-not-resolved="false"></xref> method.</p>


## Object Signature

```csharp
public enum WktExportFlags
```


## Members

### WktExportDefaults

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.WktExportFlags.yml" sourcestartlinenumber="1">Exports the geometry as is based on its type.
Attributes such as Z and M values are exported.</p>


```csharp
WktExportDefaults = 0
```
### WktExportFailIfNotSimple

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.WktExportFlags.yml" sourcestartlinenumber="1">Throws an exception if the geometry is not topologically simple.
Applies only to Polygon and Polyline geometry types.</p>


```csharp
WktExportFailIfNotSimple = 4096
```
### WktExportLineString

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.WktExportFlags.yml" sourcestartlinenumber="1">Exports a MultiLineString with one LineString as a LineString.</p>


```csharp
WktExportLineString = 4
```
### WktExportMultiLineString

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.WktExportFlags.yml" sourcestartlinenumber="1">Exports a LineString as a MultiLineString</p>


```csharp
WktExportMultiLineString = 8
```
### WktExportMultiPolygon

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.WktExportFlags.yml" sourcestartlinenumber="1">Exports a Polygon as a MultiPolygon.</p>


```csharp
WktExportMultiPolygon = 32
```
### WktExportMultipoint

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.WktExportFlags.yml" sourcestartlinenumber="1">Exports a Point as a Multipoint.</p>


```csharp
WktExportMultipoint = 2
```
### WktExportPoint

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.WktExportFlags.yml" sourcestartlinenumber="1">Exports a Multipoint with one Point as a Point.</p>


```csharp
WktExportPoint = 1
```
### WktExportPolygon

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.WktExportFlags.yml" sourcestartlinenumber="1">Exports a MultiPolygon with one Polygon as a Polygon.</p>


```csharp
WktExportPolygon = 16
```
### WktExportStripMs

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.WktExportFlags.yml" sourcestartlinenumber="1">Removes M values from the exported shape.</p>


```csharp
WktExportStripMs = 128
```
### WktExportStripZs

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.WktExportFlags.yml" sourcestartlinenumber="1">Removes Z values from the exported shape.</p>


```csharp
WktExportStripZs = 64
```


