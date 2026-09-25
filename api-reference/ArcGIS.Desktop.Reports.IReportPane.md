# IReportPane

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Reports.html">Reports</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Reports.IReportPane.yml" sourcestartlinenumber="1">Represents a pane which contains a report view.</p>


## Object Signature

```csharp
public interface IReportPane
```


## Members

### Caption

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.IReportPane.yml" sourcestartlinenumber="1">Gets or sets the caption for the pane the way it appears on the tab.</p>


```csharp
string Caption { get; set; }
```
### ReportView

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.IReportPane.yml" sourcestartlinenumber="1">Gets the report view contained within the pane.</p>


```csharp
ReportView ReportView { get; }
```
### ViewState

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.IReportPane.yml" sourcestartlinenumber="1">Gets the definition of the view within the pane.</p>


```csharp
CIMLayoutView ViewState { get; }
```


