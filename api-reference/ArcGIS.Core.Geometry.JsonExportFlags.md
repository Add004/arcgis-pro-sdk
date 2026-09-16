# JsonExportFlags

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.JsonExportFlags.yml" sourcestartlinenumber="1">Specifies the flags that control the behavior of the <xref href="ArcGIS.Core.Geometry.GeometryEngine.ExportToJson(ArcGIS.Core.Geometry.JsonExportFlags%2cArcGIS.Core.Geometry.Geometry)" data-throw-if-not-resolved="false"></xref> method.</p>


## Object Signature

```csharp
public enum JsonExportFlags
```


## Members

### JsonExportDefaults

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.JsonExportFlags.yml" sourcestartlinenumber="1">Exports the geometry as is based on its type.
Attributes such as Z and M values are exported.</p>


```csharp
JsonExportDefaults = 0
```
### JsonExportSkipCRS

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.JsonExportFlags.yml" sourcestartlinenumber="1">Exports the geometry without the spatial reference.</p>


```csharp
JsonExportSkipCRS = 1
```


