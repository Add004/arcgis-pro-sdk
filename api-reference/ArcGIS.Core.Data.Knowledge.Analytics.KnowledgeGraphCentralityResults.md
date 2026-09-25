# KnowledgeGraphCentralityResults

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Knowledge.html">Knowledge</a>.<a class="xref" href="ArcGIS.Core.Data.Knowledge.Analytics.html">Analytics</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.KnowledgeGraphCentralityResults.yml" sourcestartlinenumber="1">Represents the results of a knowledge graph centrality analysis.</p>


## Object Signature

```csharp
public class KnowledgeGraphCentralityResults
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.KnowledgeGraphCentralityResults.yml" sourcestartlinenumber="1">Contains the list of named types, entity uids, and their scores
for the computation</p>


## Members

### KnowledgeGraphCentralityResults()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.KnowledgeGraphCentralityResults.yml" sourcestartlinenumber="1">Represents the results of a knowledge graph centrality analysis.</p>


```csharp
public KnowledgeGraphCentralityResults()
```
### GetUidsForNamedType(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.KnowledgeGraphCentralityResults.yml" sourcestartlinenumber="1">Gets the set of Uids for all entities in the centrality analysis
for the given named type.</p>


```csharp
public IEnumerable<object> GetUidsForNamedType(string namedType)
```
### NamedTypes

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.KnowledgeGraphCentralityResults.yml" sourcestartlinenumber="1">Gets the list of entity named types used in the centrality analysis.</p>


```csharp
public List<string> NamedTypes { get; }
```
### RawUids

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.KnowledgeGraphCentralityResults.yml" sourcestartlinenumber="1">Gets an array of all uids for all entities in the centrality analysis.</p>


```csharp
public object[] RawUids { get; }
```
### Scores

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.KnowledgeGraphCentralityResults.yml" sourcestartlinenumber="1">Gets the centrality scores for the entities in the centrality analysis.</p>


```csharp
public KnowledgeGraphCentralityScores Scores { get; }
```


