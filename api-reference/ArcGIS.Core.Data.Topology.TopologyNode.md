# TopologyNode

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Topology.html">Topology</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyNode.yml" sourcestartlinenumber="1">Represents a topological node within a topology graph.</p>


## Object Signature

```csharp
public sealed class TopologyNode : TopologyElement, IDisposable, IEquatable<TopologyElement>, IEquatable<TopologyNode>
```


## Members

### Equals(TopologyNode)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyNode.yml" sourcestartlinenumber="1">Determines whether two <xref href="ArcGIS.Core.Data.Topology.TopologyNode" data-throw-if-not-resolved="false"></xref> instances are equal.</p>


```csharp
public bool Equals(TopologyNode other)
```
### Equals(object)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyNode.yml" sourcestartlinenumber="1">Determines whether two <xref href="ArcGIS.Core.Data.Topology.TopologyNode" data-throw-if-not-resolved="false"></xref> instances are equal.</p>


```csharp
public override bool Equals(object obj)
```
### GetEdges(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyNode.yml" sourcestartlinenumber="1">Gets the set of topological edges that are coincident with this node.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<TopologyEdge> GetEdges(bool clockwise = true)
```
### GetHashCode()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyNode.yml" sourcestartlinenumber="1">Gets a hash code for the current object.</p>


```csharp
public override int GetHashCode()
```
### operator ==(TopologyNode, TopologyNode)

- Kind: operator

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyNode.yml" sourcestartlinenumber="1">Determines whether two <xref href="ArcGIS.Core.Data.Topology.TopologyNode" data-throw-if-not-resolved="false"></xref> instances are equal.</p>


```csharp
public static bool operator ==(TopologyNode topologyNode1, TopologyNode topologyNode2)
```
### operator !=(TopologyNode, TopologyNode)

- Kind: operator

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyNode.yml" sourcestartlinenumber="1">Determines whether two <xref href="ArcGIS.Core.Data.Topology.TopologyNode" data-throw-if-not-resolved="false"></xref> instances are not equal.</p>


```csharp
public static bool operator !=(TopologyNode topologyNode1, TopologyNode topologyNode2)
```


