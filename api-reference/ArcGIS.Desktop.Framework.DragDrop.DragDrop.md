# DragDrop

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.DragDrop.html">DragDrop</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DragDrop.yml" sourcestartlinenumber="1">Represents a utility class for drag and drop operations.</p>


## Object Signature

```csharp
public static class DragDrop
```


## Members

### DragAdornerTemplateProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DragDrop.yml" sourcestartlinenumber="1">Identifies the DragAdornerTemplate attached property.</p>


```csharp
public static readonly DependencyProperty DragAdornerTemplateProperty
```
### DragHandlerProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DragDrop.yml" sourcestartlinenumber="1">Identifies the DragHandler attached property.</p>


```csharp
public static readonly DependencyProperty DragHandlerProperty
```
### DragInfoChanged

- Kind: event

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DragDrop.yml" sourcestartlinenumber="1">DragInfoChanged event</p>


```csharp
public static event EventHandler DragInfoChanged
```
### DropHandlerProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DragDrop.yml" sourcestartlinenumber="1">Identifies the DropHandler attached property.</p>


```csharp
public static readonly DependencyProperty DropHandlerProperty
```
### GetDragAdornerTemplate(UIElement)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DragDrop.yml" sourcestartlinenumber="1">Gets the drag adorner for the specified UI element.</p>


```csharp
public static DataTemplate GetDragAdornerTemplate(UIElement target)
```
### GetDragHandler(UIElement)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DragDrop.yml" sourcestartlinenumber="1">Returns the drag handler associated with the specified UI element.</p>


```csharp
public static IDragSource GetDragHandler(UIElement target)
```
### GetIsDragSource(UIElement)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DragDrop.yml" sourcestartlinenumber="1">Returns true if the target is a drag source.</p>


```csharp
public static bool GetIsDragSource(UIElement target)
```
### GetIsDropTarget(UIElement)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DragDrop.yml" sourcestartlinenumber="1">Returns true if the UI element is a drop target.</p>


```csharp
public static bool GetIsDropTarget(UIElement target)
```
### GetSkipSelection(DependencyObject)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DragDrop.yml" sourcestartlinenumber="1">Return true if selection process is skipped</p>


```csharp
public static bool GetSkipSelection(DependencyObject obj)
```
### IsDragSourceProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DragDrop.yml" sourcestartlinenumber="1">Identifies the IsDragSource attached property.</p>


```csharp
public static readonly DependencyProperty IsDragSourceProperty
```
### IsDropTargetProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DragDrop.yml" sourcestartlinenumber="1">Identifies the IsDropTarget attached property.</p>


```csharp
public static readonly DependencyProperty IsDropTargetProperty
```
### SetDragAdornerTemplate(UIElement, DataTemplate)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DragDrop.yml" sourcestartlinenumber="1">Sets the drag adorner for the specified UI element.</p>


```csharp
public static void SetDragAdornerTemplate(UIElement target, DataTemplate value)
```
### SetDragHandler(UIElement, IDragSource)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DragDrop.yml" sourcestartlinenumber="1">Connects a drag handler with a UI element.</p>


```csharp
public static void SetDragHandler(UIElement target, IDragSource value)
```
### SetDropHandler(UIElement, IDropTarget)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DragDrop.yml" sourcestartlinenumber="1">Connects a drop handler with a UI element.</p>


```csharp
public static void SetDropHandler(UIElement target, IDropTarget value)
```
### SetIsDragSource(UIElement, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DragDrop.yml" sourcestartlinenumber="1">Establishes the target element as a drag source or not.</p>


```csharp
public static void SetIsDragSource(UIElement target, bool value)
```
### SetIsDropTarget(UIElement, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DragDrop.yml" sourcestartlinenumber="1">Establishes a UI element as a drop target.</p>


```csharp
public static void SetIsDropTarget(UIElement target, bool value)
```
### SetSkipSelection(DependencyObject, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DragDrop.yml" sourcestartlinenumber="1">If set to true, drag operation does not change selection</p>


```csharp
public static void SetSkipSelection(DependencyObject obj, bool value)
```
### SkipSelectionProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DragDrop.yml" sourcestartlinenumber="1">Identifies the SkipSelection attached property</p>


```csharp
public static readonly DependencyProperty SkipSelectionProperty
```


