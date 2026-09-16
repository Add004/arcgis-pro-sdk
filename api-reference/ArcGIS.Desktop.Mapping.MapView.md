# MapView

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Represents a view of a map (2D) or a scene (3D).</p>


## Object Signature

```csharp
public class MapView
```

## Remarks

<p>A project can contain multiple maps, either 2D or 3D, and each defines the collection of layers that make up that map. 
    A map view is simply a view of a map. Map views are the primary interface used to display, navigate, select, identify, and edit data in a 2D or 3D map. 
    The MapView class provides properties and methods to navigate and interact with layers in the map. 
    The map being visualized in the view can be accessed via the <xref href="ArcGIS.Desktop.Mapping.MapView.Map" data-throw-if-not-resolved="false"></xref> property.</p>
<p>There can be multiple map views open at a given time, but there can only be one active map view. 
    The active map view will set the context for the ribbon and many of the dock panes in the application. 
    For example, the map Contents pane will reflect the layers of the active map view's map. 
    The instance of the active map view can be accessed via the static the <xref href="ArcGIS.Desktop.Mapping.MapView.Active" data-throw-if-not-resolved="false"></xref> property. 
    The active property will return null if there is no active map view. This is useful when writing commands designed to interact with the active map.</p>
<p>The map view also provides the context for the selected items in the Contents pane. 
    For example, the <xref href="ArcGIS.Desktop.Mapping.MapView.GetSelectedLayers" data-throw-if-not-resolved="false"></xref> method returns the collection of layers that are currently selected in the Contents pane. 
    This context is used to determine which contextual tabs to show, for example, when one or more feature layers are selected, the Feature Layer tab group will display, and the commands will act on the selected feature layers. 
    This is useful when writing commands to work with the selected items in the Contents pane.</p>


## Members

### Active

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Gets the active map view. Returns null if there is no active map view.</p>


```csharp
public static MapView Active { get; }
```
### ActiveRangeName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Gets the name of the active range definition in the map view.</p>


```csharp
public string ActiveRangeName { get; }
```
### AddExploratoryAnalysisAsync(ExploratoryAnalysis)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">An asynchronous function to add an ExploratoryAnalysisBase subclass instance to the MapView.  Calling
this method activates the Exploratory Analysis object and presents it on the view.</p>


```csharp
public Task AddExploratoryAnalysisAsync(ExploratoryAnalysis item)
```
### AddOverlayControl(IMapViewOverlayControl)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Add a control over the view.</p>


```csharp
public void AddOverlayControl(IMapViewOverlayControl overlayControl)
```
### Animation

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Gets the animation for the view.</p>


```csharp
public ViewAnimation Animation { get; }
```
### Camera

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Gets the current Camera of the view.</p>


```csharp
public Camera Camera { get; }
```
### CanPrint

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Gets whether the mapview can be printed</p>


```csharp
public bool CanPrint { get; }
```
### CanSetMapTOCContent(MapTOCContentType)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Gets whether the specified map TOC content type can be set on the
active TOC.</p>


```csharp
public bool CanSetMapTOCContent(MapTOCContentType mapTOCContentType)
```
### CanSetStereoCursorMode()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Checks whether the stereo model's cursor mode can be toggled between fixed and
floating states. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool CanSetStereoCursorMode()
```
### CanSetViewingMode(MapViewingMode)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Gets a value indicating if the view can be changed to the provided <xref href="ArcGIS.Core.CIM.MapViewingMode" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public bool CanSetViewingMode(MapViewingMode viewingMode)
```
### CanShowElevationProfileGraph()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Checks to see if an elevation profile can be displayed.</p>


```csharp
public bool CanShowElevationProfileGraph()
```
### CancelDrawing()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Stop the current drawing of the MapView.</p>


```csharp
public void CancelDrawing()
```
### CaptureThumbnail(int, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Capture a bitmap of the MapView content.</p>


```csharp
public BitmapSource CaptureThumbnail(int width, int height)
```
### ClearTOCSelection()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Clears the selection from the TOC.</p>


```csharp
public void ClearTOCSelection()
```
### ClientToMap(Point)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Converts a point in client coordinates relative to the top-left corner of the view to a point in the coordinates of the map or scene. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public MapPoint ClientToMap(Point clientPoint)
```
### ClientToScreen(Point)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Converts a screen point to a point in client coordinates relative to the top-left corner of the view.</p>


```csharp
public Point ClientToScreen(Point clientPoint)
```
### CloseActivePopup()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Closes the active popup window. You must be on the UI thread to call this function</p>


```csharp
public void CloseActivePopup()
```
### ClosePopups()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Close all popup windows whether pinned or not pinned (active). You must be on the UI thread to call this function</p>


```csharp
public void ClosePopups()
```
### ClosePopups(IEnumerable&lt;PopupContent&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Close all popup windows containing any of the provided popup content
whether pinned or not pinned (active). You must be on the UI thread to call this function</p>


```csharp
public void ClosePopups(IEnumerable<PopupContent> customContent)
```
### CurrentMapTOCContent

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Gets the current active TOC content type for the map view.</p>


```csharp
public MapTOCContentType CurrentMapTOCContent { get; }
```
### DrawingPaused

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Gets or sets the paused state on the map view.</p>


```csharp
public bool DrawingPaused { get; set; }
```
### ElevationProfileGraphAdded

- Kind: event

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Occurs when the elevation profile graph is added.</p>


```csharp
public event EventHandler ElevationProfileGraphAdded
```
### ElevationProfileGraphRemoved

- Kind: event

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Occurs when the elevation profile graph is removed.</p>


```csharp
public event EventHandler ElevationProfileGraphRemoved
```
### Export(ExportFormat)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Export a mapview to a variety of formats. The current camera position is used when exporting the view. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public void Export(ExportFormat exportFormat)
```
### Export(ExportFormat, Envelope)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Export a mapview to a variety of formats. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public void Export(ExportFormat exportFormat, Envelope extent)
```
### Export(ExportFormat, Camera)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Export a mapview to a variety of formats. This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public void Export(ExportFormat exportFormat, Camera camera)
```
### ExportScene3DObjects(ExportSceneContentsFormat)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Exports the scene contents to an exchange format.Supported export formats: glTF and stereolithography(STL).</p>


```csharp
public void ExportScene3DObjects(ExportSceneContentsFormat exportFormat)
```
### Extent

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Gets the current extent of the view.</p>


```csharp
public Envelope Extent { get; }
```
### FieldOfView

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Gets the field of view angle of the scene view.</p>


```csharp
public double FieldOfView { get; }
```
### FlashFeature(BasicFeatureLayer, long)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Flash a feature in the view.</p>


```csharp
public void FlashFeature(BasicFeatureLayer layer, long objectID)
```
### FlashFeature(BasicFeatureLayer, long, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Flash a feature in the view.</p>


```csharp
public void FlashFeature(BasicFeatureLayer layer, long objectID, bool showCrosshair)
```
### FlashFeature(SelectionSet)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Flash one or more features in the view simultaneously.</p>


```csharp
public void FlashFeature(SelectionSet features)
```
### FlashFeature(SelectionSet, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Flash one or more features in the view simultaneously.</p>


```csharp
public void FlashFeature(SelectionSet features, bool showCrosshair)
```
### FloorFilter

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Gets or sets the floor filter settings which determine which floor-aware data is visible in the map view.</p>


```csharp
public CIMFloorFilterSettings FloorFilter { get; set; }
```
### GetCameraEffect()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Returns the CIMCameraEffect object for the active 3D View.</p>


```csharp
public CIMCameraEffect GetCameraEffect()
```
### GetElevationProfileGraph()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Gets the elevation profile graph for the mapView. This may return null if no elevation profile graph is visible.</p>


```csharp
public ElevationProfileGraph GetElevationProfileGraph()
```
### GetExploratoryAnalysisCollection()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Get a list of the Exploratory Analysis objects that exist
for this MapView.  You can check each object's type to identify
which subclass it is.</p>


```csharp
public IReadOnlyCollection<ExploratoryAnalysis> GetExploratoryAnalysisCollection()
```
### GetFeatures(Geometry, bool, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Return features that intersect a geometry. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SelectionSet GetFeatures(Geometry geometry, bool visualIntersect = true, bool whollyWithin = false)
```
### GetFeaturesEx(Geometry, bool, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Return features that intersect a geometry. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SelectionSet GetFeaturesEx(Geometry geometry, bool visualIntersect = true, bool whollyWithin = false)
```
### GetOverlayControls()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Get all the current overlay controls.</p>


```csharp
public IReadOnlyCollection<UIElement> GetOverlayControls()
```
### GetPostprocessingEffects()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Returns an array of active CIMPostprocessingEffect objects for the active 3D View.</p>


```csharp
public CIMPostprocessingEffect[] GetPostprocessingEffects()
```
### GetSelectedDataSourceMember()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Returns the selected DataSourceMember.</p>


```csharp
public DataSourceMember GetSelectedDataSourceMember()
```
### GetSelectedElevationSourceLayers()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Returns the collection of elevation source layers selected in the TOC.</p>


```csharp
public IReadOnlyList<Layer> GetSelectedElevationSourceLayers()
```
### GetSelectedElevationSurfaceLayers()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Returns the collection of elevation surface layers selected in the TOC.</p>


```csharp
public IReadOnlyList<ElevationSurfaceLayer> GetSelectedElevationSurfaceLayers()
```
### GetSelectedIsosurfaces()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Returns the collection of voxel isosurfaces selected in the TOC.</p>


```csharp
public IReadOnlyList<IsosurfaceDefinition> GetSelectedIsosurfaces()
```
### GetSelectedLayers()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Returns the collection of layers selected in the TOC.</p>


```csharp
public IReadOnlyList<Layer> GetSelectedLayers()
```
### GetSelectedLegendClasses()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Returns the collection of legend classes selected in the TOC.</p>


```csharp
public IReadOnlyList<LegendClass> GetSelectedLegendClasses()
```
### GetSelectedLockedSections()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Returns the collection of voxel locked sections selected in the TOC.</p>


```csharp
public IReadOnlyList<LockedSectionDefinition> GetSelectedLockedSections()
```
### GetSelectedSections()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Returns the collection of voxel sections selected in the TOC.</p>


```csharp
public IReadOnlyList<SectionDefinition> GetSelectedSections()
```
### GetSelectedSlices()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Returns the collection of voxel slices selected in the TOC.</p>


```csharp
public IReadOnlyList<SliceDefinition> GetSelectedSlices()
```
### GetSelectedStandaloneTables()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Returns the collection of tables selected in the TOC.</p>


```csharp
public IReadOnlyList<StandaloneTable> GetSelectedStandaloneTables()
```
### GetStereoAllFeaturesAreVisible()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Gets whether features are visible or not in stereo views.</p>


```csharp
public bool GetStereoAllFeaturesAreVisible()
```
### GetStereoAllFeedbackIsVisible()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Gets whether the sketch feedback is visible or not in stereo views.</p>


```csharp
public bool GetStereoAllFeedbackIsVisible()
```
### GetStereoAllSelectionIsVisible()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Gets whether the selection highlight is visible or not in stereo views.</p>


```csharp
public bool GetStereoAllSelectionIsVisible()
```
### GetStereoCursorPosition()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Gets the current stereo cursor position as a map point.</p>


```csharp
public MapPoint GetStereoCursorPosition()
```
### GetViewSize()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Returns the current size of the view.</p>


```csharp
public Size GetViewSize()
```
### GetVisualEffect()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Returns the CIMVisualEffect object for the active 3D View.</p>


```csharp
public CIMVisualEffect GetVisualEffect()
```
### HasNextCamera()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Indicates whether the map view has a next camera position.</p>


```csharp
public bool HasNextCamera()
```
### HasPreviousCamera()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Indicates whether the map view has a previous camera position.</p>


```csharp
public bool HasPreviousCamera()
```
### Invalidate(Layer, Envelope)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Invalidates an area of layer.</p>


```csharp
public void Invalidate(Layer layer, Envelope extent)
```
### Invalidate(SelectionSet)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Invalidates the features of layers.</p>


```csharp
public void Invalidate(SelectionSet features)
```
### IsLinkChartView

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Gets whether the MapView is a link chart view</p>


```csharp
public bool IsLinkChartView { get; }
```
### IsReady

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Gets a value that indicates whether the MapView can be accessed.
<remarks>This property is false while the map view processes major operations like initializing or when a 3D view changes between SceneLocal and SceneGlobal.</remarks></p>


```csharp
public bool IsReady { get; }
```
### IsStereoCursorFixed

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Gets a value indicating whether the cursor of the stereo model is fixed.</p>


```csharp
public bool IsStereoCursorFixed { get; }
```
### LinkMode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Gets or sets the method used to link views.</p>


```csharp
public static LinkMode LinkMode { get; set; }
```
### LocatorManager

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Gets the locator manager attached to this mapview.</p>


```csharp
public LocatorManager LocatorManager { get; }
```
### LookAt(MapPoint, TimeSpan?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Center the view at a given point. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool LookAt(MapPoint mapPoint, TimeSpan? duration = null)
```
### LookAtAsync(MapPoint, TimeSpan?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Center the view at a given point.</p>


```csharp
public Task<bool> LookAtAsync(MapPoint mapPoint, TimeSpan? duration = null)
```
### LookAtCamera

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Gets the current look at Camera of the view.</p>


```csharp
public Camera LookAtCamera { get; }
```
### Map

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Gets the map or scene associated with the view.</p>


```csharp
public Map Map { get; }
```
### MapToClient(MapPoint)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Converts a point in the coordinates of the map or scene to a point in client coordinates relative to the top-left corner of the view. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Point MapToClient(MapPoint mapPoint)
```
### MapToScreen(MapPoint)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Converts a point in the coordinates of the map or scene to a point in screen coordinates. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Point MapToScreen(MapPoint mapPoint)
```
### NextCamera(TimeSpan?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Go to the next camera position. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool NextCamera(TimeSpan? duration = null)
```
### NextCameraAsync(TimeSpan?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Go to the next camera position.</p>


```csharp
public Task<bool> NextCameraAsync(TimeSpan? duration = null)
```
### PanTo(Geometry, TimeSpan?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Pan the view to the extent defined by a geometry. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool PanTo(Geometry geometry, TimeSpan? duration = null)
```
### PanTo(BasicFeatureLayer, IEnumerable&lt;long&gt;, TimeSpan?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Pan the view to the extent of one or more features. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool PanTo(BasicFeatureLayer layer, IEnumerable<long> objectIDs, TimeSpan? duration = null)
```
### PanTo(BasicFeatureLayer, long, TimeSpan?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Pan the view to the extent of a feature. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool PanTo(BasicFeatureLayer layer, long objectID, TimeSpan? duration = null)
```
### PanTo(Bookmark, TimeSpan?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Pan the view to the position defined in a bookmark. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool PanTo(Bookmark bookmark, TimeSpan? duration = null)
```
### PanTo(Camera, TimeSpan?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Pan the view to a camera position. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool PanTo(Camera camera, TimeSpan? duration = null)
```
### PanTo(Layer, bool, TimeSpan?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Pan the view to the extent of a layer. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool PanTo(Layer layer, bool selectedOnly = false, TimeSpan? duration = null)
```
### PanTo(SelectionSet, TimeSpan?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Zoom the view to the extent of one or more features. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool PanTo(SelectionSet features, TimeSpan? duration = null)
```
### PanTo(IEnumerable&lt;Layer&gt;, bool, TimeSpan?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Pan the view to the extent of one or more layers. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool PanTo(IEnumerable<Layer> layers, bool selectedOnly = false, TimeSpan? duration = null)
```
### PanToAsync(Geometry, TimeSpan?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Pan the view to the extent defined by a geometry.</p>


```csharp
public Task<bool> PanToAsync(Geometry geometry, TimeSpan? duration = null)
```
### PanToAsync(BasicFeatureLayer, IEnumerable&lt;long&gt;, TimeSpan?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Pan the view to the extent of one or more features.</p>


```csharp
public Task<bool> PanToAsync(BasicFeatureLayer layer, IEnumerable<long> objectIDs, TimeSpan? duration = null)
```
### PanToAsync(BasicFeatureLayer, long, TimeSpan?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Pan the view to the extent of a feature.</p>


```csharp
public Task<bool> PanToAsync(BasicFeatureLayer layer, long objectID, TimeSpan? duration = null)
```
### PanToAsync(Bookmark, TimeSpan?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Pan the view to the position defined in a bookmark.</p>


```csharp
public Task<bool> PanToAsync(Bookmark bookmark, TimeSpan? duration = null)
```
### PanToAsync(Camera, TimeSpan?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Pan the view to a camera position.</p>


```csharp
public Task<bool> PanToAsync(Camera camera, TimeSpan? duration = null)
```
### PanToAsync(Layer, bool, TimeSpan?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Pan the view to the extent of a layer.</p>


```csharp
public Task<bool> PanToAsync(Layer layer, bool selectedOnly = false, TimeSpan? duration = null)
```
### PanToAsync(SelectionSet, TimeSpan?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Zoom the view to the extent of one or more features.</p>


```csharp
public Task<bool> PanToAsync(SelectionSet features, TimeSpan? duration = null)
```
### PanToAsync(IEnumerable&lt;Layer&gt;, bool, TimeSpan?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Pan the view to the extent of one or more layers.</p>


```csharp
public Task<bool> PanToAsync(IEnumerable<Layer> layers, bool selectedOnly = false, TimeSpan? duration = null)
```
### PanToSelected(TimeSpan?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Pan the view to the extent of the selected features in the map or scene. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool PanToSelected(TimeSpan? duration = null)
```
### PanToSelectedAsync(TimeSpan?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Pan the view to the extent of the selected features in the map or scene.</p>


```csharp
public Task<bool> PanToSelectedAsync(TimeSpan? duration = null)
```
### PreviousCamera(TimeSpan?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Go to the previous camera position. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool PreviousCamera(TimeSpan? duration = null)
```
### PreviousCameraAsync(TimeSpan?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Go to the previous camera position.</p>


```csharp
public Task<bool> PreviousCameraAsync(TimeSpan? duration = null)
```
### Print()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Print a mapview using default printer settings.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Print()
```
### Print(PrinterSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Print the mapview using the specified settings.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
[Obsolete("Deprecated at 3.5. Please use Print(PrinterSettingsInfo) instead")]
public void Print(PrinterSettings printerSettings)
```
### Print(PrinterSettingsInfo)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Print a mapview using the specified settings.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Print(PrinterSettingsInfo printerSettingsInfo)
```
### Range

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Gets or sets the range extent visible in the map view.</p>


```csharp
public RangeExtent Range { get; set; }
```
### RangeNames

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Gets the range names defined on layers in the map view.</p>


```csharp
public List<string> RangeNames { get; }
```
### Redraw(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Force a redraw of the map view. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Redraw(bool clearCache)
```
### RedrawAsync(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Force a redraw of the map view</p>


```csharp
public Task RedrawAsync(bool clearCache)
```
### RemoveExploratoryAnalysisAsync(ExploratoryAnalysis)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Removes the provided ExploratoryAnalysisBase instance from the MapView.  It
will no longer be tracked or drawn in the view.  The parameter provided should be
destroyed after it has been removed to avoid errors or confusion.</p>


```csharp
public Task RemoveExploratoryAnalysisAsync(ExploratoryAnalysis item)
```
### RemoveOverlayControl(IMapViewOverlayControl)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Remove a control from over the view.</p>


```csharp
public bool RemoveOverlayControl(IMapViewOverlayControl overlayControl)
```
### SceneDrawingMode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Gets the current drawing mode of the scene view.</p>


```csharp
public SceneDrawingMode SceneDrawingMode { get; }
```
### ScreenToClient(Point)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Converts a point in client coordinates relative to the top-left corner of the view to a screen point.</p>


```csharp
public Point ScreenToClient(Point screenPoint)
```
### ScreenToMap(Point)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Converts a point in screen coordinates to a point in the coordinates of the map or scene. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public MapPoint ScreenToMap(Point screenPoint)
```
### SelectDataSourceMember(DataSourceMember)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Selects the DataSourceMember in the TOC.</p>


```csharp
public void SelectDataSourceMember(DataSourceMember dataSourceMember)
```
### SelectElements(Geometry, SelectionCombinationMethod, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Select elements that visually intersect a geometry.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SelectElements(Geometry geometry, SelectionCombinationMethod method, bool isWhollyWithin)
```
### SelectElevationSourceLayers(IReadOnlyCollection&lt;Layer&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Selects elevation source layers in the TOC.</p>


```csharp
public void SelectElevationSourceLayers(IReadOnlyCollection<Layer> elevationSourceLayers)
```
### SelectElevationSurfaceLayers(IReadOnlyCollection&lt;ElevationSurfaceLayer&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Selects elevation surface layers in the TOC.</p>


```csharp
public void SelectElevationSurfaceLayers(IReadOnlyCollection<ElevationSurfaceLayer> elevationSurfaceLayers)
```
### SelectFeatures(Geometry, SelectionCombinationMethod, bool, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Select features that intersect a geometry. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SelectionSet SelectFeatures(Geometry geometry, SelectionCombinationMethod method = SelectionCombinationMethod.New, bool isVisualIntersect = true, bool isWhollyWithin = false)
```
### SelectFeaturesEx(Geometry, SelectionCombinationMethod, bool, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Select features that intersect a geometry. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SelectionSet SelectFeaturesEx(Geometry geometry, SelectionCombinationMethod method = SelectionCombinationMethod.New, bool isVisualIntersect = true, bool isWhollyWithin = false)
```
### SelectLayers(IReadOnlyCollection&lt;Layer&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Selects layers in the TOC.</p>


```csharp
public void SelectLayers(IReadOnlyCollection<Layer> layers)
```
### SelectLegendClasses(IReadOnlyCollection&lt;LegendClass&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Selects legend classes in the TOC.</p>


```csharp
public void SelectLegendClasses(IReadOnlyCollection<LegendClass> legendClasses)
```
### SelectStandaloneTables(IReadOnlyCollection&lt;StandaloneTable&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Selects standalone tables in the TOC.</p>


```csharp
public void SelectStandaloneTables(IReadOnlyCollection<StandaloneTable> standaloneTables)
```
### SelectVoxelIsosurface(IsosurfaceDefinition)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Selects the voxel isosurface in the TOC.</p>


```csharp
public void SelectVoxelIsosurface(IsosurfaceDefinition isosurface)
```
### SelectVoxelLockedSection(LockedSectionDefinition)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Selects the voxel locked section in the TOC.</p>


```csharp
public void SelectVoxelLockedSection(LockedSectionDefinition section)
```
### SelectVoxelSection(SectionDefinition)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Selects the voxel section in the TOC.</p>


```csharp
public void SelectVoxelSection(SectionDefinition section)
```
### SelectVoxelSlice(SliceDefinition)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Selects the voxel slice in the TOC.</p>


```csharp
public void SelectVoxelSlice(SliceDefinition slice)
```
### SetActiveRangeName(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Sets the active range name for the map view.</p>


```csharp
public Task SetActiveRangeName(string rangeName)
```
### SetCameraEffect(CIMCameraEffect)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Sets the Camera Effect for the active 3D View. Only works on 3D Views.</p>


```csharp
public void SetCameraEffect(CIMCameraEffect cameraEffect)
```
### SetCursorPosition(MapPoint)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Set the cursor position to the specified map point.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetCursorPosition(MapPoint mapPoint)
```
### SetCursorPosition(Point)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Set the cursor position to the specified client point.</p>


```csharp
public void SetCursorPosition(Point clientPoint)
```
### SetFieldOfView(double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Sets the field of view angle of the scene view.</p>


```csharp
public void SetFieldOfView(double fieldOfView)
```
### SetMapTOCContentAsync(MapTOCContentType)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Sets the map TOC content type on the active TOC. This method must be called
on the UI thread.</p>


```csharp
public void SetMapTOCContentAsync(MapTOCContentType mapTOCContentType)
```
### SetPostprocessingEffects(CIMPostprocessingEffect[])

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Set the Postprocessing Effects for the active 3D View. Only works on 3D Views.
Can set multiple effects simultaneously by adding them to the array being passed in.</p>


```csharp
public void SetPostprocessingEffects(CIMPostprocessingEffect[] postprocessingEffects)
```
### SetSceneDrawingMode(SceneDrawingMode)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Sets the perspective of the scene view.</p>


```csharp
public void SetSceneDrawingMode(SceneDrawingMode drawingMode)
```
### SetStereoAllFeaturesVisible(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Set the feature visibility for stereo views.</p>


```csharp
public void SetStereoAllFeaturesVisible(bool visible)
```
### SetStereoAllFeedbackVisible(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Set the sketch feedback visibility for stereo views.</p>


```csharp
public void SetStereoAllFeedbackVisible(bool visible)
```
### SetStereoAllSelectionVisible(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Set the selection highlight visibility for stereo views.</p>


```csharp
public void SetStereoAllSelectionVisible(bool visible)
```
### SetStereoCursorMode(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Sets the stereo model's cursor to either fixed or floating states.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetStereoCursorMode(bool cursorFixed)
```
### SetViewingMode(MapViewingMode)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Set the perspective of the map view. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetViewingMode(MapViewingMode viewingMode)
```
### SetViewingModeAsync(MapViewingMode)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Set the perspective of the map view..</p>


```csharp
public Task SetViewingModeAsync(MapViewingMode viewingMode)
```
### SetVisualEffect(CIMVisualEffect)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Sets the Visual Effect for the active 3D View. Only works on 3D Views.</p>


```csharp
public void SetVisualEffect(CIMVisualEffect visualEffect)
```
### ShowCustomPopup(IEnumerable&lt;PopupContent&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Show a custom pop-up. This method must be called on the UI thread.</p>


```csharp
public void ShowCustomPopup(IEnumerable<PopupContent> popupContent)
```
### ShowCustomPopup(IEnumerable&lt;PopupContent&gt;, IEnumerable&lt;PopupCommand&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Show a custom pop-up. This method must be called on the UI thread.</p>


```csharp
public void ShowCustomPopup(IEnumerable<PopupContent> popupContent, IEnumerable<PopupCommand> commands, bool includeDefaultCommands)
```
### ShowCustomPopup(IEnumerable&lt;PopupContent&gt;, IEnumerable&lt;PopupCommand&gt;, bool, PopupDefinition)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Show a custom pop-up. This method must be called on the UI thread.</p>


```csharp
public void ShowCustomPopup(IEnumerable<PopupContent> popupContent, IEnumerable<PopupCommand> commands, bool includeDefaultCommands, PopupDefinition popupDef)
```
### ShowElevationProfileGraph(MapPoint, MapPoint, int, ElevationProfileParameters)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Shows an elevation profile of the line calculated between <code class="paramref">startPoint</code> and <code class="paramref">endPoint</code>.
Intermediate points are calculated at equal distances between the end points according to the <code class="paramref">numPoints</code> specified.
The calculation is performed according to the <code class="paramref">profileParameters</code>
specified.   The <code class="paramref">profileParameters</code> allows you to specify the elevation surface layer the calculation is performed
against along with whether the generated elevation profile line is densified.</p>


```csharp
public void ShowElevationProfileGraph(MapPoint startPoint, MapPoint endPoint, int numPoints, ElevationProfileParameters profileParameters = null)
```
### ShowElevationProfileGraph(ElevationProfileResult)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Shows the elevation profile of the specified ElevationProfileResult.  An ElevationProfileResult is obtained
from a Map.GetElevationProfileFromSurface function call.  The Z values of the geometry of the
<code class="paramref">elevationProfile</code> is displayed as-is; no additional Z calculations are performed.</p>


```csharp
public void ShowElevationProfileGraph(ElevationProfileResult elevationProfile)
```
### ShowElevationProfileGraph(MapMember, IEnumerable&lt;long&gt;, ElevationProfileParameters)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Shows an elevation profile of a set of line features.  The calculation is performed according to the <code class="paramref">profileParameters</code>
specified.   The <code class="paramref">profileParameters</code> allows you to specify the elevation surface layer the calculation is performed
against along with whether the generated elevation profile line is densified.</p>


```csharp
public void ShowElevationProfileGraph(MapMember lineLayer, IEnumerable<long> oids, ElevationProfileParameters profileParameters = null)
```
### ShowElevationProfileGraph(IEnumerable&lt;MapPoint&gt;, ElevationProfileParameters)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Shows an elevation profile of a collection of points. The calculation is performed according to the <code class="paramref">profileParameters</code>
specified.   The <code class="paramref">profileParameters</code> allows you to specify the elevation surface layer the calculation is performed
against along with whether the generated elevation profile line is densified.</p>


```csharp
public void ShowElevationProfileGraph(IEnumerable<MapPoint> pts, ElevationProfileParameters profileParameters = null)
```
### ShowElevationProfileGraph(IEnumerable&lt;Polyline&gt;, ElevationProfileParameters)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Shows an elevation profile of a collection of polylines.  The calculation is performed according to the <code class="paramref">profileParameters</code>
specified.   The <code class="paramref">profileParameters</code> allows you to specify the elevation surface layer the calculation is performed
against along with whether the generated elevation profile line is densified.</p>


```csharp
public void ShowElevationProfileGraph(IEnumerable<Polyline> polylines, ElevationProfileParameters profileParameters = null)
```
### ShowPopup(MapMember, long)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Show a pop-up for a feature. This method must be called on the UI thread.</p>


```csharp
public void ShowPopup(MapMember mapMember, long featureID)
```
### ShowPopup(MapMember, long, PopupDefinition)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Show a pop-up for a feature. This method must be called on the UI thread.</p>


```csharp
public void ShowPopup(MapMember mapMember, long featureID, PopupDefinition popupDef)
```
### ShowPopup(SelectionSet)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Show a pop-up for multiple features. This method must be called on the UI thread.</p>


```csharp
public void ShowPopup(SelectionSet features)
```
### ShowPopup(SelectionSet, PopupDefinition)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Show a pop-up for multiple features. This method must be called on the UI thread.</p>


```csharp
public void ShowPopup(SelectionSet features, PopupDefinition popupDef)
```
### Time

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Gets or sets the time range visible in the map view.</p>


```csharp
public TimeRange Time { get; set; }
```
### ViewSizeChanged

- Kind: event

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Occurs when the view size changed. Use <xref href="ArcGIS.Desktop.Mapping.MapView.GetViewSize" data-throw-if-not-resolved="false"></xref> to get the size.</p>


```csharp
public event EventHandler ViewSizeChanged
```
### ViewingMode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Gets the perspective of the view.</p>


```csharp
public MapViewingMode ViewingMode { get; }
```
### ZoomInFixed(TimeSpan?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Zoom the Camera in by a fixed amount. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool ZoomInFixed(TimeSpan? duration = null)
```
### ZoomInFixedAsync(TimeSpan?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Zoom the Camera in by a fixed amount.</p>


```csharp
public Task<bool> ZoomInFixedAsync(TimeSpan? duration = null)
```
### ZoomOutFixed(TimeSpan?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Zoom the Camera out by a fixed amount. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool ZoomOutFixed(TimeSpan? duration = null)
```
### ZoomOutFixedAsync(TimeSpan?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Zoom the Camera out by a fixed amount.</p>


```csharp
public Task<bool> ZoomOutFixedAsync(TimeSpan? duration = null)
```
### ZoomTo(Geometry, TimeSpan?, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Zoom the view to the extent defined by a geometry. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool ZoomTo(Geometry geometry, TimeSpan? duration = null, bool maintainViewDirection = false)
```
### ZoomTo(BasicFeatureLayer, IEnumerable&lt;long&gt;, TimeSpan?, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Zoom the view to the extent of one or more features. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool ZoomTo(BasicFeatureLayer layer, IEnumerable<long> objectIDs, TimeSpan? duration = null, bool maintainViewDirection = false)
```
### ZoomTo(BasicFeatureLayer, long, TimeSpan?, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Zoom the view to the extent of a feature. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool ZoomTo(BasicFeatureLayer layer, long objectID, TimeSpan? duration = null, bool maintainViewDirection = false)
```
### ZoomTo(BasicFeatureLayer, long, TimeSpan?, bool, double?, double?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Zoom the view to the extent of a feature.</p>


```csharp
public bool ZoomTo(BasicFeatureLayer layer, long objectID, TimeSpan? duration, bool maintainViewDirection, double? factor, double? mapScaleOrDistance)
```
### ZoomTo(Bookmark, TimeSpan?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Zoom the view to the position defined in a bookmark. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool ZoomTo(Bookmark bookmark, TimeSpan? duration = null)
```
### ZoomTo(Camera, TimeSpan?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Zoom the view to a camera position. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool ZoomTo(Camera camera, TimeSpan? duration = null)
```
### ZoomTo(Layer, bool, TimeSpan?, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Zoom the view to the extent of a layer. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool ZoomTo(Layer layer, bool selectedOnly = false, TimeSpan? duration = null, bool maintainViewDirection = false)
```
### ZoomTo(SelectionSet, TimeSpan?, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Zoom the view to the extent of one or more features. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool ZoomTo(SelectionSet features, TimeSpan? duration = null, bool maintainViewDirection = false)
```
### ZoomTo(IEnumerable&lt;Layer&gt;, bool, TimeSpan?, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Zoom the view to the extent of one or more layers. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool ZoomTo(IEnumerable<Layer> layers, bool selectedOnly = false, TimeSpan? duration = null, bool maintainViewDirection = false)
```
### ZoomToAsync(Geometry, TimeSpan?, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Zoom the view to the extent defined by a geometry.</p>


```csharp
public Task<bool> ZoomToAsync(Geometry geometry, TimeSpan? duration = null, bool maintainViewDirection = false)
```
### ZoomToAsync(BasicFeatureLayer, IEnumerable&lt;long&gt;, TimeSpan?, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Zoom the view to the extent of one or more features.</p>


```csharp
public Task<bool> ZoomToAsync(BasicFeatureLayer layer, IEnumerable<long> objectIDs, TimeSpan? duration = null, bool maintainViewDirection = false)
```
### ZoomToAsync(BasicFeatureLayer, long, TimeSpan?, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Zoom the view to the extent of a feature.</p>


```csharp
public Task<bool> ZoomToAsync(BasicFeatureLayer layer, long objectID, TimeSpan? duration = null, bool maintainViewDirection = false)
```
### ZoomToAsync(BasicFeatureLayer, long, TimeSpan?, bool, double?, double?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Zoom the view to the extent of a feature.</p>


```csharp
public Task<bool> ZoomToAsync(BasicFeatureLayer layer, long objectID, TimeSpan? duration, bool maintainViewDirection, double? factor, double? mapScaleOrDistance)
```
### ZoomToAsync(Bookmark, TimeSpan?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Zoom the view to the position defined in a bookmark.</p>


```csharp
public Task<bool> ZoomToAsync(Bookmark bookmark, TimeSpan? duration = null)
```
### ZoomToAsync(Camera, TimeSpan?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Zoom the view to a camera position.</p>


```csharp
public Task<bool> ZoomToAsync(Camera camera, TimeSpan? duration = null)
```
### ZoomToAsync(Layer, bool, TimeSpan?, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Zoom the view to the extent of a layer.</p>


```csharp
public Task<bool> ZoomToAsync(Layer layer, bool selectedOnly = false, TimeSpan? duration = null, bool maintainViewDirection = false)
```
### ZoomToAsync(SelectionSet, TimeSpan?, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Zoom the view to the extent of one or more features.</p>


```csharp
public Task<bool> ZoomToAsync(SelectionSet features, TimeSpan? duration = null, bool maintainViewDirection = false)
```
### ZoomToAsync(IEnumerable&lt;Layer&gt;, bool, TimeSpan?, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Zoom the view to the extent of one or more layers.</p>


```csharp
public Task<bool> ZoomToAsync(IEnumerable<Layer> layers, bool selectedOnly = false, TimeSpan? duration = null, bool maintainViewDirection = false)
```
### ZoomToFullExtent(TimeSpan?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Zoom the view to the full extent of the map or scene. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool ZoomToFullExtent(TimeSpan? duration = null)
```
### ZoomToFullExtentAsync(TimeSpan?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Zoom the view to the full extent of the map or scene.</p>


```csharp
public Task<bool> ZoomToFullExtentAsync(TimeSpan? duration = null)
```
### ZoomToSelected(TimeSpan?, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Zoom the view to the extent of the selected features in the map or scene. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool ZoomToSelected(TimeSpan? duration = null, bool maintainViewDirection = false)
```
### ZoomToSelectedAsync(TimeSpan?, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapView.yml" sourcestartlinenumber="1">Zoom the view to the extent of the selected features in the map or scene.</p>


```csharp
public Task<bool> ZoomToSelectedAsync(TimeSpan? duration = null, bool maintainViewDirection = false)
```


