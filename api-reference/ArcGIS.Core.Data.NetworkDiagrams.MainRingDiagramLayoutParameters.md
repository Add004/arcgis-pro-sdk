# MainRingDiagramLayoutParameters

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.NetworkDiagrams.html">NetworkDiagrams</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.MainRingDiagramLayoutParameters.yml" sourcestartlinenumber="1">Represents the Main Ring diagram layout parameters. This layout algorithm arranges the diagram features in a network diagram around a main ring.</p>


## Object Signature

```csharp
public sealed class MainRingDiagramLayoutParameters : DiagramLayoutParameters
```

## Remarks

<ul>
  <li>
    This layout algorithm arranges the diagram features around the main ring and hierarchically lays out the subset of diagram features that connect to each diagram junction placed along the main ring.
    </li>
  <li>
    The main ring is the loop formed by the largest number of edges in the network diagram.
    </li>
  <li>
    If the network diagram contains no loops, the Main Ring layout algorithm execution has no effect.
    </li>
  <li>
    This layout algorithm is typically used in the telecommunications industry.
    </li>
</ul>


## Members

### AbsoluteUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.MainRingDiagramLayoutParameters.yml" sourcestartlinenumber="1">Indicates whether or not the distances are in absolute units.</p>


```csharp
public bool AbsoluteUnit { get; set; }
```
### BreakPointPosition

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.MainRingDiagramLayoutParameters.yml" sourcestartlinenumber="1">Relative position (between 0 and 1) of the break point on the subtree edges.</p>


```csharp
public double BreakPointPosition { get; set; }
```
### Offset

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.MainRingDiagramLayoutParameters.yml" sourcestartlinenumber="1">Indicates the distance that will separate the detected overlapping edge segments.</p>


```csharp
public double Offset { get; set; }
```
### PreserveContainers

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.MainRingDiagramLayoutParameters.yml" sourcestartlinenumber="1">Indicates whether or not the containers are preserved.</p>


```csharp
public bool PreserveContainers { get; set; }
```
### RingHeight

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.MainRingDiagramLayoutParameters.yml" sourcestartlinenumber="1">Specifies the height of the ring.</p>


```csharp
public double RingHeight { get; set; }
```
### RingType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.MainRingDiagramLayoutParameters.yml" sourcestartlinenumber="1">The type of ring.</p>


```csharp
public MainRingDiagramLayoutParameters.MainRingType RingType { get; set; }
```
### RingWidth

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.MainRingDiagramLayoutParameters.yml" sourcestartlinenumber="1">Specifies the width of the ring.</p>


```csharp
public double RingWidth { get; set; }
```
### SubTreeAlongSpacing

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.MainRingDiagramLayoutParameters.yml" sourcestartlinenumber="1">Specifies the spacing between diagram junctions that are displayed along the tree direction.</p>


```csharp
public double SubTreeAlongSpacing { get; set; }
```
### SubTreeEdgeType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.MainRingDiagramLayoutParameters.yml" sourcestartlinenumber="1">The type of display for the diagram edges related to the tree branches.</p>


```csharp
public MainRingDiagramLayoutParameters.EdgeType SubTreeEdgeType { get; set; }
```
### SubTreePerpendicularSpacing

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.MainRingDiagramLayoutParameters.yml" sourcestartlinenumber="1">Specifies the spacing between diagram junctions that are displayed perpendicular to the tree direction and belong to the same subtree level.</p>


```csharp
public double SubTreePerpendicularSpacing { get; set; }
```
### SubtreeType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.MainRingDiagramLayoutParameters.yml" sourcestartlinenumber="1">Specifies how the trees coming out of the main ring's junctions will be positioned.</p>


```csharp
public MainRingDiagramLayoutParameters.TreeType SubtreeType { get; set; }
```


