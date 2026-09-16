# LayoutProjectItem

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Layouts.html">Layouts</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutProjectItem.yml" sourcestartlinenumber="1">Represents a layout project item.</p>


## Object Signature

```csharp
public sealed class LayoutProjectItem : ProjectItem, IProjectItemEdit, IProjectItemRename, IPortalProjectItem
```

## Remarks

<p>Each <xref href="ArcGIS.Desktop.Layouts.Layout?text=Layout" data-throw-if-not-resolved="false"></xref> in a project is associated with a LayoutProjectItem.  This item contains numerous 
    read-only metadata properties about the layout. Although a layout may exist in the project, it may not be loaded (an open layout view).  To reference the 
    actual layout and ensure it is loaded into memory, you must use the <xref href="ArcGIS.Desktop.Layouts.LayoutProjectItem.GetLayout?text=GetLayout" data-throw-if-not-resolved="false"></xref> method.</p>


## Members

### CanOpenView()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutProjectItem.yml" sourcestartlinenumber="1">Gets whether the view can be opened</p>


```csharp
protected override bool CanOpenView()
```
### GetLayout()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutProjectItem.yml" sourcestartlinenumber="1">Loads and returns the <xref href="ArcGIS.Desktop.Layouts.Layout?text=Layout" data-throw-if-not-resolved="false"></xref> associated with the LayoutPrjectItem.  This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public Layout GetLayout()
```


