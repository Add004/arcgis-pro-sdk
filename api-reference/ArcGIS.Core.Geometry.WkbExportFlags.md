# WkbExportFlags

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.WkbExportFlags.yml" sourcestartlinenumber="1">Specifies the flags that control the behavior of the <xref href="ArcGIS.Core.Geometry.GeometryEngine.ExportToWKB(ArcGIS.Core.Geometry.WkbExportFlags%2cArcGIS.Core.Geometry.Geometry)" data-throw-if-not-resolved="false"></xref> and
<xref href="ArcGIS.Core.Geometry.GeometryEngine.ExportToWKB(ArcGIS.Core.Geometry.WkbExportFlags%2cArcGIS.Core.Geometry.Geometry%2cSystem.Byte%5b%5d%40)" data-throw-if-not-resolved="false"></xref> methods.</p>


## Object Signature

```csharp
public enum WkbExportFlags
```


## Members

### WkbExportDefaults

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.WkbExportFlags.yml" sourcestartlinenumber="1">Exports the geometry as is based on its type.
Attributes such as Z and M values are exported.</p>


```csharp
WkbExportDefaults = 0
```
### WkbExportFailIfNotSimple

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.WkbExportFlags.yml" sourcestartlinenumber="1">Throws an exception if the geometry is not topologically simple.
Applies only to Polygon and Polyline geometry types.</p>


```csharp
WkbExportFailIfNotSimple = 4096
```
### WkbExportLineString

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.WkbExportFlags.yml" sourcestartlinenumber="1">Exports a MultiLineString with one LineString as a LineString.</p>


```csharp
WkbExportLineString = 4
```
### WkbExportMultiLineString

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.WkbExportFlags.yml" sourcestartlinenumber="1">Exports a LineString as a MultiLineString.</p>


```csharp
WkbExportMultiLineString = 8
```
### WkbExportMultiPolygon

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.WkbExportFlags.yml" sourcestartlinenumber="1">Exports a Polygon as a MultiPolygon.</p>


```csharp
WkbExportMultiPolygon = 32
```
### WkbExportMultipoint

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.WkbExportFlags.yml" sourcestartlinenumber="1">Exports a Point as a Multipoint.</p>


```csharp
WkbExportMultipoint = 2
```
### WkbExportPoint

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.WkbExportFlags.yml" sourcestartlinenumber="1">Exports a Multipoint with one Point as a Point.</p>


```csharp
WkbExportPoint = 1
```
### WkbExportPolygon

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.WkbExportFlags.yml" sourcestartlinenumber="1">Exports a MultiPolygon with one Polygon as a Polygon.</p>


```csharp
WkbExportPolygon = 16
```
### WkbExportStripMs

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.WkbExportFlags.yml" sourcestartlinenumber="1">Removes M values from the exported shape.</p>


```csharp
WkbExportStripMs = 128
```
### WkbExportStripZs

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.WkbExportFlags.yml" sourcestartlinenumber="1">Removes Z values from the exported shape.</p>


```csharp
WkbExportStripZs = 64
```


