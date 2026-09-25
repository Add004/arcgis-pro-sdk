# TopologyElement

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Topology.html">Topology</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyElement.yml" sourcestartlinenumber="1">Represents a topological element within a topology graph.</p>


## Object Signature

```csharp
public class TopologyElement : CoreObjectsBase, IDisposable, IEquatable<TopologyElement>
```


## Members

### Equals(TopologyElement)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyElement.yml" sourcestartlinenumber="1">Determines whether two <xref href="ArcGIS.Core.Data.Topology.TopologyElement" data-throw-if-not-resolved="false"></xref> instances are equal.</p>


```csharp
public bool Equals(TopologyElement other)
```
### Equals(object)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyElement.yml" sourcestartlinenumber="1">Determines whether two <xref href="ArcGIS.Core.Data.Topology.TopologyElement" data-throw-if-not-resolved="false"></xref> instances are equal.</p>


```csharp
public override bool Equals(object obj)
```
### GetHashCode()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyElement.yml" sourcestartlinenumber="1">Gets a hash code for the current object.</p>


```csharp
public override int GetHashCode()
```
### GetParentFeatures()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyElement.yml" sourcestartlinenumber="1">Gets the parent feature(s) that spawn this topology element.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<FeatureInfo> GetParentFeatures()
```
### GetShape()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyElement.yml" sourcestartlinenumber="1">Gets the shape of this topology element.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Geometry GetShape()
```
### IsVisited()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyElement.yml" sourcestartlinenumber="1">Gets a value indicating whether this topology element has been visited.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool IsVisited()
```
### SetVisited(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyElement.yml" sourcestartlinenumber="1">Sets a value indicating whether this topology element has been visited.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetVisited(bool visited)
```
### operator ==(TopologyElement, TopologyElement)

- Kind: operator

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyElement.yml" sourcestartlinenumber="1">Determines whether two <xref href="ArcGIS.Core.Data.Topology.TopologyElement" data-throw-if-not-resolved="false"></xref> instances are equal.</p>


```csharp
public static bool operator ==(TopologyElement topologyElement1, TopologyElement topologyElement2)
```
### operator !=(TopologyElement, TopologyElement)

- Kind: operator

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyElement.yml" sourcestartlinenumber="1">Determines whether two <xref href="ArcGIS.Core.Data.Topology.TopologyElement" data-throw-if-not-resolved="false"></xref> instances are not equal.</p>


```csharp
public static bool operator !=(TopologyElement topologyElement1, TopologyElement topologyElement2)
```


