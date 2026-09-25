# FullTextSearchTermExpression

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.FullTextSearchTermExpression.yml" sourcestartlinenumber="1"><code>FullTextSearchTermExpression</code> is used for full-text search with search terms, phrases, or keywords.</p>


## Object Signature

```csharp
public sealed class FullTextSearchTermExpression : FullTextExpression
```


## Members

### FullTextSearchTermExpression()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.FullTextSearchTermExpression.yml" sourcestartlinenumber="1">Initializes a new instance of the <xref href="ArcGIS.Core.Data.FullTextSearchTermExpression" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public FullTextSearchTermExpression()
```
### SearchFields

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.FullTextSearchTermExpression.yml" sourcestartlinenumber="1">Gets and sets the fields to be searched.</p>


```csharp
public string SearchFields { get; set; }
```
### SearchTerm

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.FullTextSearchTermExpression.yml" sourcestartlinenumber="1">Gets and sets the search term, keyword, or phrase.</p>


```csharp
public string SearchTerm { get; set; }
```
### SearchType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.FullTextSearchTermExpression.yml" sourcestartlinenumber="1">Gets and sets the type of search.</p>


```csharp
public FullTextSearchType SearchType { get; set; }
```


