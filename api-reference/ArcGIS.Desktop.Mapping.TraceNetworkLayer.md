# TraceNetworkLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.TraceNetworkLayer.yml" sourcestartlinenumber="1">Represents a trace network</p>


## Object Signature

```csharp
public sealed class TraceNetworkLayer : CompositeLayer, IMetadataInfo, IMetadataSource, ILayerContainer
```


## Members

### GetDiagramManager()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TraceNetworkLayer.yml" sourcestartlinenumber="1">Gets diagram manager associated with the layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public DiagramManager GetDiagramManager()
```
### TNVersion

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TraceNetworkLayer.yml" sourcestartlinenumber="1">Gets the Trace Network layer version.</p>


```csharp
public int TNVersion { get; }
```


