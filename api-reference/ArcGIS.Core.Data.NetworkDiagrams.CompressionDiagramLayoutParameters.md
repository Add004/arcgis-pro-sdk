# CompressionDiagramLayoutParameters

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.NetworkDiagrams.html">NetworkDiagrams</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.CompressionDiagramLayoutParameters.yml" sourcestartlinenumber="1">Represents the Compression diagram layout parameters. This layout algorithm compresses the diagram features toward the middle of the diagram.</p>


## Object Signature

```csharp
public sealed class CompressionDiagramLayoutParameters : DiagramLayoutParameters
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.CompressionDiagramLayoutParameters.yml" sourcestartlinenumber="1">This algorithm is useful for networks that span thousands of miles and are otherwise difficult to view and understand in their true geographic positions—for example, in the transmission utilities industry.</p>


## Members

### MaxDistanceForGrouping

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.CompressionDiagramLayoutParameters.yml" sourcestartlinenumber="1">Gets and sets the maximum distance for grouping.</p>


```csharp
public double MaxDistanceForGrouping { get; set; }
```
### PreserveContainers

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.CompressionDiagramLayoutParameters.yml" sourcestartlinenumber="1">Indicates whether or not the containers are preserved.</p>


```csharp
public bool PreserveContainers { get; set; }
```
### VertexRemovalRule

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.CompressionDiagramLayoutParameters.yml" sourcestartlinenumber="1">Gets and sets the vertex removal rule.</p>


```csharp
public CompressionDiagramLayoutParameters.VertexRule VertexRemovalRule { get; set; }
```


