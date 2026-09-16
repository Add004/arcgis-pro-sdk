# KnowledgeGraphDataModel

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Knowledge.html">Knowledge</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphDataModel.yml" sourcestartlinenumber="1">Represents the data model for the knowledge graph.</p>


## Object Signature

```csharp
public sealed class KnowledgeGraphDataModel : CoreObjectsBase, IDisposable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphDataModel.yml" sourcestartlinenumber="1">The data model includes metadata about the knowledge graph, including
but not limited to entity and relationship types, spatial reference,
and information about generation of unique identifiers.</p>


## Members

### GetEntityTypes()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphDataModel.yml" sourcestartlinenumber="1">Gets a dictionary, with the keys being the names of the entity types
in the data model, and the values being objects containing information
about each entity type.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyDictionary<string, KnowledgeGraphEntityType> GetEntityTypes()
```
### GetIdentifierInfo()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphDataModel.yml" sourcestartlinenumber="1">Gets an object containing information about unique identifiers in
the knowledge graph.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public KnowledgeGraphIdentifierInfo GetIdentifierInfo()
```
### GetIsArcGISManaged()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphDataModel.yml" sourcestartlinenumber="1">Gets a boolean indicating whether the data in the knowledge
graph is ArcGIS managed.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool GetIsArcGISManaged()
```
### GetIsStrict()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphDataModel.yml" sourcestartlinenumber="1">Get a boolean indicating whether the data model is strict.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool GetIsStrict()
```
### GetMetaEntityTypes()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphDataModel.yml" sourcestartlinenumber="1">Gets a dictionary, with the keys being the names of the meta entity types
in the data model, and the values being objects containing information
about each meta entity type.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyDictionary<string, KnowledgeGraphEntityType> GetMetaEntityTypes()
```
### GetOIDPropertyName()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphDataModel.yml" sourcestartlinenumber="1">Gets the name of the ObjectID property for the knowledge graph.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetOIDPropertyName()
```
### GetProvenanceType()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphDataModel.yml" sourcestartlinenumber="1">Gets the provenance entity type.   If the knowledge graph does not support provenance, then null will be returned.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public KnowledgeGraphEntityType GetProvenanceType()
```
### GetRelationshipTypes()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphDataModel.yml" sourcestartlinenumber="1">Gets a dictionary, with the keys being the names of the relationship types
in the data model, and the values being objects containing information
about each relationship type.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyDictionary<string, KnowledgeGraphRelationshipType> GetRelationshipTypes()
```
### GetSpatialReference()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphDataModel.yml" sourcestartlinenumber="1">Get the spatial reference for the knowledge graph.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SpatialReference GetSpatialReference()
```
### GetTimestamp()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphDataModel.yml" sourcestartlinenumber="1">Get the timestamp indicating when the data model was last modified.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public DateTime GetTimestamp()
```


