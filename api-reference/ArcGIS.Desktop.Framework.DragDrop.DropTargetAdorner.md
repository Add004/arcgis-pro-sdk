# DropTargetAdorner

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.DragDrop.html">DragDrop</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DropTargetAdorner.yml" sourcestartlinenumber="1">Represents a drop target adorner. This is an abstract class.</p>


## Object Signature

```csharp
public abstract class DropTargetAdorner : Adorner, IAnimatable, IFrameworkInputElement, IInputElement, ISupportInitialize, IQueryAmbient
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DropTargetAdorner.yml" sourcestartlinenumber="1">Drop targets adorners are the UI elements that appear over a valid drop target. Leaf classes typically override OnRender.</p>


## Members

### Detatch()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DropTargetAdorner.yml" sourcestartlinenumber="1">Removes the specified adorner from the adorner layer.</p>


```csharp
public void Detatch()
```
### DropInfo

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.DragDrop.DropTargetAdorner.yml" sourcestartlinenumber="1">Gets or sets information about the drop target and data being dropped.</p>


```csharp
public DropInfo DropInfo { get; set; }
```


