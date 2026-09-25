# KnowledgeGraphRelationshipValue

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Knowledge.html">Knowledge</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphRelationshipValue.yml" sourcestartlinenumber="1">Represents a knowledge graph relationship.</p>


## Object Signature

```csharp
public class KnowledgeGraphRelationshipValue : KnowledgeGraphNamedObjectValue, IDisposable
```


## Members

### GetDestinationID()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphRelationshipValue.yml" sourcestartlinenumber="1">Gets the ID of the destination value associated with the relationship.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public virtual object GetDestinationID()
```
### GetHasRelatedEntityIDs()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphRelationshipValue.yml" sourcestartlinenumber="1">Gets whether the relationship has associated entity ids.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public virtual bool GetHasRelatedEntityIDs()
```
### GetOriginID()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphRelationshipValue.yml" sourcestartlinenumber="1">Gets the ID of the origin value associated with the relationship.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public virtual object GetOriginID()
```


