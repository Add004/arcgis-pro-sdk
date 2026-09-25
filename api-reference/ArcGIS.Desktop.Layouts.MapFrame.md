# MapFrame

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Layouts.html">Layouts</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapFrame.yml" sourcestartlinenumber="1">Represents a map frame on a page layout.</p>


## Object Signature

```csharp
public sealed class MapFrame : Element, IEquatable<Element>, IComparable, IElement, IElementInternal, IDisposable
```

## Remarks

<p>
    The MapFrame class primarily manages the placement of maps and scenes on a page layout. You can use <xref href="ArcGIS.Desktop.Layouts.MapFrame.Map?text=Map" data-throw-if-not-resolved="false"></xref> 
    and <xref href="ArcGIS.Desktop.Layouts.MapFrame.SetMap(ArcGIS.Desktop.Mapping.Map)?text=SetMap" data-throw-if-not-resolved="false"></xref> members to get and set the <xref href="ArcGIS.Desktop.Mapping.Map?text=Map" data-throw-if-not-resolved="false"></xref> associated with a MapFrame.  
    </p>
<p>
    The <xref href="ArcGIS.Desktop.Layouts.MapFrame.Export(ArcGIS.Desktop.Mapping.ExportFormat)?text=Export" data-throw-if-not-resolved="false"></xref> method allows you to export only the contents of a map frame instead of, for example, exporting an 
    entire page layout.
    </p>
<p>
    If you want to change the geographic extent within a map frame, you can use the <xref href="ArcGIS.Desktop.Layouts.MapFrame.Camera?text=Camera" data-throw-if-not-resolved="false"></xref> and
    <xref href="ArcGIS.Desktop.Layouts.MapFrame.SetCamera?text=SetCamera" data-throw-if-not-resolved="false"></xref> members to get and set the <xref href="ArcGIS.Desktop.Mapping.Camera?text=Camera" data-throw-if-not-resolved="false"></xref> associated with 
    a MapFrame. <xref href="ArcGIS.Desktop.Mapping.MapView.SetCamera?text=SetCamera" data-throw-if-not-resolved="false"></xref> is an overloaded method that allows you to change the map frame extent to a camera 
    position, a bookmark location, and so on.
    </p>


## Members

### AddGrid(GridStyleItem)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapFrame.yml" sourcestartlinenumber="1">Add a grid or a graticule to a map frame. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void AddGrid(GridStyleItem gridStyleItem)
```
### Camera

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapFrame.yml" sourcestartlinenumber="1">Gets the camera settings associated with the map frame.</p>


```csharp
public Camera Camera { get; }
```
### Export(ExportFormat)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapFrame.yml" sourcestartlinenumber="1">Export a layout to a variety of formats. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Export(ExportFormat exportFormat)
```
### GetAutoCamera()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapFrame.yml" sourcestartlinenumber="1">Gets the auto camera associated with the map frame</p>


```csharp
public CIMAutoCamera GetAutoCamera()
```
### GetGrids()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapFrame.yml" sourcestartlinenumber="1">Get the grids or graticules associated with the map frame.</p>


```csharp
public CIMMapGrid[] GetGrids()
```
### GetLayerVisibilityOverrides()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapFrame.yml" sourcestartlinenumber="1">Gets the layer visibility overrides for this map frame.</p>


```csharp
public IReadOnlyList<(Layer layer, bool visibility)> GetLayerVisibilityOverrides()
```
### GetMapView(LayoutView)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapFrame.yml" sourcestartlinenumber="1">Gets the map Frame's viewer on the specified layout pane. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public MapView GetMapView(LayoutView layoutView)
```
### GetViewCenter()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapFrame.yml" sourcestartlinenumber="1">Get the center point of the current extent of the map frame view.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public MapPoint GetViewCenter()
```
### GetViewExtent()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapFrame.yml" sourcestartlinenumber="1">Gets the current extent of the map frame view.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Envelope GetViewExtent()
```
### IsActivated

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapFrame.yml" sourcestartlinenumber="1">Gets whether the map frame is activated or not. Refer to
<xref href="ArcGIS.Desktop.Layouts.LayoutView.ActivateMapFrame(ArcGIS.Desktop.Layouts.MapFrame)" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public bool IsActivated { get; }
```
### IsLayerVisibilityOverrideEnabled

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapFrame.yml" sourcestartlinenumber="1">Gets whether this map frame uses layer visibility overrides.</p>


```csharp
public bool IsLayerVisibilityOverrideEnabled { get; }
```
### IsMapSeriesMapFrame()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapFrame.yml" sourcestartlinenumber="1">Gets whether this map frame is associated with a layout map series. This method must be
called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public bool IsMapSeriesMapFrame()
```
### Map

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapFrame.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Desktop.Mapping.Map?text=Map" data-throw-if-not-resolved="false"></xref> associated with the MapFrame.</p>


```csharp
public Map Map { get; }
```
### MapToPage(Coordinate2D)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapFrame.yml" sourcestartlinenumber="1">Translates a point in map coordinates to a point in page coordinates.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Coordinate2D MapToPage(Coordinate2D mapCoord)
```
### MapToPage(MapPoint)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapFrame.yml" sourcestartlinenumber="1">Translates a point in map coordinates to a point in page coordinates.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public MapPoint MapToPage(MapPoint mapPoint)
```
### PageToMap(Coordinate2D)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapFrame.yml" sourcestartlinenumber="1">Translates a point in page coordinates to a point in map coordinates.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Coordinate2D PageToMap(Coordinate2D pageCoord)
```
### PageToMap(MapPoint)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapFrame.yml" sourcestartlinenumber="1">Translates a point in page coordinates to a point in map coordinates.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public MapPoint PageToMap(MapPoint pagePoint)
```
### SetAutoCamera(CIMAutoCamera)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapFrame.yml" sourcestartlinenumber="1">Sets the auto camera for the map frame display constraints. This method must be called on the MCT.
Use QueuedTask.Run.</p>


```csharp
public void SetAutoCamera(CIMAutoCamera autoCamera)
```
### SetCamera(Envelope)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapFrame.yml" sourcestartlinenumber="1">Sets the map frame extent using an envelope. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetCamera(Envelope extent)
```
### SetCamera(Bookmark)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapFrame.yml" sourcestartlinenumber="1">Sets the map frame extent defined in a bookmark. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetCamera(Bookmark bookmark)
```
### SetCamera(Camera)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapFrame.yml" sourcestartlinenumber="1">Sets the map frame extent to a camera position. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetCamera(Camera camera)
```
### SetCamera(Layer, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapFrame.yml" sourcestartlinenumber="1">Sets the map frame extent using the a layer's extent. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetCamera(Layer layer, bool useSelectedFeatures = false)
```
### SetCamera(IEnumerable&lt;Layer&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapFrame.yml" sourcestartlinenumber="1">Sets the map frame extent using the extent of multiple layers. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetCamera(IEnumerable<Layer> layers, bool useSelectedFeatures = false)
```
### SetGrids(CIMMapGrid[])

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapFrame.yml" sourcestartlinenumber="1">Update the grids or graticules of a map frame. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetGrids(CIMMapGrid[] grids)
```
### SetLayerVisibilityOverrideEnabled(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapFrame.yml" sourcestartlinenumber="1">Enables or disables layer visibility overrides for this map frame. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetLayerVisibilityOverrideEnabled(bool isEnabled)
```
### SetLayerVisibilityOverrides(Layer, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapFrame.yml" sourcestartlinenumber="1">Sets the layer visibility override for a layer in this map frame. Radio group overrides are normalized so exactly one sublayer remains visible. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetLayerVisibilityOverrides(Layer layer, bool isVisible)
```
### SetLayerVisibilityOverrides(IEnumerable&lt;(Layer layer, bool visibility)&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapFrame.yml" sourcestartlinenumber="1">Sets layer visibility overrides for this map frame. Radio group overrides are normalized so exactly one sublayer remains visible. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetLayerVisibilityOverrides(IEnumerable<(Layer layer, bool visibility)> overrides)
```
### SetLayerVisibilityOverrides(List&lt;Layer&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapFrame.yml" sourcestartlinenumber="1">Sets the layer visibility override for a list of layers in this map frame. Radio group overrides are normalized so exactly one sublayer remains visible. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetLayerVisibilityOverrides(List<Layer> layers, bool isVisible)
```
### SetMap(Map)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapFrame.yml" sourcestartlinenumber="1">Sets the <xref href="ArcGIS.Desktop.Mapping.Map?text=Map" data-throw-if-not-resolved="false"></xref> associated with the MapFrame.  This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public void SetMap(Map map)
```
### ValidateAutoCamera(CIMAutoCamera)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapFrame.yml" sourcestartlinenumber="1">Validates the input CIMAutoCamera for the given <xref href="ArcGIS.Core.CIM.CIMAutoCamera.Source" data-throw-if-not-resolved="false"></xref> and
<xref href="ArcGIS.Core.CIM.CIMAutoCamera.AutoCameraType" data-throw-if-not-resolved="false"></xref> values. This method must be called on the MCT.
Use QueuedTask.Run.</p>


```csharp
public bool ValidateAutoCamera(CIMAutoCamera autoCamera)
```


