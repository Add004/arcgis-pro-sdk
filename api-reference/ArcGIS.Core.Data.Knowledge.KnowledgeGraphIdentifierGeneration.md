# KnowledgeGraphIdentifierGeneration

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Knowledge.html">Knowledge</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphIdentifierGeneration.yml" sourcestartlinenumber="1">Represents an object containing information about how the knowledge
graph service generates unique identifiers.</p>


## Object Signature

```csharp
public sealed class KnowledgeGraphIdentifierGeneration : CoreObjectsBase, IDisposable
```


## Members

### GetMethodHint()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphIdentifierGeneration.yml" sourcestartlinenumber="1">Gets the UUID method hint for the knowledge graph.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public KnowledgeGraphUUIDMethodHint GetMethodHint()
```


