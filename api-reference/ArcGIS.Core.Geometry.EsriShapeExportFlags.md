# EsriShapeExportFlags

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.EsriShapeExportFlags.yml" sourcestartlinenumber="1">Specifies the flags that control the behavior of the
<xref href="ArcGIS.Core.Geometry.GeometryEngine.ExportToEsriShape(ArcGIS.Core.Geometry.EsriShapeExportFlags%2cArcGIS.Core.Geometry.Geometry)" data-throw-if-not-resolved="false"></xref> and
<xref href="ArcGIS.Core.Geometry.GeometryEngine.ExportToEsriShape(ArcGIS.Core.Geometry.EsriShapeExportFlags%2cArcGIS.Core.Geometry.Geometry%2cSystem.Byte%5b%5d%40)" data-throw-if-not-resolved="false"></xref> methods.</p>


## Object Signature

```csharp
public enum EsriShapeExportFlags
```


## Members

### EsriShapeExportAngularDensify

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.EsriShapeExportFlags.yml" sourcestartlinenumber="1">Exports densified versions of non-linear segments.
Generates new vertices at constant angles along those segments.</p>


```csharp
EsriShapeExportAngularDensify = 2
```
### EsriShapeExportDefaults

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.EsriShapeExportFlags.yml" sourcestartlinenumber="1">Exports curves, Z-values, and M-values.
Performs byte swapping if the current platform architecture is big-endian.</p>


```csharp
EsriShapeExportDefaults = 0
```
### EsriShapeExportDistanceDensify

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.EsriShapeExportFlags.yml" sourcestartlinenumber="1">Exports densified versions of non-linear segments.
Generates new vertices using a Douglas-Peucker style algorithm.</p>


```csharp
EsriShapeExportDistanceDensify = 4
```
### EsriShapeExportNoCompress

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.EsriShapeExportFlags.yml" sourcestartlinenumber="1">Does not compress the output shapefile buffer.</p>


```csharp
EsriShapeExportNoCompress = 2048
```
### EsriShapeExportNoSwap

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.EsriShapeExportFlags.yml" sourcestartlinenumber="1">Does not perform byte swapping on the output shapefile buffer.</p>


```csharp
EsriShapeExportNoSwap = 1
```
### EsriShapeExportStripMaterials

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.EsriShapeExportFlags.yml" sourcestartlinenumber="1">Removes materials attributes from exported multipatch.</p>


```csharp
EsriShapeExportStripMaterials = 512
```
### EsriShapeExportStripMs

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.EsriShapeExportFlags.yml" sourcestartlinenumber="1">Removes M values from exported shape.</p>


```csharp
EsriShapeExportStripMs = 32
```
### EsriShapeExportStripNormals

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.EsriShapeExportFlags.yml" sourcestartlinenumber="1">Removes normals from exported multipatch.</p>


```csharp
EsriShapeExportStripNormals = 256
```
### EsriShapeExportStripTextures

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.EsriShapeExportFlags.yml" sourcestartlinenumber="1">Removes textures from exported multipatch.</p>


```csharp
EsriShapeExportStripTextures = 128
```
### EsriShapeExportStripZs

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.EsriShapeExportFlags.yml" sourcestartlinenumber="1">Removes Z values from exported shape.</p>


```csharp
EsriShapeExportStripZs = 16
```
### EsriShapeExportTrueNaNs

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.EsriShapeExportFlags.yml" sourcestartlinenumber="1">Exports undefined double precision values as true NaNs (IEEE Non-A-Number).
The default is to use large, negative values.</p>


```csharp
EsriShapeExportTrueNaNs = 8
```


