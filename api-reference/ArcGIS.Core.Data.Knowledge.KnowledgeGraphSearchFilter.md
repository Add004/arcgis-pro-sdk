# KnowledgeGraphSearchFilter

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Knowledge.html">Knowledge</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphSearchFilter.yml" sourcestartlinenumber="1">Represents a filter for performing a full text search against a
<xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraph" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class KnowledgeGraphSearchFilter
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphSearchFilter.yml" sourcestartlinenumber="1">Refer to <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraph.SubmitSearch(ArcGIS.Core.Data.Knowledge.KnowledgeGraphSearchFilter)" data-throw-if-not-resolved="false"></xref></p>


## Members

### KnowledgeGraphSearchFilter()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphSearchFilter.yml" sourcestartlinenumber="1">Represents a filter for performing a full text search against a
<xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraph" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public KnowledgeGraphSearchFilter()
```
### MaxRowCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphSearchFilter.yml" sourcestartlinenumber="1">Gets or sets the maximum number of rows returned by the search.
The default value is 100.</p>


```csharp
public int MaxRowCount { get; set; }
```
### Offset

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphSearchFilter.yml" sourcestartlinenumber="1">Gets or sets the index of the first result to return.
The default value is 0.</p>


```csharp
public int Offset { get; set; }
```
### ReturnSearchContext

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphSearchFilter.yml" sourcestartlinenumber="1">Gets or sets whether to include search context fields.
The default value is false.</p>


```csharp
public bool ReturnSearchContext { get; set; }
```
### SearchTarget

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphSearchFilter.yml" sourcestartlinenumber="1">Gets or sets the target of the search.
The default value is <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphNamedTypeCategory.Entity" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public KnowledgeGraphNamedTypeCategory SearchTarget { get; set; }
```
### SearchText

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphSearchFilter.yml" sourcestartlinenumber="1">Gets or sets the search query used to filter the returned rows.
This text should abide by the
<a href="https://lucene.apache.org/core/2_9_4/queryparsersyntax.html">Apache Lucene query syntax</a>.</p>


```csharp
public string SearchText { get; set; }
```


