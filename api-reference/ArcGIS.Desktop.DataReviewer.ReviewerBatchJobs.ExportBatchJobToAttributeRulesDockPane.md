# ExportBatchJobToAttributeRulesDockPane

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.DataReviewer.html">DataReviewer</a>.<a class="xref" href="ArcGIS.Desktop.DataReviewer.ReviewerBatchJobs.html">ReviewerBatchJobs</a>
- Assembly: ArcGIS.Desktop.DataReviewer.dll

<p sourcefile="api/ArcGIS.Desktop.DataReviewer.ReviewerBatchJobs.ExportBatchJobToAttributeRulesDockPane.yml" sourcestartlinenumber="1">This class is not for public use and is used internally by the system to
implement support for other esri modules</p>


## Object Signature

```csharp
[Obsolete("Data quality workflows and related tools based on the Reviewer Workspace are deprecated. As a result, the Data Reviewer Assembly and Namespaces will be removed at ArcGIS Pro 4.0, the next major release. It is recommended that users migrate to ArcGIS Data Reviewer attribute rules-based workflows. Learn more about migrating to attribute rules, https://www.esri.com/arcgis-blog/products/data-reviewer/data-management/migrating-to-attributes-rules-using-arcgis-data-reviewer/", DiagnosticId = "ARCGISPRO40", UrlFormat = "https://www.esri.com/arcgis-blog/products/data-reviewer/data-management/migrating-to-attributes-rules-using-arcgis-data-reviewer/")]
public class ExportBatchJobToAttributeRulesDockPane : DockPane, IDataErrorInfo
```


## Members

### ExportBatchJobToAttributeRulesDockPane()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.DataReviewer.ReviewerBatchJobs.ExportBatchJobToAttributeRulesDockPane.yml" sourcestartlinenumber="1">This class is not for public use and is used internally by the system to
implement support for other esri modules</p>


```csharp
public ExportBatchJobToAttributeRulesDockPane()
```
### BatchJobFile

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.DataReviewer.ReviewerBatchJobs.ExportBatchJobToAttributeRulesDockPane.yml" sourcestartlinenumber="1">Path of source .RBJ file</p>


```csharp
[Obsolete("Data quality workflows and related tools based on the Reviewer Workspace are deprecated. As a result, the Data Reviewer Assembly and Namespaces will be removed at ArcGIS Pro 4.0, the next major release. It is recommended that users migrate to ArcGIS Data Reviewer attribute rules-based workflows. Learn more about migrating to attribute rules, https://www.esri.com/arcgis-blog/products/data-reviewer/data-management/migrating-to-attributes-rules-using-arcgis-data-reviewer/", DiagnosticId = "ARCGISPRO40", UrlFormat = "https://www.esri.com/arcgis-blog/products/data-reviewer/data-management/migrating-to-attributes-rules-using-arcgis-data-reviewer/")]
public string BatchJobFile { get; set; }
```
### BatchJobFileName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.DataReviewer.ReviewerBatchJobs.ExportBatchJobToAttributeRulesDockPane.yml" sourcestartlinenumber="1">This class is not for public use and is used internally by the system to
implement support for other esri modules</p>


```csharp
[Obsolete("Data quality workflows and related tools based on the Reviewer Workspace are deprecated. As a result, the Data Reviewer Assembly and Namespaces will be removed at ArcGIS Pro 4.0, the next major release. It is recommended that users migrate to ArcGIS Data Reviewer attribute rules-based workflows. Learn more about migrating to attribute rules, https://www.esri.com/arcgis-blog/products/data-reviewer/data-management/migrating-to-attributes-rules-using-arcgis-data-reviewer/", DiagnosticId = "ARCGISPRO40", UrlFormat = "https://www.esri.com/arcgis-blog/products/data-reviewer/data-management/migrating-to-attributes-rules-using-arcgis-data-reviewer/")]
public string BatchJobFileName { get; }
```
### ChooseBatchJobFileCommand

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.DataReviewer.ReviewerBatchJobs.ExportBatchJobToAttributeRulesDockPane.yml" sourcestartlinenumber="1">UI binding</p>


```csharp
[Obsolete("Data quality workflows and related tools based on the Reviewer Workspace are deprecated. As a result, the Data Reviewer Assembly and Namespaces will be removed at ArcGIS Pro 4.0, the next major release. It is recommended that users migrate to ArcGIS Data Reviewer attribute rules-based workflows. Learn more about migrating to attribute rules, https://www.esri.com/arcgis-blog/products/data-reviewer/data-management/migrating-to-attributes-rules-using-arcgis-data-reviewer/", DiagnosticId = "ARCGISPRO40", UrlFormat = "https://www.esri.com/arcgis-blog/products/data-reviewer/data-management/migrating-to-attributes-rules-using-arcgis-data-reviewer/")]
public ICommand ChooseBatchJobFileCommand { get; }
```
### ChooseDestinationWorkspaceCommand

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.DataReviewer.ReviewerBatchJobs.ExportBatchJobToAttributeRulesDockPane.yml" sourcestartlinenumber="1">UI binding</p>


```csharp
[Obsolete("Data quality workflows and related tools based on the Reviewer Workspace are deprecated. As a result, the Data Reviewer Assembly and Namespaces will be removed at ArcGIS Pro 4.0, the next major release. It is recommended that users migrate to ArcGIS Data Reviewer attribute rules-based workflows. Learn more about migrating to attribute rules, https://www.esri.com/arcgis-blog/products/data-reviewer/data-management/migrating-to-attributes-rules-using-arcgis-data-reviewer/", DiagnosticId = "ARCGISPRO40", UrlFormat = "https://www.esri.com/arcgis-blog/products/data-reviewer/data-management/migrating-to-attributes-rules-using-arcgis-data-reviewer/")]
public ICommand ChooseDestinationWorkspaceCommand { get; }
```
### ChooseOutputCSVLocationCommand

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.DataReviewer.ReviewerBatchJobs.ExportBatchJobToAttributeRulesDockPane.yml" sourcestartlinenumber="1">UI binding</p>


```csharp
[Obsolete("Data quality workflows and related tools based on the Reviewer Workspace are deprecated. As a result, the Data Reviewer Assembly and Namespaces will be removed at ArcGIS Pro 4.0, the next major release. It is recommended that users migrate to ArcGIS Data Reviewer attribute rules-based workflows. Learn more about migrating to attribute rules, https://www.esri.com/arcgis-blog/products/data-reviewer/data-management/migrating-to-attributes-rules-using-arcgis-data-reviewer/", DiagnosticId = "ARCGISPRO40", UrlFormat = "https://www.esri.com/arcgis-blog/products/data-reviewer/data-management/migrating-to-attributes-rules-using-arcgis-data-reviewer/")]
public ICommand ChooseOutputCSVLocationCommand { get; }
```
### DestinationWorkspace

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.DataReviewer.ReviewerBatchJobs.ExportBatchJobToAttributeRulesDockPane.yml" sourcestartlinenumber="1">This class is not for public use and is used internally by the system to
implement support for other esri modules</p>


```csharp
[Obsolete("Data quality workflows and related tools based on the Reviewer Workspace are deprecated. As a result, the Data Reviewer Assembly and Namespaces will be removed at ArcGIS Pro 4.0, the next major release. It is recommended that users migrate to ArcGIS Data Reviewer attribute rules-based workflows. Learn more about migrating to attribute rules, https://www.esri.com/arcgis-blog/products/data-reviewer/data-management/migrating-to-attributes-rules-using-arcgis-data-reviewer/", DiagnosticId = "ARCGISPRO40", UrlFormat = "https://www.esri.com/arcgis-blog/products/data-reviewer/data-management/migrating-to-attributes-rules-using-arcgis-data-reviewer/")]
public Item DestinationWorkspace { get; set; }
```
### DestinationWorkspaceName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.DataReviewer.ReviewerBatchJobs.ExportBatchJobToAttributeRulesDockPane.yml" sourcestartlinenumber="1">Validation workspace name</p>


```csharp
[Obsolete("Data quality workflows and related tools based on the Reviewer Workspace are deprecated. As a result, the Data Reviewer Assembly and Namespaces will be removed at ArcGIS Pro 4.0, the next major release. It is recommended that users migrate to ArcGIS Data Reviewer attribute rules-based workflows. Learn more about migrating to attribute rules, https://www.esri.com/arcgis-blog/products/data-reviewer/data-management/migrating-to-attributes-rules-using-arcgis-data-reviewer/", DiagnosticId = "ARCGISPRO40", UrlFormat = "https://www.esri.com/arcgis-blog/products/data-reviewer/data-management/migrating-to-attributes-rules-using-arcgis-data-reviewer/")]
public string DestinationWorkspaceName { get; }
```
### DestinationWorkspacePath

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.DataReviewer.ReviewerBatchJobs.ExportBatchJobToAttributeRulesDockPane.yml" sourcestartlinenumber="1">Validation workspace used while converting</p>


```csharp
[Obsolete("Data quality workflows and related tools based on the Reviewer Workspace are deprecated. As a result, the Data Reviewer Assembly and Namespaces will be removed at ArcGIS Pro 4.0, the next major release. It is recommended that users migrate to ArcGIS Data Reviewer attribute rules-based workflows. Learn more about migrating to attribute rules, https://www.esri.com/arcgis-blog/products/data-reviewer/data-management/migrating-to-attributes-rules-using-arcgis-data-reviewer/", DiagnosticId = "ARCGISPRO40", UrlFormat = "https://www.esri.com/arcgis-blog/products/data-reviewer/data-management/migrating-to-attributes-rules-using-arcgis-data-reviewer/")]
public string DestinationWorkspacePath { get; set; }
```
### Error

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.DataReviewer.ReviewerBatchJobs.ExportBatchJobToAttributeRulesDockPane.yml" sourcestartlinenumber="1">This class is not for public use and is used internally by the system to
implement support for other esri modules</p>


```csharp
public string Error { get; }
```
### ExportCommand

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.DataReviewer.ReviewerBatchJobs.ExportBatchJobToAttributeRulesDockPane.yml" sourcestartlinenumber="1">UI binding</p>


```csharp
[Obsolete("Data quality workflows and related tools based on the Reviewer Workspace are deprecated. As a result, the Data Reviewer Assembly and Namespaces will be removed at ArcGIS Pro 4.0, the next major release. It is recommended that users migrate to ArcGIS Data Reviewer attribute rules-based workflows. Learn more about migrating to attribute rules, https://www.esri.com/arcgis-blog/products/data-reviewer/data-management/migrating-to-attributes-rules-using-arcgis-data-reviewer/", DiagnosticId = "ARCGISPRO40", UrlFormat = "https://www.esri.com/arcgis-blog/products/data-reviewer/data-management/migrating-to-attributes-rules-using-arcgis-data-reviewer/")]
public ICommand ExportCommand { get; }
```
### IsFinished

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.DataReviewer.ReviewerBatchJobs.ExportBatchJobToAttributeRulesDockPane.yml" sourcestartlinenumber="1">UI binding</p>


```csharp
[Obsolete("Data quality workflows and related tools based on the Reviewer Workspace are deprecated. As a result, the Data Reviewer Assembly and Namespaces will be removed at ArcGIS Pro 4.0, the next major release. It is recommended that users migrate to ArcGIS Data Reviewer attribute rules-based workflows. Learn more about migrating to attribute rules, https://www.esri.com/arcgis-blog/products/data-reviewer/data-management/migrating-to-attributes-rules-using-arcgis-data-reviewer/", DiagnosticId = "ARCGISPRO40", UrlFormat = "https://www.esri.com/arcgis-blog/products/data-reviewer/data-management/migrating-to-attributes-rules-using-arcgis-data-reviewer/")]
public bool IsFinished { get; set; }
```
### IsReady

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.DataReviewer.ReviewerBatchJobs.ExportBatchJobToAttributeRulesDockPane.yml" sourcestartlinenumber="1">UI binding</p>


```csharp
[Obsolete("Data quality workflows and related tools based on the Reviewer Workspace are deprecated. As a result, the Data Reviewer Assembly and Namespaces will be removed at ArcGIS Pro 4.0, the next major release. It is recommended that users migrate to ArcGIS Data Reviewer attribute rules-based workflows. Learn more about migrating to attribute rules, https://www.esri.com/arcgis-blog/products/data-reviewer/data-management/migrating-to-attributes-rules-using-arcgis-data-reviewer/", DiagnosticId = "ARCGISPRO40", UrlFormat = "https://www.esri.com/arcgis-blog/products/data-reviewer/data-management/migrating-to-attributes-rules-using-arcgis-data-reviewer/")]
public bool IsReady { get; }
```
### IsRunning

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.DataReviewer.ReviewerBatchJobs.ExportBatchJobToAttributeRulesDockPane.yml" sourcestartlinenumber="1">UI binding</p>


```csharp
[Obsolete("Data quality workflows and related tools based on the Reviewer Workspace are deprecated. As a result, the Data Reviewer Assembly and Namespaces will be removed at ArcGIS Pro 4.0, the next major release. It is recommended that users migrate to ArcGIS Data Reviewer attribute rules-based workflows. Learn more about migrating to attribute rules, https://www.esri.com/arcgis-blog/products/data-reviewer/data-management/migrating-to-attributes-rules-using-arcgis-data-reviewer/", DiagnosticId = "ARCGISPRO40", UrlFormat = "https://www.esri.com/arcgis-blog/products/data-reviewer/data-management/migrating-to-attributes-rules-using-arcgis-data-reviewer/")]
public bool IsRunning { get; set; }
```
### this[string]

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.DataReviewer.ReviewerBatchJobs.ExportBatchJobToAttributeRulesDockPane.yml" sourcestartlinenumber="1">This class is not for public use and is used internally by the system to
implement support for other esri modules</p>


```csharp
public string this[string columnName] { get; }
```
### OutputCSVLocation

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.DataReviewer.ReviewerBatchJobs.ExportBatchJobToAttributeRulesDockPane.yml" sourcestartlinenumber="1">Location of generated .CSV files</p>


```csharp
[Obsolete("Data quality workflows and related tools based on the Reviewer Workspace are deprecated. As a result, the Data Reviewer Assembly and Namespaces will be removed at ArcGIS Pro 4.0, the next major release. It is recommended that users migrate to ArcGIS Data Reviewer attribute rules-based workflows. Learn more about migrating to attribute rules, https://www.esri.com/arcgis-blog/products/data-reviewer/data-management/migrating-to-attributes-rules-using-arcgis-data-reviewer/", DiagnosticId = "ARCGISPRO40", UrlFormat = "https://www.esri.com/arcgis-blog/products/data-reviewer/data-management/migrating-to-attributes-rules-using-arcgis-data-reviewer/")]
public string OutputCSVLocation { get; set; }
```
### OutputCSVLocationName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.DataReviewer.ReviewerBatchJobs.ExportBatchJobToAttributeRulesDockPane.yml" sourcestartlinenumber="1">This class is not for public use and is used internally by the system to
implement support for other esri modules</p>


```csharp
[Obsolete("Data quality workflows and related tools based on the Reviewer Workspace are deprecated. As a result, the Data Reviewer Assembly and Namespaces will be removed at ArcGIS Pro 4.0, the next major release. It is recommended that users migrate to ArcGIS Data Reviewer attribute rules-based workflows. Learn more about migrating to attribute rules, https://www.esri.com/arcgis-blog/products/data-reviewer/data-management/migrating-to-attributes-rules-using-arcgis-data-reviewer/", DiagnosticId = "ARCGISPRO40", UrlFormat = "https://www.esri.com/arcgis-blog/products/data-reviewer/data-management/migrating-to-attributes-rules-using-arcgis-data-reviewer/")]
public string OutputCSVLocationName { get; }
```
### ReadOnly

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.DataReviewer.ReviewerBatchJobs.ExportBatchJobToAttributeRulesDockPane.yml" sourcestartlinenumber="1">Whether BatchJobFile can be edited</p>


```csharp
[Obsolete("Data quality workflows and related tools based on the Reviewer Workspace are deprecated. As a result, the Data Reviewer Assembly and Namespaces will be removed at ArcGIS Pro 4.0, the next major release. It is recommended that users migrate to ArcGIS Data Reviewer attribute rules-based workflows. Learn more about migrating to attribute rules, https://www.esri.com/arcgis-blog/products/data-reviewer/data-management/migrating-to-attributes-rules-using-arcgis-data-reviewer/", DiagnosticId = "ARCGISPRO40", UrlFormat = "https://www.esri.com/arcgis-blog/products/data-reviewer/data-management/migrating-to-attributes-rules-using-arcgis-data-reviewer/")]
public bool ReadOnly { get; set; }
```
### Summary

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.DataReviewer.ReviewerBatchJobs.ExportBatchJobToAttributeRulesDockPane.yml" sourcestartlinenumber="1">This class is not for public use and is used internally by the system to
implement support for other esri modules</p>


```csharp
[Obsolete("Data quality workflows and related tools based on the Reviewer Workspace are deprecated. As a result, the Data Reviewer Assembly and Namespaces will be removed at ArcGIS Pro 4.0, the next major release. It is recommended that users migrate to ArcGIS Data Reviewer attribute rules-based workflows. Learn more about migrating to attribute rules, https://www.esri.com/arcgis-blog/products/data-reviewer/data-management/migrating-to-attributes-rules-using-arcgis-data-reviewer/", DiagnosticId = "ARCGISPRO40", UrlFormat = "https://www.esri.com/arcgis-blog/products/data-reviewer/data-management/migrating-to-attributes-rules-using-arcgis-data-reviewer/")]
public FlowDocument Summary { get; }
```
### SummaryFilePath

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.DataReviewer.ReviewerBatchJobs.ExportBatchJobToAttributeRulesDockPane.yml" sourcestartlinenumber="1">UI binding</p>


```csharp
[Obsolete("Data quality workflows and related tools based on the Reviewer Workspace are deprecated. As a result, the Data Reviewer Assembly and Namespaces will be removed at ArcGIS Pro 4.0, the next major release. It is recommended that users migrate to ArcGIS Data Reviewer attribute rules-based workflows. Learn more about migrating to attribute rules, https://www.esri.com/arcgis-blog/products/data-reviewer/data-management/migrating-to-attributes-rules-using-arcgis-data-reviewer/", DiagnosticId = "ARCGISPRO40", UrlFormat = "https://www.esri.com/arcgis-blog/products/data-reviewer/data-management/migrating-to-attributes-rules-using-arcgis-data-reviewer/")]
public string SummaryFilePath { get; set; }
```


