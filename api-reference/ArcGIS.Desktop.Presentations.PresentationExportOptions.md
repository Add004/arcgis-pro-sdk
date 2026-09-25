# PresentationExportOptions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Presentations.html">Presentations</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationExportOptions.yml" sourcestartlinenumber="1">Represents a collection of settings for exporting a presentation.</p>


## Object Signature

```csharp
public class PresentationExportOptions
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationExportOptions.yml" sourcestartlinenumber="1">Before you can export a presentation, you need to configure your <xref href="ArcGIS.Desktop.Mapping.ExportFormat?text=ExportFormat" data-throw-if-not-resolved="false"></xref>
and construct export settings.</p>


## Members

### PresentationExportOptions()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationExportOptions.yml" sourcestartlinenumber="1">Creates a collection of export options specific for exporting a presentation.</p>


```csharp
public PresentationExportOptions()
```
### CustomPages

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationExportOptions.yml" sourcestartlinenumber="1">Gets or sets a string that represents a list of pages and/or page ranges.</p>


```csharp
public string CustomPages { get; set; }
```
### PageRangeOption

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationExportOptions.yml" sourcestartlinenumber="1">Gets or sets the the page range option.</p>


```csharp
public ExportPageOptions PageRangeOption { get; set; }
```


