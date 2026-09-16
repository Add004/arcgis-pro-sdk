# TrajectoryLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.TrajectoryLayer.yml" sourcestartlinenumber="1">Represents a trajectory layer.</p>


## Object Signature

```csharp
public sealed class TrajectoryLayer : CompositeLayer, IMetadataInfo, IMetadataSource, ILayerContainer
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.TrajectoryLayer.yml" sourcestartlinenumber="1">The trajectory layer is a composite layer which is a representation of a trajectory dataset. The trajectory layer is drawn based on the <xref href="ArcGIS.Core.CIM.CIMRenderer" data-throw-if-not-resolved="false"></xref></p>


## Members

### GetFootprintLayer()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TrajectoryLayer.yml" sourcestartlinenumber="1">Gets the footprint sub-layer. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public FeatureTrajectorySubLayer GetFootprintLayer()
```
### GetPointLayer()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TrajectoryLayer.yml" sourcestartlinenumber="1">Gets the point sub-layer. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public FeatureTrajectorySubLayer GetPointLayer()
```


