# NitfLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.NitfLayer.yml" sourcestartlinenumber="1">Represents a layer containing a NITF dataset.</p>


## Object Signature

```csharp
public sealed class NitfLayer : CompositeLayerWithTables, IMetadataInfo, IMetadataSource, IStandaloneTableContainer, ILayerContainerEdit, ILayerContainer
```


## Members

### CanRemoveLayer(Layer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.NitfLayer.yml" sourcestartlinenumber="1">Determines if a layer can be removed from the container.</p>


```csharp
public bool CanRemoveLayer(Layer layer)
```
### CanRemoveLayers(IEnumerable&lt;Layer&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.NitfLayer.yml" sourcestartlinenumber="1">Determines if the layers can be removed from the container.</p>


```csharp
public bool CanRemoveLayers(IEnumerable<Layer> layers)
```
### MoveLayer(Layer, CompositeLayer, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.NitfLayer.yml" sourcestartlinenumber="1">Move a layer to another position within the specified container.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void MoveLayer(Layer layer, CompositeLayer targetLayer, int position)
```
### MoveLayer(Layer, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.NitfLayer.yml" sourcestartlinenumber="1">Moves a layer to another position within the container.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void MoveLayer(Layer layer, int position)
```
### RemoveLayer(Layer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.NitfLayer.yml" sourcestartlinenumber="1">Removes a specified layer from the map.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveLayer(Layer layer)
```
### RemoveLayers(IEnumerable&lt;Layer&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.NitfLayer.yml" sourcestartlinenumber="1">Removes the specified layers from the map.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveLayers(IEnumerable<Layer> layers)
```


