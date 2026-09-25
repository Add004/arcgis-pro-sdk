# NitfFeatureSubLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.NitfFeatureSubLayer.yml" sourcestartlinenumber="1">Represents a NITF feature layer.</p>


## Object Signature

```csharp
public sealed class NitfFeatureSubLayer : FeatureLayer, IMetadataInfo, IMetadataSource, IDisplayTable, ITableDefinitionQueries, IArcadeEvaluatorObject
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.NitfFeatureSubLayer.yml" sourcestartlinenumber="1">The NITF feature layer is a representation of a CSSHPA DES in a NITF file.</p>


## Members

### GetIsFeatureDrawOrderSupported()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.NitfFeatureSubLayer.yml" sourcestartlinenumber="1">Gets whether or not feature drawing order is supported on the layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public override bool GetIsFeatureDrawOrderSupported()
```


