# WktImportFlags

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.WktImportFlags.yml" sourcestartlinenumber="1">Specifies the flags that control the behavior of the <xref href="ArcGIS.Core.Geometry.GeometryEngine.ImportFromWKT(ArcGIS.Core.Geometry.WktImportFlags%2cSystem.String%2cArcGIS.Core.Geometry.SpatialReference)" data-throw-if-not-resolved="false"></xref> method.</p>


## Object Signature

```csharp
public enum WktImportFlags
```


## Members

### WktImportDefaults

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.WktImportFlags.yml" sourcestartlinenumber="1">Assumes the geometry comes from a trusted source and is topologically simple.</p>


```csharp
WktImportDefaults = 0
```
### WktImportNonTrusted

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.WktImportFlags.yml" sourcestartlinenumber="1">Does not assume that the input string represents a topologically simple geometry.</p>


```csharp
WktImportNonTrusted = 2
```


