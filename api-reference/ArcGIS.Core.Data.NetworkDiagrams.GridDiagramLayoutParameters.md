# GridDiagramLayoutParameters

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.NetworkDiagrams.html">NetworkDiagrams</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.GridDiagramLayoutParameters.yml" sourcestartlinenumber="1">Represents the Grid diagram layout parameters. This layout algorithm positions diagram junctions relative to a predefined magnetic grid.</p>


## Object Signature

```csharp
public sealed class GridDiagramLayoutParameters : DiagramLayoutParameters
```

## Remarks

<ul>
  <li>This algorithm positions diagram junctions relative to a magnetic grid that has cell sizes fixed by the <xref href="ArcGIS.Core.Data.NetworkDiagrams.GridDiagramLayoutParameters.CellWidth" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Core.Data.NetworkDiagrams.GridDiagramLayoutParameters.CellHeight" data-throw-if-not-resolved="false"></xref> parameter values.</li>
  <li>A grid with a specified cell size is essentially placed on the top of the diagram. The algorithm controls the number of cells that comprise a grid. 
    This is calculated by factoring in the number of junctions that are going to be placed in the grid and the number of junctions that belong to each cell in the virtual grid.</li>
</ul>


## Members

### CellHeight

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.GridDiagramLayoutParameters.yml" sourcestartlinenumber="1">The height of each grid cell.</p>


```csharp
public double CellHeight { get; set; }
```
### CellWidth

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.GridDiagramLayoutParameters.yml" sourcestartlinenumber="1">The width of each grid cell.</p>


```csharp
public double CellWidth { get; set; }
```
### PreserveContainers

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.GridDiagramLayoutParameters.yml" sourcestartlinenumber="1">Indicates whether or not the containers are preserved.</p>


```csharp
public bool PreserveContainers { get; set; }
```


