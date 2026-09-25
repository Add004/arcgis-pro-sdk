# KnowledgeGraphCentralityScores

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Knowledge.html">Knowledge</a>.<a class="xref" href="ArcGIS.Core.Data.Knowledge.Analytics.html">Analytics</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.KnowledgeGraphCentralityScores.yml" sourcestartlinenumber="1">Represents the set of scores for a knowledge graph centrality analysis.</p>


## Object Signature

```csharp
public class KnowledgeGraphCentralityScores
```


## Members

### this[object]

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.KnowledgeGraphCentralityScores.yml" sourcestartlinenumber="1">Indexer to retrieve the array of scores for a specific entity
identified by its UID.</p>


```csharp
public double[] this[object uid] { get; }
```
### Measures

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.KnowledgeGraphCentralityScores.yml" sourcestartlinenumber="1">Gets the array of centrality measures used in the centrality analysis</p>


```csharp
public CentralityMeasure[] Measures { get; }
```
### RawScores

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.KnowledgeGraphCentralityScores.yml" sourcestartlinenumber="1">Gets the &quot;raw&quot; array of all scores for all entities used in the centrality analysis.</p>


```csharp
public double[] RawScores { get; }
```


