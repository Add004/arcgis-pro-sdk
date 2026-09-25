# ReportCustomTemplateDataSourceInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Reports.html">Reports</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportCustomTemplateDataSourceInfo.yml" sourcestartlinenumber="1">Represents the data source, fields, map and chart data for a subreport of a custom template</p>


## Object Signature

```csharp
public class ReportCustomTemplateDataSourceInfo
```


## Members

### ChartValues

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportCustomTemplateDataSourceInfo.yml" sourcestartlinenumber="1">Gets and sets the list of chart names used to assign to the charts in the template.</p>


```csharp
public List<string> ChartValues { get; set; }
```
### ChartValuesDictionary

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportCustomTemplateDataSourceInfo.yml" sourcestartlinenumber="1">Gets the dictionary of the chart elements and the assigned chart name.</p>


```csharp
public Dictionary<string, string> ChartValuesDictionary { get; }
```
### DataConnection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportCustomTemplateDataSourceInfo.yml" sourcestartlinenumber="1">Gets the report data source data connection.</p>


```csharp
public CIMDataConnection DataConnection { get; }
```
### DefinitionQuery

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportCustomTemplateDataSourceInfo.yml" sourcestartlinenumber="1">Gets and sets the DefinitionQuery property.</p>


```csharp
public string DefinitionQuery { get; set; }
```
### IsRelateDataSource

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportCustomTemplateDataSourceInfo.yml" sourcestartlinenumber="1">Indicates the given data source is a relate data source.</p>


```csharp
public bool IsRelateDataSource { get; }
```
### MapMember

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportCustomTemplateDataSourceInfo.yml" sourcestartlinenumber="1">Gets the report data source map member.</p>


```csharp
public MapMember MapMember { get; }
```
### MapValues

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportCustomTemplateDataSourceInfo.yml" sourcestartlinenumber="1">Gets and sets the list of map URI strings used to assign to the map frames in the template.</p>


```csharp
public List<string> MapValues { get; set; }
```
### MapValuesDictionary

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportCustomTemplateDataSourceInfo.yml" sourcestartlinenumber="1">Gets the dictionary of map frame elements and the assigned URI string.</p>


```csharp
public Dictionary<string, string> MapValuesDictionary { get; }
```
### RelateDataSourceParentElementName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportCustomTemplateDataSourceInfo.yml" sourcestartlinenumber="1">Gets the parent element name of the relate data source. Will be null or empty if the data source is not a relate data source.</p>


```csharp
public string RelateDataSourceParentElementName { get; }
```
### RelateName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportCustomTemplateDataSourceInfo.yml" sourcestartlinenumber="1">Gets and sets the RelateName property.</p>


```csharp
public string RelateName { get; set; }
```
### SetReportDataSource(CIMDataConnection)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportCustomTemplateDataSourceInfo.yml" sourcestartlinenumber="1">Sets the report data source data connection.</p>


```csharp
public void SetReportDataSource(CIMDataConnection dataConnection)
```
### SetReportDataSource(MapMember)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportCustomTemplateDataSourceInfo.yml" sourcestartlinenumber="1">Sets the report data source map member.</p>


```csharp
public void SetReportDataSource(MapMember mapMember)
```
### TokenInfoValues

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportCustomTemplateDataSourceInfo.yml" sourcestartlinenumber="1">Gets the TokenFieldInfos property.</p>


```csharp
public TemplateTokenFieldInfoValues TokenInfoValues { get; }
```


