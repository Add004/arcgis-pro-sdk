# MapSeriesExportOptions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Layouts.html">Layouts</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapSeriesExportOptions.yml" sourcestartlinenumber="1">Represents a collection of settings for exporting a map series.</p>


## Object Signature

```csharp
public class MapSeriesExportOptions
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapSeriesExportOptions.yml" sourcestartlinenumber="1">Before you can export a map series, you need to configure your <xref href="ArcGIS.Desktop.Mapping.ExportFormat?text=ExportFormat" data-throw-if-not-resolved="false"></xref>
and you need to construct your export settings.</p>


## Members

### MapSeriesExportOptions()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapSeriesExportOptions.yml" sourcestartlinenumber="1">Creates a collection of export options specific to exporting a map series.</p>


```csharp
public MapSeriesExportOptions()
```
### CustomPages

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapSeriesExportOptions.yml" sourcestartlinenumber="1">Gets or sets a string that represents a list of pages and/or page ranges.</p>


```csharp
public string CustomPages { get; set; }
```
### DoOrderPagesByGrouping

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapSeriesExportOptions.yml" sourcestartlinenumber="1">Gets or set if series pages are exported in the grouping order shown in the Contents pane.</p>


```csharp
public bool DoOrderPagesByGrouping { get; set; }
```
### ExportFileOptions

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapSeriesExportOptions.yml" sourcestartlinenumber="1">Gets and sets how the map series will be exported to file.</p>


```csharp
public ExportFileOptions ExportFileOptions { get; set; }
```
### ExportPages

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapSeriesExportOptions.yml" sourcestartlinenumber="1">Gets and sets the collection of map series pages to be exported.</p>


```csharp
public ExportPages ExportPages { get; set; }
```
### ShowSelectedSymbology

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.MapSeriesExportOptions.yml" sourcestartlinenumber="1">Gets or sets if feature layer selection symbology is exported.</p>


```csharp
public bool ShowSelectedSymbology { get; set; }
```


