# LinearDispatchDiagramLayoutParameters.Placement

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.NetworkDiagrams.html">NetworkDiagrams</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.LinearDispatchDiagramLayoutParameters.Placement.yml" sourcestartlinenumber="1">The way the layout algorithm will move the diagram junctions.</p>


## Object Signature

```csharp
public enum LinearDispatchDiagramLayoutParameters.Placement
```


## Members

### EqualDistance

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.LinearDispatchDiagramLayoutParameters.Placement.yml" sourcestartlinenumber="1">Equal distance between junctions. All junctions with two connected edges will move so the distances between them and their two connected junctions are equal.</p>


```csharp
EqualDistance = 1
```
### IterativeDistance

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.LinearDispatchDiagramLayoutParameters.Placement.yml" sourcestartlinenumber="1">Distance is computed iteratively. All the junctions with two connected edges will move slightly according to the <xref href="ArcGIS.Core.Data.NetworkDiagrams.LinearDispatchDiagramLayoutParameters.NumberOfIterations" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Core.Data.NetworkDiagrams.LinearDispatchDiagramLayoutParameters.MaximumShift" data-throw-if-not-resolved="false"></xref> parameter values.</p>


```csharp
IterativeDistance = 3
```
### UserDefinedDistance

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.LinearDispatchDiagramLayoutParameters.Placement.yml" sourcestartlinenumber="1">User defined distance. All junctions with two connected edges will move so there is a minimum distance (<xref href="ArcGIS.Core.Data.NetworkDiagrams.LinearDispatchDiagramLayoutParameters.MinimumShift" data-throw-if-not-resolved="false"></xref>) between them and the other end of the edges they connect to. This occurs at the end of the layout execution.</p>


```csharp
UserDefinedDistance = 2
```


