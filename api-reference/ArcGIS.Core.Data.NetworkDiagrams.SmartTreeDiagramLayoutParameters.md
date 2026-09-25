# SmartTreeDiagramLayoutParameters

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.NetworkDiagrams.html">NetworkDiagrams</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.SmartTreeDiagramLayoutParameters.yml" sourcestartlinenumber="1">Represents the Smart Tree diagram layout parameters. This layout algorithm arranges diagram features hierarchically and places them in a smart tree.</p>


## Object Signature

```csharp
public sealed class SmartTreeDiagramLayoutParameters : DiagramLayoutParameters
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.SmartTreeDiagramLayoutParameters.yml" sourcestartlinenumber="1">This layout algorithm arranges the diagram features hierarchically and places them in a smart tree according to the direction and spacing distances specified.</p>
<ul><li>
When a root junction is specified in the diagram, the Smart Tree Layout algorithm builds a smart tree starting from that junction.
</li><li>
When several root junctions are specified in the diagram, those root junctions are aligned along the same axis perpendicularly to the tree direction and appear as different start points for a tree branch of the diagram.
</li><li>If no root junction is specified, the algorithm selects the diagram junction associated with the smallest utility network topology index and considers this junction the root junction.
</li></ul>


## Members

### AbsoluteUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.SmartTreeDiagramLayoutParameters.yml" sourcestartlinenumber="1">Indicates whether or not the distances are in absolute units.</p>


```csharp
public bool AbsoluteUnit { get; set; }
```
### AlongSpacing

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.SmartTreeDiagramLayoutParameters.yml" sourcestartlinenumber="1">Specifies the spacing between diagram junctions that are displayed along the smart tree direction.</p>


```csharp
public double AlongSpacing { get; set; }
```
### AttributeAvailability

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.SmartTreeDiagramLayoutParameters.yml" sourcestartlinenumber="1">Gets and sets the Attribute availability to Junction or Edge</p>


```csharp
public SmartTreeDiagramLayoutParameters.EElementType AttributeAvailability { get; set; }
```
### AttributeName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.SmartTreeDiagramLayoutParameters.yml" sourcestartlinenumber="1">Name of the attribute used by the sort.</p>


```csharp
public string AttributeName { get; set; }
```
### AttributeSortOrder

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.SmartTreeDiagramLayoutParameters.yml" sourcestartlinenumber="1">Gets and sets the order of the sort.</p>


```csharp
public SmartTreeDiagramLayoutParameters.ESortingOrder AttributeSortOrder { get; set; }
```
### BreakPointPosition

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.SmartTreeDiagramLayoutParameters.yml" sourcestartlinenumber="1">Relative position (between 0 and 1) of the break point on the subtree edges.</p>


```csharp
public double BreakPointPosition { get; set; }
```
### Direction

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.SmartTreeDiagramLayoutParameters.yml" sourcestartlinenumber="1">The direction of the tree.</p>


```csharp
public SmartTreeDiagramLayoutParameters.TreeDirection Direction { get; set; }
```
### DisjoinedGraphSpacing

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.SmartTreeDiagramLayoutParameters.yml" sourcestartlinenumber="1">The minimum spacing that must separate features belonging to disjoined graphs when the diagram contains such graphs.</p>


```csharp
public double DisjoinedGraphSpacing { get; set; }
```
### EdgesType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.SmartTreeDiagramLayoutParameters.yml" sourcestartlinenumber="1">The type of display for the diagram edges related to the tree branches.</p>


```csharp
public SmartTreeDiagramLayoutParameters.EdgeType EdgesType { get; set; }
```
### Offset

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.SmartTreeDiagramLayoutParameters.yml" sourcestartlinenumber="1">Indicates the distance that will separate the detected overlapping edge segments.</p>


```csharp
public double Offset { get; set; }
```
### OrderTreeBranches

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.SmartTreeDiagramLayoutParameters.yml" sourcestartlinenumber="1">Sort by attribute, or use position.</p>


```csharp
public bool OrderTreeBranches { get; set; }
```
### PerpendicularSpacing

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.SmartTreeDiagramLayoutParameters.yml" sourcestartlinenumber="1">Specifies the spacing between diagram junctions that are displayed perpendicular to the smart tree direction and belong to the same subtree level.</p>


```csharp
public double PerpendicularSpacing { get; set; }
```
### PreserveContainers

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.SmartTreeDiagramLayoutParameters.yml" sourcestartlinenumber="1">Indicates whether or not the containers are preserved.</p>


```csharp
public bool PreserveContainers { get; set; }
```
### SubtreeSpacing

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.SmartTreeDiagramLayoutParameters.yml" sourcestartlinenumber="1">Determines the spacing between two neighboring subtrees.</p>


```csharp
public double SubtreeSpacing { get; set; }
```


