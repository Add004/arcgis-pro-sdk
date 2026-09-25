# MapTool

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Extensions.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Represents a tool command used to perform interactive operations on a <xref href="ArcGIS.Desktop.Mapping.MapView" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public abstract class MapTool : Tool
```

## Remarks

<p>This base class can be used to create tools to interactively identify and select features in the view or to create custom construction and editing tools. 
    It provides virtual methods that can be overridden to perform actions when keyboard and mouse events occur in the map view, such 
    as <xref href="ArcGIS.Desktop.Mapping.MapTool.OnToolMouseDown(ArcGIS.Desktop.Mapping.MapViewMouseButtonEventArgs)" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Desktop.Mapping.MapTool.OnToolKeyDown(ArcGIS.Desktop.Mapping.MapViewKeyEventArgs)" data-throw-if-not-resolved="false"></xref>. When overriding mouse and keyboard virtual methods if you need to execute any asynchronous code 
    first set the handled property on the event arguments to true, override the corresponding "Handle...Async" method,
    and add your asynchronous code.</p>
<p>By setting the <xref href="ArcGIS.Desktop.Mapping.MapTool.IsSketchTool" data-throw-if-not-resolved="false"></xref> property to true, the tool will create a sketch in the map view with a left mouse click.
    Use the <xref href="ArcGIS.Desktop.Mapping.MapTool.SketchType" data-throw-if-not-resolved="false"></xref> property to set the geometry type of the sketch and use the 
    <xref href="ArcGIS.Desktop.Mapping.MapTool.SketchOutputMode" data-throw-if-not-resolved="false"></xref> property to specify whether the sketch geometry is in screen or map coordinates.
    Override <xref href="ArcGIS.Desktop.Mapping.MapTool.OnSketchCompleteAsync(ArcGIS.Core.Geometry.Geometry)" data-throw-if-not-resolved="false"></xref> to add behavior to the tool when the sketch is finished.</p>


## Members

### MapTool()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Default constructor for MapTool.</p>


```csharp
public MapTool()
```
### ActivateSelectAsync(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Toggles the tool between sketch and selection modes.
Only supported when <xref href="ArcGIS.Desktop.Mapping.MapTool.SketchType" data-throw-if-not-resolved="false"></xref> is set to Point, Line, Polygon, or Multipoint.</p>


```csharp
protected Task<bool> ActivateSelectAsync(bool activate)
```
### ActiveMapView

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Gets the active <xref href="ArcGIS.Desktop.Mapping.MapView" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
protected MapView ActiveMapView { get; }
```
### AddOverlay(CIMGraphic, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Add an overlay graphic to the map view.</p>


```csharp
protected IDisposable AddOverlay(CIMGraphic graphic, double referenceScale = -1)
```
### AddOverlay(CIMGraphic, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Add an overlay graphic to the map view.</p>


```csharp
protected IDisposable AddOverlay(CIMGraphic graphic, double referenceScale, double showThrough)
```
### AddOverlay(Geometry, CIMSymbolReference, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Add an overlay graphic to the map view.</p>


```csharp
protected IDisposable AddOverlay(Geometry geometry, CIMSymbolReference symbol = null, double referenceScale = -1)
```
### AddOverlay(Geometry, CIMSymbolReference, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Add an overlay graphic to the map view.</p>


```csharp
protected IDisposable AddOverlay(Geometry geometry, CIMSymbolReference symbol, double referenceScale, double showThrough)
```
### AddOverlay(Layer, long, CIMSymbolReference, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Add an overlay graphic for a feature on the map view.</p>


```csharp
protected IDisposable AddOverlay(Layer layer, long oid, CIMSymbolReference symbol = null, double referenceScale = -1)
```
### AddOverlay(IEnumerable&lt;CIMGraphic&gt;, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Add a set of overlay graphics to the map view.</p>


```csharp
protected IDisposable AddOverlay(IEnumerable<CIMGraphic> graphics, double referenceScale = -1)
```
### AddOverlay(IEnumerable&lt;CIMGraphic&gt;, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Add a set of overlay graphics to the map view.</p>


```csharp
protected IDisposable AddOverlay(IEnumerable<CIMGraphic> graphics, double referenceScale, double showThrough)
```
### AddOverlayAsync(CIMGraphic, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Add an overlay graphic to the map view.</p>


```csharp
protected Task<IDisposable> AddOverlayAsync(CIMGraphic graphic, double referenceScale = -1)
```
### AddOverlayAsync(CIMGraphic, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Add an overlay graphic to the map view.</p>


```csharp
protected Task<IDisposable> AddOverlayAsync(CIMGraphic graphic, double referenceScale, double showThrough)
```
### AddOverlayAsync(Geometry, CIMSymbolReference, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Add an overlay graphic to the map view.</p>


```csharp
protected Task<IDisposable> AddOverlayAsync(Geometry geometry, CIMSymbolReference symbol = null, double referenceScale = -1)
```
### AddOverlayAsync(Geometry, CIMSymbolReference, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Add an overlay graphic to the map view.</p>


```csharp
protected Task<IDisposable> AddOverlayAsync(Geometry geometry, CIMSymbolReference symbol, double referenceScale, double showThrough)
```
### AddOverlayAsync(Layer, long, CIMSymbolReference, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Add an overlay graphic for a feature on the map view.</p>


```csharp
protected Task<IDisposable> AddOverlayAsync(Layer layer, long oid, CIMSymbolReference symbol = null, double referenceScale = -1)
```
### AddOverlayAsync(IEnumerable&lt;CIMGraphic&gt;, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Add a set of overlay graphics to the map view.</p>


```csharp
protected Task<IDisposable> AddOverlayAsync(IEnumerable<CIMGraphic> graphics, double referenceScale = -1)
```
### AddOverlayAsync(IEnumerable&lt;CIMGraphic&gt;, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Add a set of overlay graphics to the map view.</p>


```csharp
protected Task<IDisposable> AddOverlayAsync(IEnumerable<CIMGraphic> graphics, double referenceScale, double showThrough)
```
### ClearSketchAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Clears the current sketch in the active map view.</p>


```csharp
protected Task ClearSketchAsync()
```
### CompleteSketchOnMouseUp

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Gets or sets the mouse up behavior for Rectangle/Circle/Ellipse/Freehand sketches.</p>


```csharp
protected bool? CompleteSketchOnMouseUp { get; set; }
```
### ContextMenuID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Gets or sets the DAML ID of the context menu for the tool.</p>


```csharp
protected string ContextMenuID { get; set; }
```
### ContextToolbarID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Gets or sets the DAML ID of the toolbar to display for the tool.</p>


```csharp
protected string ContextToolbarID { get; set; }
```
### ControlID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Gets or sets the DAML ID of the embeddable control to show in the dock pane when the tool is active.</p>


```csharp
protected string ControlID { get; set; }
```
### CreateFeatureAsync(EditingTemplate, Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Creates a new EditOperation to create a feature using the given template and geometry.</p>


```csharp
protected Task<bool> CreateFeatureAsync(EditingTemplate template, Geometry geometry)
```
### CurrentTemplate

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Gets the active editing template being used by the tool.</p>


```csharp
protected EditingTemplate CurrentTemplate { get; }
```
### CurrentTemplateRows

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Gets or sets the number of rows to be created with the current template. Use this when the MapTool is registered with the
&quot;esri_editing_construction_table&quot; category indicating the tool is a table construction tool.</p>


```csharp
protected int CurrentTemplateRows { get; set; }
```
### EmbeddableControl

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Gets the EmbeddableControl created for the tool. This is the control set by the <xref href="ArcGIS.Desktop.Mapping.MapTool.ControlID" data-throw-if-not-resolved="false"></xref> property.</p>


```csharp
protected EmbeddableControl EmbeddableControl { get; }
```
### FinishSketchAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Finishes the current sketch in the active map view.</p>


```csharp
protected Task<bool> FinishSketchAsync()
```
### FireSketchEvents

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Gets or sets whether the tool supports firing sketch events when the map sketch changes.   Default value is false.</p>


```csharp
protected bool FireSketchEvents { get; set; }
```
### GeomIsSimpleAsFeature

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Gets or sets whether the geometry constructed from a finished sketch should be simplified prior to being returned to <xref href="ArcGIS.Desktop.Mapping.MapTool.OnSketchCompleteAsync(ArcGIS.Core.Geometry.Geometry)" data-throw-if-not-resolved="false"></xref>. The default value is true.</p>


```csharp
protected bool GeomIsSimpleAsFeature { get; set; }
```
### GetCurrentSketchAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Gets the current geometry of the sketch without finishing it.</p>


```csharp
protected Task<Geometry> GetCurrentSketchAsync()
```
### GetSketchSegmentSymbolOptions()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Gets the default segment sketching symbol information.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
protected SegmentSymbolOptions GetSketchSegmentSymbolOptions()
```
### GetSketchVertexSymbolOptions(VertexSymbolType)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Gets the symbol for a vertex while sketching.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
protected VertexSymbolOptions GetSketchVertexSymbolOptions(VertexSymbolType symbolType)
```
### HandleDoubleClickAsync(MapViewMouseButtonEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Occurs when the <xref href="ArcGIS.Desktop.Mapping.MapTool.OnToolDoubleClick(ArcGIS.Desktop.Mapping.MapViewMouseButtonEventArgs)" data-throw-if-not-resolved="false"></xref> event is handled.</p>


```csharp
protected virtual Task HandleDoubleClickAsync(MapViewMouseButtonEventArgs args)
```
### HandleKeyDownAsync(MapViewKeyEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Occurs when the <xref href="ArcGIS.Desktop.Mapping.MapTool.OnToolKeyDown(ArcGIS.Desktop.Mapping.MapViewKeyEventArgs)" data-throw-if-not-resolved="false"></xref> event is handled.</p>


```csharp
protected virtual Task HandleKeyDownAsync(MapViewKeyEventArgs args)
```
### HandleKeyUpAsync(MapViewKeyEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Occurs when the <xref href="ArcGIS.Desktop.Mapping.MapTool.OnToolKeyUp(ArcGIS.Desktop.Mapping.MapViewKeyEventArgs)" data-throw-if-not-resolved="false"></xref> event is handled.</p>


```csharp
protected virtual Task HandleKeyUpAsync(MapViewKeyEventArgs args)
```
### HandleMouseDownAsync(MapViewMouseButtonEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Occurs when the <xref href="ArcGIS.Desktop.Mapping.MapTool.OnToolMouseDown(ArcGIS.Desktop.Mapping.MapViewMouseButtonEventArgs)" data-throw-if-not-resolved="false"></xref> event is handled.</p>


```csharp
protected virtual Task HandleMouseDownAsync(MapViewMouseButtonEventArgs args)
```
### HandleMouseUpAsync(MapViewMouseButtonEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Occurs when the <xref href="ArcGIS.Desktop.Mapping.MapTool.OnToolMouseUp(ArcGIS.Desktop.Mapping.MapViewMouseButtonEventArgs)" data-throw-if-not-resolved="false"></xref> event is handled.</p>


```csharp
protected virtual Task HandleMouseUpAsync(MapViewMouseButtonEventArgs args)
```
### HandleOnPaneActivateAsync(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Called to inform the Tool a Pane referencing it as the active tool is activating or deactivating.</p>


```csharp
protected virtual Task HandleOnPaneActivateAsync(bool active)
```
### IsSketchTipControlTransparent

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Gets and sets if the sketch tip embeddable control is transparent. The default value is false.
The sketch tip embeddable control is the control set by the <xref href="ArcGIS.Desktop.Mapping.MapTool.SketchTipID" data-throw-if-not-resolved="false"></xref> property.</p>


```csharp
protected bool IsSketchTipControlTransparent { get; set; }
```
### IsSketchTool

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Gets or sets whether the MapTool's default behavior of a left click should be to create a sketch.</p>


```csharp
protected bool IsSketchTool { get; set; }
```
### IsWYSIWYG

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Gets or sets whether the sketch shows a symbol.</p>


```csharp
protected bool IsWYSIWYG { get; set; }
```
### KeepControlOpenAfterDeactivation

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Optional property to allow tool's embeddable control to remain open after the tool is deactivated.</p>


```csharp
protected bool KeepControlOpenAfterDeactivation { get; set; }
```
### OnCurrentTemplateUpdated()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Occurs when the current template is modified.</p>


```csharp
protected virtual void OnCurrentTemplateUpdated()
```
### OnSelectionChangedAsync(MapSelectionChangedEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Occurs when the selection changes in the map.</p>


```csharp
protected virtual Task OnSelectionChangedAsync(MapSelectionChangedEventArgs args)
```
### OnSketchCanceledAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Occurs when a sketch is canceled.</p>


```csharp
protected virtual Task<bool> OnSketchCanceledAsync()
```
### OnSketchCompleteAsync(Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Occurs when a sketch is finished.</p>


```csharp
protected virtual Task<bool> OnSketchCompleteAsync(Geometry geometry)
```
### OnSketchModifiedAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Occurs when a sketch is modified.</p>


```csharp
protected virtual Task<bool> OnSketchModifiedAsync()
```
### OnToolActivateAsync(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Occurs when the tool is activated.</p>


```csharp
protected virtual Task OnToolActivateAsync(bool hasMapViewChanged)
```
### OnToolDeactivateAsync(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Occurs when the tool is deactivated.</p>


```csharp
protected virtual Task OnToolDeactivateAsync(bool hasMapViewChanged)
```
### OnToolDoubleClick(MapViewMouseButtonEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Occurs when a mouse button is clicked on the view two or more times.</p>


```csharp
protected virtual void OnToolDoubleClick(MapViewMouseButtonEventArgs args)
```
### OnToolKeyDown(MapViewKeyEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Occurs when a key is pressed and the view has focus.</p>


```csharp
protected virtual void OnToolKeyDown(MapViewKeyEventArgs args)
```
### OnToolKeyUp(MapViewKeyEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Occurs when a key is released and the view has focus.</p>


```csharp
protected virtual void OnToolKeyUp(MapViewKeyEventArgs args)
```
### OnToolMouseDown(MapViewMouseButtonEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Occurs when a mouse button is pressed on the view.</p>


```csharp
protected virtual void OnToolMouseDown(MapViewMouseButtonEventArgs args)
```
### OnToolMouseMove(MapViewMouseEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Occurs when the mouse pointer moves over the view.</p>


```csharp
protected virtual void OnToolMouseMove(MapViewMouseEventArgs args)
```
### OnToolMouseUp(MapViewMouseButtonEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Occurs when a mouse button is released on the view.</p>


```csharp
protected virtual void OnToolMouseUp(MapViewMouseButtonEventArgs args)
```
### OnUpdate()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Called periodically by the framework once the tool has been created.</p>


```csharp
protected override void OnUpdate()
```
### OverlayControlCanResize

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Gets or sets whether the embeddable control on the map view can be resized.</p>


```csharp
protected bool OverlayControlCanResize { get; set; }
```
### OverlayControlID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Gets or sets the DAML ID of the embeddable control to show on the map view when the tool is active.</p>


```csharp
protected string OverlayControlID { get; set; }
```
### OverlayControlPositionRatio

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Gets or sets the position of the embeddable control on the map view as a ratio.</p>


```csharp
protected Point OverlayControlPositionRatio { get; set; }
```
### OverlayEmbeddableControl

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Gets the EmbeddableControl created for the tool to be shown on the map view. This is control set by the <xref href="ArcGIS.Desktop.Mapping.MapTool.OverlayControlID" data-throw-if-not-resolved="false"></xref> property.</p>


```csharp
protected EmbeddableControl OverlayEmbeddableControl { get; }
```
### ResetSketchSegmentSymbolOptions()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Sets the current sketch segment symbol back to the options defined in the application settings.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
protected void ResetSketchSegmentSymbolOptions()
```
### ResetSketchVertexSymbolOptions()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Sets the current sketch vertex symbols back to the options defined in the application settings.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
protected void ResetSketchVertexSymbolOptions()
```
### SegmentContextMenuID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Gets or sets the DAML ID of the context menu shown when modifying a segment.</p>


```csharp
protected string SegmentContextMenuID { get; set; }
```
### SetCurrentSketchAsync(Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Sets the current geometry of the sketch without finishing it.</p>


```csharp
protected Task SetCurrentSketchAsync(Geometry geometry)
```
### SetSketchSegmentSymbolOptions(SegmentSymbolOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Sets the segment sketching symbol information.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
protected void SetSketchSegmentSymbolOptions(SegmentSymbolOptions options)
```
### SetSketchVertexSymbolOptions(VertexSymbolType, VertexSymbolOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Sets the symbol for a vertex while sketching.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
protected void SetSketchVertexSymbolOptions(VertexSymbolType symbolType, VertexSymbolOptions vertexSymbol)
```
### ShowGroundToGridCorrections

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Gets or sets whether the ground to grid corrections heads-up display is shown when ground to grid is turned on in the UI. Default is false.</p>


```csharp
protected bool ShowGroundToGridCorrections { get; set; }
```
### ShowUncommittedSketchDialog

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Gets or sets whether the uncommitted sketch dialog is shown. Default is false.</p>


```csharp
protected bool ShowUncommittedSketchDialog { get; set; }
```
### SketchMode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Gets and sets the SketchMode for the MapTool.</p>


```csharp
protected SketchMode SketchMode { get; set; }
```
### SketchNumberOfSides

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Gets or sets the number of sides for a regular polygon.  Use when <xref href="ArcGIS.Desktop.Mapping.MapTool.SketchType" data-throw-if-not-resolved="false"></xref> = <xref href="ArcGIS.Desktop.Mapping.SketchGeometryType.RegularPolygon" data-throw-if-not-resolved="false"></xref>
or <xref href="ArcGIS.Desktop.Mapping.MapTool.SketchType" data-throw-if-not-resolved="false"></xref> = <xref href="ArcGIS.Desktop.Mapping.SketchGeometryType.RegularPolyline" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
protected int SketchNumberOfSides { get; set; }
```
### SketchOutputMode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Gets or sets if the sketch geometry should be created using map or screen coordinates.</p>


```csharp
protected SketchOutputMode SketchOutputMode { get; set; }
```
### SketchOverlaySymbol

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Gets or sets the sketch symbology when the sketch is in selection mode.</p>


```csharp
protected CIMSymbolReference SketchOverlaySymbol { get; set; }
```
### SketchSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Gets or sets the symbol to use for the sketch. This is only supported when creating a sketch in map coordinates.</p>


```csharp
protected CIMSymbolReference SketchSymbol { get; set; }
```
### SketchTip

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Gets and sets text for a sketch tip.The text follows the cursor when the tool is active.</p>


```csharp
protected string SketchTip { get; set; }
```
### SketchTipControlPosition

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Gets and sets the position for the sketch tip embeddable control.  The default value is <xref href="ArcGIS.Desktop.Mapping.SketchTipControlPosition.LowerRight" data-throw-if-not-resolved="false"></xref>.
The sketch tip embeddable control is the control set by the <xref href="ArcGIS.Desktop.Mapping.MapTool.SketchTipID" data-throw-if-not-resolved="false"></xref> property.</p>


```csharp
protected SketchTipControlPosition SketchTipControlPosition { get; set; }
```
### SketchTipEmbeddableControl

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Gets the Embeddable Control for the sketch tip for this tool.
This is the control set by the <xref href="ArcGIS.Desktop.Mapping.MapTool.SketchTipID" data-throw-if-not-resolved="false"></xref> property.</p>


```csharp
protected EmbeddableControl SketchTipEmbeddableControl { get; }
```
### SketchTipID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Gets and sets the DAML ID of the embeddable control to show as a sketch tip.The control follows the cursor when the tool is active.</p>


```csharp
protected string SketchTipID { get; set; }
```
### SketchType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Gets or sets the type or shape of the geometry to be created by the sketch.</p>


```csharp
protected SketchGeometryType? SketchType { get; set; }
```
### SnappingResults

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Desktop.Mapping.SnapResult" data-throw-if-not-resolved="false"></xref> for each vertex in the current sketch.</p>


```csharp
protected IReadOnlyList<SnapResult> SnappingResults { get; }
```
### StartSketchAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Start a new sketch.</p>


```csharp
protected Task StartSketchAsync()
```
### StartSketchAsync(EditingTemplate)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Start a new sketch using the given template.</p>


```csharp
protected Task StartSketchAsync(EditingTemplate template)
```
### UpdateCursor()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Occurs when a cursor is set on this tool.
Forward the cursor to the inner tool.</p>


```csharp
protected override sealed void UpdateCursor()
```
### UpdateOverlay(IEnumerable&lt;IDisposable&gt;, IEnumerable&lt;Geometry&gt;, CIMSymbolReference, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Updates the geometry and symbol for a set of overlay graphics on the map view. Each overlay is drawn with the same symbol.</p>


```csharp
protected bool UpdateOverlay(IEnumerable<IDisposable> overlays, IEnumerable<Geometry> geometries, CIMSymbolReference symbol, double referenceScale = -1, double showThrough = 0)
```
### UpdateOverlay(IDisposable, CIMGraphic, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Updates the graphic for an overlay graphic on the map view.</p>


```csharp
protected bool UpdateOverlay(IDisposable overlay, CIMGraphic graphic, double referenceScale = -1, double showThrough = 0)
```
### UpdateOverlay(IDisposable, Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Updates the geometry for an overlay graphic on the map view.</p>


```csharp
protected bool UpdateOverlay(IDisposable overlay, Geometry geometry)
```
### UpdateOverlay(IDisposable, Geometry, CIMSymbolReference, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Updates the geometry and symbol for an overlay graphic on the map view.</p>


```csharp
protected bool UpdateOverlay(IDisposable overlay, Geometry geometry, CIMSymbolReference symbol = null, double referenceScale = -1)
```
### UpdateOverlay(IDisposable, Geometry, CIMSymbolReference, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Updates the geometry and symbol for an overlay graphic on the map view.</p>


```csharp
protected bool UpdateOverlay(IDisposable overlay, Geometry geometry, CIMSymbolReference symbol, double referenceScale, double showThrough)
```
### UpdateOverlay(IDisposable, IEnumerable&lt;CIMGraphic&gt;, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Updates the graphics for an overlay graphic on the map view.</p>


```csharp
protected bool UpdateOverlay(IDisposable overlay, IEnumerable<CIMGraphic> graphics, double referenceScale = -1, double showThrough = 0)
```
### UseSelection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Gets or sets if the sketch needs a selection in order to operate. This requirement allows the tool to have two different modes;
the normal sketch mode and an additional selection mode.The user is able to toggle the tool between sketch and select
modes by pressing and holding down the SHIFT key. When this occurs the sketch is suspended and the user can select additional
features.  Releasing the SHIFT key puts the tool back into sketch mode, restores the previous state of the sketch (and the
sketch undo / redo stack) and allows you to resume sketching.</p>
<p></p>
<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="9">The default value is false.</p>


```csharp
protected bool UseSelection { get; set; }
```
### UseSnapping

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Gets or sets whether to use snapping to precisely sketch on the active map view. The default value is false.</p>


```csharp
protected bool UseSnapping { get; set; }
```
### UsesCurrentTemplate

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapTool.yml" sourcestartlinenumber="1">Gets or sets whether the sketch is for creating a feature and should use the CurrentTemplate.</p>


```csharp
protected bool UsesCurrentTemplate { get; set; }
```


