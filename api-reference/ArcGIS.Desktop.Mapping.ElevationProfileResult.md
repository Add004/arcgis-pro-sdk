# ElevationProfileResult

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationProfileResult.yml" sourcestartlinenumber="1">Defines the result of calling Map.GetElevationProfileFromSurface().</p>


## Object Signature

```csharp
public class ElevationProfileResult
```


## Members

### Polyline

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationProfileResult.yml" sourcestartlinenumber="1">Gets the elevation profile polyline, provided the <xref href="ArcGIS.Desktop.Mapping.ElevationProfileResult.Status" data-throw-if-not-resolved="false"></xref> is <xref href="ArcGIS.Desktop.Mapping.SurfaceZsResultStatus.Ok" data-throw-if-not-resolved="false"></xref>.
The polyline is null if no elevation profile cane be determined.</p>


```csharp
public Polyline Polyline { get; }
```
### Status

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationProfileResult.yml" sourcestartlinenumber="1">Gets the result status.</p>


```csharp
public SurfaceZsResultStatus Status { get; }
```


