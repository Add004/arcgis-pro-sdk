# ILayoutFactory

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Layouts.html">Layouts</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Layouts.ILayoutFactory.yml" sourcestartlinenumber="1">Provides access to layout creation members.</p>


## Object Signature

```csharp
public interface ILayoutFactory
```


## Members

### CopyLayout(Layout)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.ILayoutFactory.yml" sourcestartlinenumber="1">Creates a new layout by copying another layout.  This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
Layout CopyLayout(Layout sourceLayout)
```
### CreateLayout(CIMPage)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.ILayoutFactory.yml" sourcestartlinenumber="1">Creates a new layout using a defined CIM page.  This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
Layout CreateLayout(CIMPage cimPage = null)
```
### CreateLayout(double, double, LinearUnit, bool, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.ILayoutFactory.yml" sourcestartlinenumber="1">Creates a layout using a simple set of parameters. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
Layout CreateLayout(double width, double height, LinearUnit units, bool showRulers = true, double smallestRulerDivision = 0.5)
```


