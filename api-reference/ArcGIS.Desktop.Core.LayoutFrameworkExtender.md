# LayoutFrameworkExtender

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Core.LayoutFrameworkExtender.yml" sourcestartlinenumber="1">Contains extension methods to extend the <xref href="ArcGIS.Desktop.Framework.PaneCollection?text=PaneCollection" data-throw-if-not-resolved="false"></xref> class.</p>


## Object Signature

```csharp
public static class LayoutFrameworkExtender
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Core.LayoutFrameworkExtender.yml" sourcestartlinenumber="1">The class is primarily used to extend application panes that display the contents of a layout view.  The same members will appear on both the extension class
and the <xref href="ArcGIS.Desktop.Framework.PaneCollection?text=PaneCollection" data-throw-if-not-resolved="false"></xref> class.</p>


## Members

### CloseLayoutPanes(PaneCollection, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.LayoutFrameworkExtender.yml" sourcestartlinenumber="1">Close the layout panes that reference the specified layout path.</p>


```csharp
public static void CloseLayoutPanes(this PaneCollection paneCollection, string layoutUri = null)
```
### CreateLayoutPaneAsync(PaneCollection, Layout)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.LayoutFrameworkExtender.yml" sourcestartlinenumber="1">Create and activate a new layout pane using a Layout reference. Must be called on GUI thread.</p>


```csharp
public static Task<ILayoutPane> CreateLayoutPaneAsync(this PaneCollection paneCollection, Layout layout)
```
### FindLayoutPanes(PaneCollection, Layout)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.LayoutFrameworkExtender.yml" sourcestartlinenumber="1">Find the layout panes that reference a specific layout.</p>


```csharp
public static IList<ILayoutPane> FindLayoutPanes(this PaneCollection paneCollection, Layout layout = null)
```


