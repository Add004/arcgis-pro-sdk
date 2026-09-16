# SearchQuery

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.html">Workflow</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.html">Client</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Models.html">Models</a>
- Assembly: ArcGIS.Desktop.Workflow.Client.dll

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.SearchQuery.yml" sourcestartlinenumber="1">Search criteria for querying job information</p>


## Object Signature

```csharp
public class SearchQuery
```


## Members

### SearchQuery()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.SearchQuery.yml" sourcestartlinenumber="1">Search criteria for querying job information</p>


```csharp
public SearchQuery()
```
### Fields

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.SearchQuery.yml" sourcestartlinenumber="1">A list of fields whose value you want returned in the search result. If no fields are defined in the search query,
jobName, priority, dueDate and currentStep fields are returned.</p>


```csharp
public List<string> Fields { get; set; }
```
### Num

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.SearchQuery.yml" sourcestartlinenumber="1">Number of results to return in the page.</p>


```csharp
public int Num { get; set; }
```
### Q

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.SearchQuery.yml" sourcestartlinenumber="1">Query for the search you are performing</p>


```csharp
public string Q { get; set; }
```
### Search

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.SearchQuery.yml" sourcestartlinenumber="1">Match criteria for a simple search</p>


```csharp
public string Search { get; set; }
```
### SortFields

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.SearchQuery.yml" sourcestartlinenumber="1">The fields which you want to sort the results by and whether you want to sort the results in ascending or descending order.</p>


```csharp
public List<SortField> SortFields { get; set; }
```
### Start

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.SearchQuery.yml" sourcestartlinenumber="1">Index of the results from which you want to start the list of results</p>


```csharp
public int Start { get; set; }
```


