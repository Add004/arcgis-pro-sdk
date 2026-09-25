# RadialTreeDiagramLayoutParameters

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.NetworkDiagrams.html">NetworkDiagrams</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.RadialTreeDiagramLayoutParameters.yml" sourcestartlinenumber="1">Represents the Radial Tree diagram layout parameters. This layout algorithm arranges diagram features hierarchically and places them in a radial tree.</p>


## Object Signature

```csharp
public sealed class RadialTreeDiagramLayoutParameters : DiagramLayoutParameters
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.RadialTreeDiagramLayoutParameters.yml" sourcestartlinenumber="1">This layout algorithm arranges the diagram features hierarchically and places them in a radial tree according to the specified radius parameters.
It works from a root junction that it uses as the circle center to arrange the subtrees starting from this root in concentric circles, each circle corresponding to one hierarchical level.</p>


## Members

### AbsoluteUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.RadialTreeDiagramLayoutParameters.yml" sourcestartlinenumber="1">Indicates whether or not the distances are in absolute units.</p>


```csharp
public bool AbsoluteUnit { get; set; }
```
### DisjoinedGraphSpacing

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.RadialTreeDiagramLayoutParameters.yml" sourcestartlinenumber="1">Minimum spacing that must separate features belonging to disjoined graphs.</p>


```csharp
public double DisjoinedGraphSpacing { get; set; }
```
### InitialRadius

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.RadialTreeDiagramLayoutParameters.yml" sourcestartlinenumber="1">Radius of the first concentric circle whose center is the radial tree root junction.</p>


```csharp
public double InitialRadius { get; set; }
```
### PreserveContainers

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.RadialTreeDiagramLayoutParameters.yml" sourcestartlinenumber="1">Indicates whether or not the containers are preserved.</p>


```csharp
public bool PreserveContainers { get; set; }
```
### RadiusFactor

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.RadialTreeDiagramLayoutParameters.yml" sourcestartlinenumber="1">Multiplicative factor used to increase or decrease the radius of each concentric circle.</p>


```csharp
public double RadiusFactor { get; set; }
```


