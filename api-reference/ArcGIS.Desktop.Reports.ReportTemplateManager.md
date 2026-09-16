# ReportTemplateManager

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Reports.html">Reports</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportTemplateManager.yml" sourcestartlinenumber="1">Manages the report templates.</p>


## Object Signature

```csharp
public static class ReportTemplateManager
```


## Members

### GetCustomTemplateDefinition(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportTemplateManager.yml" sourcestartlinenumber="1">Gets the definition of a custom template to be populated and used to create a report. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static ReportCustomTemplateDefinition GetCustomTemplateDefinition(string templateName)
```
### GetCustomTemplateInfo(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportTemplateManager.yml" sourcestartlinenumber="1">Gets the custom report templates.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static ReportTemplate GetCustomTemplateInfo(string templatePath)
```
### GetCustomTemplateInfoAsync(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportTemplateManager.yml" sourcestartlinenumber="1">Gets the custom report templates.</p>


```csharp
public static Task<ReportTemplate> GetCustomTemplateInfoAsync(string templatePath)
```
### GetCustomTemplates(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportTemplateManager.yml" sourcestartlinenumber="1">Gets the custom report templates.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static IReadOnlyList<ReportTemplate> GetCustomTemplates(string templatePath)
```
### GetCustomTemplatesAsync(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportTemplateManager.yml" sourcestartlinenumber="1">Gets the custom report templates.</p>


```csharp
public static Task<IReadOnlyList<ReportTemplate>> GetCustomTemplatesAsync(string templatePath)
```
### GetTemplates()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportTemplateManager.yml" sourcestartlinenumber="1">Gets the report templates. They are loaded if needed.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static IReadOnlyList<ReportTemplate> GetTemplates()
```
### GetTemplatesAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportTemplateManager.yml" sourcestartlinenumber="1">Gets the report templates. They are loaded if needed.</p>


```csharp
public static Task<IReadOnlyList<ReportTemplate>> GetTemplatesAsync()
```


