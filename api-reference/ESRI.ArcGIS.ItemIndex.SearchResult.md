# SearchResult

- Type: class
- Namespace: <a class="xref" href="ESRI.html">ESRI</a>.<a class="xref" href="ESRI.ArcGIS.html">ArcGIS</a>.<a class="xref" href="ESRI.ArcGIS.ItemIndex.html">ItemIndex</a>
- Assembly: ESRI.ArcGIS.ItemIndex.dll

<p sourcefile="api/ESRI.ArcGIS.ItemIndex.SearchResult.yml" sourcestartlinenumber="1">This delegate is not for public use and is used internally by the system to
implement support for other ArcGIS Pro modules.</p>


## Object Signature

```csharp
public class SearchResult
```


## Members

### SearchResult()

- Kind: constructor

<p sourcefile="api/ESRI.ArcGIS.ItemIndex.SearchResult.yml" sourcestartlinenumber="1">This delegate is not for public use and is used internally by the system to
implement support for other ArcGIS Pro modules.</p>


```csharp
public SearchResult()
```
### Items

- Kind: property

<p sourcefile="api/ESRI.ArcGIS.ItemIndex.SearchResult.yml" sourcestartlinenumber="1">The set of ItemInfoValue returned by the search operation.</p>


```csharp
public ItemInfoValue[] Items { get; set; }
```
### NextStart

- Kind: property

<p sourcefile="api/ESRI.ArcGIS.ItemIndex.SearchResult.yml" sourcestartlinenumber="1">The next start position of search results.</p>


```csharp
public int NextStart { get; set; }
```
### Token

- Kind: property

<p sourcefile="api/ESRI.ArcGIS.ItemIndex.SearchResult.yml" sourcestartlinenumber="1">The identifier to identify the search owner and client.</p>


```csharp
public string Token { get; set; }
```
### TotalCount

- Kind: property

<p sourcefile="api/ESRI.ArcGIS.ItemIndex.SearchResult.yml" sourcestartlinenumber="1">The total number of items returned by the search operation.</p>


```csharp
public int TotalCount { get; set; }
```


