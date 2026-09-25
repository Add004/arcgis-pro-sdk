# SurfaceZsResult

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.SurfaceZsResult.yml" sourcestartlinenumber="1">Defines the result of calling Map.GetZsFromSurfaceAsync()</p>


## Object Signature

```csharp
public sealed class SurfaceZsResult
```


## Members

### Geometry

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SurfaceZsResult.yml" sourcestartlinenumber="1">Gets the output geometry, provided the <xref href="ArcGIS.Desktop.Mapping.SurfaceZsResult.Status" data-throw-if-not-resolved="false"></xref> is <xref href="ArcGIS.Desktop.Mapping.SurfaceZsResultStatus.Ok" data-throw-if-not-resolved="false"></xref>. Null otherwise.</p>


```csharp
public Geometry Geometry { get; }
```
### Status

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SurfaceZsResult.yml" sourcestartlinenumber="1">Gets the result status.</p>


```csharp
public SurfaceZsResultStatus Status { get; }
```


