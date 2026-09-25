# TopologyDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Topology.html">Topology</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyDefinition.yml" sourcestartlinenumber="1">Represents the schema and properties of a <xref href="ArcGIS.Core.Data.Topology.Topology" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class TopologyDefinition : Definition, IDisposable
```


## Members

### DatasetType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyDefinition.yml" sourcestartlinenumber="1">Gets the dataset type.</p>


```csharp
public override DatasetType DatasetType { get; }
```
### GetClusterTolerance()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyDefinition.yml" sourcestartlinenumber="1">Gets the cluster tolerance of the topology.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double GetClusterTolerance()
```
### GetFeatureClassNames()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyDefinition.yml" sourcestartlinenumber="1">Gets the name of all the <xref href="ArcGIS.Core.Data.FeatureClass" data-throw-if-not-resolved="false"></xref>s that participate in the <xref href="ArcGIS.Core.Data.Topology.Topology" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<string> GetFeatureClassNames()
```
### GetRules()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyDefinition.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Topology.TopologyRule" data-throw-if-not-resolved="false"></xref>s defined for this <xref href="ArcGIS.Core.Data.Topology.Topology" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<TopologyRule> GetRules()
```
### GetZClusterTolerance()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyDefinition.yml" sourcestartlinenumber="1">Gets the Z cluster tolerance of the topology.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double GetZClusterTolerance()
```


