# SurfaceZsResultStatus

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.SurfaceZsResultStatus.yml" sourcestartlinenumber="1">Defines the status types resulting from calling Map.GetZsFromSurfaceAsync().  See <xref href="ArcGIS.Desktop.Mapping.SurfaceZsResult" data-throw-if-not-resolved="false"></xref></p>


## Object Signature

```csharp
public enum SurfaceZsResultStatus
```


## Members

### CalculationError

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.SurfaceZsResultStatus.yml" sourcestartlinenumber="1">Error: something went wrong when calculating, probably a SpatialReference issue.</p>


```csharp
CalculationError = 4
```
### Canceled

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.SurfaceZsResultStatus.yml" sourcestartlinenumber="1">Information: the calculation was canceled, Zs are not available</p>


```csharp
Canceled = 2
```
### InvalidState

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.SurfaceZsResultStatus.yml" sourcestartlinenumber="1">Error: something went wrong internally.</p>


```csharp
InvalidState = 5
```
### NoVisibleSource

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.SurfaceZsResultStatus.yml" sourcestartlinenumber="1">The specified <xref href="ArcGIS.Desktop.Mapping.ElevationSurfaceLayer" data-throw-if-not-resolved="false"></xref> has no visible elevation sources, all Zs were set to a constant value, Zs are available.</p>


```csharp
NoVisibleSource = 1
```
### Ok

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.SurfaceZsResultStatus.yml" sourcestartlinenumber="1">Calculation went fine, Zs are available.</p>


```csharp
Ok = 0
```
### OutsideDomain

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.SurfaceZsResultStatus.yml" sourcestartlinenumber="1">Information: input is entirely outside the surface domain, Zs are not available.</p>


```csharp
OutsideDomain = 3
```


