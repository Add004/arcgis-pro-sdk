# Map

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Represents the primary object used for the organization of geographic data.</p>


## Object Signature

```csharp
public sealed class Map : PropertyChangedBase, ILayerContainerEdit, ILayerContainer, IStandaloneTableContainerEdit, IStandaloneTableContainer, IElementContainer, ISuspendableObservableCollection, IMetadataInfo, IArcadeEvaluatorObject
```

## Remarks

<p>To create a Map, you must call one of the create methods of the <xref href="ArcGIS.Desktop.Mapping.MapFactory?text=MapFactory" data-throw-if-not-resolved="false"></xref> class.</p>
<p>To open a map, use <xref href="ArcGIS.Desktop.Core.ProApp.Panes.CreateMapPaneAsync?text=ProApp.Panes.CreateMapPaneAsync" data-throw-if-not-resolved="false"></xref> method.</p>
<p>You can also think of a Map as a container of layers, StandaloneTables, bookmarks etc. You need to use a  <xref href="ArcGIS.Desktop.Mapping.MapView?text=MapView" data-throw-if-not-resolved="false"></xref> to interact with a map.
    Multiple MapViews can be opened for a Map at a given time, but there can only be one active MapView which is returned by the <xref href="ArcGIS.Desktop.Mapping.MapView.Active?text=MapView.Active" data-throw-if-not-resolved="false"></xref> static member.
    Use the <xref href="MapView.Active.Map?text=Map" data-throw-if-not-resolved="false"></xref> property to access the Map object associated with the MapView.
    The Map object has properties that operate on all layers within the map, such as spatial reference, reference scale, and so on, along with methods that manipulate the map's layers.</p>


## Members

### AddBookmark(CIMBookmark)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Creates a new bookmark using a CIM definition of a bookmark. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Bookmark AddBookmark(CIMBookmark bookmark)
```
### AddBookmark(MapView, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Creates a new bookmark using the current location and time of the map view.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Bookmark AddBookmark(MapView mapView, string name)
```
### AddBookmark(MapView, string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Creates a new bookmark using the current location and time of the map view.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Bookmark AddBookmark(MapView mapView, string name, string description)
```
### Animation

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets the animation for the map.</p>


```csharp
public Animation Animation { get; }
```
### AutoFillFeatureCache

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets the flag indicating if the feature cache is automatically filled for layers in the map.</p>


```csharp
public bool AutoFillFeatureCache { get; }
```
### CMYKColorProfile

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets the CMYK color profile</p>


```csharp
public string CMYKColorProfile { get; }
```
### CalculateFullExtent()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Returns the full extent of the map.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Envelope CalculateFullExtent()
```
### CanAdd(Item, MapType?, MapViewingMode?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Indicates whether or not an item can be added to the map.</p>


```csharp
public static bool CanAdd(Item item, MapType? mapType, MapViewingMode? mapViewingMode = null)
```
### CanFillFeatureCache()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Determines whether a fill feature cache operation can be executed.  Only one fill feature cache operation can
be executed at any one time.</p>


```csharp
public bool CanFillFeatureCache()
```
### CanGroupMapMembers(IEnumerable&lt;MapMember&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Checks whether the collection of map members can be grouped.
This method must be called on the MCT. Use QueuedTask.Run</p>


```csharp
public bool CanGroupMapMembers(IEnumerable<MapMember> mmembers)
```
### CanRemoveLayer(Layer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Determines if a layer can be removed from the container.</p>


```csharp
public bool CanRemoveLayer(Layer layer)
```
### CanRemoveLayers(IEnumerable&lt;Layer&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Determines if the layers can be removed from the container.</p>


```csharp
public bool CanRemoveLayers(IEnumerable<Layer> layers)
```
### CanUngroupLayer(GroupLayer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Checks whether the group layer can be ungrouped.
This method must be called on the MCT. Use QueuedTask.Run</p>


```csharp
public bool CanUngroupLayer(GroupLayer groupLayerToUngroup)
```
### CancelFeatureCacheRequestsAsync(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Cancels any existing feature cache requests.</p>


```csharp
public Task CancelFeatureCacheRequestsAsync(bool showNotification)
```
### ChangeVersion(VersionBase, VersionBase)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Change GeoDatabase version of layers and standalone tables of fromVersionBase.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void ChangeVersion(VersionBase fromVersionBase, VersionBase toVersionBase)
```
### ClearClipGeometry()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Clear the current map clip geometry. This method must
be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void ClearClipGeometry()
```
### ClearElevationSurfaceLayers()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Will remove all elevation surfaces from the map with the exception of Ground. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void ClearElevationSurfaceLayers()
```
### ClearFeatureCacheAsync(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Empties the feature cache for all web feature layers (feature services) in the map.</p>


```csharp
public Task ClearFeatureCacheAsync(bool showNotification)
```
### ClearFeatureCacheAsync(IEnumerable&lt;Layer&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Empties the feature cache for the specified web feature layers (feature services) that are part of this map.
Layers that are not part of this map or do not support feature caching are ignored.</p>


```csharp
public Task ClearFeatureCacheAsync(IEnumerable<Layer> layers, bool showNotification)
```
### ClearSelection()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Clear the selection in the map.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void ClearSelection()
```
### ColorModel

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets the current color model</p>


```csharp
public ColorModel ColorModel { get; }
```
### DefaultViewingMode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets the map's default viewing mode.</p>


```csharp
public MapViewingMode DefaultViewingMode { get; }
```
### ExportBookmarks(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Export bookmarks from the active map or scene to a BKMX file. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void ExportBookmarks(string filePath)
```
### FillFeatureCacheAsync(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Fills the feature cache for all visible web feature layers (feature services) in the map.</p>


```csharp
public Task FillFeatureCacheAsync(bool showNotification)
```
### FillFeatureCacheAsync(IEnumerable&lt;Layer&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Fills the feature cache for the specified web feature layers (feature services) that are part of this map.
Layers that are not part of this map or do not support feature caching are ignored.</p>


```csharp
public Task FillFeatureCacheAsync(IEnumerable<Layer> layers, bool showNotification)
```
### FindAndReplaceWorkspacePath(string, string, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Performs a find and replace of workspace paths for all layers and tables in the map that share that workspace path.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void FindAndReplaceWorkspacePath(string findWorkspacePath, string replaceWorkspacePath, bool validate = true)
```
### FindElevationSurfaceLayer(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Finds an elevation surface layer using a URI.</p>


```csharp
public ElevationSurfaceLayer FindElevationSurfaceLayer(string layerURI)
```
### FindLayer(string, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Finds a layer using a URI.</p>


```csharp
public Layer FindLayer(string layerURI, bool recursive = true)
```
### FindLayers(string, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Finds layers by name.</p>


```csharp
public IReadOnlyList<Layer> FindLayers(string name, bool recursive = true)
```
### FindStandaloneTable(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Finds a StandaloneTable using a URI. Group layers within the map are also searched.</p>


```csharp
public StandaloneTable FindStandaloneTable(string tableURI)
```
### FindStandaloneTables(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Finds StandaloneTables by name. Group layers within the map are also searched.</p>


```csharp
public IReadOnlyList<StandaloneTable> FindStandaloneTables(string name)
```
### GetAvailableElevationUnitFormats()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets the list of available elevation unit formats for the given scene.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IList<DisplayUnitFormat> GetAvailableElevationUnitFormats()
```
### GetAvailableLocationUnitFormats()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets the list of available map location unit formats for the given map.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IList<DisplayUnitFormat> GetAvailableLocationUnitFormats()
```
### GetBookmarks()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Returns the map's collection of bookmarks. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public ReadOnlyObservableCollection<Bookmark> GetBookmarks()
```
### GetCanEditMetadata()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets whether the Map metadata can be edited or not. This method must be called on the MCT.
Use QueuedTask.Run.</p>


```csharp
public bool GetCanEditMetadata()
```
### GetClipGeometry()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Get the current map clipping geometry. This method must be called
on the MCT. Use QueuedTask.Run.</p>


```csharp
public Polygon GetClipGeometry()
```
### GetCustomElevationSurfaceLayers()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets the list of custom elevation surface layers for the map.</p>


```csharp
public IReadOnlyList<ElevationSurfaceLayer> GetCustomElevationSurfaceLayers()
```
### GetCustomFullExtent()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Returns the custom full extent of the map.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Envelope GetCustomFullExtent()
```
### GetDefaultExtent()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Returns the default full extent of the map.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Envelope GetDefaultExtent()
```
### GetDefinition()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Returns the map definition.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMMap GetDefinition()
```
### GetElementCount()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets the number of elements in the map.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public long GetElementCount()
```
### GetElementStorageSize()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets the storage size of all the elements in the map.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double GetElementStorageSize()
```
### GetElevationProfileFromSurface(MapPoint, MapPoint, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets an elevation profile calculated between <code class="paramref">startPoint</code> and <code class="paramref">endPoint</code>.
Intermediate points are calculated at equal distances between the end points according to the <code class="paramref">numPoints</code> specified.
The Z values of the calculated polyline are populated from the Ground Surface Layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public ElevationProfileResult GetElevationProfileFromSurface(MapPoint startPoint, MapPoint endPoint, int numPoints)
```
### GetElevationProfileFromSurface(MapPoint, MapPoint, int, ElevationSurfaceLayer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets an elevation profile calculated between <code class="paramref">startPoint</code> and <code class="paramref">endPoint</code>.
Intermediate points are calculated at equal distances between the end points according to the <code class="paramref">numPoints</code> specified.
The Z values of the calculated polyline are populated from the Ground Surface Layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public ElevationProfileResult GetElevationProfileFromSurface(MapPoint startPoint, MapPoint endPoint, int numPoints, ElevationSurfaceLayer surfaceLayer)
```
### GetElevationProfileFromSurface(MapPoint, MapPoint, int, ElevationSurfaceLayer, SurfaceZsMissingHandler)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets an elevation profile calculated between <code class="paramref">startPoint</code> and <code class="paramref">endPoint</code>.
Intermediate points are calculated at equal distances between the end points according to the <code class="paramref">numPoints</code> specified.
The Z values of the calculated polyline are populated from the specified Elevation Surface Layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public ElevationProfileResult GetElevationProfileFromSurface(MapPoint startPoint, MapPoint endPoint, int numPoints, ElevationSurfaceLayer surfaceLayer, SurfaceZsMissingHandler missingHandler)
```
### GetElevationProfileFromSurface(IEnumerable&lt;MapPoint&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets an elevation profile for the specified points.
The Z values of the calculated polyline are populated from the Ground Surface Layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public ElevationProfileResult GetElevationProfileFromSurface(IEnumerable<MapPoint> points)
```
### GetElevationProfileFromSurface(IEnumerable&lt;MapPoint&gt;, ElevationSurfaceLayer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets an elevation profile for the specified points.
The Z values of the calculated polyline are populated from the specified Elevation Surface Layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public ElevationProfileResult GetElevationProfileFromSurface(IEnumerable<MapPoint> points, ElevationSurfaceLayer surfaceLayer)
```
### GetElevationProfileFromSurface(IEnumerable&lt;MapPoint&gt;, ElevationSurfaceLayer, SurfaceZsMissingHandler)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets an elevation profile for the specified points.
The Z values of the calculated polyline are populated from the specified Elevation Surface Layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public ElevationProfileResult GetElevationProfileFromSurface(IEnumerable<MapPoint> points, ElevationSurfaceLayer surfaceLayer, SurfaceZsMissingHandler missingHandler)
```
### GetElevationProfileFromSurface(IEnumerable&lt;Polyline&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets an elevation profile for the specified polylines.
The Z values of the calculated polyline are populated from the Ground Surface Layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public ElevationProfileResult GetElevationProfileFromSurface(IEnumerable<Polyline> polylines)
```
### GetElevationProfileFromSurface(IEnumerable&lt;Polyline&gt;, ElevationSurfaceLayer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets an elevation profile for the specified polylines.
The Z values of the calculated polyline are populated from the specified Elevation Surface Layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public ElevationProfileResult GetElevationProfileFromSurface(IEnumerable<Polyline> polylines, ElevationSurfaceLayer surfaceLayer)
```
### GetElevationProfileFromSurface(IEnumerable&lt;Polyline&gt;, ElevationSurfaceLayer, SurfaceZsMissingHandler)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets an elevation profile for the specified polylines.
The Z values of the calculated polyline are populated from the specified Elevation Surface Layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public ElevationProfileResult GetElevationProfileFromSurface(IEnumerable<Polyline> polylines, ElevationSurfaceLayer surfaceLayer, SurfaceZsMissingHandler missingHandler)
```
### GetElevationProfileFromSurfaceAsync(MapPoint, MapPoint, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets an elevation profile calculated between <code class="paramref">startPoint</code> and <code class="paramref">endPoint</code>.
Intermediate points are calculated at equal distances between the end points according to the <code class="paramref">numPoints</code> specified.
The Z values of the calculated polyline are populated from the Ground Surface Layer.</p>


```csharp
public Task<ElevationProfileResult> GetElevationProfileFromSurfaceAsync(MapPoint startPoint, MapPoint endPoint, int numPoints)
```
### GetElevationProfileFromSurfaceAsync(MapPoint, MapPoint, int, ElevationSurfaceLayer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets an elevation profile calculated between <code class="paramref">startPoint</code> and <code class="paramref">endPoint</code>.
Intermediate points are calculated at equal distances between the end points according to the <code class="paramref">numPoints</code> specified.
The Z values of the calculated polyline are populated from the Ground Surface Layer.</p>


```csharp
public Task<ElevationProfileResult> GetElevationProfileFromSurfaceAsync(MapPoint startPoint, MapPoint endPoint, int numPoints, ElevationSurfaceLayer surfaceLayer)
```
### GetElevationProfileFromSurfaceAsync(MapPoint, MapPoint, int, ElevationSurfaceLayer, SurfaceZsMissingHandler)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets an elevation profile calculated between <code class="paramref">startPoint</code> and <code class="paramref">endPoint</code>.
Intermediate points are calculated at equal distances between the end points according to the <code class="paramref">numPoints</code> specified.
The Z values of the calculated polyline are populated from the specified Elevation Surface Layer.</p>


```csharp
public Task<ElevationProfileResult> GetElevationProfileFromSurfaceAsync(MapPoint startPoint, MapPoint endPoint, int numPoints, ElevationSurfaceLayer surfaceLayer, SurfaceZsMissingHandler missingHandler)
```
### GetElevationProfileFromSurfaceAsync(MapPoint, MapPoint, int, ElevationSurfaceLayer, SurfaceZsMissingHandler, CancellationToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets an elevation profile calculated between <code class="paramref">startPoint</code> and <code class="paramref">endPoint</code>.
Intermediate points are calculated at equal distances between the end points according to the <code class="paramref">numPoints</code> specified.
The Z values of the calculated polyline are populated from the specified Elevation Surface Layer.</p>


```csharp
public Task<ElevationProfileResult> GetElevationProfileFromSurfaceAsync(MapPoint startPoint, MapPoint endPoint, int numPoints, ElevationSurfaceLayer surfaceLayer, SurfaceZsMissingHandler missingHandler, CancellationToken cancellationToken)
```
### GetElevationProfileFromSurfaceAsync(IEnumerable&lt;MapPoint&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets an elevation profile for the specified points.
The Z values of the calculated polyline are populated from the Ground Surface Layer.</p>


```csharp
public Task<ElevationProfileResult> GetElevationProfileFromSurfaceAsync(IEnumerable<MapPoint> points)
```
### GetElevationProfileFromSurfaceAsync(IEnumerable&lt;MapPoint&gt;, ElevationSurfaceLayer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets an elevation profile for the specified points.
The Z values of the calculated polyline are populated from the specified Elevation Surface Layer.</p>


```csharp
public Task<ElevationProfileResult> GetElevationProfileFromSurfaceAsync(IEnumerable<MapPoint> points, ElevationSurfaceLayer surfaceLayer)
```
### GetElevationProfileFromSurfaceAsync(IEnumerable&lt;MapPoint&gt;, ElevationSurfaceLayer, SurfaceZsMissingHandler)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets an elevation profile for the specified points.
The Z values of the calculated polyline are populated from the specified Elevation Surface Layer.</p>


```csharp
public Task<ElevationProfileResult> GetElevationProfileFromSurfaceAsync(IEnumerable<MapPoint> points, ElevationSurfaceLayer surfaceLayer, SurfaceZsMissingHandler missingHandler)
```
### GetElevationProfileFromSurfaceAsync(IEnumerable&lt;MapPoint&gt;, ElevationSurfaceLayer, SurfaceZsMissingHandler, CancellationToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets an elevation profile for the specified points.
The Z values of the calculated polyline are populated from the specified Elevation Surface Layer.</p>


```csharp
public Task<ElevationProfileResult> GetElevationProfileFromSurfaceAsync(IEnumerable<MapPoint> points, ElevationSurfaceLayer surfaceLayer, SurfaceZsMissingHandler missingHandler, CancellationToken cancellationToken)
```
### GetElevationProfileFromSurfaceAsync(IEnumerable&lt;Polyline&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets an elevation profile for the specified polylines.
The Z values of the calculated polyline are populated from the Ground Surface Layer.</p>


```csharp
public Task<ElevationProfileResult> GetElevationProfileFromSurfaceAsync(IEnumerable<Polyline> polylines)
```
### GetElevationProfileFromSurfaceAsync(IEnumerable&lt;Polyline&gt;, ElevationSurfaceLayer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets an elevation profile for the specified polylines.
The Z values of the calculated polyline are populated from the specified Elevation Surface Layer.</p>


```csharp
public Task<ElevationProfileResult> GetElevationProfileFromSurfaceAsync(IEnumerable<Polyline> polylines, ElevationSurfaceLayer surfaceLayer)
```
### GetElevationProfileFromSurfaceAsync(IEnumerable&lt;Polyline&gt;, ElevationSurfaceLayer, SurfaceZsMissingHandler)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets an elevation profile for the specified polylines.
The Z values of the calculated polyline are populated from the specified Elevation Surface Layer.</p>


```csharp
public Task<ElevationProfileResult> GetElevationProfileFromSurfaceAsync(IEnumerable<Polyline> polylines, ElevationSurfaceLayer surfaceLayer, SurfaceZsMissingHandler missingHandler)
```
### GetElevationProfileFromSurfaceAsync(IEnumerable&lt;Polyline&gt;, ElevationSurfaceLayer, SurfaceZsMissingHandler, CancellationToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets an elevation profile for the specified polylines.
The Z values of the calculated polyline are populated from the specified Elevation Surface Layer.</p>


```csharp
public Task<ElevationProfileResult> GetElevationProfileFromSurfaceAsync(IEnumerable<Polyline> polylines, ElevationSurfaceLayer surfaceLayer, SurfaceZsMissingHandler missingHandler, CancellationToken cancellationToken)
```
### GetElevationSurfaceLayers()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets the list of elevation surface layers for the map.</p>


```csharp
public IReadOnlyList<ElevationSurfaceLayer> GetElevationSurfaceLayers()
```
### GetElevationUnitFormat()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets the current scene elevation unit format. This method must
be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public DisplayUnitFormat GetElevationUnitFormat()
```
### GetGeneralPlacementProperties()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Returns the general label placement properties of the map.
This method must be called on the MCT. Use QueuedTask.Run   .</p>


```csharp
public CIMGeneralPlacementProperties GetGeneralPlacementProperties()
```
### GetGroundElevationSurfaceLayer()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets the ground elevation surface layer from the map.</p>


```csharp
public ElevationSurfaceLayer GetGroundElevationSurfaceLayer()
```
### GetHighlightSelection()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Get the highlight selection for the map.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SelectionSet GetHighlightSelection()
```
### GetLabelEngine()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Returns the label engine type of the map.
This method must be called on the MCT. Use QueuedTask.Run  .</p>


```csharp
public LabelEngine GetLabelEngine()
```
### GetLayerTemplatePackages()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets the collection of layer template packages installed with Pro for use with maps.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<Item> GetLayerTemplatePackages()
```
### GetLayersAsFlattenedList()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Returns a read only flat list of layers where nested groups are not preserved.</p>


```csharp
public IReadOnlyList<Layer> GetLayersAsFlattenedList()
```
### GetLocationUnitFormat()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets the current map location unit format for the current project. This method must
be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public DisplayUnitFormat GetLocationUnitFormat()
```
### GetMapMembersAsFlattenedList()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Returns a read only flat list of mapMembers where nested groups are not preserved.</p>


```csharp
public IReadOnlyList<MapMember> GetMapMembersAsFlattenedList()
```
### GetMapPanes()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Get the collection of map panes for the map</p>


```csharp
public IReadOnlyList<IMapPane> GetMapPanes()
```
### GetMetadata()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets the Map metadata. This method must be called on the MCT.
Use QueuedTask.Run.</p>


```csharp
public string GetMetadata()
```
### GetSelection()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Get the selection for the map.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SelectionSet GetSelection()
```
### GetSnapshot()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets a readonly snapshot of the layers</p>


```csharp
public IReadOnlyList<Layer> GetSnapshot()
```
### GetStandaloneTablesAsFlattenedList()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Returns a read only flat list of StandaloneTables where nested groups are not preserved.</p>


```csharp
public IReadOnlyList<StandaloneTable> GetStandaloneTablesAsFlattenedList()
```
### GetStereoCursorFixedMode()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets a value indicating whether the cursor of the stereo model is fixed.</p>


```csharp
public bool GetStereoCursorFixedMode()
```
### GetZsFromSurface(Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Obtains a geometry that is similar to the given input geometry, where some or all Z values are populated from the default Ground Surface Layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SurfaceZsResult GetZsFromSurface(Geometry geometry)
```
### GetZsFromSurface(Geometry, ElevationSurfaceLayer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Obtains a geometry that is similar to the given input geometry, where some or all Z values are populated from the specified Elevation Surface Layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SurfaceZsResult GetZsFromSurface(Geometry geometry, ElevationSurfaceLayer surfaceLayer)
```
### GetZsFromSurface(Geometry, ElevationSurfaceLayer, SurfaceZsMissingHandler)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Obtains a geometry that is similar to the given input geometry, where some or all Z values are populated from the specified Elevation Surface Layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SurfaceZsResult GetZsFromSurface(Geometry geometry, ElevationSurfaceLayer surfaceLayer, SurfaceZsMissingHandler missingHandler)
```
### GetZsFromSurfaceAsync(Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Obtains a geometry that is similar to the given input geometry, where some or all Z values are populated from the default Ground Surface Layer.</p>


```csharp
public Task<SurfaceZsResult> GetZsFromSurfaceAsync(Geometry geometry)
```
### GetZsFromSurfaceAsync(Geometry, ElevationSurfaceLayer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Obtains a geometry that is similar to the given input geometry, where some or all Z values are populated from the specified Elevation Surface Layer.</p>


```csharp
public Task<SurfaceZsResult> GetZsFromSurfaceAsync(Geometry geometry, ElevationSurfaceLayer surfaceLayer)
```
### GetZsFromSurfaceAsync(Geometry, ElevationSurfaceLayer, SurfaceZsMissingHandler)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Obtains a geometry that is similar to the given input geometry, where some or all Z values are populated from the specified Elevation Surface Layer.</p>


```csharp
public Task<SurfaceZsResult> GetZsFromSurfaceAsync(Geometry geometry, ElevationSurfaceLayer surfaceLayer, SurfaceZsMissingHandler missingHandler)
```
### GetZsFromSurfaceAsync(Geometry, ElevationSurfaceLayer, SurfaceZsMissingHandler, CancellationToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Obtains a geometry that is similar to the given input geometry, where some or all Z values are populated from the specified Elevation Surface Layer.</p>


```csharp
public Task<SurfaceZsResult> GetZsFromSurfaceAsync(Geometry geometry, ElevationSurfaceLayer surfaceLayer, SurfaceZsMissingHandler missingHandler, CancellationToken cancellationToken)
```
### GroupMapMembers(IEnumerable&lt;MapMember&gt;, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Groups the input collection of map members into a new Group Layer.
This method must be called on the MCT. Use QueuedTask.Run</p>


```csharp
public GroupLayer GroupMapMembers(IEnumerable<MapMember> mmembersToGroup, string groupLayerName)
```
### ImportBookmarks(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Import bookmarks from ArcMap, ArcGlobe, and ArcScene bookmark files (<em sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">.dat) or ArcGIS Pro bookmark files (</em>.bmkx).
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public ReadOnlyObservableCollection<Bookmark> ImportBookmarks(string filePath)
```
### IsInImageCoordinateSpace

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets whether the map contains a focused raster layer.</p>


```csharp
public bool IsInImageCoordinateSpace { get; }
```
### IsLinkChart

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets whether the map is of type Link Chart.</p>


```csharp
public bool IsLinkChart { get; }
```
### IsScene

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets whether the map is of type scene.</p>


```csharp
public bool IsScene { get; }
```
### LayerTemplatePackages

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets the collection of layer template packages installed with Pro for use with maps</p>


```csharp
[Obsolete("This property is deprecated at 3.8. Please use GetLayerTemplatePackages() instead.")]
public IReadOnlyList<Item> LayerTemplatePackages { get; }
```
### Layers

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets a read-only collection of layers from the layer container.</p>


```csharp
public ReadOnlyObservableCollection<Layer> Layers { get; }
```
### MapType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets the map type.</p>


```csharp
public MapType MapType { get; }
```
### MoveBookmark(Bookmark, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Moves the bookmark to a new index in the map's collection of bookmarks.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void MoveBookmark(Bookmark bookmark, int newIndex)
```
### MoveLayer(Layer, GroupLayer, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Moves a layer to a different position in the specified targetlayer container.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void MoveLayer(Layer layer, GroupLayer targetLayer, int position)
```
### MoveLayer(Layer, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Moves a layer to a different position in the table of contents.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void MoveLayer(Layer layer, int position)
```
### MoveStandaloneTable(StandaloneTable, CompositeLayerWithTables, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Moves a StandaloneTable to a position within the specified targetLayer container.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void MoveStandaloneTable(StandaloneTable table, CompositeLayerWithTables targetLayer, int position)
```
### MoveStandaloneTable(StandaloneTable, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Moves a StandaloneTable to a position within the map StandaloneTable container.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void MoveStandaloneTable(StandaloneTable table, int position)
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets the name of the map.</p>


```csharp
public string Name { get; }
```
### NearPlaneClipDistance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets the clip distance for the map</p>


```csharp
public double NearPlaneClipDistance { get; }
```
### NearPlaneClipDistanceMode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets the clipping mode for the map</p>


```csharp
public ClipDistanceMode NearPlaneClipDistanceMode { get; }
```
### OpenViewAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Open a new view for this map.</p>


```csharp
public Task OpenViewAsync()
```
### OperationManager

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets the OperationManager.</p>


```csharp
public OperationManager OperationManager { get; }
```
### RGBColorProfile

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets the RGB color profile</p>


```csharp
public string RGBColorProfile { get; }
```
### ReferenceScale

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets the reference scale of the map.</p>


```csharp
public double ReferenceScale { get; }
```
### RemoveBookmark(Bookmark)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Removes the bookmark from the map. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveBookmark(Bookmark bookmark)
```
### RemoveLayer(Layer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Removes a specified layer from the map.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveLayer(Layer layer)
```
### RemoveLayers(IEnumerable&lt;Layer&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Removes the specified layers from the map.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveLayers(IEnumerable<Layer> layers)
```
### RemoveStandaloneTable(StandaloneTable)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Removes the specified StandaloneTable from the map.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveStandaloneTable(StandaloneTable table)
```
### RemoveStandaloneTables(IEnumerable&lt;StandaloneTable&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Removes the specified StandaloneTables from the map.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveStandaloneTables(IEnumerable<StandaloneTable> tables)
```
### ReplaceDatasource(Datastore, Datastore, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Performs a find and replace of workspace paths for all layers and tables in the map that share that workspace path.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void ReplaceDatasource(Datastore findDatabaseStore, Datastore replaceDatabaseStore, bool validate = true)
```
### SaveAsFile(string, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Saves the map as a mapx file.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SaveAsFile(string fullPathToMapXFile, bool overwrite)
```
### SaveAsWebMapFile(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Save the current map to webmap file format. This method must be called
on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SaveAsWebMapFile(string webMapFileName)
```
### SelectionCount

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets the number of rows and features selected in the map.</p>


```csharp
public int SelectionCount { get; }
```
### SetAutoFillFeatureCache(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Sets the flag indicating if the feature cache is automatically filled for layers in the map.</p>


```csharp
public void SetAutoFillFeatureCache(bool autoFill)
```
### SetBasemapLayers(Item)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Sets the current basemap layers in the map.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetBasemapLayers(Item baseMapItem)
```
### SetBasemapLayers(Basemap)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Sets the current basemap layers in the map.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetBasemapLayers(Basemap basemap)
```
### SetClipGeometry(Polygon, CIMLineSymbol)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Set map clipping to the provided clip polygon. This method must
be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetClipGeometry(Polygon clipPolygon, CIMLineSymbol border)
```
### SetClipGeometry(Polygon, IEnumerable&lt;Layer&gt;, IEnumerable&lt;ElevationSurfaceLayer&gt;, CIMLineSymbol)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Set map clipping to the provided clip polygon. Specify layers or elevation surfaces to be excluded from the clipping operation.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetClipGeometry(Polygon clipPolygon, IEnumerable<Layer> excludeLayers, IEnumerable<ElevationSurfaceLayer> excludeSurfaces, CIMLineSymbol border)
```
### SetCustomFullExtent(Envelope)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Updates the custom full extent of the map.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetCustomFullExtent(Envelope customFullExtent)
```
### SetDefinition(CIMMap)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Sets the map definition.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDefinition(CIMMap mapDefinition)
```
### SetElevationUnitFormat(DisplayUnitFormat)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Sets the current scene elevation unit format. This method must
be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetElevationUnitFormat(DisplayUnitFormat unitFormat)
```
### SetGeneralPlacementProperties(CIMGeneralPlacementProperties)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Updates the general label placement properties of the map.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetGeneralPlacementProperties(CIMGeneralPlacementProperties generalLabelPlacementProperties)
```
### SetLabelEngine(LabelEngine)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Updates the label engine type of the map.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetLabelEngine(LabelEngine labelEngine)
```
### SetLocationUnitFormat(DisplayUnitFormat)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Sets the current map location unit format for the current project. This method must
be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetLocationUnitFormat(DisplayUnitFormat unitFormat)
```
### SetMetadata(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Sets the Map metadata. This method must be called on the MCT.
Use QueuedTask.Run.</p>


```csharp
public void SetMetadata(string metadataXml)
```
### SetName(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Updates the name of the map.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetName(string name)
```
### SetReferenceScale(double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Updates the reference scale of the map.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetReferenceScale(double referenceScale)
```
### SetSelection(SelectionSet, SelectionCombinationMethod)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Set the selection in the map.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SelectionSet SetSelection(SelectionSet selectionSet, SelectionCombinationMethod method = SelectionCombinationMethod.New)
```
### SetSpatialReference(SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Updates the spatial reference of the map.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetSpatialReference(SpatialReference spatialReference)
```
### SetStereoCursorFixedMode(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Toggles the stereo model's cursor between fixed and floating states.</p>


```csharp
[Obsolete("SetStereoCursorFixedMode is deprecated at 3.7. This method is obsolete. Use the MapView.SetStereoCursorMode instead.")]
public void SetStereoCursorFixedMode(bool cursorFixed)
```
### SimulateOverprint

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets if simulate overprint is set</p>


```csharp
public bool SimulateOverprint { get; }
```
### SpatialReference

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets the spatial reference of the map.</p>


```csharp
public SpatialReference SpatialReference { get; }
```
### StandaloneTables

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets all standalone tables of the map.</p>


```csharp
public ReadOnlyObservableCollection<StandaloneTable> StandaloneTables { get; }
```
### TargetGraphicsLayer

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets or sets the graphics layer that acts as a target for interactive drawing tools.</p>


```csharp
public GraphicsLayer TargetGraphicsLayer { get; set; }
```
### ToString()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Returns the name of the map.</p>


```csharp
public override string ToString()
```
### URI

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Gets the unique URI of this map.</p>


```csharp
public string URI { get; }
```
### UngroupLayer(GroupLayer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Map.yml" sourcestartlinenumber="1">Ungroups the specified group layer.
This method must be called on the MCT. Use QueuedTask.Run</p>


```csharp
public void UngroupLayer(GroupLayer groupLayerToUngroup)
```


