# ReportDataSource

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Reports.html">Reports</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportDataSource.yml" sourcestartlinenumber="1">Represents the data source for a report.</p>


## Object Signature

```csharp
public class ReportDataSource
```


## Members

### ReportDataSource(CIMDataConnection, string, bool, IEnumerable&lt;CIMReportField&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportDataSource.yml" sourcestartlinenumber="1">Creates a ReportDataSource object using a data connection.</p>


```csharp
[Obsolete("Use ReportDataSource(CIMDataConnection, String, IEnumerable<CIMReportField>) instead.")]
public ReportDataSource(CIMDataConnection dataConnection, string definitionQuery, bool useSelectionSet, IEnumerable<CIMReportField> fields)
```
### ReportDataSource(CIMDataConnection, string, IEnumerable&lt;CIMReportField&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportDataSource.yml" sourcestartlinenumber="1">Creates a ReportDataSource object using a data connection.</p>


```csharp
public ReportDataSource(CIMDataConnection dataConnection, string definitionQuery, IEnumerable<CIMReportField> fields)
```
### ReportDataSource(MapMember, string, bool, IEnumerable&lt;CIMReportField&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportDataSource.yml" sourcestartlinenumber="1">Creates a ReportDataSource object using a MapMember.</p>


```csharp
[Obsolete("Use ReportDataSource(MapMember, String, IEnumerable<CIMReportField>) instead.")]
public ReportDataSource(MapMember mapMember, string definitionQuery, bool useSelectionSet, IEnumerable<CIMReportField> fields)
```
### ReportDataSource(MapMember, string, IEnumerable&lt;CIMReportField&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportDataSource.yml" sourcestartlinenumber="1">Creates a ReportDataSource object using a MapMember.</p>


```csharp
public ReportDataSource(MapMember mapMember, string definitionQuery, IEnumerable<CIMReportField> fields)
```
### ConnectionStatus

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportDataSource.yml" sourcestartlinenumber="1">Gets a value indicating the DataSource's connection status.</p>


```csharp
public ConnectionStatus ConnectionStatus { get; set; }
```
### DataConnection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportDataSource.yml" sourcestartlinenumber="1">Gets the data connection to the source.</p>


```csharp
public CIMDataConnection DataConnection { get; }
```
### DefinitionFilter

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportDataSource.yml" sourcestartlinenumber="1">Get the spatial filter.</p>


```csharp
public CIMDefinitionFilter DefinitionFilter { get; }
```
### DefinitionQuery

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportDataSource.yml" sourcestartlinenumber="1">Gets the definition query.</p>


```csharp
public string DefinitionQuery { get; }
```
### Fields

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportDataSource.yml" sourcestartlinenumber="1">Gets the report fields.</p>


```csharp
public IEnumerable<CIMReportField> Fields { get; }
```
### GroupFieldNames

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportDataSource.yml" sourcestartlinenumber="1">Gets all the group field names.</p>


```csharp
public IEnumerable<string> GroupFieldNames { get; }
```
### GroupFields

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportDataSource.yml" sourcestartlinenumber="1">Gets all the group fields</p>


```csharp
public IEnumerable<CIMReportField> GroupFields { get; }
```
### MapMember

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportDataSource.yml" sourcestartlinenumber="1">Gets the Layer or Standalone table in the project.</p>


```csharp
public MapMember MapMember { get; }
```
### SupportsSelection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportDataSource.yml" sourcestartlinenumber="1">Gets the value indicating that the source supports selection.</p>


```csharp
public bool SupportsSelection { get; }
```
### UseSelectionSet

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportDataSource.yml" sourcestartlinenumber="1">Gets the value indicating that the selection of the Layer or Table should be used for the report.</p>


```csharp
public bool UseSelectionSet { get; }
```


