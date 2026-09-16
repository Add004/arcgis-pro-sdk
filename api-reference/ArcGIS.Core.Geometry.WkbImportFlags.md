# WkbImportFlags

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.WkbImportFlags.yml" sourcestartlinenumber="1">Specifies the flags that control the behavior of the <xref href="ArcGIS.Core.Geometry.GeometryEngine.ImportFromWKB(ArcGIS.Core.Geometry.WkbImportFlags%2cSystem.Byte%5b%5d%2cArcGIS.Core.Geometry.SpatialReference)" data-throw-if-not-resolved="false"></xref> method.</p>


## Object Signature

```csharp
public enum WkbImportFlags
```


## Members

### WkbImportDefaults

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.WkbImportFlags.yml" sourcestartlinenumber="1">Assumes the geometry comes from a trusted source and is topologically simple.</p>


```csharp
WkbImportDefaults = 0
```
### WkbImportNonTrusted

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.WkbImportFlags.yml" sourcestartlinenumber="1">Does not assume that the input shapefile buffer represents a topologically simple geometry.</p>


```csharp
WkbImportNonTrusted = 2
```


