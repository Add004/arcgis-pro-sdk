# DiagramManager

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.NetworkDiagrams.html">NetworkDiagrams</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramManager.yml" sourcestartlinenumber="1">Represents a diagram manager object, the core class in the network diagram API.</p>


## Object Signature

```csharp
public sealed class DiagramManager : CoreObjectsBase, IDisposable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramManager.yml" sourcestartlinenumber="1">The DiagramManager object is obtained by calling <xref href="ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork.GetDiagramManager" data-throw-if-not-resolved="false"></xref>.  Use the DiagramManager class to:</p>
<ul><li>Create network diagrams</li><li>Retrieve diagram templates</li><li>Retrieve network diagrams</li></ul>


## Members

### CreateNetworkDiagram(DiagramTemplate, IEnumerable&lt;Guid&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramManager.yml" sourcestartlinenumber="1">Creates a <xref href="ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram" data-throw-if-not-resolved="false"></xref> based on a <xref href="ArcGIS.Core.Data.NetworkDiagrams.DiagramTemplate" data-throw-if-not-resolved="false"></xref>
from a list of row GlobalIDs.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public NetworkDiagram CreateNetworkDiagram(DiagramTemplate diagramTemplate, IEnumerable<Guid> globalIDs)
```
### CreateNetworkDiagramFromCircuitName(DiagramTemplate, string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramManager.yml" sourcestartlinenumber="1">Creates a <xref href="ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram" data-throw-if-not-resolved="false"></xref> based on a <xref href="ArcGIS.Core.Data.NetworkDiagrams.DiagramTemplate" data-throw-if-not-resolved="false"></xref>
from circuit name.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public NetworkDiagram CreateNetworkDiagramFromCircuitName(DiagramTemplate diagramTemplate, string circuitName)
```
### CreateNetworkDiagramFromCircuitName(DiagramTemplate, string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramManager.yml" sourcestartlinenumber="1">Creates a <xref href="ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram" data-throw-if-not-resolved="false"></xref> based on a <xref href="ArcGIS.Core.Data.NetworkDiagrams.DiagramTemplate" data-throw-if-not-resolved="false"></xref>
from circuit name.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public NetworkDiagram CreateNetworkDiagramFromCircuitName(DiagramTemplate diagramTemplate, string circuitName, string telecomDomainName)
```
### CreateNetworkDiagramFromTraceLocations(DiagramTemplate, Table, Table, Table)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramManager.yml" sourcestartlinenumber="1">Creates a <xref href="ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram" data-throw-if-not-resolved="false"></xref> based on a <xref href="ArcGIS.Core.Data.NetworkDiagrams.DiagramTemplate" data-throw-if-not-resolved="false"></xref>
from trace locations stored in tables.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public NetworkDiagram CreateNetworkDiagramFromTraceLocations(DiagramTemplate diagramTemplate, Table startingPointsTable, Table stoppingPointsTable, Table barriersTable)
```
### GetDiagramTemplate(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramManager.yml" sourcestartlinenumber="1">Retrieves the <xref href="ArcGIS.Core.Data.NetworkDiagrams.DiagramTemplate" data-throw-if-not-resolved="false"></xref> with the specified name.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public DiagramTemplate GetDiagramTemplate(string name)
```
### GetDiagramTemplateNames(DiagramTemplateInputType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramManager.yml" sourcestartlinenumber="1">Gets the list of diagram template names available for the <xref href="ArcGIS.Core.Data.NetworkDiagrams.DiagramTemplateInputType" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<string> GetDiagramTemplateNames(DiagramTemplateInputType diagramTemplateInput)
```
### GetDiagramTemplates()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramManager.yml" sourcestartlinenumber="1">Gets the full list of available <xref href="ArcGIS.Core.Data.NetworkDiagrams.DiagramTemplate" data-throw-if-not-resolved="false"></xref>s.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<DiagramTemplate> GetDiagramTemplates()
```
### GetNetworkDiagram(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramManager.yml" sourcestartlinenumber="1">Retrieves the <xref href="ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram" data-throw-if-not-resolved="false"></xref> with the specified name.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public NetworkDiagram GetNetworkDiagram(string name)
```
### GetNetworkDiagrams()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramManager.yml" sourcestartlinenumber="1">Gets the full list of <xref href="ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram" data-throw-if-not-resolved="false"></xref>s.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<NetworkDiagram> GetNetworkDiagrams()
```
### GetNetworkDiagrams(Envelope)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramManager.yml" sourcestartlinenumber="1">Gets the list of <xref href="ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram" data-throw-if-not-resolved="false"></xref>s which overlap with the specified extent.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<NetworkDiagram> GetNetworkDiagrams(Envelope extentOfInterest)
```
### GetNetworkDiagrams(Envelope, IEnumerable&lt;Guid&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramManager.yml" sourcestartlinenumber="1">Gets the list of <xref href="ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram" data-throw-if-not-resolved="false"></xref>s which either overlap the specified extent or contain at least one of the specified features.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<NetworkDiagram> GetNetworkDiagrams(Envelope extentOfInterest, IEnumerable<Guid> globalIDs)
```
### GetNetworkDiagrams(IEnumerable&lt;Guid&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramManager.yml" sourcestartlinenumber="1">Gets the list of <xref href="ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram" data-throw-if-not-resolved="false"></xref>s which contain at least one of the specified features.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<NetworkDiagram> GetNetworkDiagrams(IEnumerable<Guid> globalIDs)
```
### GetNetwork&lt;T&gt;()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.DiagramManager.yml" sourcestartlinenumber="1">Gets the network related to this diagram manager.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public T GetNetwork<T>() where T : Dataset
```


