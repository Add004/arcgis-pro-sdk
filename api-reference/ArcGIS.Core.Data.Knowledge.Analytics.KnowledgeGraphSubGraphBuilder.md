# KnowledgeGraphSubGraphBuilder

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Knowledge.html">Knowledge</a>.<a class="xref" href="ArcGIS.Core.Data.Knowledge.Analytics.html">Analytics</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.KnowledgeGraphSubGraphBuilder.yml" sourcestartlinenumber="1">A builder for creating a <xref href="ArcGIS.Core.CIM.CIMKnowledgeGraphSubGraph" data-throw-if-not-resolved="false"></xref>
for use in KnowledgeGraph operations such as centrality.</p>


## Object Signature

```csharp
public sealed class KnowledgeGraphSubGraphBuilder
```

## Remarks

<pre><code sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.KnowledgeGraphSubGraphBuilder.yml" sourcestartlinenumber="1">        This builder aids in building a &lt;xref href=&quot;ArcGIS.Core.CIM.CIMKnowledgeGraphSubGraph&quot; data-throw-if-not-resolved=&quot;false&quot;&gt;&lt;/xref&gt; from
        a &lt;xref href=&quot;ArcGIS.Core.Data.Knowledge.KnowledgeGraphIDSet&quot; data-throw-if-not-resolved=&quot;false&quot;&gt;&lt;/xref&gt;. To build a more complex &lt;xref href=&quot;ArcGIS.Core.CIM.CIMKnowledgeGraphSubGraph&quot; data-throw-if-not-resolved=&quot;false&quot;&gt;&lt;/xref&gt;
        or use property filters (&lt;xref href=&quot;ArcGIS.Core.CIM.CIMKnowledgeGraphNamedTypeFilterByType.PropertyFilterPredicate&quot; data-throw-if-not-resolved=&quot;false&quot;&gt;&lt;/xref&gt;), create
        the &lt;xref href=&quot;ArcGIS.Core.CIM.CIMKnowledgeGraphSubGraph&quot; data-throw-if-not-resolved=&quot;false&quot;&gt;&lt;/xref&gt; and its component filters &lt;xref href=&quot;ArcGIS.Core.CIM.CIMKnowledgeGraphNamedTypeFilterByInstances&quot; data-throw-if-not-resolved=&quot;false&quot;&gt;&lt;/xref&gt;
        and &lt;xref href=&quot;ArcGIS.Core.CIM.CIMKnowledgeGraphNamedTypeFilterByType&quot; data-throw-if-not-resolved=&quot;false&quot;&gt;&lt;/xref&gt;
        manually.

        &lt;p&gt;&lt;/p&gt;

        The following are examples of what a CIMKnowledgeGraphSubGraph would look like given a Knowledge Graph with entity types
        (A, B, C, D).&lt;br /&gt;Refer to &lt;xref href=&quot;ArcGIS.Core.CIM.CIMKnowledgeGraphSubGraph.EntityFilters&quot; data-throw-if-not-resolved=&quot;false&quot;&gt;&lt;/xref&gt; defining the list of filters for entities, and
        &lt;xref href=&quot;ArcGIS.Core.CIM.CIMKnowledgeGraphNamedTypeFilter.FilterType&quot; data-throw-if-not-resolved=&quot;false&quot;&gt;&lt;/xref&gt; defining whether a particular filter includes or excludes the instances it represents.
        Ordering of filters does not matter.&lt;br /&gt;&lt;br /&gt;
        o When the collection of filters in the CIMKnowledgeGraphSubGraph is null, all entities
        are implicitly in the subgraph, i.e the resulting set of entities in the subgraph is {A, B, C, D}.&lt;br /&gt;
        o When there is a single filter and it includes A, the resulting set of entities in the subgraph is {A}.&lt;br /&gt;
        o When there is a single filter and it excludes A, the resulting set of entities in the subgraph is {B, C, D}.&lt;br /&gt;
        o When there are two filters, one filter includes A and one filter excludes B, the resulting set of
        entities in the subgraph is still {A}. (i.e. B, C, and D are all excluded, the &quot;exclusion&quot;
        filter was unnecessary in this case as only A was explicitly included) &lt;br /&gt;&lt;br /&gt;To include or exclude just a specific &lt;i&gt;subset&lt;/i&gt; of entities within a given entity type, use
        either &lt;xref href=&quot;ArcGIS.Core.CIM.CIMKnowledgeGraphNamedTypeFilterByInstances.InstancesIDs&quot; data-throw-if-not-resolved=&quot;false&quot;&gt;&lt;/xref&gt; or
        &lt;xref href=&quot;ArcGIS.Core.CIM.CIMKnowledgeGraphNamedTypeFilterByType.PropertyFilterPredicate&quot; data-throw-if-not-resolved=&quot;false&quot;&gt;&lt;/xref&gt;.
</code></pre>
<p></p>
<pre><code sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.KnowledgeGraphSubGraphBuilder.yml" sourcestartlinenumber="25">        The filtering behaviors described above for entities apply equally to relationships - which are
        configured in exactly the same way. Refer to &lt;xref href=&quot;ArcGIS.Core.CIM.CIMKnowledgeGraphSubGraph.RelationshipFilters&quot; data-throw-if-not-resolved=&quot;false&quot;&gt;&lt;/xref&gt;.
        &lt;br /&gt;Note: relationships having at least one entity endpoint that is not in the subgraph are also not
        in the subgraph.
</code></pre>


## Members

### KnowledgeGraphSubGraphBuilder()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.KnowledgeGraphSubGraphBuilder.yml" sourcestartlinenumber="1">Creates a new empty instance of the KnowledgeGraphSubGraphBuilder class.</p>


```csharp
public KnowledgeGraphSubGraphBuilder()
```
### KnowledgeGraphSubGraphBuilder(KnowledgeGraphIDSet)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.KnowledgeGraphSubGraphBuilder.yml" sourcestartlinenumber="1">Creates an instance of the KnowledgeGraphSubGraphBuilder class initialized with the named types and ids in the
<code class="paramref">kgIDSet</code>.</p>


```csharp
public KnowledgeGraphSubGraphBuilder(KnowledgeGraphIDSet kgIDSet)
```
### ToCIMKnowledgeGraphSubGraph()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.KnowledgeGraphSubGraphBuilder.yml" sourcestartlinenumber="1">Create the <xref href="ArcGIS.Core.CIM.CIMKnowledgeGraphSubGraph" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public CIMKnowledgeGraphSubGraph ToCIMKnowledgeGraphSubGraph()
```


