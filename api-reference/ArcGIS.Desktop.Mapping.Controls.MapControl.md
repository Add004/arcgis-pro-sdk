# MapControl

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Controls.html">Controls</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControl.yml" sourcestartlinenumber="1">Represents a control that can be embedded inside a dock pane, view pane or a dialog and used to display
project items such as 2D and 3D maps, feature layers, rater datasets, layer packages etc.</p>


## Object Signature

```csharp
public sealed class MapControl : UserControl, IAnimatable, IFrameworkInputElement, IInputElement, ISupportInitialize, IQueryAmbient, IAddChild, IDisposable, IComponentConnector
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControl.yml" sourcestartlinenumber="1">The MapControl is a native control and if it is placed in a transparent native window then the
MapControl will also be transparent and will not display. An example of this is if you use the
MapControl as an embeddable control by associating it with a MapTool then the MapControl will be
hosted in a transparent native window and will not be visible.</p>


## Members

### MapControl()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControl.yml" sourcestartlinenumber="1">Initializes a new instance of the ArcGIS.Desktop.Mapping.Controls.MapControl class.</p>


```csharp
public MapControl()
```
### AddOverlay(CIMGraphic, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControl.yml" sourcestartlinenumber="1">Add an overlay graphic to the map control.</p>


```csharp
public IDisposable AddOverlay(CIMGraphic graphic, double referenceScale = -1)
```
### AddOverlay(CIMGraphic, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControl.yml" sourcestartlinenumber="1">Add an overlay graphic to the map control.</p>


```csharp
public IDisposable AddOverlay(CIMGraphic graphic, double referenceScale, double showThrough)
```
### AddOverlay(Geometry, CIMSymbolReference)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControl.yml" sourcestartlinenumber="1">Add an overlay graphic to the map control.</p>


```csharp
public IDisposable AddOverlay(Geometry geom, CIMSymbolReference symbol = null)
```
### AddOverlay(Geometry, CIMSymbolReference, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControl.yml" sourcestartlinenumber="1">Add an overlay graphic to the map control.</p>


```csharp
public IDisposable AddOverlay(Geometry geom, CIMSymbolReference symbol, double referenceScale, double showThrough)
```
### Camera

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControl.yml" sourcestartlinenumber="1">Gets or sets the Camera of a ArcGIS.Desktop.Mapping.Controls.MapControl.</p>


```csharp
public Camera Camera { get; set; }
```
### CameraChanged

- Kind: event

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControl.yml" sourcestartlinenumber="1">Occurs when camera changes.</p>


```csharp
public event EventHandler CameraChanged
```
### CameraProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControl.yml" sourcestartlinenumber="1">Identifies the ArcGIS.Desktop.Mapping.Controls.MapControl.Camera dependency property.</p>


```csharp
public static readonly DependencyProperty CameraProperty
```
### CaptureThumbnail(int, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControl.yml" sourcestartlinenumber="1">Capture a bitmap of the MapControl content.</p>


```csharp
public BitmapSource CaptureThumbnail(int width, int height)
```
### ClientToMap(Point)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControl.yml" sourcestartlinenumber="1">Converts a point in client coordinates relative to the top-left corner of the view to a point in the coordinates of the map or scene. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public MapPoint ClientToMap(Point clientPoint)
```
### ClientToScreen(Point)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControl.yml" sourcestartlinenumber="1">Converts a screen point to a point in client coordinates relative to the top-left corner of the view.</p>


```csharp
public Point ClientToScreen(Point clientPoint)
```
### ControlInitialized

- Kind: event

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControl.yml" sourcestartlinenumber="1">Occurs when the control is initialized.</p>


```csharp
public event EventHandler ControlInitialized
```
### Dispose()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControl.yml" sourcestartlinenumber="1">Releases unmanaged resources.</p>


```csharp
public void Dispose()
```
### DrawComplete

- Kind: event

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControl.yml" sourcestartlinenumber="1">Occurs when drawing completes.</p>


```csharp
public event EventHandler DrawComplete
```
### DrawStarted

- Kind: event

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControl.yml" sourcestartlinenumber="1">Occurs when drawing starts.</p>


```csharp
public event EventHandler DrawStarted
```
### Extent

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControl.yml" sourcestartlinenumber="1">Gets or sets the Extent of a ArcGIS.Desktop.Mapping.Controls.MapControl.</p>


```csharp
public Envelope Extent { get; set; }
```
### ExtentChanged

- Kind: event

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControl.yml" sourcestartlinenumber="1">Occurs when extent changes.</p>


```csharp
public event EventHandler ExtentChanged
```
### ExtentProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControl.yml" sourcestartlinenumber="1">Identifies the ArcGIS.Desktop.Mapping.Controls.MapControl.Extent dependency property.</p>


```csharp
public static readonly DependencyProperty ExtentProperty
```
### InitializeComponent()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControl.yml" sourcestartlinenumber="1">InitializeComponent</p>


```csharp
public void InitializeComponent()
```
### IsDrawing

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControl.yml" sourcestartlinenumber="1">Gets the IsDrawing property.</p>


```csharp
public bool IsDrawing { get; }
```
### IsDrawingProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControl.yml" sourcestartlinenumber="1">Identifies the IsDrawing dependency property.</p>


```csharp
public static readonly DependencyProperty IsDrawingProperty
```
### IsLoadingViewContent

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControl.yml" sourcestartlinenumber="1">Gets the IsLoadingViewContent property.</p>


```csharp
public bool IsLoadingViewContent { get; }
```
### IsLoadingViewContentProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControl.yml" sourcestartlinenumber="1">Identifies the IsLoadingViewContent dependency property.</p>


```csharp
public static readonly DependencyProperty IsLoadingViewContentProperty
```
### IsReady

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControl.yml" sourcestartlinenumber="1">Gets the IsReady property.</p>


```csharp
public bool IsReady { get; }
```
### IsReadyProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControl.yml" sourcestartlinenumber="1">Identifies the ArcGIS.Desktop.Mapping.Controls.MapControl.IsReady dependency property.</p>


```csharp
public static readonly DependencyProperty IsReadyProperty
```
### IsViewerFocused

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControl.yml" sourcestartlinenumber="1">Gets or sets the IsViewerFocused of a ArcGIS.Desktop.Mapping.Controls.MapControl.</p>


```csharp
public bool IsViewerFocused { get; set; }
```
### IsViewerFocusedProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControl.yml" sourcestartlinenumber="1">Identifies the ArcGIS.Desktop.Mapping.Controls.MapControl.IsViewerFocused dependency property.</p>


```csharp
public static readonly DependencyProperty IsViewerFocusedProperty
```
### MapToClient(MapPoint)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControl.yml" sourcestartlinenumber="1">Converts a point in the coordinates of the map or scene to a point in client coordinates relative to the top-left corner of the view. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Point MapToClient(MapPoint mapPoint)
```
### MapToScreen(MapPoint)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControl.yml" sourcestartlinenumber="1">Converts a point in the coordinates of the map or scene to a point in screen coordinates. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Point MapToScreen(MapPoint mapPoint)
```
### OnCreateAutomationPeer()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControl.yml" sourcestartlinenumber="1">Creates and returns an System.Windows.Automation.Peers.AutomationPeer for this
ArcGIS.Desktop.Mapping.Controls.MapControl.</p>


```csharp
protected override AutomationPeer OnCreateAutomationPeer()
```
### OverlayControl

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControl.yml" sourcestartlinenumber="1">Gets or sets the OverlayControl property.</p>


```csharp
public UIElement OverlayControl { get; set; }
```
### OverlayControlProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControl.yml" sourcestartlinenumber="1">Identifies the OverlayControl dependency property.</p>


```csharp
public static readonly DependencyProperty OverlayControlProperty
```
### ScreenToClient(Point)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControl.yml" sourcestartlinenumber="1">Converts a point in client coordinates relative to the top-left corner of the view to a screen point.</p>


```csharp
public Point ScreenToClient(Point screenPoint)
```
### ScreenToMap(Point)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControl.yml" sourcestartlinenumber="1">Converts a point in screen coordinates to a point in the coordinates of the map or scene. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public MapPoint ScreenToMap(Point screenPoint)
```
### SpatialReference

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControl.yml" sourcestartlinenumber="1">Gets the spatial reference of the map control.</p>


```csharp
public SpatialReference SpatialReference { get; }
```
### UpdateOverlay(IDisposable, CIMGraphic, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControl.yml" sourcestartlinenumber="1">Updates the graphic for an overlay graphic on the map control.</p>


```csharp
public bool UpdateOverlay(IDisposable disposable, CIMGraphic graphic, double referenceScale, double showThrough)
```
### UpdateOverlay(IDisposable, Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControl.yml" sourcestartlinenumber="1">Updates the geometry for an overlay graphic on the map control.</p>


```csharp
public bool UpdateOverlay(IDisposable disposable, Geometry geometry)
```
### UpdateOverlay(IDisposable, Geometry, CIMSymbolReference)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControl.yml" sourcestartlinenumber="1">Updates the geometry and symbol for an overlay graphic on the map control.</p>


```csharp
public bool UpdateOverlay(IDisposable disposable, Geometry geometry, CIMSymbolReference symbol)
```
### UpdateOverlay(IDisposable, Geometry, CIMSymbolReference, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControl.yml" sourcestartlinenumber="1">Updates the geometry and symbol for an overlay graphic on the map control.</p>


```csharp
public bool UpdateOverlay(IDisposable disposable, Geometry geometry, CIMSymbolReference symbol, double referenceScale, double showThrough)
```
### ViewContent

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControl.yml" sourcestartlinenumber="1">Gets or sets the ViewContent of a ArcGIS.Desktop.Mapping.Controls.MapControl.</p>


```csharp
public MapControlContent ViewContent { get; set; }
```
### ViewContentLoaded

- Kind: event

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControl.yml" sourcestartlinenumber="1">Occurs when the ViewContent of the control has been loaded.</p>


```csharp
public event EventHandler ViewContentLoaded
```
### ViewContentProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.MapControl.yml" sourcestartlinenumber="1">Identifies the ArcGIS.Desktop.Mapping.Controls.MapControl.ViewContent dependency property.</p>


```csharp
public static readonly DependencyProperty ViewContentProperty
```


