# ILayerFactory

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.ILayerFactory.yml" sourcestartlinenumber="1">Layer Factory interface for creating layers. See <xref href="ArcGIS.Desktop.Mapping.LayerFactory" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public interface ILayerFactory
```


## Members

### CanCopyLayer(Layer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ILayerFactory.yml" sourcestartlinenumber="1">Gets if the the layer can be copied. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
bool CanCopyLayer(Layer layer)
```
### CanCreateLayerFrom(Item)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ILayerFactory.yml" sourcestartlinenumber="1">Indicates whether a layer can be created from an Item.</p>


```csharp
bool CanCreateLayerFrom(Item item)
```
### CanCreateLayer&lt;T&gt;(LayerCreationParams, ILayerContainerEdit)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ILayerFactory.yml" sourcestartlinenumber="1">Indicates whether a layer can be created using the specified LayerCreationParams and added to the container.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
bool CanCreateLayer<T>(LayerCreationParams layerParams, ILayerContainerEdit container) where T : Layer
```
### CanCreateLayers(BulkLayerCreationParams, ILayerContainerEdit)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ILayerFactory.yml" sourcestartlinenumber="1">Indicates whether Layers can be created using the specified <xref href="ArcGIS.Desktop.Mapping.BulkLayerCreationParams" data-throw-if-not-resolved="false"></xref> and added to the container.</p>


```csharp
bool CanCreateLayers(BulkLayerCreationParams layerParams, ILayerContainerEdit container)
```
### CopyLayer(Layer, ILayerContainerEdit, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ILayerFactory.yml" sourcestartlinenumber="1">Copy a layer. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
Layer CopyLayer(Layer layer, ILayerContainerEdit container, int index = 0)
```
### CreateGroupLayer(ILayerContainerEdit, int, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ILayerFactory.yml" sourcestartlinenumber="1">Create a group layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
GroupLayer CreateGroupLayer(ILayerContainerEdit container, int index, string layerName = "")
```
### CreateLayer(Uri, ILayerContainerEdit, int, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ILayerFactory.yml" sourcestartlinenumber="1">Creates a new Layer instance with the specified path to a dataset and adds it to a container such as a map or a group layer. Optionally you can provide a name to override the default display name.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
Layer CreateLayer(Uri dataUri, ILayerContainerEdit container, int index = 0, string layerName = "")
```
### CreateLayer&lt;T&gt;(LayerCreationParams, ILayerContainerEdit)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ILayerFactory.yml" sourcestartlinenumber="1">Creates a new Layer instance using the specified LayerCreationParams and adds that to a container such as a map or group layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
T CreateLayer<T>(LayerCreationParams layerParams, ILayerContainerEdit container) where T : Layer
```
### CreateLayers(BulkLayerCreationParams, ILayerContainerEdit)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ILayerFactory.yml" sourcestartlinenumber="1">Creates a readonly list of new Layer instances using the specified BulkLayerCreationParams and adds it to a container such as a map.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
IReadOnlyList<Layer> CreateLayers(BulkLayerCreationParams layerParams, ILayerContainerEdit container)
```
### CreateLayers(IEnumerable&lt;Uri&gt;, ILayerContainerEdit, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ILayerFactory.yml" sourcestartlinenumber="1">Creates a readonly list of new Layer instances for each of the specified dataset paths and adds them to a container such as a map.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
IReadOnlyList<Layer> CreateLayers(IEnumerable<Uri> dataUris, ILayerContainerEdit container, int index = 0)
```


