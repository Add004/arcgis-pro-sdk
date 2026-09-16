# FeatureTrajectorySubLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureTrajectorySubLayer.yml" sourcestartlinenumber="1">Represents a feature sub-layer of the trajectory layer.</p>


## Object Signature

```csharp
public sealed class FeatureTrajectorySubLayer : FeatureLayer, IMetadataInfo, IMetadataSource, IDisplayTable, ITableDefinitionQueries, IArcadeEvaluatorObject
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureTrajectorySubLayer.yml" sourcestartlinenumber="1">This class can be used to distinguish feature layers which are sub-layers of a trajectory layer from other types of feature layers.</p>


## Members

### GetIsFeatureDrawOrderSupported()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureTrajectorySubLayer.yml" sourcestartlinenumber="1">Gets whether or not feature drawing order is supported on the layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public override bool GetIsFeatureDrawOrderSupported()
```


