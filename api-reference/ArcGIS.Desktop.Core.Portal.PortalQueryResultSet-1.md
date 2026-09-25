# PortalQueryResultSet&lt;T&gt;

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.Portal.html">Portal</a>
- Assembly: ArcGIS.Desktop.Catalog.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalQueryResultSet-1.yml" sourcestartlinenumber="1">Represents the result of a portal search returning an enumeration of T objects.</p>


## Object Signature

```csharp
public sealed class PortalQueryResultSet<T>
```


## Members

### NextQueryParameters

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalQueryResultSet-1.yml" sourcestartlinenumber="1">Gets the query params for the next set of results based on the next start index. This is automatically generated if there are
more results left to be retrieved. This will be <b>null</b> if there are no more results for the next page.</p>


```csharp
public PortalQueryParameters NextQueryParameters { get; }
```
### QueryParameters

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalQueryResultSet-1.yml" sourcestartlinenumber="1">Gets the query parameters used to make the search.</p>


```csharp
public PortalQueryParameters QueryParameters { get; }
```
### Results

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalQueryResultSet-1.yml" sourcestartlinenumber="1">Gets the present results of the query.</p>


```csharp
public IReadOnlyList<T> Results { get; }
```
### TotalResultsCount

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalQueryResultSet-1.yml" sourcestartlinenumber="1">Gets the total number of results irrespective of the paging.</p>


```csharp
public int TotalResultsCount { get; }
```


