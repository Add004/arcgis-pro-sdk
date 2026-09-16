# Report

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Reports.html">Reports</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Represent a report.</p>


## Object Signature

```csharp
public sealed class Report : PropertyChangedBase, IDisposable
```


## Members

### ActiveSection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Gets or sets the ActiveSection property.</p>


```csharp
public ReportSectionElement ActiveSection { get; }
```
### AddGroup(string, bool, bool, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Adds a group section to the report. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void AddGroup(string fieldName, bool sortAscending, bool caseSensitiveSort, string parentGroupFieldName)
```
### AddGroup(string, bool, bool, string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Adds a group section to the report. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void AddGroup(string fieldName, bool sortAscending, bool caseSensitiveSort, string parentGroupFieldName, string containerSectionName)
```
### AddLayoutPage(Item, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Adds a layout page section to the report. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void AddLayoutPage(Item layoutItem, int insertIndex)
```
### AddLayoutPage(Item, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Adds a layout page section to the report. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void AddLayoutPage(Item layoutItem, string insertSectionName)
```
### AddRelatedReport(string, string, string, CIMReportDataSource, CIMReportElementFieldProperties[], string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Adds a related report section to the report. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void AddRelatedReport(string relateName, string relateTitle, string insertSectionName, CIMReportDataSource reportDataSource, CIMReportElementFieldProperties[] statProperties, string templatePath, string styling)
```
### AddSubReport(Item, int, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Adds a subreport to the report. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void AddSubReport(Item reportItem, int insertIndex, bool adjustPageSize)
```
### AddTemplateSubReport(string, int, bool, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Adds a template subreport to the report. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void AddTemplateSubReport(string templatePath, int insertIndex, bool adjustPageSize, bool newTemplate)
```
### ClearElementSelection()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Clears all selected elements in the report.</p>


```csharp
public void ClearElementSelection()
```
### ConnectionStatus

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Gets a value indicating the report's connection status.</p>


```csharp
public ConnectionStatus ConnectionStatus { get; }
```
### DataSource

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Gets the data source of the report.</p>


```csharp
public ReportDataSource DataSource { get; }
```
### DataSources

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Gets the data source of the report.</p>


```csharp
public IReadOnlyDictionary<string, ReportDataSource> DataSources { get; }
```
### DeleteElement(Element)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Deletes the specified element from the report.  Note that section elements cannot be deleted and will be ignored if specified.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void DeleteElement(Element element)
```
### DeleteElements(IEnumerable&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Deletes the set of elements from the report.  Note that section elements cannot be deleted and will be ignored if specified.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void DeleteElements(IEnumerable<Element> elements)
```
### Elements

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Gets the collection of elements in the report.</p>


```csharp
public ReadOnlyObservableCollection<Element> Elements { get; }
```
### ExportToPDF(string, PDFFormat, ReportExportOptions, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Export a report to a PDF format. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void ExportToPDF(string outputName, PDFFormat exportFormat, ReportExportOptions reportExportOptions, bool useSelection)
```
### FindElement(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Finds the report element by name.</p>


```csharp
public Element FindElement(string elementName)
```
### FindElements(IEnumerable&lt;string&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Finds the elements with the given names on the report.</p>


```csharp
public IList<Element> FindElements(IEnumerable<string> elementNames)
```
### GetDefinition()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Returns the element's CIM definition.  This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public CIMReport GetDefinition()
```
### GetElementsAsFlattenedList()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Get the collection of <xref href="ArcGIS.Desktop.Layouts.Element" data-throw-if-not-resolved="false"></xref> from the report as a flattened list.
Nested groups within <xref href="ArcGIS.Desktop.Layouts.GroupElement" data-throw-if-not-resolved="false"></xref> are <b>not</b> preserved.</p>


```csharp
public IReadOnlyList<Element> GetElementsAsFlattenedList()
```
### GetExpressions(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Gets the expressions of the report section.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public List<CIMExpressionInfo> GetExpressions(string reportSectionName)
```
### GetSelectedElements()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Gets the set of selected elements on the report.</p>


```csharp
public ReadOnlyObservableCollection<Element> GetSelectedElements()
```
### GetStatistics(CIMReportSectionElement)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Returns the statistics in the given Report or Related Report Section.</p>


```csharp
public List<CIMReportElementFieldProperties> GetStatistics(CIMReportSectionElement reportSection)
```
### MoveGroupSection(ReportGroupHeader, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Moves the group section elements to new location. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void MoveGroupSection(ReportGroupHeader groupHeaderSection, bool moveUp)
```
### MoveRelateSection(string, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Moves the relate section to new location. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void MoveRelateSection(string relateSection, bool moveUp)
```
### MoveReportSectionElement(ReportSectionElement, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Moves the report section element to new index location. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void MoveReportSectionElement(ReportSectionElement reportSectionElement, int newIndex)
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Gets or sets the Name property.</p>


```csharp
public string Name { get; }
```
### OperationManager

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Gets the OperationManager which is responsible for managing the undo/redo stack.</p>


```csharp
public OperationManager OperationManager { get; }
```
### Page

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Gets or sets the Page property.</p>


```csharp
public CIMPage Page { get; }
```
### RemoveGroups(IEnumerable&lt;string&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Removes the group from the report. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveGroups(IEnumerable<string> groupFieldNames)
```
### RemoveGroups(IEnumerable&lt;string&gt;, IEnumerable&lt;string&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Removes the group from the report. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveGroups(IEnumerable<string> groupFieldNames, IEnumerable<string> parentSectionNames)
```
### RemoveRelatedReport(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Removes the related report from the report. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveRelatedReport(string relatedReportName)
```
### RemoveSectionElement(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Removes the report section element from the report. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveSectionElement(string sectionName)
```
### RemoveSupplementalPage(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Removes the supplemental page from the report. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveSupplementalPage(string pageName)
```
### ReplaceLayoutPage(Item, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Replaces a layout page section with a new layout definition. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void ReplaceLayoutPage(Item layoutItem, string layoutPageSectionName)
```
### SelectAllElements()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Select all report elements in a report.</p>


```csharp
public void SelectAllElements()
```
### SelectElement(Element)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Selects the specified element in the report.</p>


```csharp
public void SelectElement(Element element)
```
### SelectElements(IEnumerable&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Selects the set of elements in the report.</p>


```csharp
public void SelectElements(IEnumerable<Element> elements)
```
### SetDataSource(ReportDataSource)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Updates the data source of the report.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDataSource(ReportDataSource dataSource)
```
### SetDataSource(ReportDataSource, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Updates the data source of the report.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDataSource(ReportDataSource dataSource, string reportSectionName)
```
### SetDataSourceFields(IEnumerable&lt;CIMReportField&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Updates the grouping and sorting fields of the report.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDataSourceFields(IEnumerable<CIMReportField> reportFields)
```
### SetDataSourceFields(string, IEnumerable&lt;CIMReportField&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Updates the grouping and sorting fields of the report.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDataSourceFields(string reportSectionName, IEnumerable<CIMReportField> reportFields)
```
### SetDefinition(CIMReport)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Applies the changes made to a modified <xref href="ArcGIS.Core.CIM.CIMReport" data-throw-if-not-resolved="false"></xref> back to the report. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDefinition(CIMReport cimReport)
```
### SetDefinitionFilter(CIMDefinitionFilter, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Updates the definition filter of the report.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDefinitionFilter(CIMDefinitionFilter definitionFilter, string datasourceSection)
```
### SetDefinitionQuery(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Updates the definition query of the report.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDefinitionQuery(string defQuery)
```
### SetDefinitionQuery(string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Updates the definition query of the report.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDefinitionQuery(string defQuery, string datasourceSection)
```
### SetExpressions(IEnumerable&lt;CIMExpressionInfo&gt;, string, IEnumerable&lt;string&gt;, IEnumerable&lt;string&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Updates the expressions of the report section.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetExpressions(IEnumerable<CIMExpressionInfo> expressions, string reportSectionName, IEnumerable<string> oldExpressionNames, IEnumerable<string> renamedExpressionNames)
```
### SetName(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Updates the name of the report.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetName(string name)
```
### SetPage(CIMPage)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Sets the page of the report.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetPage(CIMPage page)
```
### SetPageHeight(double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Updates the page height of the report.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetPageHeight(double pageHeight)
```
### SetRelatedDataSource(ReportDataSource, string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Updates the data source of the related report section.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetRelatedDataSource(ReportDataSource dataSource, string relatedReportElementName, string relateName)
```
### SetRelatedDataSourceFields(string, IEnumerable&lt;CIMReportField&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Updates the grouping and sorting fields of the related report section.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetRelatedDataSourceFields(string relatedReportElementName, IEnumerable<CIMReportField> reportFields)
```
### SetRelatedReportName(string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Updates the name of the related report element.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetRelatedReportName(string relatedReportElementName, string newName)
```
### URI

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Gets or sets the URI property.</p>


```csharp
public string URI { get; }
```
### UnSelectElement(Element)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Unselect the element on the report.</p>


```csharp
public void UnSelectElement(Element element)
```
### UnSelectElements(IEnumerable&lt;Element&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.Report.yml" sourcestartlinenumber="1">Unselect the elements on the report.</p>


```csharp
public void UnSelectElements(IEnumerable<Element> elements = null)
```


