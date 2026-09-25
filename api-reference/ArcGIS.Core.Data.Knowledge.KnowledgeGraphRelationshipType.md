# KnowledgeGraphRelationshipType

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Knowledge.html">Knowledge</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphRelationshipType.yml" sourcestartlinenumber="1">Represents a relationship type in the knowledge graph.</p>


## Object Signature

```csharp
public sealed class KnowledgeGraphRelationshipType : KnowledgeGraphNamedObjectType, IDisposable
```


## Members

### GetEndPoints()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphRelationshipType.yml" sourcestartlinenumber="1">Get a list of observed end points for the relationship type
in the knowledge graph.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<KnowledgeGraphEndPoint> GetEndPoints()
```


