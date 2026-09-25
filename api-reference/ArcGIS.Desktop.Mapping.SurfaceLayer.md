# SurfaceLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.SurfaceLayer.yml" sourcestartlinenumber="1">Represents a surface layer displaying 3D analysis data in a map or scene.</p>


## Object Signature

```csharp
public class SurfaceLayer : Layer, IMetadataInfo, IMetadataSource
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.SurfaceLayer.yml" sourcestartlinenumber="1">See <xref href="ArcGIS.Desktop.Mapping.TinLayer" data-throw-if-not-resolved="false"></xref>, <xref href="ArcGIS.Desktop.Mapping.LasDatasetLayer" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Desktop.Mapping.TerrainLayer" data-throw-if-not-resolved="false"></xref> for layers that derive
from this base class.</p>


## Members

### CanCreateRenderer(TinRendererDefinition)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SurfaceLayer.yml" sourcestartlinenumber="1">Determines whether a renderer can be created and is valid for the surface layer using the specified <xref href="ArcGIS.Desktop.Mapping.TinRendererDefinition" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool CanCreateRenderer(TinRendererDefinition rendererDefinition)
```
### CanGetLineOfSight(LineOfSightParams)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SurfaceLayer.yml" sourcestartlinenumber="1">Determines whether a Line of Sight analysis can be calculated for the given set of parameters.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool CanGetLineOfSight(LineOfSightParams lineOfSightParams)
```
### CanSetRenderer(CIMTinRenderer, SurfaceRendererTarget)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SurfaceLayer.yml" sourcestartlinenumber="1">Determines whether a renderer is valid and can be applied for the surface layer and target,
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool CanSetRenderer(CIMTinRenderer renderer, SurfaceRendererTarget surfaceRendererTarget)
```
### CreateRenderer(TinRendererDefinition)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SurfaceLayer.yml" sourcestartlinenumber="1">Creates a renderer for a surface layer using a <xref href="ArcGIS.Desktop.Mapping.TinRendererDefinition" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMTinRenderer CreateRenderer(TinRendererDefinition rendererDefinition)
```
### GetLineOfSight(LineOfSightParams)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SurfaceLayer.yml" sourcestartlinenumber="1">Performs a line of sight analysis for an observer and target point on the surface.  Determines if the target point is visible from a given observer point.
This method requires a 3D Analyst license.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public virtual LineOfSightResult GetLineOfSight(LineOfSightParams lineOfSightParams)
```
### GetRenderers()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SurfaceLayer.yml" sourcestartlinenumber="1">Gets the set of renderers used to draw the surface layer. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<CIMTinRenderer> GetRenderers()
```
### GetRenderersAsDictionary()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SurfaceLayer.yml" sourcestartlinenumber="1">Gets the set of renderers used to draw the surface layer. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Dictionary<SurfaceRendererTarget, CIMTinRenderer> GetRenderersAsDictionary()
```
### GetRenderersAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SurfaceLayer.yml" sourcestartlinenumber="1">Gets the set of renderers used to draw the surface layer.</p>


```csharp
public Task<IReadOnlyList<CIMTinRenderer>> GetRenderersAsync()
```
### RemoveRenderer(SurfaceRendererTarget)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SurfaceLayer.yml" sourcestartlinenumber="1">Removes a surface layer's renderer that applies to the specified target.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveRenderer(SurfaceRendererTarget surfaceRendererTarget)
```
### SetRenderer(CIMTinRenderer, SurfaceRendererTarget)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SurfaceLayer.yml" sourcestartlinenumber="1">Specifies the surface layer's renderer which determines how the layer draws.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetRenderer(CIMTinRenderer renderer, SurfaceRendererTarget surfaceRendererTarget)
```


