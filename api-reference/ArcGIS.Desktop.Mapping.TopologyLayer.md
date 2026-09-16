# TopologyLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.TopologyLayer.yml" sourcestartlinenumber="1">Represents a topology composite layer.</p>


## Object Signature

```csharp
public sealed class TopologyLayer : CompositeLayer, IMetadataInfo, IMetadataSource, ILayerContainer, ITopologyLayerContainer
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.TopologyLayer.yml" sourcestartlinenumber="1">The topology layer is a composite layer that is a representation of the topology dataset. The topology layer contains a dirty area and error sublayers. See <xref href="ArcGIS.Core.CIM.CIMTopologyLayer" data-throw-if-not-resolved="false"></xref>.</p>


## Members

### GetTopology()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TopologyLayer.yml" sourcestartlinenumber="1">Gets the topology dataset associated with the layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Topology GetTopology()
```


