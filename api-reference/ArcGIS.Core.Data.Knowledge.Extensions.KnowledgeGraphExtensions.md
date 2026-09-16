# KnowledgeGraphExtensions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Knowledge.html">Knowledge</a>.<a class="xref" href="ArcGIS.Core.Data.Knowledge.Extensions.html">Extensions</a>
- Assembly: ArcGIS.Desktop.Extensions.dll

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Extensions.KnowledgeGraphExtensions.yml" sourcestartlinenumber="1">Extension methods for KnowledgeGraph</p>


## Object Signature

```csharp
public static class KnowledgeGraphExtensions
```


## Members

### ComputeCentrality(KnowledgeGraph, CIMKnowledgeGraphCentralityConfiguration, CIMKnowledgeGraphSubGraph, IEnumerable&lt;CentralityMeasure&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Extensions.KnowledgeGraphExtensions.yml" sourcestartlinenumber="1">Computes centrality measures for the specified knowledge graph and subgraph.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static KnowledgeGraphCentralityResults ComputeCentrality(this KnowledgeGraph kg, CIMKnowledgeGraphCentralityConfiguration configuration, CIMKnowledgeGraphSubGraph subGraph, IEnumerable<CentralityMeasure> centralityMeasures)
```
### RunFilteredFindPaths(KnowledgeGraph, CIMFilteredFindPathsConfiguration)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Extensions.KnowledgeGraphExtensions.yml" sourcestartlinenumber="1">Find paths in the specified knowledge graph using Filtered Find Paths (FFP).
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static KnowledgeGraphFilteredFindPathsResults RunFilteredFindPaths(this KnowledgeGraph kg, CIMFilteredFindPathsConfiguration configuration)
```


