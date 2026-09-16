# Tool

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Contracts.html">Contracts</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Tool.yml" sourcestartlinenumber="1">Represents a tool control. This is an abstract class.</p>


## Object Signature

```csharp
public abstract class Tool : Button, INotifyPropertyChanged
```

## Remarks

<p>
  All ribbon control elements share several attributes. The loadOnClick attribute determines when the control should be
  created by the framework. By default, controls appear enabled, but are not actually instantiated until they are
  clicked. This simple just-in-time (JIT) strategy improves resource utilization and startup time by deferring the instantiation
  of controls until they are initiated by the end user. Note that non-visible controls are never loaded until
  they become visible (or are executed programmatically), regardless of the value assigned to loadOnClick.
</p>
<p>
  Tooltips are defined using the tooltip sub-element and may span as many lines as necessary.  The image attribute is used
  to supply an image that will appear next to the tip text. Command tooltips also support a disabledText element, this string
  is additional displayed when the command is disabled.
</p>
<p>
  Most controls support multiple sizes in the ribbon. For example, a button can render small (small icon only),
  medium (small icon with text), and large (large icon over text). Use the smallImage and largeImage attributes to
  specify unique images for the different sizes.  Images don’t have to be graphics, you can also use XAML. You can
  also use overlayLargeImage and overlaySmallImage to draw a graphic or XAML overtop of the corresponding images. If
  the image should flip when running right-to-left, e.g. arrow buttons, set the flipImageRTL attribute to true.
</p>
<p>
  The disableIfBusy element is used to signal that the control should be disabled whenever the primary worker thread is
  busy. This prevents work from queuing up. This element is true by default. Controls that always need to be enabled such
  as the close application button should set this to false.
</p>
<p>
  All control declarations support a condition attribute allowing the assignment of a condition.  If the specified condition
  isn’t met, the control will be automatically disabled by the framework.  In addition, controls remain unloaded until their
  is met.  If no condition is specified, the control is assumed to be always relevant.
</p>


## Members

### Cursor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Tool.yml" sourcestartlinenumber="1">Gets or sets the mouse pointer for this tool.</p>


```csharp
public Cursor Cursor { get; set; }
```
### OnActivateAsync(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Tool.yml" sourcestartlinenumber="1">Called to inform the Tool it has been activated or deactivated.</p>


```csharp
protected virtual Task OnActivateAsync(bool isActive)
```
### OnActivePaneChanged(Pane)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Tool.yml" sourcestartlinenumber="1">Called on the active tool when a pane change occurrs to see if the tool
wants to remain active.</p>


```csharp
protected virtual bool? OnActivePaneChanged(Pane pane)
```
### OnDoubleClick(MouseButtonEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Tool.yml" sourcestartlinenumber="1">Occurs when a mouse button is clicked on a Pane two or more times.</p>


```csharp
protected virtual void OnDoubleClick(MouseButtonEventArgs e)
```
### OnKeyDown(KeyEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Tool.yml" sourcestartlinenumber="1">Occurs when a key is pressed and the tool is active.</p>


```csharp
protected virtual void OnKeyDown(KeyEventArgs k)
```
### OnKeyUp(KeyEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Tool.yml" sourcestartlinenumber="1">Occurs when a key is released and the tool is active.</p>


```csharp
protected virtual void OnKeyUp(KeyEventArgs k)
```
### OnMouseDown(MouseButtonEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Tool.yml" sourcestartlinenumber="1">Occurs when a mouse button is pressed on a Pane and the tool is active.</p>


```csharp
protected virtual void OnMouseDown(MouseButtonEventArgs e)
```
### OnMouseEnter(MouseEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Tool.yml" sourcestartlinenumber="1">Occurs when the mouse pointer enters a Pane and the tool is active.</p>


```csharp
protected virtual void OnMouseEnter(MouseEventArgs e)
```
### OnMouseLeave(MouseEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Tool.yml" sourcestartlinenumber="1">Occurs when the mouse pointer leaves a Pane and the tool is active.</p>


```csharp
protected virtual void OnMouseLeave(MouseEventArgs e)
```
### OnMouseMove(MouseEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Tool.yml" sourcestartlinenumber="1">Occurs when the mouse pointer moves over a Pane and the tool is active.</p>


```csharp
protected virtual void OnMouseMove(MouseEventArgs e)
```
### OnMouseUp(MouseButtonEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Tool.yml" sourcestartlinenumber="1">Occurs when any mouse button is released over a Pane.</p>


```csharp
protected virtual void OnMouseUp(MouseButtonEventArgs e)
```
### OnPaneActivateAsync(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Tool.yml" sourcestartlinenumber="1">Called to inform the Tool a Pane referencing it as the active tool is activating or deactivating.</p>


```csharp
protected virtual Task OnPaneActivateAsync(bool isActive)
```
### OnPointerDown(RoutedEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Tool.yml" sourcestartlinenumber="1">Occurs when a pointer is pressed on a Pane and the tool is active.</p>


```csharp
protected virtual void OnPointerDown(RoutedEventArgs e)
```
### OnPointerUp(RoutedEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Tool.yml" sourcestartlinenumber="1">Occurs when a pointer is released over a Pane.</p>


```csharp
protected virtual void OnPointerUp(RoutedEventArgs e)
```
### OnTouch(TouchInputEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Tool.yml" sourcestartlinenumber="1">Occurs when a touch event occurs over a Pane.</p>


```csharp
protected virtual void OnTouch(TouchInputEventArgs e)
```
### Shortcuts

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Tool.yml" sourcestartlinenumber="1">Gets a read only ShortCut collection for the current tool.</p>


```csharp
protected ReadOnlyCollection<ShortCut> Shortcuts { get; }
```
### UpdateCursor()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Tool.yml" sourcestartlinenumber="1">Occurs when a cursor is set on this tool.</p>


```csharp
protected virtual void UpdateCursor()
```


