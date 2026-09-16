# KnowledgeGraphPathValue

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Knowledge.html">Knowledge</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphPathValue.yml" sourcestartlinenumber="1">Represents a path value in a knowledge graph.</p>


## Object Signature

```csharp
public class KnowledgeGraphPathValue : KnowledgeGraphValue, IDisposable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphPathValue.yml" sourcestartlinenumber="1">Paths represent a series of connected entities and relationships
usually described by an openCypher query of the form (e1)-[]-&gt;(e2),
(e1)-[]-&gt;(e2)&lt;-[]-&gt;(e3), and so on</p>


## Members

### GetEntity(ulong)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphPathValue.yml" sourcestartlinenumber="1">Get the entity value at the specified index in the path.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public KnowledgeGraphEntityValue GetEntity(ulong index)
```
### GetEntityCount()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphPathValue.yml" sourcestartlinenumber="1">Gets the number of entities in the path.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public ulong GetEntityCount()
```
### GetRelationship(ulong)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphPathValue.yml" sourcestartlinenumber="1">Get the relationship value at the specified index in the path.
relationship[n] connects entity[n] and entity[n+1].
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public KnowledgeGraphRelationshipValue GetRelationship(ulong index)
```
### GetRelationshipCount()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphPathValue.yml" sourcestartlinenumber="1">Gets the number of relationships in the path.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public ulong GetRelationshipCount()
```


