# ReportSectionChangedEventArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Reports.html">Reports</a>.<a class="xref" href="ArcGIS.Desktop.Reports.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Reports.Events.ReportSectionChangedEventArgs.yml" sourcestartlinenumber="1">Provides data for the <xref href="ArcGIS.Desktop.Reports.Events.ReportSectionChangedEvent?text=ReportSectionChangedEvent" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class ReportSectionChangedEventArgs : EventArgs
```


## Members

### ElementName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.Events.ReportSectionChangedEventArgs.yml" sourcestartlinenumber="1">Gets the name of the section element that changed.</p>


```csharp
public string ElementName { get; set; }
```
### Report

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.Events.ReportSectionChangedEventArgs.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Desktop.Reports.Report?text=Report" data-throw-if-not-resolved="false"></xref> that changed.</p>


```csharp
public Report Report { get; }
```
### ReportEventHint

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.Events.ReportSectionChangedEventArgs.yml" sourcestartlinenumber="1">Gets the hint to indicate what changed.</p>


```csharp
public ReportEventHint ReportEventHint { get; set; }
```
### ReportSectionElement

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.Events.ReportSectionChangedEventArgs.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Desktop.Reports.ReportSectionElement?text=ReportSectionElement" data-throw-if-not-resolved="false"></xref> that changed.
This object will be null if the element was removed.</p>


```csharp
public ReportSectionElement ReportSectionElement { get; }
```


