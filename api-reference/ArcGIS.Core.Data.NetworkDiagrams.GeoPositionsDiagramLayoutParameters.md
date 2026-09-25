# GeoPositionsDiagramLayoutParameters

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.NetworkDiagrams.html">NetworkDiagrams</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.GeoPositionsDiagramLayoutParameters.yml" sourcestartlinenumber="1">Represents the Geo Positions diagram layout parameters. This layout algorithm moves each diagram junction and edge feature so they match the geographical positions of the associated network features.</p>


## Object Signature

```csharp
public sealed class GeoPositionsDiagramLayoutParameters : DiagramLayoutParameters
```


## Members

### RestoreEdgesGeographicPositions

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.GeoPositionsDiagramLayoutParameters.yml" sourcestartlinenumber="1">Indicates whether or not the geographic positions of the edges are restored to the geographic positions of their vertices.</p>


```csharp
public bool RestoreEdgesGeographicPositions { get; set; }
```


