# ReportSectionElement

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Reports.html">Reports</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportSectionElement.yml" sourcestartlinenumber="1">Represents an abstract report element.</p>


## Object Signature

```csharp
public abstract class ReportSectionElement : GroupElement, IEquatable<Element>, IComparable, IElement, IElementInternal, IDisposable, IElementContainer, IElementContainerInternal, ISuspendableObservableCollection
```


## Members

### ClearElementSelection()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportSectionElement.yml" sourcestartlinenumber="1">Clear all report elements in the report section.</p>


```csharp
public virtual void ClearElementSelection()
```
### GetSelectedElements()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportSectionElement.yml" sourcestartlinenumber="1">Returns a collection of selected report elements in the report section.</p>


```csharp
public virtual IReadOnlyList<Element> GetSelectedElements()
```
### SelectAllElements()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportSectionElement.yml" sourcestartlinenumber="1">Select all report elements in the report section.</p>


```csharp
public virtual void SelectAllElements()
```
### SelectElements(IReadOnlyList&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportSectionElement.yml" sourcestartlinenumber="1">Set the selected report elements for the report section.</p>


```csharp
public virtual void SelectElements(IReadOnlyList<Element> elements)
```
### ZoomToSelectedElements()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportSectionElement.yml" sourcestartlinenumber="1">Zoom the report view to the extent of the selected elements of the section.  This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public virtual bool ZoomToSelectedElements()
```


