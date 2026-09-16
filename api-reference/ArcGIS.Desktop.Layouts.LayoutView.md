# LayoutView

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Layouts.html">Layouts</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutView.yml" sourcestartlinenumber="1">Represents the view of layout in a pane.</p>


## Object Signature

```csharp
public sealed class LayoutView
```

## Remarks

<p>
    A project can contain multiple layouts.  A layout view is a pane that displays the view of a layout.  
    Layout views are the primary interface used to display, navigate, and select layout elements.  
    The layout being visualized in the view can be accessed via the <xref href="ArcGIS.Desktop.Layouts.LayoutView.Layout?text=Layout+" data-throw-if-not-resolved="false"></xref> property.
    </p>
<p>
    There can be multiple layout views open at a given time, but there can only be one active layout view.  
    The active layout view will set the context for the ribbon and many of the dock panes in the application.
    The <xref href="ArcGIS.Desktop.Layouts.LayoutView.Active?text=Active+" data-throw-if-not-resolved="false"></xref> property will return null if there is no active layout view.
    </p>
<p>
    The layout view has several "ZoomTo" navigation methods and it also provides the context for managing selected items in the Contents pane.  
    For example, the <xref href="ArcGIS.Desktop.Layouts.LayoutView.GetSelectedElements?text=GetSelectedElements+" data-throw-if-not-resolved="false"></xref> method returns a collection of selected page layout elements.
    </p>


## Members

### ActivateMapFrame(MapFrame)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutView.yml" sourcestartlinenumber="1">Activate the map frame on the layout view. This method must be called
on the <b>UI</b> thread.</p>


```csharp
public void ActivateMapFrame(MapFrame mapFrame)
```
### ActivatedMapFrame

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutView.yml" sourcestartlinenumber="1">Gets the activated map frame or null if a map frame is not activated</p>


```csharp
public MapFrame ActivatedMapFrame { get; }
```
### ActivatedMapView

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutView.yml" sourcestartlinenumber="1">Gets the activated map view or null if there is no <xref href="ArcGIS.Desktop.Layouts.LayoutView.ActivatedMapFrame" data-throw-if-not-resolved="false"></xref></p>


```csharp
public MapView ActivatedMapView { get; }
```
### Active

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutView.yml" sourcestartlinenumber="1">Gets the active layout view.</p>


```csharp
public static LayoutView Active { get; }
```
### ActiveElementContainer

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutView.yml" sourcestartlinenumber="1">Gets the active element container</p>


```csharp
public IElementContainer ActiveElementContainer { get; }
```
### ActiveMapFrame

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutView.yml" sourcestartlinenumber="1">Gets the active map frame on a layout.</p>


```csharp
public MapFrame ActiveMapFrame { get; }
```
### CanActivateMapFrame(MapFrame)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutView.yml" sourcestartlinenumber="1">Check whether or not the given map frame can be activated on the layout view</p>


```csharp
public bool CanActivateMapFrame(MapFrame mapFrame)
```
### CaptureThumbnail(int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutView.yml" sourcestartlinenumber="1">Capture a bitmap of the LayoutView content.</p>


```csharp
public BitmapSource CaptureThumbnail(int dpi)
```
### CaptureThumbnail(int, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutView.yml" sourcestartlinenumber="1">Capture a bitmap of the LayoutView content.</p>


```csharp
public BitmapSource CaptureThumbnail(int width, int height)
```
### ClearElementSelection()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutView.yml" sourcestartlinenumber="1">Clear all layout elements in the layout view.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void ClearElementSelection()
```
### ClientToPage(Point)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutView.yml" sourcestartlinenumber="1">Converts a point in client coordinates to a point in page coordinates.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Coordinate2D ClientToPage(Point clientPoint)
```
### ClientToScreen(Point)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutView.yml" sourcestartlinenumber="1">Converts a point in screen coordinates to a point in client coordinates.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Point ClientToScreen(Point clientPoint)
```
### DeactivateMapFrame()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutView.yml" sourcestartlinenumber="1">Deactivate the <xref href="ArcGIS.Desktop.Layouts.LayoutView.ActivatedMapFrame" data-throw-if-not-resolved="false"></xref> on the layout view. This method
must be called on the <b>UI</b> thread.</p>


```csharp
public void DeactivateMapFrame()
```
### DrawingPaused

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutView.yml" sourcestartlinenumber="1">Gets or sets the paused state on the map view.</p>


```csharp
public bool DrawingPaused { get; set; }
```
### Extent

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutView.yml" sourcestartlinenumber="1">Gets the current extent of the layout view.</p>


```csharp
public Envelope Extent { get; }
```
### GetSelectedElements()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutView.yml" sourcestartlinenumber="1">Returns a collection of selected layout elements.</p>


```csharp
public IReadOnlyList<Element> GetSelectedElements()
```
### GetViewSize()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutView.yml" sourcestartlinenumber="1">Returns the current size of the view in pixels.</p>


```csharp
public Size GetViewSize()
```
### IsReady

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutView.yml" sourcestartlinenumber="1">Gets a value that indicates whether the LayoutView can be accessed. This property is <code>false</code> while the layout view processes major operations.</p>


```csharp
public bool IsReady { get; }
```
### Layout

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutView.yml" sourcestartlinenumber="1">Gets the layout associated with the layout view.</p>


```csharp
public Layout Layout { get; }
```
### PageToClient(Coordinate2D)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutView.yml" sourcestartlinenumber="1">Converts a point in page coordinates to a point in client coordinates.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Point PageToClient(Coordinate2D pageCoord)
```
### PageToScreen(Coordinate2D)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutView.yml" sourcestartlinenumber="1">Converts a point in page coordinates to screen coordinates.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Point PageToScreen(Coordinate2D pageCoord)
```
### Refresh()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutView.yml" sourcestartlinenumber="1">Force the layout view to redraw. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Refresh()
```
### ScreenToClient(Point)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutView.yml" sourcestartlinenumber="1">Converts a point in screen coordinates to a point in client coordinates.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Point ScreenToClient(Point screenPoint)
```
### ScreenToPage(Point)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutView.yml" sourcestartlinenumber="1">Converts a point in screen coordinates to a point in page coordinates.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Coordinate2D ScreenToPage(Point screenPoint)
```
### SelectAllElements()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutView.yml" sourcestartlinenumber="1">Select all layout elements in a layout view.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SelectAllElements()
```
### SelectElement(Element)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutView.yml" sourcestartlinenumber="1">Set the element selected for the layout view.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SelectElement(Element element)
```
### SelectElements(Geometry, SelectionCombinationMethod, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutView.yml" sourcestartlinenumber="1">Select elements that visually intersect a geometry.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SelectElements(Geometry geometry, SelectionCombinationMethod method, bool isWhollyWithin)
```
### SelectElements(IReadOnlyList&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutView.yml" sourcestartlinenumber="1">Set the selected layout elements for the layout view.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SelectElements(IReadOnlyList<Element> elements)
```
### UnSelectElement(Element)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutView.yml" sourcestartlinenumber="1">Unselect the element within the layout view.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void UnSelectElement(Element element)
```
### UnSelectElements(IEnumerable&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutView.yml" sourcestartlinenumber="1">Unselect the elements within the layout view.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void UnSelectElements(IEnumerable<Element> elements = null)
```
### ZoomPercentage

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutView.yml" sourcestartlinenumber="1">Gets the current zoom percentage of the layout view.</p>


```csharp
public double ZoomPercentage { get; }
```
### ZoomTo(Geometry, TimeSpan?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutView.yml" sourcestartlinenumber="1">Zoom the layout view to the extent defined by a geometry.  This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public bool ZoomTo(Geometry geometry, TimeSpan? duration = null)
```
### ZoomTo100Percent(TimeSpan?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutView.yml" sourcestartlinenumber="1">Zoom to the layout view to 100 percent.  This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public bool ZoomTo100Percent(TimeSpan? duration = null)
```
### ZoomToElement(Element, TimeSpan?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutView.yml" sourcestartlinenumber="1">Zoom to the extent of the element.
This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public bool ZoomToElement(Element element, TimeSpan? duration = null)
```
### ZoomToElements(IEnumerable&lt;Element&gt;, TimeSpan?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutView.yml" sourcestartlinenumber="1">Zoom to the extent of the elements.
This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public bool ZoomToElements(IEnumerable<Element> elements, TimeSpan? duration = null)
```
### ZoomToNext(TimeSpan?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutView.yml" sourcestartlinenumber="1">Zoom the layout view to the next extent.  This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public bool ZoomToNext(TimeSpan? duration = null)
```
### ZoomToPageWidth(TimeSpan?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutView.yml" sourcestartlinenumber="1">Zoom the layout view to the width of the page.  This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public bool ZoomToPageWidth(TimeSpan? duration = null)
```
### ZoomToPrevious(TimeSpan?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutView.yml" sourcestartlinenumber="1">Zoom the layout view to the previous extent.  This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public bool ZoomToPrevious(TimeSpan? duration = null)
```
### ZoomToSelectedElements(TimeSpan?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutView.yml" sourcestartlinenumber="1">Zoom the layout view to the extent of the selected elements.  This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public bool ZoomToSelectedElements(TimeSpan? duration = null)
```
### ZoomToWholePage(TimeSpan?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutView.yml" sourcestartlinenumber="1">Zoom the layout view to the whole page.  This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public bool ZoomToWholePage(TimeSpan? duration = null)
```


