# LayoutExtensions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Layouts.html">Layouts</a>
- Assembly: ArcGIS.Desktop.Extensions.dll

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutExtensions.yml" sourcestartlinenumber="1">Layout Extension methods.</p>


## Object Signature

```csharp
public static class LayoutExtensions
```


## Members

### ClearSketchAsync(LayoutView)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutExtensions.yml" sourcestartlinenumber="1">Clears the current sketch in the view.</p>


```csharp
public static Task ClearSketchAsync(this LayoutView layoutView)
```
### GetCurrentSketchAsync(LayoutView)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutExtensions.yml" sourcestartlinenumber="1">Gets the current geometry of the sketch without finishing it.</p>


```csharp
public static Task<Geometry> GetCurrentSketchAsync(this LayoutView layoutView)
```
### SelectElements(LayoutView, Geometry, SelectionCombinationMethod, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutExtensions.yml" sourcestartlinenumber="1">Select elements that visually intersect a geometry.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static IReadOnlyList<Element> SelectElements(this LayoutView layoutView, Geometry geometry, SelectionCombinationMethod method = 0, bool isWhollyWithin = false)
```


