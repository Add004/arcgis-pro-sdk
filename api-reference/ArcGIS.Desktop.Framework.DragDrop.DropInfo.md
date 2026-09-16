# DropInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.DragDrop.html">DragDrop</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DropInfo.yml" sourcestartlinenumber="1">Represents information about the drop target and data being dropped.</p>


## Object Signature

```csharp
public class DropInfo
```


## Members

### Data

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DropInfo.yml" sourcestartlinenumber="1">Gets the drag data.</p>


```csharp
public object Data { get; }
```
### DragEventArgs

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DropInfo.yml" sourcestartlinenumber="1">Gets arguments relevant to all drag-and-drop events.</p>


```csharp
public DragEventArgs DragEventArgs { get; }
```
### DragInfo

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DropInfo.yml" sourcestartlinenumber="1">Gets a <xref href="ArcGIS.Desktop.Framework.DragDrop.DropInfo.DragInfo" data-throw-if-not-resolved="false"></xref> object holding information about the source of the drag,
if the drag came from within the framework.</p>


```csharp
public DragInfo DragInfo { get; }
```
### DropTargetAdorner

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DropInfo.yml" sourcestartlinenumber="1">Gets or sets the class of drop target to display.</p>


```csharp
public Type DropTargetAdorner { get; set; }
```
### Effects

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DropInfo.yml" sourcestartlinenumber="1">Gets or sets the allowed effects for the drop.</p>


```csharp
public DragDropEffects Effects { get; set; }
```
### Handled

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DropInfo.yml" sourcestartlinenumber="1">Gets or sets boolean indicating if the drop was handled.</p>


```csharp
public bool Handled { get; set; }
```
### InsertIndex

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DropInfo.yml" sourcestartlinenumber="1">Gets the current insert position within <xref href="ArcGIS.Desktop.Framework.DragDrop.DropInfo.TargetCollection" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public int InsertIndex { get; set; }
```
### Items

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DropInfo.yml" sourcestartlinenumber="1">A list collection of the drop items.</p>


```csharp
public List<DropDataItem> Items
```
### TargetCollection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DropInfo.yml" sourcestartlinenumber="1">Gets the collection that the target ItemsControl is bound to.</p>


```csharp
public IEnumerable TargetCollection { get; }
```
### TargetItem

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DropInfo.yml" sourcestartlinenumber="1">Gets the object that the current drop target is bound to.</p>


```csharp
public object TargetItem { get; set; }
```
### TargetModel

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DropInfo.yml" sourcestartlinenumber="1">Allows drop handlers to specify an alternate target object.</p>


```csharp
public object TargetModel { get; set; }
```
### VisualTarget

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DropInfo.yml" sourcestartlinenumber="1">Gets the control that is the current drop target.</p>


```csharp
public UIElement VisualTarget { get; }
```
### VisualTargetItem

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DropInfo.yml" sourcestartlinenumber="1">Gets the item in an ItemsControl that is the current drop target.</p>


```csharp
public UIElement VisualTargetItem { get; set; }
```
### VisualTargetOrientation

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DropInfo.yml" sourcestartlinenumber="1">Gets the orientation of the current drop target.</p>


```csharp
public Orientation VisualTargetOrientation { get; }
```


