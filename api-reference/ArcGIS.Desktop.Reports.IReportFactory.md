# IReportFactory

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Reports.html">Reports</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Reports.IReportFactory.yml" sourcestartlinenumber="1">Provides access to report creation members.</p>


## Object Signature

```csharp
public interface IReportFactory
```


## Members

### CopyReport(Report)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.IReportFactory.yml" sourcestartlinenumber="1">Copy an existing report.</p>


```csharp
Report CopyReport(Report report)
```
### CreateReport(string, ReportCustomTemplateDefinition)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.IReportFactory.yml" sourcestartlinenumber="1">Creates a new report using a custom template and adds it to a project. The source data for the report can be either
a Layer or Table or a data connection to the data. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
Report CreateReport(string name, ReportCustomTemplateDefinition templateDataDef)
```
### CreateReport(string, ReportDataSource)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.IReportFactory.yml" sourcestartlinenumber="1">Creates a new report and adds it to a project. The source data for the report can be either
a Layer or Table or a data connection to the data. This method must be called on the MCT. Use QueuedTask.Run. Not supported for custom report templates (.rptt).</p>


```csharp
Report CreateReport(string name, ReportDataSource reportDataSource)
```
### CreateReport(string, ReportDataSource, CIMPage, IEnumerable&lt;ReportFieldStatistic&gt;, ReportTemplate, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.IReportFactory.yml" sourcestartlinenumber="1">Creates a new report and adds it to a project. The source data for the report can be either
a Layer or Table or a data connection to the data. This method must be called on the MCT. Use QueuedTask.Run. Not supported for custom report templates (.rptt).</p>


```csharp
Report CreateReport(string name, ReportDataSource reportDataSource, CIMPage page, IEnumerable<ReportFieldStatistic> statistics, ReportTemplate template, string styling)
```


