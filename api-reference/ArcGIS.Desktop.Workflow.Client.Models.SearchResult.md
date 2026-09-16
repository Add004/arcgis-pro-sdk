# SearchResult

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.html">Workflow</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.html">Client</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Models.html">Models</a>
- Assembly: ArcGIS.Desktop.Workflow.Client.dll

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.SearchResult.yml" sourcestartlinenumber="1">Results from a job search</p>


## Object Signature

```csharp
public class SearchResult
```


## Members

### SearchResult()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.SearchResult.yml" sourcestartlinenumber="1">Results from a job search</p>


```csharp
public SearchResult()
```
### Fields

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.SearchResult.yml" sourcestartlinenumber="1">Fields returned in the search result, including field name and type</p>


```csharp
public List<SearchResultField> Fields { get; }
```
### NextStart

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.SearchResult.yml" sourcestartlinenumber="1">Index of the results from which the list of results will start on next page. If there are no more results, -1 is returned.</p>


```csharp
public int NextStart { get; }
```
### Num

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.SearchResult.yml" sourcestartlinenumber="1">Number of results returned in the page</p>


```csharp
public int Num { get; }
```
### Q

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.SearchResult.yml" sourcestartlinenumber="1">Search query string used</p>


```csharp
public string Q { get; }
```
### Results

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.SearchResult.yml" sourcestartlinenumber="1">Results of the search</p>


```csharp
public List<Dictionary<string, object>> Results { get; }
```
### Start

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.SearchResult.yml" sourcestartlinenumber="1">Index of the results from which the list of results start on this page</p>


```csharp
public int Start { get; }
```


