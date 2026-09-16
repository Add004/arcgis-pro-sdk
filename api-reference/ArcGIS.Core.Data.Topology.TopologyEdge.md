# TopologyEdge

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Topology.html">Topology</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyEdge.yml" sourcestartlinenumber="1">Represents a topological edge within a topology graph.</p>


## Object Signature

```csharp
public sealed class TopologyEdge : TopologyElement, IDisposable, IEquatable<TopologyElement>, IEquatable<TopologyEdge>
```


## Members

### Equals(TopologyEdge)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyEdge.yml" sourcestartlinenumber="1">Determines whether two <xref href="ArcGIS.Core.Data.Topology.TopologyEdge" data-throw-if-not-resolved="false"></xref> instances are equal.</p>


```csharp
public bool Equals(TopologyEdge other)
```
### Equals(object)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyEdge.yml" sourcestartlinenumber="1">Determines whether two <xref href="ArcGIS.Core.Data.Topology.TopologyEdge" data-throw-if-not-resolved="false"></xref> instances are equal.</p>


```csharp
public override bool Equals(object obj)
```
### GetFromNode()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyEdge.yml" sourcestartlinenumber="1">Gets the topology node at the <i>from</i> point of this edge.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public TopologyNode GetFromNode()
```
### GetHashCode()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyEdge.yml" sourcestartlinenumber="1">Gets a hash code for the current object.</p>


```csharp
public override int GetHashCode()
```
### GetLeftParentFeatures(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyEdge.yml" sourcestartlinenumber="1">Gets the set of parents (polygon features) that cover this edge. If <code class="paramref">boundedByEdge</code> is true,
then only polygons lying to the left of the edge will be returned.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<FeatureInfo> GetLeftParentFeatures(bool boundedByEdge = true)
```
### GetRightParentFeatures(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyEdge.yml" sourcestartlinenumber="1">Gets the set of parents (polygon features) that cover this edge. If <code class="paramref">boundedByEdge</code> is true,
then only polygons lying to the right of the edge will be returned.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<FeatureInfo> GetRightParentFeatures(bool boundedByEdge = true)
```
### GetToNode()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyEdge.yml" sourcestartlinenumber="1">Gets the topology node at the <i>to</i> point of this edge.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public TopologyNode GetToNode()
```
### operator ==(TopologyEdge, TopologyEdge)

- Kind: operator

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyEdge.yml" sourcestartlinenumber="1">Determines whether two <xref href="ArcGIS.Core.Data.Topology.TopologyEdge" data-throw-if-not-resolved="false"></xref> instances are equal.</p>


```csharp
public static bool operator ==(TopologyEdge topologyEdge1, TopologyEdge topologyEdge2)
```
### operator !=(TopologyEdge, TopologyEdge)

- Kind: operator

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyEdge.yml" sourcestartlinenumber="1">Determines whether two <xref href="ArcGIS.Core.Data.Topology.TopologyEdge" data-throw-if-not-resolved="false"></xref> instances are not equal.</p>


```csharp
public static bool operator !=(TopologyEdge topologyEdge1, TopologyEdge topologyEdge2)
```


