# ReportSection

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Reports.html">Reports</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportSection.yml" sourcestartlinenumber="1">Represents a report section.</p>


## Object Signature

```csharp
public class ReportSection : ReportSectionElement, IEquatable<Element>, IComparable, IElement, IElementInternal, IDisposable, IElementContainer, IElementContainerInternal, ISuspendableObservableCollection
```


## Members

### DataSource

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportSection.yml" sourcestartlinenumber="1">Gets or sets the DataSource property.</p>


```csharp
public ReportDataSource DataSource { get; }
```
### FindGroupSections(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportSection.yml" sourcestartlinenumber="1">Find the group header and footer sections for a field.</p>


```csharp
public (ReportGroupHeader header, ReportGroupFooter footer) FindGroupSections(string fieldName)
```
### GetCIMExpressionInfos()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportSection.yml" sourcestartlinenumber="1">Gets the expressions.</p>


```csharp
public List<CIMExpressionInfo> GetCIMExpressionInfos()
```


