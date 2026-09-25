# PresentationFrameworkExtender

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Core.PresentationFrameworkExtender.yml" sourcestartlinenumber="1">Contains extension methods to extend the <xref href="ArcGIS.Desktop.Framework.PaneCollection?text=PaneCollection" data-throw-if-not-resolved="false"></xref> class.</p>


## Object Signature

```csharp
public static class PresentationFrameworkExtender
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Core.PresentationFrameworkExtender.yml" sourcestartlinenumber="1">The class is primarily used to extend application panes that display the contents of a presentation view.  The same members will appear on both the extension class
and the <xref href="ArcGIS.Desktop.Framework.PaneCollection?text=PaneCollection" data-throw-if-not-resolved="false"></xref> class.</p>


## Members

### ClosePresentationPanes(PaneCollection, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.PresentationFrameworkExtender.yml" sourcestartlinenumber="1">Closes the presentation panes that reference the specified presentation path.</p>


```csharp
public static void ClosePresentationPanes(this PaneCollection paneCollection, string presentationUri = null)
```
### CreatePresentationPaneAsync(PaneCollection, Presentation)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.PresentationFrameworkExtender.yml" sourcestartlinenumber="1">Creates and activates a new presentation pane using a Presentation reference. Must be called on GUI thread.</p>


```csharp
public static Task<IPresentationPane> CreatePresentationPaneAsync(this PaneCollection paneCollection, Presentation presentation)
```
### FindPresentationPanes(PaneCollection, Presentation)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.PresentationFrameworkExtender.yml" sourcestartlinenumber="1">Finds the presentation panes that reference a specific presentation.</p>


```csharp
public static IList<IPresentationPane> FindPresentationPanes(this PaneCollection paneCollection, Presentation presentation = null)
```


