# EsriShapeImportFlags

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.EsriShapeImportFlags.yml" sourcestartlinenumber="1">Specifies the flags that control the behavior of the <xref href="ArcGIS.Core.Geometry.GeometryEngine.ImportFromEsriShape(ArcGIS.Core.Geometry.EsriShapeImportFlags%2cSystem.Byte%5b%5d%2cArcGIS.Core.Geometry.SpatialReference)" data-throw-if-not-resolved="false"></xref> method.</p>


## Object Signature

```csharp
public enum EsriShapeImportFlags
```


## Members

### EsriShapeImportDefaults

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.EsriShapeImportFlags.yml" sourcestartlinenumber="1">Assumes the geometry comes from a trusted source and is topologically simple.
Performs byte swapping if the current platform is big-endian.</p>


```csharp
EsriShapeImportDefaults = 0
```
### EsriShapeImportNoSwap

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.EsriShapeImportFlags.yml" sourcestartlinenumber="1">Assumes shapefile standard byte ordering, regardless of current platform architecture.
The default is to perform byte swapping if the current platform architecture is big-endian.</p>


```csharp
EsriShapeImportNoSwap = 1
```
### EsriShapeNonTrusted

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.EsriShapeImportFlags.yml" sourcestartlinenumber="1">Does not assume that the input shapefile buffer represents a topologically correct geometry.</p>


```csharp
EsriShapeNonTrusted = 2
```


