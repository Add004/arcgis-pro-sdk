# PresentationView

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Presentations.html">Presentations</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationView.yml" sourcestartlinenumber="1">Represents the view of a presentation in a pane.</p>


## Object Signature

```csharp
public sealed class PresentationView
```

## Remarks

<p>
    A project can contain multiple presentations. A presentation view is a pane that displays the view of a presentation. 
    Presentation views are the primary interface used to display, navigate, and select presentation page elements. 
    The presentation being visualized in the view can be accessed via the <xref href="ArcGIS.Desktop.Presentations.PresentationView.Presentation?text=Presentation" data-throw-if-not-resolved="false"></xref> property.
    </p>
<p>
    There can be multiple presentation views open at a given time, but there can only be one active presentation view. 
    The active presentation view will set the context for the ribbon and many of the dock panes in the application.
    The <xref href="ArcGIS.Desktop.Presentations.PresentationView.Active?text=Active+" data-throw-if-not-resolved="false"></xref> property will return null if there is no active presentation view.
    </p>
<p>
    The presentation view has several "ZoomTo" navigation methods and it also provides the context for managing selected items in the Contents pane. 
    For example, the <xref href="ArcGIS.Desktop.Presentations.PresentationView.GetSelectedElements?text=GetSelectedElements+" data-throw-if-not-resolved="false"></xref> method returns a collection of selected page presentation elements.
    </p>


## Members

### ActivateMapPageAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationView.yml" sourcestartlinenumber="1">Activates the map on the presentation view. Only a map page can be activated. This method must be called on the UI thread.</p>


```csharp
public Task<bool> ActivateMapPageAsync()
```
### Active

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationView.yml" sourcestartlinenumber="1">Gets the active presentation view.</p>


```csharp
public static PresentationView Active { get; }
```
### ActivePage

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationView.yml" sourcestartlinenumber="1">Gets the presentation page that is displayed in the view.</p>


```csharp
public PresentationPage ActivePage { get; }
```
### CaptureThumbnail(int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationView.yml" sourcestartlinenumber="1">Captures a bitmap of the PresentationView content.</p>


```csharp
public BitmapSource CaptureThumbnail(int dpi)
```
### CaptureThumbnail(int, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationView.yml" sourcestartlinenumber="1">Captures a bitmap of the PresentationView content.</p>


```csharp
public BitmapSource CaptureThumbnail(int width, int height)
```
### ClearElementSelection()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationView.yml" sourcestartlinenumber="1">Clears all presentation elements in the presentation view.</p>


```csharp
public void ClearElementSelection()
```
### ClientToPage(Point)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationView.yml" sourcestartlinenumber="1">Converts a point in client coordinates to a point in page coordinates.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Coordinate2D ClientToPage(Point clientPoint)
```
### ClientToScreen(Point)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationView.yml" sourcestartlinenumber="1">Converts a point in client coordinates to a point in screen coordinates.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Point ClientToScreen(Point clientPoint)
```
### DeactivateMapPageAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationView.yml" sourcestartlinenumber="1">Deactivates the map on the presentation view. Only an activated map page can be deactivated. This method must be called on the UI thread.</p>


```csharp
public Task<bool> DeactivateMapPageAsync()
```
### DrawingPaused

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationView.yml" sourcestartlinenumber="1">Gets or sets the paused state on the presentation view.</p>


```csharp
public bool DrawingPaused { get; set; }
```
### Extent

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationView.yml" sourcestartlinenumber="1">Gets the current extent of the presentation view.</p>


```csharp
public Envelope Extent { get; }
```
### GetSelectedElements()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationView.yml" sourcestartlinenumber="1">Returns a collection of selected presentation elements.</p>


```csharp
public IReadOnlyList<Element> GetSelectedElements()
```
### GetViewSize()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationView.yml" sourcestartlinenumber="1">Returns the current size of the view in pixels.</p>


```csharp
public Size GetViewSize()
```
### IsReady

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationView.yml" sourcestartlinenumber="1">Gets a value that indicates whether the PresentationView can be accessed. This property is <code>false</code> while the presentation view processes major operations.</p>


```csharp
public bool IsReady { get; }
```
### PageToClient(Coordinate2D)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationView.yml" sourcestartlinenumber="1">Converts a point in page coordinates to a point in client coordinates.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Point PageToClient(Coordinate2D pageCoord)
```
### PageToScreen(Coordinate2D)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationView.yml" sourcestartlinenumber="1">Converts a point in page coordinates to screen coordinates.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Point PageToScreen(Coordinate2D pageCoord)
```
### Presentation

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationView.yml" sourcestartlinenumber="1">Gets the presentation associated with the presentation view.</p>


```csharp
public Presentation Presentation { get; }
```
### Refresh()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationView.yml" sourcestartlinenumber="1">Forces the presentation view to redraw. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Refresh()
```
### ScreenToClient(Point)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationView.yml" sourcestartlinenumber="1">Converts a point in screen coordinates to a point in client coordinates.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Point ScreenToClient(Point screenPoint)
```
### ScreenToPage(Point)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationView.yml" sourcestartlinenumber="1">Converts a point in screen coordinates to a point in page coordinates.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Coordinate2D ScreenToPage(Point screenPoint)
```
### SelectAllElements()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationView.yml" sourcestartlinenumber="1">Selects all presentation elements in a presentation view.</p>


```csharp
public void SelectAllElements()
```
### SelectElement(Element)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationView.yml" sourcestartlinenumber="1">Sets the element selected for the presentation view.</p>


```csharp
public void SelectElement(Element element)
```
### SelectElements(IReadOnlyList&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationView.yml" sourcestartlinenumber="1">Sets the selected presentation elements for the presentation view.</p>


```csharp
public void SelectElements(IReadOnlyList<Element> elements)
```
### UnSelectElement(Element)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationView.yml" sourcestartlinenumber="1">Unselects the element within the presentation view.</p>


```csharp
public void UnSelectElement(Element element)
```
### UnSelectElements(IEnumerable&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationView.yml" sourcestartlinenumber="1">Unselects the elements within the presentation view.</p>


```csharp
public void UnSelectElements(IEnumerable<Element> elements = null)
```
### ZoomPercentage

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationView.yml" sourcestartlinenumber="1">Gets the current zoom percentage of the presentation view.</p>


```csharp
public double ZoomPercentage { get; }
```
### ZoomTo(Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationView.yml" sourcestartlinenumber="1">Zooms the presentation view to the extent defined by a geometry. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool ZoomTo(Geometry geometry)
```
### ZoomToElement(Element)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationView.yml" sourcestartlinenumber="1">Zooms to the extent of the element.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool ZoomToElement(Element element)
```
### ZoomToElements(IEnumerable&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationView.yml" sourcestartlinenumber="1">Zooms to the extent of the elements.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool ZoomToElements(IEnumerable<Element> elements)
```
### ZoomToPageWidth()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationView.yml" sourcestartlinenumber="1">Zooms the presentation view to the width of the page. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool ZoomToPageWidth()
```
### ZoomToSelectedElements()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationView.yml" sourcestartlinenumber="1">Zooms the presentation view to the extent of the selected elements. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool ZoomToSelectedElements()
```
### ZoomToWholePage()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationView.yml" sourcestartlinenumber="1">Zooms the presentation view to the whole page. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool ZoomToWholePage()
```


