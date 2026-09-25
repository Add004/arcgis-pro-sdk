# ElevationSurfaceLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationSurfaceLayer.yml" sourcestartlinenumber="1">Represents an elevation surface layer in the map or scene.</p>


## Object Signature

```csharp
public sealed class ElevationSurfaceLayer : CompositeLayer, IMetadataInfo, IMetadataSource, ILayerContainerEdit, ILayerContainer
```


## Members

### CanRemoveLayer(Layer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationSurfaceLayer.yml" sourcestartlinenumber="1">Determines if a layer can be removed from the container.</p>


```csharp
public bool CanRemoveLayer(Layer layer)
```
### CanRemoveLayers(IEnumerable&lt;Layer&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationSurfaceLayer.yml" sourcestartlinenumber="1">Determines if the layers can be removed from the container.</p>


```csharp
public bool CanRemoveLayers(IEnumerable<Layer> layers)
```
### ElevationMode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationSurfaceLayer.yml" sourcestartlinenumber="1">Get the elevation mode of the surface.</p>


```csharp
public ElevationMode ElevationMode { get; }
```
### EnableSurfaceShading

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationSurfaceLayer.yml" sourcestartlinenumber="1">Gets whether this elevation surface has shadows.</p>


```csharp
public bool EnableSurfaceShading { get; }
```
### GetCIMColor()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationSurfaceLayer.yml" sourcestartlinenumber="1">Gets the color to be used for the surface.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMColor GetCIMColor()
```
### GetEnableNavigationBelowGound()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationSurfaceLayer.yml" sourcestartlinenumber="1">Gets whether navigation below ground is enabled.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool GetEnableNavigationBelowGound()
```
### MoveLayer(Layer, ElevationSurfaceLayer, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationSurfaceLayer.yml" sourcestartlinenumber="1">Move a layer to another position within the specified container.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void MoveLayer(Layer layer, ElevationSurfaceLayer targetLayer, int position)
```
### MoveLayer(Layer, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationSurfaceLayer.yml" sourcestartlinenumber="1">Moves a layer to another position within the container.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void MoveLayer(Layer layer, int position)
```
### RemoveLayer(Layer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationSurfaceLayer.yml" sourcestartlinenumber="1">Removes a layer from the container.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveLayer(Layer layer)
```
### RemoveLayers(IEnumerable&lt;Layer&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationSurfaceLayer.yml" sourcestartlinenumber="1">Remove multiple layers from the container.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveLayers(IEnumerable<Layer> layers)
```
### SetCIMColor(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationSurfaceLayer.yml" sourcestartlinenumber="1">Sets the color to be used for the surface.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetCIMColor(CIMColor color)
```
### SetEnableNavigationBelowGound(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationSurfaceLayer.yml" sourcestartlinenumber="1">Sets whether navigation below ground is enabled. Can only be set for ground surface.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetEnableNavigationBelowGound(bool navigateBelowGround)
```
### SetEnableSurfaceShading(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationSurfaceLayer.yml" sourcestartlinenumber="1">Sets whether this elevation surface has shadows.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetEnableSurfaceShading(bool isEnabled)
```
### SetName(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationSurfaceLayer.yml" sourcestartlinenumber="1">Sets the display name for the Elevation Surface Layer. The Ground elevation surface layer cannot be renamed;
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public override void SetName(string newName)
```
### SetSurfaceTINShadingMode(SurfaceTINShadingMode)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationSurfaceLayer.yml" sourcestartlinenumber="1">Sets the elevation surface shading mode for TIN elevation sources.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetSurfaceTINShadingMode(SurfaceTINShadingMode surfaceTINShadingMode)
```
### SetVerticalExaggeration(double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationSurfaceLayer.yml" sourcestartlinenumber="1">Sets a factor by which to scale the surface relief.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetVerticalExaggeration(double verticalExaggeration)
```
### SurfaceTINShadingMode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationSurfaceLayer.yml" sourcestartlinenumber="1">Gets the elevation surface shading mode for TIN elevation sources.</p>


```csharp
public SurfaceTINShadingMode SurfaceTINShadingMode { get; }
```
### VerticalExaggeration

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ElevationSurfaceLayer.yml" sourcestartlinenumber="1">Gets the factor by which to scale the surface relief.</p>


```csharp
public double VerticalExaggeration { get; }
```


