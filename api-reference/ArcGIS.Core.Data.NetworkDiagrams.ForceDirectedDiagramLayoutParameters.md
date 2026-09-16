# ForceDirectedDiagramLayoutParameters

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.NetworkDiagrams.html">NetworkDiagrams</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.ForceDirectedDiagramLayoutParameters.yml" sourcestartlinenumber="1">Represents the Force Directed diagram layout parameters.</p>


## Object Signature

```csharp
public sealed class ForceDirectedDiagramLayoutParameters : DiagramLayoutParameters
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.ForceDirectedDiagramLayoutParameters.yml" sourcestartlinenumber="1">This layout algorithm uses a physical analogy to draw graphs by considering a graph a force system in which it tries to locally minimize the energy.
It searches for an equilibrium state of the force system—a position for each diagram junction where the total force on each junction is zero.</p>
<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.ForceDirectedDiagramLayoutParameters.yml" sourcestartlinenumber="4">Because this algorithm has a tendency to emphasize loops contained in a network diagram, it is often used by operators who manage highly meshed networks, such as water, wastewater, or gas.</p>


## Members

### BreakPointPosition

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.ForceDirectedDiagramLayoutParameters.yml" sourcestartlinenumber="1">Relative position (between 0.15 and 0.40) of the break point on the diagram edges.</p>


```csharp
public double BreakPointPosition { get; set; }
```
### DegreeOfFreedom

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.ForceDirectedDiagramLayoutParameters.yml" sourcestartlinenumber="1">Gets and sets the degree of freedom.</p>


```csharp
public ForceDirectedDiagramLayoutParameters.Freedom DegreeOfFreedom { get; set; }
```
### EdgeTypes

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.ForceDirectedDiagramLayoutParameters.yml" sourcestartlinenumber="1">Edge types related to the branches.</p>


```csharp
public ForceDirectedDiagramLayoutParameters.EdgeType EdgeTypes { get; set; }
```
### NumberOfIterations

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.ForceDirectedDiagramLayoutParameters.yml" sourcestartlinenumber="1">Gets and sets the number of iterations used when computing the layout.</p>


```csharp
public int NumberOfIterations { get; set; }
```
### PreserveContainers

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.ForceDirectedDiagramLayoutParameters.yml" sourcestartlinenumber="1">Indicates whether or not the containers are preserved.</p>


```csharp
public bool PreserveContainers { get; set; }
```
### RepelFactor

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.ForceDirectedDiagramLayoutParameters.yml" sourcestartlinenumber="1">Factor used to quickly increase diagram junctions displacement for junctions that are close together.</p>


```csharp
public double RepelFactor { get; set; }
```


