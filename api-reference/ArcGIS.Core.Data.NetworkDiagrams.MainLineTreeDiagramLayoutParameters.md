# MainLineTreeDiagramLayoutParameters

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.NetworkDiagrams.html">NetworkDiagrams</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.MainLineTreeDiagramLayoutParameters.yml" sourcestartlinenumber="1">Represents the Mainline Tree diagram layout parameters. This layout algorithm arranges diagram junctions and edges hierarchically along a main line.</p>


## Object Signature

```csharp
public sealed class MainLineTreeDiagramLayoutParameters : DiagramLayoutParameters
```

## Remarks

<ul>
  <li>This layout algorithm arranges the junctions and edges in the input network diagram hierarchically along a main line and places its related branches on the left side, the right side, or both sides of the main line.</li>
  <li>Root and end junctions can be specified in the diagram so the Mainline Tree layout algorithm builds a main line starting at a specified root junction and ending at a specified end junction.</li>
</ul>


## Members

### AbsoluteUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.MainLineTreeDiagramLayoutParameters.yml" sourcestartlinenumber="1">Indicates whether or not the distances are in absolute units.</p>


```csharp
public bool AbsoluteUnit { get; set; }
```
### AlongSpacing

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.MainLineTreeDiagramLayoutParameters.yml" sourcestartlinenumber="1">Spacing between diagram junctions that display along the axis of the main line.</p>


```csharp
public double AlongSpacing { get; set; }
```
### BreakPointPosition

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.MainLineTreeDiagramLayoutParameters.yml" sourcestartlinenumber="1">Relative position (between 0 and 1) of the break point on the subtree edges.</p>


```csharp
public double BreakPointPosition { get; set; }
```
### Direction

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.MainLineTreeDiagramLayoutParameters.yml" sourcestartlinenumber="1">The direction of the main line.</p>


```csharp
public MainLineTreeDiagramLayoutParameters.TreeDirection Direction { get; set; }
```
### DisjoinedGraphSpacing

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.MainLineTreeDiagramLayoutParameters.yml" sourcestartlinenumber="1">The minimum spacing that must separate features belonging to disjoined graphs when the diagram contains such graphs.</p>


```csharp
public double DisjoinedGraphSpacing { get; set; }
```
### EdgeTypes

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.MainLineTreeDiagramLayoutParameters.yml" sourcestartlinenumber="1">The type of display for the diagram edges related to the tree branches.</p>


```csharp
public MainLineTreeDiagramLayoutParameters.EdgeType EdgeTypes { get; set; }
```
### Offset

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.MainLineTreeDiagramLayoutParameters.yml" sourcestartlinenumber="1">Indicates the distance that will separate the detected overlapping edge segments.</p>


```csharp
public double Offset { get; set; }
```
### PerpendicularSpacing

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.MainLineTreeDiagramLayoutParameters.yml" sourcestartlinenumber="1">Spacing between diagram junctions that display along the axis perpendicular to the main line.</p>


```csharp
public double PerpendicularSpacing { get; set; }
```
### Placement

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.MainLineTreeDiagramLayoutParameters.yml" sourcestartlinenumber="1">The way the branches which start from the main line are placed for <xref href="ArcGIS.Core.Data.NetworkDiagrams.MainLineTreeDiagramLayoutParameters" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public MainLineTreeDiagramLayoutParameters.BranchPlacement Placement { get; set; }
```
### PreserveContainers

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.MainLineTreeDiagramLayoutParameters.yml" sourcestartlinenumber="1">Indicates whether or not the containers are preserved.</p>


```csharp
public bool PreserveContainers { get; set; }
```


