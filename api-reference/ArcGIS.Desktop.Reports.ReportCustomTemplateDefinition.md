# ReportCustomTemplateDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Reports.html">Reports</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportCustomTemplateDefinition.yml" sourcestartlinenumber="1">Represents the data to create a report using a custom template</p>


## Object Signature

```csharp
public class ReportCustomTemplateDefinition
```


## Members

### ReportCustomTemplateDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportCustomTemplateDefinition.yml" sourcestartlinenumber="1">Creates a ReportCustomTemplateDefinition object.</p>


```csharp
public ReportCustomTemplateDefinition()
```
### CanCreateReport()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportCustomTemplateDefinition.yml" sourcestartlinenumber="1">Determines if a new Report using the specified ReportCustomTemplateDefinition can be created.</p>


```csharp
public bool CanCreateReport()
```
### this[string]

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportCustomTemplateDefinition.yml" sourcestartlinenumber="1">Access and assign the data source by indexing the element name.</p>


```csharp
public object this[string elementName] { get; set; }
```
### ReportTemplateDataSourceItems

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportCustomTemplateDefinition.yml" sourcestartlinenumber="1">Gets the list of ReportCustomTemplateDataSourceInfos.</p>


```csharp
public IEnumerable<ReportCustomTemplateDataSourceInfo> ReportTemplateDataSourceItems { get; }
```
### SupplementalPageValues

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportCustomTemplateDefinition.yml" sourcestartlinenumber="1">Gets and sets the list of supplemental page items to be used in the report. An item can either be a URI to
a layout in the project or a path to a .pagx file on disk.</p>


```csharp
public List<string> SupplementalPageValues { get; set; }
```


