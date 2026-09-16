# Topology

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Topology.html">Topology</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Topology.Topology.yml" sourcestartlinenumber="1">Represents a topology dataset.</p>


## Object Signature

```csharp
public sealed class Topology : Dataset, IDisposable
```


## Members

### BuildGraph(Geometry, Action&lt;TopologyGraph&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Topology.Topology.yml" sourcestartlinenumber="1">Creates an in-memory representation of the topologically-integrated features within the current topology for
a given area.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void BuildGraph(Geometry extent, Action<TopologyGraph> callBack)
```
### GetDefinition()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Topology.Topology.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Topology.TopologyDefinition" data-throw-if-not-resolved="false"></xref> of this dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public TopologyDefinition GetDefinition()
```
### GetErrors(ErrorDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Topology.Topology.yml" sourcestartlinenumber="1">Gets the error features associated with a topology.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<TopologyError> GetErrors(ErrorDescription description)
```
### GetExtent()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Topology.Topology.yml" sourcestartlinenumber="1">Gets an <xref href="ArcGIS.Core.Geometry.Envelope" data-throw-if-not-resolved="false"></xref> representing the maximum extent of the union of all the
feature classes that participate in the <xref href="ArcGIS.Core.Data.Topology.Topology" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Envelope GetExtent()
```
### GetState()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Topology.Topology.yml" sourcestartlinenumber="1">Gets the state of the topology.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public TopologyState GetState()
```
### MarkAsException(TopologyError)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Topology.Topology.yml" sourcestartlinenumber="1">Marks the topology error specified by <code class="paramref">error</code> as an exception.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void MarkAsException(TopologyError error)
```
### Type

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Topology.Topology.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.DatasetType" data-throw-if-not-resolved="false"></xref> of this derived dataset.</p>


```csharp
public override DatasetType Type { get; }
```
### UnmarkAsException(TopologyError)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Topology.Topology.yml" sourcestartlinenumber="1">Resets <code class="paramref">error</code> currently marked as an exception to once again be an error.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void UnmarkAsException(TopologyError error)
```
### Validate(ValidationDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Topology.Topology.yml" sourcestartlinenumber="1">Ensures data integrity by validating the features in a topology in the area specified by
<xref href="ArcGIS.Core.Data.Topology.ValidationDescription.Extent" data-throw-if-not-resolved="false"></xref> against a pre-defined set of topology rules.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public ValidationResult Validate(ValidationDescription description)
```


