# ReportProjectItem

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Reports.html">Reports</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportProjectItem.yml" sourcestartlinenumber="1">Represents a report project item.</p>


## Object Signature

```csharp
public sealed class ReportProjectItem : ProjectItem, IProjectItemEdit, IProjectItemRename, IPortalProjectItem
```

## Remarks

<p>Each <xref href="ArcGIS.Desktop.Internal.Reports.Report?text=Report" data-throw-if-not-resolved="false"></xref> in a project is associated with a ReportProjectItem.  This item contains numerous 
    read-only metadata properties about the report. Although a report may exist in the project, it may not be loaded (an open report view).  To reference the 
    actual report and ensure it is loaded into memory, you must use the <xref href="ArcGIS.Desktop.Internal.Reports.ReportProjectItem.GetReport?text=GetReport" data-throw-if-not-resolved="false"></xref> method.</p>


## Members

### DisplayType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportProjectItem.yml" sourcestartlinenumber="1">Gets the report item display type string.</p>


```csharp
protected override string DisplayType { get; }
```
### GetReport()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportProjectItem.yml" sourcestartlinenumber="1">Loads and returns the <xref href="ArcGIS.Desktop.Reports.Report?text=Report" data-throw-if-not-resolved="false"></xref> associated with the ReportProjectItem.  This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public Report GetReport()
```


