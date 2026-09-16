# IDropTarget

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.DragDrop.html">DragDrop</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.IDropTarget.yml" sourcestartlinenumber="1">Definition of a drop handler.</p>


## Object Signature

```csharp
public interface IDropTarget
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.IDropTarget.yml" sourcestartlinenumber="1">All drop handlers must implement this interface.</p>


## Members

### CreateDragAdorner(DataTemplate)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.IDropTarget.yml" sourcestartlinenumber="1">Allows the creation of a custom drag adorner</p>


```csharp
UIElement CreateDragAdorner(DataTemplate template)
```
### OnDragLeave()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.IDropTarget.yml" sourcestartlinenumber="1">Notification that the mouse pointer is leaving the current element.</p>


```csharp
void OnDragLeave()
```
### OnDragOver(DropInfo)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.IDropTarget.yml" sourcestartlinenumber="1">Updates the current drag state.</p>


```csharp
void OnDragOver(DropInfo dropInfo)
```
### OnDrop(DropInfo)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.IDropTarget.yml" sourcestartlinenumber="1">Performs a drop.</p>


```csharp
void OnDrop(DropInfo dropInfo)
```


