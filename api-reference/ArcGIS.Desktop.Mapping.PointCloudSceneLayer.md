# PointCloudSceneLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.PointCloudSceneLayer.yml" sourcestartlinenumber="1">Point cloud scene layers allow for fast display and consumption of large volumes of
point cloud data.</p>


## Object Signature

```csharp
public sealed class PointCloudSceneLayer : Layer, IMetadataInfo, IMetadataSource
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.PointCloudSceneLayer.yml" sourcestartlinenumber="1">The primary source of point cloud data is usually LAS and lidar data.
Lidar surveys for terrain, buildings, forest canopy, roads, bridges, overpasses,
and more can make up the point cloud data used for a point cloud scene layer.</p>


## Members

### ClearFilters()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.PointCloudSceneLayer.yml" sourcestartlinenumber="1">Clears all filters. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void ClearFilters()
```
### CreateRenderer(PointCloudRendererDefinition)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.PointCloudSceneLayer.yml" sourcestartlinenumber="1">Creates a CIMPointCloudRenderer from a PointCloudRendererDefinition for use with
<xref href="ArcGIS.Desktop.Mapping.PointCloudSceneLayer.SetRenderer(ArcGIS.Core.CIM.CIMPointCloudRenderer)" data-throw-if-not-resolved="false"></xref> .
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMPointCloudRenderer CreateRenderer(PointCloudRendererDefinition rendererDefinition)
```
### EyeDomeLightingRadius

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PointCloudSceneLayer.yml" sourcestartlinenumber="1">Gets the Eye Dome Lighting (EDL) radius value.  The EDL radius controls the width of effects.</p>


```csharp
public double EyeDomeLightingRadius { get; }
```
### EyeDomeLightingStrength

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PointCloudSceneLayer.yml" sourcestartlinenumber="1">Gets the Eye Dome Lighting (EDL) strength value. The EDL strength adjusts the intensity of the resulting effects.</p>


```csharp
public double EyeDomeLightingStrength { get; }
```
### GetAvailableClassCodesAndLabels()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.PointCloudSceneLayer.yml" sourcestartlinenumber="1">Gets the available classification codes and their corresponding labels.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Dictionary<int, string> GetAvailableClassCodesAndLabels()
```
### GetAvailableClassFlagsAndLabels()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.PointCloudSceneLayer.yml" sourcestartlinenumber="1">Get the available classification flags and labels.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Dictionary<int, string> GetAvailableClassFlagsAndLabels()
```
### GetAvailablePointCloudRendererFields(PointCloudRendererType)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.PointCloudSceneLayer.yml" sourcestartlinenumber="1">Gets the available fields for the specified renderer type.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<string> GetAvailablePointCloudRendererFields(PointCloudRendererType rendererType)
```
### GetDataSourceType()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.PointCloudSceneLayer.yml" sourcestartlinenumber="1">Gets the data source type.</p>


```csharp
public SceneLayerDataSourceType GetDataSourceType()
```
### GetFilters()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.PointCloudSceneLayer.yml" sourcestartlinenumber="1">Gets a list of the currently applied filters.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<CIMPointCloudFilter> GetFilters()
```
### GetRenderer()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.PointCloudSceneLayer.yml" sourcestartlinenumber="1">Returns the renderer used to draw the point cloud scene layer
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMPointCloudRenderer GetRenderer()
```
### IsEyeDomeLightingEnabled

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PointCloudSceneLayer.yml" sourcestartlinenumber="1">Gets whether Eye Dome Lighting (EDL) is enabled on the layer.</p>


```csharp
public bool IsEyeDomeLightingEnabled { get; }
```
### IsSnappable

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PointCloudSceneLayer.yml" sourcestartlinenumber="1">Gets whether feature snapping is enabled</p>


```csharp
public bool IsSnappable { get; }
```
### RendererType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PointCloudSceneLayer.yml" sourcestartlinenumber="1">Gets the current RendererType</p>


```csharp
public PointCloudRendererType RendererType { get; }
```
### SetEyeDomeLightingEnabled(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.PointCloudSceneLayer.yml" sourcestartlinenumber="1">Enables/disables eye dome lighting. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetEyeDomeLightingEnabled(bool enabled)
```
### SetEyeDomeLightingRadius(double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.PointCloudSceneLayer.yml" sourcestartlinenumber="1">Sets the Eye Dome Lighting (EDL) radius value. The EDL radius controls the width of effects.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetEyeDomeLightingRadius(double value)
```
### SetEyeDomeLightingStrength(double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.PointCloudSceneLayer.yml" sourcestartlinenumber="1">Sets the Eye Dome Lighting (EDL) strength value. The EDL strength adjusts the intensity of the resulting effects.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetEyeDomeLightingStrength(double value)
```
### SetFilters(IEnumerable&lt;CIMPointCloudFilter&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.PointCloudSceneLayer.yml" sourcestartlinenumber="1">Sets a collection of filters.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetFilters(IEnumerable<CIMPointCloudFilter> filters)
```
### SetRenderer(CIMPointCloudRenderer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.PointCloudSceneLayer.yml" sourcestartlinenumber="1">Specifies the point cloud scene layer's renderer object which determines how the layer draws.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetRenderer(CIMPointCloudRenderer renderer)
```
### SetSnappable(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.PointCloudSceneLayer.yml" sourcestartlinenumber="1">Enables or disables snapping on the point cloud layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetSnappable(bool isSnappable)
```


