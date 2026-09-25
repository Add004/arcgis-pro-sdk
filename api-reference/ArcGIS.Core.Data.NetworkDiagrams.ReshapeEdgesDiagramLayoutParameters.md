# ReshapeEdgesDiagramLayoutParameters

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.NetworkDiagrams.html">NetworkDiagrams</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.ReshapeEdgesDiagramLayoutParameters.yml" sourcestartlinenumber="1">Represents the Reshape Diagram Edges diagram layout parameters. This layout algorithm processes simple operations on vertices along edges.</p>


## Object Signature

```csharp
public sealed class ReshapeEdgesDiagramLayoutParameters : DiagramLayoutParameters
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.ReshapeEdgesDiagramLayoutParameters.yml" sourcestartlinenumber="1">This layout is used to process simple operations on vertices along edges in network diagrams.
It enables you to reduce all vertices or some vertices along diagram edges, square diagram edges with the addition of vertices on edges, and separate diagram edges that overlap.</p>


## Members

### AttributeName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.ReshapeEdgesDiagramLayoutParameters.yml" sourcestartlinenumber="1">Name of the attribute used by the sort when executing the <xref href="ArcGIS.Core.Data.NetworkDiagrams.ReshapeEdgesDiagramLayoutParameters.Operation.SeparateOverlappingEdges" data-throw-if-not-resolved="false"></xref> operation.</p>


```csharp
public string AttributeName { get; set; }
```
### AttributeSortOrder

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.ReshapeEdgesDiagramLayoutParameters.yml" sourcestartlinenumber="1">The order of the sort when executing the <xref href="ArcGIS.Core.Data.NetworkDiagrams.ReshapeEdgesDiagramLayoutParameters.Operation.SeparateOverlappingEdges" data-throw-if-not-resolved="false"></xref> operation.</p>


```csharp
public ReshapeEdgesDiagramLayoutParameters.ESortingOrder AttributeSortOrder { get; set; }
```
### BreakpointSpacing

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.ReshapeEdgesDiagramLayoutParameters.yml" sourcestartlinenumber="1">Breakpoint spacing when executing the <xref href="ArcGIS.Core.Data.NetworkDiagrams.ReshapeEdgesDiagramLayoutParameters.Operation.SquareEdges" data-throw-if-not-resolved="false"></xref> operation.</p>


```csharp
public double BreakpointSpacing { get; set; }
```
### CircularArcRadius

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.ReshapeEdgesDiagramLayoutParameters.yml" sourcestartlinenumber="1">Circular arc radius when executing the <xref href="ArcGIS.Core.Data.NetworkDiagrams.ReshapeEdgesDiagramLayoutParameters.Operation.MarkCrossingEdges" data-throw-if-not-resolved="false"></xref> operation.</p>


```csharp
public double CircularArcRadius { get; set; }
```
### EdgeSpacing

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.ReshapeEdgesDiagramLayoutParameters.yml" sourcestartlinenumber="1">Edge spacing when executing the <xref href="ArcGIS.Core.Data.NetworkDiagrams.ReshapeEdgesDiagramLayoutParameters.Operation.SeparateOverlappingEdges" data-throw-if-not-resolved="false"></xref> operation.</p>


```csharp
public double EdgeSpacing { get; set; }
```
### MarkCrossingPosition

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.ReshapeEdgesDiagramLayoutParameters.yml" sourcestartlinenumber="1">Specifies the position of the mark crossing when executing the <xref href="ArcGIS.Core.Data.NetworkDiagrams.ReshapeEdgesDiagramLayoutParameters.Operation.MarkCrossingEdges" data-throw-if-not-resolved="false"></xref> operation.</p>


```csharp
public ReshapeEdgesDiagramLayoutParameters.MarkPosition MarkCrossingPosition { get; set; }
```
### PreserveContainers

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.ReshapeEdgesDiagramLayoutParameters.yml" sourcestartlinenumber="1">Indicates whether or not the containers are preserved.</p>


```csharp
public bool PreserveContainers { get; set; }
```
### PreservePath

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.ReshapeEdgesDiagramLayoutParameters.yml" sourcestartlinenumber="1">Indicates whether or not the path is preserved if the <xref href="ArcGIS.Core.Data.NetworkDiagrams.ReshapeEdgesDiagramLayoutParameters.ReshapeOperation" data-throw-if-not-resolved="false"></xref> equals <xref href="ArcGIS.Core.Data.NetworkDiagrams.ReshapeEdgesDiagramLayoutParameters.Operation.SquareEdges" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public bool PreservePath { get; set; }
```
### ReshapeOperation

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.ReshapeEdgesDiagramLayoutParameters.yml" sourcestartlinenumber="1">Specifies how edges will be reshaped.</p>


```csharp
public ReshapeEdgesDiagramLayoutParameters.Operation ReshapeOperation { get; set; }
```
### SegmentSpacing

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.ReshapeEdgesDiagramLayoutParameters.yml" sourcestartlinenumber="1">Segment spacing when executing the <xref href="ArcGIS.Core.Data.NetworkDiagrams.ReshapeEdgesDiagramLayoutParameters.Operation.SquareEdges" data-throw-if-not-resolved="false"></xref> operation.</p>


```csharp
public double SegmentSpacing { get; set; }
```
### ThresholdAngle

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.ReshapeEdgesDiagramLayoutParameters.yml" sourcestartlinenumber="1">Threshold angle when executing the <xref href="ArcGIS.Core.Data.NetworkDiagrams.ReshapeEdgesDiagramLayoutParameters.Operation.ReduceVerticesByAngle" data-throw-if-not-resolved="false"></xref> operation.</p>


```csharp
public double ThresholdAngle { get; set; }
```
### areEdgesOrderedByAttribute

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.ReshapeEdgesDiagramLayoutParameters.yml" sourcestartlinenumber="1">Sort by attribute when executing the <xref href="ArcGIS.Core.Data.NetworkDiagrams.ReshapeEdgesDiagramLayoutParameters.Operation.SeparateOverlappingEdges" data-throw-if-not-resolved="false"></xref> operation.</p>


```csharp
public bool areEdgesOrderedByAttribute { get; set; }
```


