# ReportExportOptions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Reports.html">Reports</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportExportOptions.yml" sourcestartlinenumber="1">Represents a collection of settings for exporting a report.</p>


## Object Signature

```csharp
public class ReportExportOptions
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportExportOptions.yml" sourcestartlinenumber="1">Before you can export a report, you need to configure your <xref href="ArcGIS.Desktop.Mapping.ExportFormat?text=ExportFormat" data-throw-if-not-resolved="false"></xref>
and you need to construct your export settings.</p>


## Members

### ReportExportOptions()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportExportOptions.yml" sourcestartlinenumber="1">Creates a collection of export options specific to exporting a report.</p>


```csharp
public ReportExportOptions()
```
### CustomPages

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportExportOptions.yml" sourcestartlinenumber="1">Gets or sets a string that represents a list of pages and/or page ranges.</p>


```csharp
public string CustomPages { get; set; }
```
### ExportPageOption

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportExportOptions.yml" sourcestartlinenumber="1">Gets and sets the collection of report pages to be exported.</p>


```csharp
public ExportPageOptions ExportPageOption { get; set; }
```
### StartingPageNumberLabelOffset

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportExportOptions.yml" sourcestartlinenumber="1">Gets and sets the starting page number label offset.</p>


```csharp
public int StartingPageNumberLabelOffset { get; set; }
```
### TotalPageNumberOverride

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportExportOptions.yml" sourcestartlinenumber="1">Gets and sets the total page number label offset.</p>


```csharp
public int TotalPageNumberOverride { get; set; }
```


