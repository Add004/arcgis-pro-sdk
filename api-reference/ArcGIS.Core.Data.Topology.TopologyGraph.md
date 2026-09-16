# TopologyGraph

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Topology.html">Topology</a>
- Assembly: ArcGIS.Core.dll

<p>
    Represents an in-memory representation of the topologically-integrated features within the current topology.
    </p>
<p>
    When a topology graph is built via <xref href="ArcGIS.Core.Data.Topology.Topology.BuildGraph(ArcGIS.Core.Geometry.Geometry%2cSystem.Action%7bArcGIS.Core.Data.Topology.TopologyGraph%7d)" data-throw-if-not-resolved="false"></xref>, spatial relationships between features
    are discovered, analyzed and established to form an in-memory graph of topological elements. These topological
    elements consist of <xref href="ArcGIS.Core.Data.Topology.TopologyNode" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Core.Data.Topology.TopologyEdge" data-throw-if-not-resolved="false"></xref>, which correspond to points and
    lines, respectively, in the feature space.
    </p>
<p>
    A <i>parent feature</i> refers to a feature in the feature space from which one or more topological elements are
    created in the topology graph space.
    </p>


## Object Signature

```csharp
public sealed class TopologyGraph : CoreObjectsBase, IDisposable
```


## Members

### FindClosestElement&lt;T&gt;(MapPoint, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyGraph.yml" sourcestartlinenumber="1">Finds a topological element in the topology graph closest to the location specified by <code class="paramref">queryPoint</code>
that is also within <code class="paramref">searchRadius</code> units.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public T FindClosestElement<T>(MapPoint queryPoint, double searchRadius) where T : TopologyElement
```
### GetEdges()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyGraph.yml" sourcestartlinenumber="1">Gets all the <xref href="ArcGIS.Core.Data.Topology.TopologyEdge" data-throw-if-not-resolved="false"></xref>s that exist in the topology graph.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<TopologyEdge> GetEdges()
```
### GetEdges(Feature)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyGraph.yml" sourcestartlinenumber="1">Gets the set of <xref href="ArcGIS.Core.Data.Topology.TopologyEdge" data-throw-if-not-resolved="false"></xref>s corresponding to the feature specified by <code class="paramref">parentFeature</code>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<TopologyEdge> GetEdges(Feature parentFeature)
```
### GetNodes()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyGraph.yml" sourcestartlinenumber="1">Gets all the <xref href="ArcGIS.Core.Data.Topology.TopologyNode" data-throw-if-not-resolved="false"></xref>s that exist in the topology graph.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<TopologyNode> GetNodes()
```
### GetNodes(Feature)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyGraph.yml" sourcestartlinenumber="1">Gets the set of <xref href="ArcGIS.Core.Data.Topology.TopologyNode" data-throw-if-not-resolved="false"></xref>s corresponding to the feature specified by <code class="paramref">parentFeature</code>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<TopologyNode> GetNodes(Feature parentFeature)
```


