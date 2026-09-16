# KnowledgeGraphUniformIdentifier

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Knowledge.html">Knowledge</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphUniformIdentifier.yml" sourcestartlinenumber="1">Represents a unique identifier information object for a knowledge graph
that uses a uniform property as the unique identifier for entities and
relationships.</p>


## Object Signature

```csharp
public sealed class KnowledgeGraphUniformIdentifier : KnowledgeGraphIdentifierInfo, IDisposable
```


## Members

### GetIdentifierName()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphUniformIdentifier.yml" sourcestartlinenumber="1">Get the name of the property serving as the unique identifier for
entities and relationships in the knowledge graph.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetIdentifierName()
```


