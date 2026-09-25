# XLSXFormat

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.XLSXFormat.yml" sourcestartlinenumber="1">Represents an Excel spreadsheet (XLSX) object that can be used to export a
<xref href="ArcGIS.Desktop.Layouts.Report?text=Report" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class XLSXFormat : ExportFormat
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.XLSXFormat.yml" sourcestartlinenumber="1">XLSX files</p>


## Members

### XLSXFormat()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.XLSXFormat.yml" sourcestartlinenumber="1">Initialize a new instance of XLSXFormat.</p>


```csharp
public XLSXFormat()
```
### AutoRowHeight

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.XLSXFormat.yml" sourcestartlinenumber="1">Gets or sets if row heights are automatically set.</p>


```csharp
public bool AutoRowHeight { get; set; }
```
### DisplayGridLines

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.XLSXFormat.yml" sourcestartlinenumber="1">Gets or sets if grid lines will be displayed.</p>


```csharp
public bool DisplayGridLines { get; set; }
```
### ExportSheetOption

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.XLSXFormat.yml" sourcestartlinenumber="1">Gets or sets the export sheet option.</p>


```csharp
public ExportXLSXSheetOptions ExportSheetOption { get; set; }
```
### ExportValuesAsText

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.XLSXFormat.yml" sourcestartlinenumber="1">Gets or sets if data values are exported for unsupported numeric formats.</p>


```csharp
public bool ExportValuesAsText { get; set; }
```
### RemoveVerticalSpace

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.XLSXFormat.yml" sourcestartlinenumber="1">Gets or sets the removal of empty rows.</p>


```csharp
public bool RemoveVerticalSpace { get; set; }
```
### UseCellMerging

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.XLSXFormat.yml" sourcestartlinenumber="1">Gets or sets if cells will be merged.</p>


```csharp
public bool UseCellMerging { get; set; }
```


