# DragInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.DragDrop.html">DragDrop</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DragInfo.yml" sourcestartlinenumber="1">Represents information about the data being dragged.</p>


## Object Signature

```csharp
public class DragInfo
```


## Members

### DragInfo(object, MouseButtonEventArgs)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DragInfo.yml" sourcestartlinenumber="1">Instantiates a new DragInfo instance.</p>


```csharp
public DragInfo(object sender, MouseButtonEventArgs e)
```
### Data

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DragInfo.yml" sourcestartlinenumber="1">Gets or sets the drag data.</p>


```csharp
public object Data { get; set; }
```
### DragStartPosition

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DragInfo.yml" sourcestartlinenumber="1">Gets the position of the click that initiated the drag, relative to <xref href="ArcGIS.Desktop.Framework.DragDrop.DragInfo.VisualSource" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public Point DragStartPosition { get; }
```
### Effects

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DragInfo.yml" sourcestartlinenumber="1">Gets or sets the allowed effects for the drag.</p>


```csharp
public DragDropEffects Effects { get; set; }
```
### MouseButton

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DragInfo.yml" sourcestartlinenumber="1">Gets the mouse button that initiated the drag.</p>


```csharp
public MouseButton MouseButton { get; }
```
### OutOfProcData

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DragInfo.yml" sourcestartlinenumber="1">Gets or sets the drag data meant for other instances of Pro. Clients should set this when<br>
<xref href="ArcGIS.Desktop.Framework.DragDrop.DragInfo.Data" data-throw-if-not-resolved="false"></xref> cannot be serialized, and they need a different representation for
out-of-process cases.</p>


```csharp
public object OutOfProcData { get; set; }
```
### SourceCollection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DragInfo.yml" sourcestartlinenumber="1">Gets the collection that the source ItemsControl is bound to.</p>


```csharp
public IEnumerable SourceCollection { get; }
```
### SourceItem

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DragInfo.yml" sourcestartlinenumber="1">Gets the object that a dragged item is bound to.</p>


```csharp
public object SourceItem { get; }
```
### SourceItems

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DragInfo.yml" sourcestartlinenumber="1">Gets a collection of objects that the selected items in an ItemsControl are bound to.</p>


```csharp
public IEnumerable SourceItems { get; }
```
### VisualSource

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DragInfo.yml" sourcestartlinenumber="1">Gets the control that initiated the drag.</p>


```csharp
public UIElement VisualSource { get; }
```
### VisualSourceItem

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DragInfo.yml" sourcestartlinenumber="1">Gets the item in an ItemsControl that started the drag.</p>


```csharp
public UIElement VisualSourceItem { get; }
```


