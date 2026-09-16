# KnowledgeGraph

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Knowledge.html">Knowledge</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraph.yml" sourcestartlinenumber="1">Represents a Knowledge Graph datastore.</p>


## Object Signature

```csharp
public sealed class KnowledgeGraph : Datastore, IDisposable
```


## Members

### KnowledgeGraph(KnowledgeGraphConnectionProperties)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraph.yml" sourcestartlinenumber="1">Opens a knowledge graph datastore with a <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphConnectionProperties" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public KnowledgeGraph(KnowledgeGraphConnectionProperties connectionProperties)
```
### ApplyEdits(Action)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraph.yml" sourcestartlinenumber="1">Executes the <code class="paramref">action</code> delegate as a single transaction.
The transaction either completes successfully or is aborted and rolled back.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void ApplyEdits(Action action)
```
### GetConnector()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraph.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Connector" data-throw-if-not-resolved="false"></xref> associated with the currently opened knowledge graph data store.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public override Connector GetConnector()
```
### GetDataModel()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraph.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphDataModel" data-throw-if-not-resolved="false"></xref> for the knowledge graph.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public KnowledgeGraphDataModel GetDataModel()
```
### GetDefinition&lt;T&gt;(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraph.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.TableDefinition" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Core.Data.FeatureClassDefinition" data-throw-if-not-resolved="false"></xref>
associated with <code class="paramref">name</code>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public T GetDefinition<T>(string name) where T : Definition
```
### GetDefinitions&lt;T&gt;()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraph.yml" sourcestartlinenumber="1">Gets an <xref href="System.Collections.Generic.IReadOnlyList%601" data-throw-if-not-resolved="false"></xref> of specific <xref href="ArcGIS.Core.Data.Definition" data-throw-if-not-resolved="false"></xref> instances
associated with each dataset of type <code class="typeparamref">T</code> in the knowledge graph.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<T> GetDefinitions<T>() where T : Definition
```
### GetDomains()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraph.yml" sourcestartlinenumber="1">Gets all the <xref href="ArcGIS.Core.Data.Domain" data-throw-if-not-resolved="false"></xref> in this knowledge graph.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<Domain> GetDomains()
```
### GetPropertyNameInfo()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraph.yml" sourcestartlinenumber="1">Gets the object containing the unique identifier property names in this knowledge graph.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public KnowledgeGraphPropertyInfo GetPropertyNameInfo()
```
### GetSpatialReference()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraph.yml" sourcestartlinenumber="1">Gets the spatial reference of the knowledge graph.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SpatialReference GetSpatialReference()
```
### GetSupportedSearchTargets()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraph.yml" sourcestartlinenumber="1">Gets the supported search targets for the knowledge graph.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<KnowledgeGraphNamedTypeCategory> GetSupportedSearchTargets()
```
### OpenDataset&lt;T&gt;(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraph.yml" sourcestartlinenumber="1">Gets a specific <xref href="ArcGIS.Core.Data.Dataset" data-throw-if-not-resolved="false"></xref> instance associated with <code class="paramref">name</code> of type <code class="typeparamref">T</code>
in the knowledge graph. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public T OpenDataset<T>(string name) where T : Dataset
```
### SubmitQuery(KnowledgeGraphQueryFilter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraph.yml" sourcestartlinenumber="1">Performs an openCypher query on the knowledge graph using the
given <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphQueryFilter" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public KnowledgeGraphCursor SubmitQuery(KnowledgeGraphQueryFilter queryFilter)
```
### SubmitSearch(KnowledgeGraphSearchFilter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraph.yml" sourcestartlinenumber="1">Perform a text search on the knowledge graph using the given
<xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphSearchFilter" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public KnowledgeGraphCursor SubmitSearch(KnowledgeGraphSearchFilter searchFilter)
```
### TransformToIDs(string, IEnumerable&lt;long&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraph.yml" sourcestartlinenumber="1">Translates a set of objectIDs for a Knowledge Graph type into IDs.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<object> TransformToIDs(string typeName, IEnumerable<long> oids)
```
### TransformToObjectIDs(string, IEnumerable&lt;object&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraph.yml" sourcestartlinenumber="1">Translates a set of ids for a Knowledge Graph type into objectIDs.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<long> TransformToObjectIDs(string typeName, IEnumerable<object> ids)
```
### TransformToObjectIDs&lt;ListType&gt;(Dictionary&lt;string, ListType&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraph.yml" sourcestartlinenumber="1">Translates a set of IDs by type for a Knowledge Graph type into objectIDs.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Dictionary<string, List<long>> TransformToObjectIDs<ListType>(Dictionary<string, ListType> dict) where ListType : IEnumerable<object>
```


