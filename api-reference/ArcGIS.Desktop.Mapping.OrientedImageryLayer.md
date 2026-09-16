# OrientedImageryLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.OrientedImageryLayer.yml" sourcestartlinenumber="1">Represents an oriented imagery layer.</p>


## Object Signature

```csharp
public sealed class OrientedImageryLayer : FeatureLayer, IMetadataInfo, IMetadataSource, IDisplayTable, ITableDefinitionQueries, IArcadeEvaluatorObject
```


## Members

### GetIsFeatureDrawOrderSupported()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.OrientedImageryLayer.yml" sourcestartlinenumber="1">Gets whether or not feature drawing order is supported on the layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public override bool GetIsFeatureDrawOrderSupported()
```


