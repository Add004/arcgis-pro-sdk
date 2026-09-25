# RelativeMainlineDiagramLayoutParameters

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.NetworkDiagrams.html">NetworkDiagrams</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.RelativeMainlineDiagramLayoutParameters.yml" sourcestartlinenumber="1">Represents the Relative Mainline diagram layout parameters. This layout algorithm arranges diagram junctions and edges along a relative main line.</p>


## Object Signature

```csharp
public sealed class RelativeMainlineDiagramLayoutParameters : DiagramLayoutParameters
```

## Remarks

<ul>
  <li>This layout algorithm arranges the network diagram features in the input network diagram along parallel straight lines for which all the connected edges have the same attribute value. 
    It also places the branches coming from those lines, preserving both their directions regarding the straight lines and distances proportional to the initial distances and relative to each other.
    </li>
</ul>


## Members

### AlignmentAttributeName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.RelativeMainlineDiagramLayoutParameters.yml" sourcestartlinenumber="1">The name of the network attribute that will be used to align individual line features.</p>


```csharp
public string AlignmentAttributeName { get; set; }
```
### BranchValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.RelativeMainlineDiagramLayoutParameters.yml" sourcestartlinenumber="1">The TypeAttributeName values that identify the branches.</p>


```csharp
public string[] BranchValues { get; set; }
```
### BreakPointAngle

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.RelativeMainlineDiagramLayoutParameters.yml" sourcestartlinenumber="1">The angle that will be used to position the break point on the branches.</p>


```csharp
public double BreakPointAngle { get; set; }
```
### CompressAlongDirection

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.RelativeMainlineDiagramLayoutParameters.yml" sourcestartlinenumber="1">Indicates whether or not the compression along the main line direction is active.</p>


```csharp
public bool CompressAlongDirection { get; set; }
```
### CompressionRatio

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.RelativeMainlineDiagramLayoutParameters.yml" sourcestartlinenumber="1">Compression ratio used to compress the junction along the axis of the main line.</p>


```csharp
public double CompressionRatio { get; set; }
```
### Direction

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.RelativeMainlineDiagramLayoutParameters.yml" sourcestartlinenumber="1">The direction of the relative main line.</p>


```csharp
public RelativeMainlineDiagramLayoutParameters.TreeDirection Direction { get; set; }
```
### ExcludedValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.RelativeMainlineDiagramLayoutParameters.yml" sourcestartlinenumber="1">The TypeAttributeName values that identify the edges that must be excluded from the straight lines; that is, crossovers or ladders.</p>


```csharp
public string[] ExcludedValues { get; set; }
```
### LengthAttributeName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.RelativeMainlineDiagramLayoutParameters.yml" sourcestartlinenumber="1">The network attribute that the layout algorithm uses to measure the length of the diagram edges.</p>


```csharp
public string LengthAttributeName { get; set; }
```
### LineAttributeName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.RelativeMainlineDiagramLayoutParameters.yml" sourcestartlinenumber="1">The name of the network attribute that will be used to identify the lines which compose the straight lines.</p>


```csharp
public string LineAttributeName { get; set; }
```
### MainlineValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.RelativeMainlineDiagramLayoutParameters.yml" sourcestartlinenumber="1">The TypeAttributeName values that identify the main lines.</p>


```csharp
public string[] MainlineValues { get; set; }
```
### MinimalDistance

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.RelativeMainlineDiagramLayoutParameters.yml" sourcestartlinenumber="1">Minimal distance that must be kept between two adjacent groups of neighbor junctions.</p>


```csharp
public double MinimalDistance { get; set; }
```
### OffsetBetweenBranches

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.RelativeMainlineDiagramLayoutParameters.yml" sourcestartlinenumber="1">The spacing between two adjacent branches along the axis perpendicular to the direction of the line.</p>


```csharp
public double OffsetBetweenBranches { get; set; }
```
### TypeAttributeName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.RelativeMainlineDiagramLayoutParameters.yml" sourcestartlinenumber="1">The name of the network attribute that is used to group lines into types.</p>


```csharp
public string TypeAttributeName { get; set; }
```


