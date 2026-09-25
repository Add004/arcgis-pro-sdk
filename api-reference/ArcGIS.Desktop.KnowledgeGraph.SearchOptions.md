# SearchOptions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.KnowledgeGraph.html">KnowledgeGraph</a>
- Assembly: ArcGIS.Desktop.KnowledgeGraph.dll

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.SearchOptions.yml" sourcestartlinenumber="1">Represents the search options of the investigation view.  See <xref href="ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigationView.GetSearchOptions" data-throw-if-not-resolved="false"></xref> or
<xref href="ArcGIS.Desktop.KnowledgeGraph.KnowledgeGraphInvestigationView.SetSearchOptions(ArcGIS.Desktop.KnowledgeGraph.SearchOptions)" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class SearchOptions
```


## Members

### SearchOptions(InvestigationSearchMode)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.SearchOptions.yml" sourcestartlinenumber="1">Creates an instance of the SearchOptions for a specific search mode.<br>
Use this constructor if the SearchMode is <xref href="ArcGIS.Desktop.KnowledgeGraph.InvestigationSearchMode.Search" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Desktop.KnowledgeGraph.InvestigationSearchMode.Query" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public SearchOptions(InvestigationSearchMode searchMode)
```
### SearchOptions(InvestigationSearchMode, InvestigationSearchScope, List&lt;string&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.SearchOptions.yml" sourcestartlinenumber="1">Creates an instance of the SearchOptions.
Use this constructor if the SearchMode is <xref href="ArcGIS.Desktop.KnowledgeGraph.InvestigationSearchMode.AdvancedSearch" data-throw-if-not-resolved="false"></xref> and the scope and filers are to be
configured.</p>


```csharp
public SearchOptions(InvestigationSearchMode searchMode, InvestigationSearchScope searchScope, List<string> filters = null)
```
### Filters

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.SearchOptions.yml" sourcestartlinenumber="1">Gets the set of named object types to be used as a search filter.  Null means all types are to be searched.
This is ignored if the <xref href="ArcGIS.Desktop.KnowledgeGraph.SearchOptions.SearchMode" data-throw-if-not-resolved="false"></xref> is <xref href="ArcGIS.Desktop.KnowledgeGraph.InvestigationSearchMode.Query" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public List<string> Filters { get; set; }
```
### SearchMode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.SearchOptions.yml" sourcestartlinenumber="1">Gets the search mode of the options.  Default is <xref href="ArcGIS.Desktop.KnowledgeGraph.InvestigationSearchMode.Search" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public InvestigationSearchMode SearchMode { get; set; }
```
### SearchScope

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.KnowledgeGraph.SearchOptions.yml" sourcestartlinenumber="1">Gets the search scope of the options. This is ignored if the <xref href="ArcGIS.Desktop.KnowledgeGraph.SearchOptions.SearchMode" data-throw-if-not-resolved="false"></xref> is <xref href="ArcGIS.Desktop.KnowledgeGraph.InvestigationSearchMode.Query" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public InvestigationSearchScope SearchScope { get; set; }
```


