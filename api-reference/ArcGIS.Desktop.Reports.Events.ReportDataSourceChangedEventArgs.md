# ReportDataSourceChangedEventArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Reports.html">Reports</a>.<a class="xref" href="ArcGIS.Desktop.Reports.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Reports.Events.ReportDataSourceChangedEventArgs.yml" sourcestartlinenumber="1">Provides data for the <xref href="ArcGIS.Desktop.Reports.Events.ReportDataSourceChangedEvent?text=ReportDataSourceChangedEvent" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class ReportDataSourceChangedEventArgs : EventArgs
```


## Members

### DataSource

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.Events.ReportDataSourceChangedEventArgs.yml" sourcestartlinenumber="1">Gets the new <xref href="ArcGIS.Desktop.Reports.ReportDataSource?text=ReportDataSource" data-throw-if-not-resolved="false"></xref> properties.</p>


```csharp
public ReportDataSource DataSource { get; set; }
```
### Report

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.Events.ReportDataSourceChangedEventArgs.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Desktop.Reports.Report?text=Report" data-throw-if-not-resolved="false"></xref> that changed.</p>


```csharp
public Report Report { get; }
```
### ReportEventHint

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.Events.ReportDataSourceChangedEventArgs.yml" sourcestartlinenumber="1">Gets the property of the <xref href="ArcGIS.Desktop.Reports.ReportDataSource?text=ReportDataSource" data-throw-if-not-resolved="false"></xref> that changed.</p>


```csharp
public ReportEventHint ReportEventHint { get; set; }
```
### ReportSectionElement

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.Events.ReportDataSourceChangedEventArgs.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Desktop.Reports.ReportSectionElement?text=ReportSectionElement" data-throw-if-not-resolved="false"></xref> that changed.</p>


```csharp
public ReportSectionElement ReportSectionElement { get; }
```


