# AngleDirectedDiagramLayoutParameters

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.NetworkDiagrams.html">NetworkDiagrams</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.AngleDirectedDiagramLayoutParameters.yml" sourcestartlinenumber="1">Represents the Angle Directed diagram layout parameters. This layout algorithm moves a diagram's edges in specified alignment directions.</p>


## Object Signature

```csharp
public sealed class AngleDirectedDiagramLayoutParameters : DiagramLayoutParameters
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.AngleDirectedDiagramLayoutParameters.yml" sourcestartlinenumber="1">This layout algorithm progressively moves the diagram's edges in specified alignment directions. For each diagram edge, this layout considers its current direction, searches for the nearest desired direction among those specified, and moves the edge in that direction.</p>


## Members

### NumberOfDirections

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.AngleDirectedDiagramLayoutParameters.yml" sourcestartlinenumber="1">The number of directions that must be used to align the diagram edges and their connected junctions.</p>


```csharp
public AngleDirectedDiagramLayoutParameters.Directions NumberOfDirections { get; set; }
```
### NumberOfIterations

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.AngleDirectedDiagramLayoutParameters.yml" sourcestartlinenumber="1">Gets and sets the number of iterations used when computing the layout.</p>


```csharp
public int NumberOfIterations { get; set; }
```
### PreserveContainers

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.AngleDirectedDiagramLayoutParameters.yml" sourcestartlinenumber="1">Indicates whether or not the containers are preserved.</p>


```csharp
public bool PreserveContainers { get; set; }
```


