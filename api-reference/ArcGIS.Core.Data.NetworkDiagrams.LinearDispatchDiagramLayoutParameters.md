# LinearDispatchDiagramLayoutParameters

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.NetworkDiagrams.html">NetworkDiagrams</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.LinearDispatchDiagramLayoutParameters.yml" sourcestartlinenumber="1">Represents the Linear Dispatch diagram layout parameters. This layout algorithms spaces out diagram junctions that are visually too close, overlapping, or coincident.</p>


## Object Signature

```csharp
public sealed class LinearDispatchDiagramLayoutParameters : DiagramLayoutParameters
```

## Remarks

<ul>
  <li>This layout algorithm spaces out diagram junctions that are visually too close, overlapping, or coincident. It moves junctions along their connected edges. 
    The movement along the edges depends on the current and relative position of junctions and on the layout parameters.</li>
  <li>This algorithm also separates diagram edges connected to the target junctions. The valence for these junctions is taken into account—that is, 
    the number of their adjacent edges as well as the edge paths can be preserved.</li>
  <li>This layout is especially useful for water, wastewater, and gas but can be deployed for other industries as well.</li>
</ul>


## Members

### AbsoluteUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.LinearDispatchDiagramLayoutParameters.yml" sourcestartlinenumber="1">Indicates whether or not the distances are in absolute units.</p>


```csharp
public bool AbsoluteUnit { get; set; }
```
### ExpandLeaves

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.LinearDispatchDiagramLayoutParameters.yml" sourcestartlinenumber="1">Indicates whether or not the leaf junctions are expanded.</p>


```csharp
public bool ExpandLeaves { get; set; }
```
### JunctionsPlacement

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.LinearDispatchDiagramLayoutParameters.yml" sourcestartlinenumber="1">Specifies how the junctions will move.</p>


```csharp
public LinearDispatchDiagramLayoutParameters.Placement JunctionsPlacement { get; set; }
```
### LeavesShift

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.LinearDispatchDiagramLayoutParameters.yml" sourcestartlinenumber="1">The maximum distance the leaf junctions must be expanded from the junctions to which they connect.</p>


```csharp
public double LeavesShift { get; set; }
```
### MaximumShift

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.LinearDispatchDiagramLayoutParameters.yml" sourcestartlinenumber="1">The maximum distance the junctions with two connections can be spaced from the junctions to which they connect.</p>


```csharp
public double MaximumShift { get; set; }
```
### MinimumShift

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.LinearDispatchDiagramLayoutParameters.yml" sourcestartlinenumber="1">The minimum distance that will separate each junction with two connected edges from its two edge extremities after the layout execution.</p>


```csharp
public double MinimumShift { get; set; }
```
### MoveLeaves

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.LinearDispatchDiagramLayoutParameters.yml" sourcestartlinenumber="1">Specifies whether the leaf junctions— the junctions with one connection— can be moved during the algorithm execution</p>


```csharp
public bool MoveLeaves { get; set; }
```
### NumberOfIterations

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.LinearDispatchDiagramLayoutParameters.yml" sourcestartlinenumber="1">Gets and sets the number of iterations used when computing the layout.</p>


```csharp
public int NumberOfIterations { get; set; }
```
### PreservePath

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.LinearDispatchDiagramLayoutParameters.yml" sourcestartlinenumber="1">Indicates whether or not the path is preserved.</p>


```csharp
public bool PreservePath { get; set; }
```


