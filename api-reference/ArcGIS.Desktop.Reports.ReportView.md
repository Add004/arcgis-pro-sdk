# ReportView

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Reports.html">Reports</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportView.yml" sourcestartlinenumber="1">Represents the view of report in a pane.</p>


## Object Signature

```csharp
public sealed class ReportView
```

## Remarks

<p>
    A project can contain multiple rerports.  A report view is a pane that displays the view of a report.  
    Report views are the primary interface used to display, navigate, and select report elements.  
    The report being visualized in the view can be accessed via the <xref href="ArcGIS.Desktop.Reports.ReportView.Report?text=Report+" data-throw-if-not-resolved="false"></xref> property.
    </p>
<p>
    There can be multiple report views open at a given time, but there can only be one active report view.  
    The active report view will set the context for the ribbon and many of the dock panes in the application.
    The <xref href="ArcGIS.Desktop.Reports.ReportView.Active?text=Active+" data-throw-if-not-resolved="false"></xref> property will return null if there is no active report view.
    </p>
<p>
    The report view has several "ZoomTo" nagivation methods and it also provides the context for managing selected items in the Contents pane.  
    For example, the <xref href="ArcGIS.Desktop.Reports.ReportView.GetSelectedElements?text=GetSelectedElements+" data-throw-if-not-resolved="false"></xref> method returns a collection of selected page report elements.
    </p>


## Members

### Active

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportView.yml" sourcestartlinenumber="1">Gets the active report view.</p>


```csharp
public static ReportView Active { get; }
```
### ClearElementSelection()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportView.yml" sourcestartlinenumber="1">Clear all report elements in the report view.</p>


```csharp
public void ClearElementSelection()
```
### GetSelectedElements()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportView.yml" sourcestartlinenumber="1">Returns a collection of selected report elements.</p>


```csharp
public IReadOnlyList<Element> GetSelectedElements()
```
### Refresh()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportView.yml" sourcestartlinenumber="1">Force the report view to redraw. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Refresh()
```
### Report

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportView.yml" sourcestartlinenumber="1">Gets the report associated with the report view.</p>


```csharp
public Report Report { get; }
```
### SelectAllElements()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportView.yml" sourcestartlinenumber="1">Select all report elements in a report view.</p>


```csharp
public void SelectAllElements()
```
### SelectElement(Element)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportView.yml" sourcestartlinenumber="1">Set the element selected for the report view.</p>


```csharp
public void SelectElement(Element element)
```
### SelectElements(IReadOnlyList&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportView.yml" sourcestartlinenumber="1">Set the selected report elements for the report view.</p>


```csharp
public void SelectElements(IReadOnlyList<Element> elements)
```
### UnSelectElement(Element)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportView.yml" sourcestartlinenumber="1">Unselect the element within the report view.</p>


```csharp
public void UnSelectElement(Element element)
```
### UnSelectElements(IEnumerable&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportView.yml" sourcestartlinenumber="1">Unselect the elements within the report view.</p>


```csharp
public void UnSelectElements(IEnumerable<Element> elements = null)
```
### ZoomTo(Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportView.yml" sourcestartlinenumber="1">Zoom the report view to the extent defined by a geometry.  This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public bool ZoomTo(Geometry geometry)
```
### ZoomToElement(Element)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportView.yml" sourcestartlinenumber="1">Zoom to the extent of the element.
This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public bool ZoomToElement(Element element)
```
### ZoomToElements(IEnumerable&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportView.yml" sourcestartlinenumber="1">Zoom to the extent of the elements.
This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public bool ZoomToElements(IEnumerable<Element> elements)
```
### ZoomToPageWidth()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportView.yml" sourcestartlinenumber="1">Zoom the report view to the width of the page.  This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public bool ZoomToPageWidth()
```
### ZoomToSelectedElements()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportView.yml" sourcestartlinenumber="1">Zoom the report view to the extent of the selected elements.  This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public bool ZoomToSelectedElements()
```
### ZoomToWholePage()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportView.yml" sourcestartlinenumber="1">Zoom the report view to the whole page.  This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public bool ZoomToWholePage()
```


