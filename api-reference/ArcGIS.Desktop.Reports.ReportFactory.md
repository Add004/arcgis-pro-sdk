# ReportFactory

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Reports.html">Reports</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportFactory.yml" sourcestartlinenumber="1">Provides methods to create new report project items.</p>


## Object Signature

```csharp
public class ReportFactory : IReportFactory
```

## Remarks

<p>
    Creating a new report generates a new report project item that appears in the Reports folder in the Contents pane.  
    </p>
<p>
    A new report project item is not automatically opened in a report view pane.  
    </p>


## Members

### CopyReport(Report)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportFactory.yml" sourcestartlinenumber="1">Copy an existing report.  This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Report CopyReport(Report report)
```
### CreateReport(string, ReportCustomTemplateDefinition)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportFactory.yml" sourcestartlinenumber="1">Creates a new report using a custom template and adds it to a project. The source data for the report can be either
a Layer or Table or a data connection to the data. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Report CreateReport(string name, ReportCustomTemplateDefinition templateDataDef)
```
### CreateReport(string, ReportDataSource)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportFactory.yml" sourcestartlinenumber="1">Creates a new report and adds it to a project. The source data for the report can be either
a Layer or Table or a data connection to the data. This method must be called on the MCT. Use QueuedTask.Run. Not supported for custom report templates (.rptt).</p>


```csharp
public Report CreateReport(string name, ReportDataSource reportDataSource)
```
### CreateReport(string, ReportDataSource, CIMPage, IEnumerable&lt;ReportFieldStatistic&gt;, ReportTemplate, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportFactory.yml" sourcestartlinenumber="1">Creates a new report and adds it to a project. The source data for the report can be either
a Layer or Table or a data connection to the data. This method must be called on the MCT. Use QueuedTask.Run. Not supported for custom report templates (.rptt).</p>


```csharp
public Report CreateReport(string name, ReportDataSource reportDataSource, CIMPage page, IEnumerable<ReportFieldStatistic> statistics, ReportTemplate template, string styling)
```
### Instance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportFactory.yml" sourcestartlinenumber="1">Gets the singleton instance for IReportFactory.</p>


```csharp
public static IReportFactory Instance { get; }
```


