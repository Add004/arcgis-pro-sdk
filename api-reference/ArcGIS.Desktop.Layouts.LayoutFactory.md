# LayoutFactory

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Layouts.html">Layouts</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutFactory.yml" sourcestartlinenumber="1">Provides methods to create new layout project items.</p>


## Object Signature

```csharp
public class LayoutFactory : ILayoutFactory
```

## Remarks

<p>
    Creating a new layout simply generates a new layout project item that appears in the Layouts folder in the Contents pane.  
    The next logical steps are to create new layout elements.  Refer to the <xref href="ArcGIS.Desktop.Layouts.ElementFactory?text=ElementFactory" data-throw-if-not-resolved="false"></xref>
    to add new elements to layout.
    </p>
<p>
    A new layout project item is not automatically opened in a layout view pane.  
    Use methods in the <xref href="ArcGIS.Desktop.Core.LayoutFrameworkExtender?text=+LayoutFrameworkExtender+" data-throw-if-not-resolved="false"></xref> to open a layout project item in a pane.
    </p>


## Members

### CopyLayout(Layout)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutFactory.yml" sourcestartlinenumber="1">Creates a layout by copying another layout. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Layout CopyLayout(Layout sourceLayout)
```
### CreateLayout(CIMPage)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutFactory.yml" sourcestartlinenumber="1">Creates a new layout using a defined CIM page.  This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public Layout CreateLayout(CIMPage page = null)
```
### CreateLayout(double, double, LinearUnit, bool, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutFactory.yml" sourcestartlinenumber="1">Creates a layout using a simple set of parameters. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Layout CreateLayout(double width, double height, LinearUnit units, bool showRulers = true, double smallestRulerDivision = 0.5)
```
### Instance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutFactory.yml" sourcestartlinenumber="1">Gets the singleton instance for ILayoutFactory</p>


```csharp
public static ILayoutFactory Instance { get; }
```


