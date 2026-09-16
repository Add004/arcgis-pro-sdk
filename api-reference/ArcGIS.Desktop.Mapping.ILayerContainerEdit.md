# ILayerContainerEdit

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.ILayerContainerEdit.yml" sourcestartlinenumber="1">Provides access to layers inside the layer container to modify</p>


## Object Signature

```csharp
public interface ILayerContainerEdit : ILayerContainer
```


## Members

### CanRemoveLayer(Layer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ILayerContainerEdit.yml" sourcestartlinenumber="1">Determins if a layer can be removed from the container.</p>


```csharp
bool CanRemoveLayer(Layer layer)
```
### CanRemoveLayers(IEnumerable&lt;Layer&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ILayerContainerEdit.yml" sourcestartlinenumber="1">Determins if the layers can be removed from the container.</p>


```csharp
bool CanRemoveLayers(IEnumerable<Layer> layers)
```
### MoveLayer(Layer, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ILayerContainerEdit.yml" sourcestartlinenumber="1">Move a layer to another position within the container.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
void MoveLayer(Layer layer, int position)
```
### RemoveLayer(Layer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ILayerContainerEdit.yml" sourcestartlinenumber="1">Removes a layer from the container.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
void RemoveLayer(Layer layer)
```
### RemoveLayers(IEnumerable&lt;Layer&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ILayerContainerEdit.yml" sourcestartlinenumber="1">Remove multiple layers from the container.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
void RemoveLayers(IEnumerable<Layer> layers)
```


