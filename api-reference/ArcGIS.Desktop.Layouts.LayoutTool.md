# LayoutTool

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Layouts.html">Layouts</a>
- Assembly: ArcGIS.Desktop.Extensions.dll

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutTool.yml" sourcestartlinenumber="1">Represents a tool command used to perform interactive operations on a <xref href="ArcGIS.Desktop.Layouts.LayoutView" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public abstract class LayoutTool : Tool
```


## Members

### LayoutTool()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutTool.yml" sourcestartlinenumber="1">Default constructor for LayoutTool.</p>


```csharp
public LayoutTool()
```
### ActiveElementContainer

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutTool.yml" sourcestartlinenumber="1">Gets the active element container.</p>


```csharp
public IElementContainer ActiveElementContainer { get; }
```
### ClearSketchAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutTool.yml" sourcestartlinenumber="1">Clears the current sketch in the active view.</p>


```csharp
protected Task ClearSketchAsync()
```
### ContextMenuID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutTool.yml" sourcestartlinenumber="1">Gets or sets the DAML ID of the context menu for the tool.</p>


```csharp
protected string ContextMenuID { get; set; }
```
### ContextToolbarID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutTool.yml" sourcestartlinenumber="1">Gets or sets the DAML ID of the toolbar to display for the tool.</p>


```csharp
protected string ContextToolbarID { get; set; }
```
### FinishSketchAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutTool.yml" sourcestartlinenumber="1">Finishes the current sketch in the active view.</p>


```csharp
protected Task<bool> FinishSketchAsync()
```
### GetCurrentSketchAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutTool.yml" sourcestartlinenumber="1">Gets the current geometry of the sketch without finishing it.</p>


```csharp
protected Task<Geometry> GetCurrentSketchAsync()
```
### HandleDoubleClickAsync(LayoutViewMouseButtonEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutTool.yml" sourcestartlinenumber="1">Occurs when the <xref href="ArcGIS.Desktop.Layouts.LayoutTool.OnToolDoubleClick(ArcGIS.Desktop.Layouts.LayoutViewMouseButtonEventArgs)" data-throw-if-not-resolved="false"></xref> event is handled.</p>


```csharp
protected virtual Task HandleDoubleClickAsync(LayoutViewMouseButtonEventArgs args)
```
### HandleKeyDownAsync(LayoutViewKeyEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutTool.yml" sourcestartlinenumber="1">Occurs when the <xref href="ArcGIS.Desktop.Layouts.LayoutTool.OnToolKeyDown(ArcGIS.Desktop.Layouts.LayoutViewKeyEventArgs)" data-throw-if-not-resolved="false"></xref> event is handled.</p>


```csharp
protected virtual Task HandleKeyDownAsync(LayoutViewKeyEventArgs args)
```
### HandleKeyUpAsync(LayoutViewKeyEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutTool.yml" sourcestartlinenumber="1">Occurs when the <xref href="ArcGIS.Desktop.Layouts.LayoutTool.OnToolKeyUp(ArcGIS.Desktop.Layouts.LayoutViewKeyEventArgs)" data-throw-if-not-resolved="false"></xref> event is handled.</p>


```csharp
protected virtual Task HandleKeyUpAsync(LayoutViewKeyEventArgs args)
```
### HandleMouseDownAsync(LayoutViewMouseButtonEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutTool.yml" sourcestartlinenumber="1">Occurs when the <xref href="ArcGIS.Desktop.Layouts.LayoutTool.OnToolMouseDown(ArcGIS.Desktop.Layouts.LayoutViewMouseButtonEventArgs)" data-throw-if-not-resolved="false"></xref> event is handled.</p>


```csharp
protected virtual Task HandleMouseDownAsync(LayoutViewMouseButtonEventArgs args)
```
### HandleMouseUpAsync(LayoutViewMouseButtonEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutTool.yml" sourcestartlinenumber="1">Occurs when the <xref href="ArcGIS.Desktop.Layouts.LayoutTool.OnToolMouseUp(ArcGIS.Desktop.Layouts.LayoutViewMouseButtonEventArgs)" data-throw-if-not-resolved="false"></xref> event is handled.</p>


```csharp
protected virtual Task HandleMouseUpAsync(LayoutViewMouseButtonEventArgs args)
```
### HandleOnPaneActivateAsync(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutTool.yml" sourcestartlinenumber="1">Called to inform the Tool a Pane referencing it as the active tool is activating or deactivating.</p>


```csharp
protected virtual Task HandleOnPaneActivateAsync(bool active)
```
### OnSketchCanceledAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutTool.yml" sourcestartlinenumber="1">Occurs when a sketch is canceled.</p>


```csharp
protected virtual Task<bool> OnSketchCanceledAsync()
```
### OnSketchCompleteAsync(Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutTool.yml" sourcestartlinenumber="1">Occurs when a sketch is finished.</p>


```csharp
protected virtual Task<bool> OnSketchCompleteAsync(Geometry geometry)
```
### OnSketchModifiedAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutTool.yml" sourcestartlinenumber="1">Occurs when a sketch is modified.</p>


```csharp
protected virtual Task<bool> OnSketchModifiedAsync()
```
### OnToolActivateAsync(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutTool.yml" sourcestartlinenumber="1">Occurs when the tool is activated.</p>


```csharp
protected virtual Task OnToolActivateAsync(bool hasVewChanged)
```
### OnToolDeactivateAsync(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutTool.yml" sourcestartlinenumber="1">Occurs when the tool is deactivated.</p>


```csharp
protected virtual Task OnToolDeactivateAsync(bool hasVewChanged)
```
### OnToolDoubleClick(LayoutViewMouseButtonEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutTool.yml" sourcestartlinenumber="1">Occurs when a mouse button is clicked on the view two or more times.</p>


```csharp
protected virtual void OnToolDoubleClick(LayoutViewMouseButtonEventArgs args)
```
### OnToolKeyDown(LayoutViewKeyEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutTool.yml" sourcestartlinenumber="1">Occurs when a key is pressed and the view has focus.</p>


```csharp
protected virtual void OnToolKeyDown(LayoutViewKeyEventArgs args)
```
### OnToolKeyUp(LayoutViewKeyEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutTool.yml" sourcestartlinenumber="1">Occurs when a key is released and the view has focus.</p>


```csharp
protected virtual void OnToolKeyUp(LayoutViewKeyEventArgs args)
```
### OnToolMouseDown(LayoutViewMouseButtonEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutTool.yml" sourcestartlinenumber="1">Occurs when a mouse button is pressed on the view.</p>


```csharp
protected virtual void OnToolMouseDown(LayoutViewMouseButtonEventArgs args)
```
### OnToolMouseMove(LayoutViewMouseEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutTool.yml" sourcestartlinenumber="1">Occurs when the mouse pointer moves over the view.</p>


```csharp
protected virtual void OnToolMouseMove(LayoutViewMouseEventArgs args)
```
### OnToolMouseUp(LayoutViewMouseButtonEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutTool.yml" sourcestartlinenumber="1">Occurs when a mouse button is released on the view.</p>


```csharp
protected virtual void OnToolMouseUp(LayoutViewMouseButtonEventArgs args)
```
### SetCurrentSketchAsync(Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutTool.yml" sourcestartlinenumber="1">Sets the current geometry of the sketch without finishing it.</p>


```csharp
protected Task SetCurrentSketchAsync(Geometry geometry)
```
### SketchNumberOfSides

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutTool.yml" sourcestartlinenumber="1">Gets or sets the number of sides for a regular polygon.  Use when <xref href="ArcGIS.Desktop.Layouts.LayoutTool.SketchType" data-throw-if-not-resolved="false"></xref> = <xref href="ArcGIS.Desktop.Mapping.SketchGeometryType.RegularPolygon" data-throw-if-not-resolved="false"></xref>
or <xref href="ArcGIS.Desktop.Layouts.LayoutTool.SketchType" data-throw-if-not-resolved="false"></xref> = <xref href="ArcGIS.Desktop.Mapping.SketchGeometryType.RegularPolyline" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
protected int SketchNumberOfSides { get; set; }
```
### SketchSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutTool.yml" sourcestartlinenumber="1">Gets the symbol to use for the sketch.</p>


```csharp
protected CIMSymbolReference SketchSymbol { get; }
```
### SketchType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutTool.yml" sourcestartlinenumber="1">Gets or sets the type or shape of the geometry to be created by the sketch.</p>


```csharp
protected SketchGeometryType SketchType { get; set; }
```
### StartSketchAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutTool.yml" sourcestartlinenumber="1">Start a new sketch.</p>


```csharp
protected Task StartSketchAsync()
```
### UpdateCursor()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutTool.yml" sourcestartlinenumber="1">Occurs when a cursor is set on this tool.
Forward the cursor to the inner tool.</p>


```csharp
protected override sealed void UpdateCursor()
```
### UseSnapping

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutTool.yml" sourcestartlinenumber="1">Gets or sets whether to use snapping to precisely sketch on the active view. The default value is false.</p>


```csharp
protected bool UseSnapping { get; set; }
```


