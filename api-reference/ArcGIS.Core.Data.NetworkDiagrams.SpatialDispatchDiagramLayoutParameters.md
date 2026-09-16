# SpatialDispatchDiagramLayoutParameters

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.NetworkDiagrams.html">NetworkDiagrams</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.SpatialDispatchDiagramLayoutParameters.yml" sourcestartlinenumber="1">Represents the Spatial Dispatch diagram layout parameters. This layout algorithm separates diagram junctions that are visibly close to overlapping.</p>


## Object Signature

```csharp
public sealed class SpatialDispatchDiagramLayoutParameters : DiagramLayoutParameters
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.SpatialDispatchDiagramLayoutParameters.yml" sourcestartlinenumber="1">This layout algorithm progressively separates diagram junctions that are visibly close to overlapping according to their current positions and to the shift factor specified.</p>


## Members

### MaximumShiftFactor

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.SpatialDispatchDiagramLayoutParameters.yml" sourcestartlinenumber="1">Increases the diagram junction displacement for junctions that are very close together.</p>


```csharp
public double MaximumShiftFactor { get; set; }
```
### NumberOfIterations

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.SpatialDispatchDiagramLayoutParameters.yml" sourcestartlinenumber="1">Gets and sets the number of iterations used when computing the layout.</p>


```csharp
public int NumberOfIterations { get; set; }
```
### PreserveContainers

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.SpatialDispatchDiagramLayoutParameters.yml" sourcestartlinenumber="1">Indicates whether or not the containers are preserved.</p>


```csharp
public bool PreserveContainers { get; set; }
```


