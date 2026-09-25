# ReportFrameworkExtender

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Core.ReportFrameworkExtender.yml" sourcestartlinenumber="1">Contains extension methods to extend the <xref href="ArcGIS.Desktop.Framework.PaneCollection?text=PaneCollection" data-throw-if-not-resolved="false"></xref> class.</p>


## Object Signature

```csharp
public static class ReportFrameworkExtender
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Core.ReportFrameworkExtender.yml" sourcestartlinenumber="1">The class is primarily used to extend application panes that display the contents of a rerport view. The same members will appear on both the extension class
and the <xref href="ArcGIS.Desktop.Framework.PaneCollection?text=PaneCollection" data-throw-if-not-resolved="false"></xref> class.</p>


## Members

### CloseReportPanes(PaneCollection, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.ReportFrameworkExtender.yml" sourcestartlinenumber="1">Close the report panes that reference the specified report path or all report panes if reportUri is not specified.</p>


```csharp
public static void CloseReportPanes(this PaneCollection panes, string reportUri = null)
```
### CreateReportPaneAsync(PaneCollection, Report)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.ReportFrameworkExtender.yml" sourcestartlinenumber="1">Create and activate a new report pane using a Report reference. Must be called on GUI thread.</p>


```csharp
public static Task<IReportPane> CreateReportPaneAsync(this PaneCollection panes, Report report)
```
### FindReportPanes(PaneCollection, Report)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.ReportFrameworkExtender.yml" sourcestartlinenumber="1">Find the report panes that reference a specific report.</p>


```csharp
public static IEnumerable<IReportPane> FindReportPanes(this PaneCollection panes, Report report = null)
```


