# Layer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Represents the base class for all geographic data that can be added to and visualized on a map.</p>


## Object Signature

```csharp
public abstract class Layer : MapMember, IMetadataInfo, IMetadataSource
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">To create a Layer, you must call one of the create methods of the <xref href="ArcGIS.Desktop.Mapping.LayerFactory?text=LayerFactory" data-throw-if-not-resolved="false"></xref> class, instead of directly using a constructor.</p>


## Members

### AllowDrapingOnIntegratedMesh

- Kind: property


```csharp
public bool AllowDrapingOnIntegratedMesh { get; }
```
### BlendingMode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Gets the blending mode of a layer.</p>


```csharp
public BlendingMode BlendingMode { get; }
```
### CanGetZs()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Determines whether the layer can be used as an elevation source to retrieve Z values for geometries.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool CanGetZs()
```
### CanGetZsAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Determines whether the layer can be used as an elevation source to retrieve Z values for geometries.</p>


```csharp
public Task<bool> CanGetZsAsync()
```
### CanReplaceDataSource(Dataset)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Check if the layer's data source can be replace with this dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool CanReplaceDataSource(Dataset dataset)
```
### CanSetBlendingMode(BlendingMode)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Check if blending mode can be set on this layer.</p>


```csharp
public bool CanSetBlendingMode(BlendingMode mode)
```
### CanSetElevationTypeDefinition(ElevationTypeDefinition)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Gets whether the elevation type definition can be set on the layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool CanSetElevationTypeDefinition(ElevationTypeDefinition elevationTypeDefinition)
```
### ClearDisplayCache()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Refreshes the layer drawing and clears the feature cache (for layer types supporting it).
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void ClearDisplayCache()
```
### DepthPriority

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Gets the depth priority of a layer.</p>


```csharp
public int DepthPriority { get; }
```
### DisplayCacheType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Gets the layer's display cache type.</p>


```csharp
public DisplayCacheType DisplayCacheType { get; }
```
### ElevationType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Returns the elevation type of the layer.</p>


```csharp
public LayerElevationType ElevationType { get; }
```
### FindAndReplaceWorkspacePath(string, string, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Performs a find and replace of workspace path for the layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void FindAndReplaceWorkspacePath(string findWorkspacePath, string replaceWorkspacePath, bool validate = true)
```
### GetCanEditMetadata()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Gets whether the Layer metadata can be edited or not. This method must be called on the MCT.
Use QueuedTask.Run.</p>


```csharp
public override bool GetCanEditMetadata()
```
### GetDefinition()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Returns the layer's CIM definition.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public virtual CIMBaseLayer GetDefinition()
```
### GetEffectiveMaxScale()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Returns computed effective maximum scale considering all its parent group layers.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double GetEffectiveMaxScale()
```
### GetEffectiveMinScale()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Returns computed effective minimum scale considering all its parent group layers.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double GetEffectiveMinScale()
```
### GetElevationTypeDefinition()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Gets the elevation type definition for the layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public ElevationTypeDefinition GetElevationTypeDefinition()
```
### GetMetadata()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Gets the Layer metadata. This method must be called on the MCT.
Use QueuedTask.Run.</p>


```csharp
public override string GetMetadata()
```
### GetSpatialReference()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Returns the layer spatial reference.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SpatialReference GetSpatialReference()
```
### GetZs(Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Obtains a geometry that is similar to the given input geometry, where some or all Z values are populated from the layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SurfaceZsResult GetZs(Geometry geometry)
```
### GetZs(Geometry, SurfaceZsMissingHandler)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Obtains a geometry that is similar to the given input geometry, where some or all Z values are populated from the layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SurfaceZsResult GetZs(Geometry geometry, SurfaceZsMissingHandler missingHandler)
```
### GetZs(double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Obtains a point geometry with Z for the specified x,y; where the Z value is populated from the layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SurfaceZsResult GetZs(double x, double y)
```
### GetZs(double, double, SurfaceZsMissingHandler)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Obtains a point geometry with Z for the specified x,y; where the Z value is populated from the layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SurfaceZsResult GetZs(double x, double y, SurfaceZsMissingHandler missingHandler)
```
### GetZsAsync(Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Obtains a geometry that is similar to the given input geometry, where some or all Z values are populated from the layer.</p>


```csharp
public Task<SurfaceZsResult> GetZsAsync(Geometry geometry)
```
### GetZsAsync(Geometry, SurfaceZsMissingHandler)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Obtains a geometry that is similar to the given input geometry, where some or all Z values are populated from the layer.</p>


```csharp
public Task<SurfaceZsResult> GetZsAsync(Geometry geometry, SurfaceZsMissingHandler missingHandler)
```
### GetZsAsync(Geometry, SurfaceZsMissingHandler, CancellationToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Obtains a geometry that is similar to the given input geometry, where some or all Z values are populated from the layer.</p>


```csharp
public Task<SurfaceZsResult> GetZsAsync(Geometry geometry, SurfaceZsMissingHandler missingHandler, CancellationToken cancellationToken)
```
### GetZsAsync(double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Obtains a point geometry with Z for the specified (x,y); where the Z value is populated from the layer.</p>


```csharp
public Task<SurfaceZsResult> GetZsAsync(double x, double y)
```
### GetZsAsync(double, double, SurfaceZsMissingHandler)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Obtains a point geometry with Z for the specified (x,y); where the Z value is populated from the layer.</p>


```csharp
public Task<SurfaceZsResult> GetZsAsync(double x, double y, SurfaceZsMissingHandler missingHandler)
```
### GetZsAsync(double, double, SurfaceZsMissingHandler, CancellationToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Obtains a point geometry with Z for the specified (x,y); where the Z value is populated from the layer.</p>


```csharp
public Task<SurfaceZsResult> GetZsAsync(double x, double y, SurfaceZsMissingHandler missingHandler, CancellationToken cancellationToken)
```
### HasJoins

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Gets whether the layer has any joins</p>


```csharp
public bool HasJoins { get; }
```
### HasRelates

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Gets whether the layer has any relates</p>


```csharp
public bool HasRelates { get; }
```
### IsExpanded

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Gets whether the layer is expanded or collapsed on the TOC.</p>


```csharp
public bool IsExpanded { get; protected set; }
```
### IsExpandedAllTheWayUp(Layer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Gets the expanded state of the layer and it's parents.</p>


```csharp
protected static bool IsExpandedAllTheWayUp(Layer layer)
```
### IsVisible

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Gets the layer's visibility state.</p>


```csharp
public bool IsVisible { get; }
```
### IsVisibleInView(MapView)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Determines whether the layer is visible in the given map view</p>


```csharp
public bool IsVisibleInView(MapView mapView)
```
### LegendGroups

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Gets a read only collection of legend groups. Check the LegendStatus property before accessing this collection.</p>


```csharp
public ReadOnlyObservableCollection<LegendGroup> LegendGroups { get; }
```
### LegendStatus

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Gets the status of the layer's legend.</p>


```csharp
public virtual LegendStatus LegendStatus { get; protected set; }
```
### LoadLegend()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Loads the layer's legend.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void LoadLegend()
```
### MapLayerType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Gets map layer type.</p>


```csharp
public MapLayerType MapLayerType { get; }
```
### MaxDisplayCacheAge

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Gets the duration of display cache for the layer.</p>


```csharp
public TimeSpan MaxDisplayCacheAge { get; }
```
### MaxDistance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Gets the maximum distance (in meter) at which the layer is visible in a 3D scene or globe view.</p>


```csharp
public double MaxDistance { get; }
```
### MaxScale

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Gets the layer's maximum scale (representative fraction) at which the layer is visible in a 2D map view.</p>


```csharp
public double MaxScale { get; }
```
### MinDistance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Gets the minimum distance (in meter) at which the layer is visible in a 3D  scene or globe view.</p>


```csharp
public double MinDistance { get; }
```
### MinScale

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Gets the layer's minimum scale (representative fraction) at which the layer is visible in a 2D map view.</p>


```csharp
public double MinScale { get; }
```
### Parent

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Gets the parent of the layer. It is either the group layer it belongs to, or the map for layers that do not belong in any group layers.</p>


```csharp
public ILayerContainer Parent { get; }
```
### QueryExtent(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Returns the extent of the layer, optionally taking symbol size into account.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Envelope QueryExtent(bool includeSymbolSize = false)
```
### RasterizeOnExport

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Gets and sets the rasterize on export flag.</p>


```csharp
public bool RasterizeOnExport { get; set; }
```
### ReplaceDataSource(Dataset)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Replace the layer's data source.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void ReplaceDataSource(Dataset dataset)
```
### SavedMaxScale

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Gets and sets the maximum scale saved when ShowLayerAtAllScales is set to true.</p>


```csharp
public double SavedMaxScale { get; }
```
### SavedMinScale

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Gets and sets the minimum scale saved when ShowLayerAtAllScales is set to true.</p>


```csharp
public double SavedMinScale { get; }
```
### SceneLayerType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Gets the scene layer type.</p>


```csharp
public SceneLayerType SceneLayerType { get; }
```
### SetBlendingMode(BlendingMode)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Sets the layer's blending mode.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetBlendingMode(BlendingMode mode)
```
### SetCacheOptions(LayerCacheType)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Sets the layer's caching options. If the layer's feature class supports feature caching, then both the display cache and feature cache are set
otherwise just the display cache is set.  This method must be called on the MCT. Use QueuedTask.Run</p>


```csharp
public void SetCacheOptions(LayerCacheType cacheType)
```
### SetDefinition(CIMBaseLayer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Updates the layer's CIM definition.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDefinition(CIMBaseLayer baseLayer)
```
### SetDisplayCacheMaxAge(TimeSpan)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Sets the duration after which the layer's display cache will be refreshed in the local storage.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDisplayCacheMaxAge(TimeSpan displayCacheAge)
```
### SetElevationTypeDefinition(ElevationTypeDefinition)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Sets the elevation type definition for the layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetElevationTypeDefinition(ElevationTypeDefinition elevationTypeDefinition)
```
### SetExpanded(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Sets whether the layer appears expanded i.e. showing legends on the TOC.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetExpanded(bool isExpanded)
```
### SetMaxDistance(double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Sets the maximum distance (in meter) at which the layer is visible in a 3D scene or globe view.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetMaxDistance(double maxDistance)
```
### SetMaxScale(double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Sets the layer's maximum scale (representative fraction) at which the layer is visible in a 2D map view.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetMaxScale(double maxScale)
```
### SetMetadata(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Sets the Layer metadata. This method must be called on the MCT.
Use QueuedTask.Run.</p>


```csharp
public override void SetMetadata(string metadataXml)
```
### SetMinDistance(double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Sets the minimum distance (in meter) at which the layer is visible in a 3D scene or globe view.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetMinDistance(double minDistance)
```
### SetMinScale(double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Sets the layer's minimum scale (representative fraction) at which the layer is visible in a 2D map view.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetMinScale(double minScale)
```
### SetShowLayerAtAllScales(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Sets whether the layer is visible at all scales.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetShowLayerAtAllScales(bool isShowLayerAtAllScales)
```
### SetTransparency(double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Sets the transparency of the layer. 100 being fully transparent and 0 means opaque.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetTransparency(double transparency)
```
### SetUseSourceMetadata(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Sets whether or not the Layer will use its own metadata or the metadata
from its underlying source (if it has one). This method must be called on the MCT.
Use QueuedTask.Run.</p>


```csharp
public override void SetUseSourceMetadata(bool useSource)
```
### SetVisibility(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Sets the layer visibility.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetVisibility(bool isVisible)
```
### ShowLayerAtAllScales

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Gets and sets whether the layer is visible at all scales.</p>


```csharp
public bool ShowLayerAtAllScales { get; }
```
### Transparency

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Layer.yml" sourcestartlinenumber="1">Gets the transparency value set to the layer. 100 being fully transparent and 0 means opaque.</p>


```csharp
public double Transparency { get; }
```


