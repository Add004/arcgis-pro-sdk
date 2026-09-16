# DiagramLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.DiagramLayer.yml" sourcestartlinenumber="1">Represents a network diagram layer.</p>


## Object Signature

```csharp
public sealed class DiagramLayer : CompositeLayer, IMetadataInfo, IMetadataSource, ILayerContainerEdit, ILayerContainer
```


## Members

### CanRemoveLayer(Layer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.DiagramLayer.yml" sourcestartlinenumber="1">Determines if a layer can be removed from the container.</p>


```csharp
public bool CanRemoveLayer(Layer layer)
```
### CanRemoveLayers(IEnumerable&lt;Layer&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.DiagramLayer.yml" sourcestartlinenumber="1">Determines if the layers can be removed from the container.</p>


```csharp
public bool CanRemoveLayers(IEnumerable<Layer> layers)
```
### ConsistencyState

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.DiagramLayer.yml" sourcestartlinenumber="1">Gets the network diagram consistency state.</p>


```csharp
public DiagramLayerConsistencyState ConsistencyState { get; }
```
### GetNetworkDiagram()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.DiagramLayer.yml" sourcestartlinenumber="1">Gets network diagram associated with the layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public NetworkDiagram GetNetworkDiagram()
```
### MoveLayer(Layer, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.DiagramLayer.yml" sourcestartlinenumber="1">Move a layer to another position within the container.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void MoveLayer(Layer layer, int position)
```
### RemoveLayer(Layer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.DiagramLayer.yml" sourcestartlinenumber="1">Removes a layer from the container.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveLayer(Layer layer)
```
### RemoveLayers(IEnumerable&lt;Layer&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.DiagramLayer.yml" sourcestartlinenumber="1">Remove multiple layers from the container.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveLayers(IEnumerable<Layer> layers)
```


