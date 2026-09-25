# LayerFactory

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerFactory.yml" sourcestartlinenumber="1">Provides static methods to create layers.</p>


## Object Signature

```csharp
public class LayerFactory : ILayerFactory
```


## Members

### CanCopyLayer(Layer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerFactory.yml" sourcestartlinenumber="1">Gets if the the layer can be copied. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool CanCopyLayer(Layer layer)
```
### CanCreateLayerFrom(Item)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerFactory.yml" sourcestartlinenumber="1">Indicates whether a layer can be created from an Item.</p>


```csharp
public bool CanCreateLayerFrom(Item item)
```
### CanCreateLayer&lt;T&gt;(LayerCreationParams, ILayerContainerEdit)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerFactory.yml" sourcestartlinenumber="1">Determines if a new Layer instance using the specified LayerCreationParams can be created and added to the specified container.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool CanCreateLayer<T>(LayerCreationParams layerParams, ILayerContainerEdit container) where T : Layer
```
### CanCreateLayers(BulkLayerCreationParams, ILayerContainerEdit)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerFactory.yml" sourcestartlinenumber="1">Indicates whether Layers can be created using the specified <xref href="ArcGIS.Desktop.Mapping.BulkLayerCreationParams" data-throw-if-not-resolved="false"></xref> and added to the container.</p>


```csharp
public bool CanCreateLayers(BulkLayerCreationParams layerParams, ILayerContainerEdit container)
```
### CopyLayer(Layer, ILayerContainerEdit, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerFactory.yml" sourcestartlinenumber="1">Copy a layer. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Layer CopyLayer(Layer layer, ILayerContainerEdit container, int index = 0)
```
### CreateGroupLayer(ILayerContainerEdit, int, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerFactory.yml" sourcestartlinenumber="1">Create a group layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public GroupLayer CreateGroupLayer(ILayerContainerEdit container, int index, string layerName = "")
```
### CreateLayer(Uri, ILayerContainerEdit, int, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerFactory.yml" sourcestartlinenumber="1">Creates a new Layer instance with the specified path to a dataset and adds it to a container such as a map or a group layer. Optionally you can provide a name to override the default display name.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Layer CreateLayer(Uri dataUri, ILayerContainerEdit container, int index = 0, string layerName = "")
```
### CreateLayer&lt;T&gt;(LayerCreationParams, ILayerContainerEdit)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerFactory.yml" sourcestartlinenumber="1">Creates a new Layer instance using the specified LayerCreationParams and adds that to a container such as a map or group layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public T CreateLayer<T>(LayerCreationParams layerParams, ILayerContainerEdit container) where T : Layer
```
### CreateLayers(BulkLayerCreationParams, ILayerContainerEdit)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerFactory.yml" sourcestartlinenumber="1">Creates a readonly list of new Layer instances using the specified <xref href="ArcGIS.Desktop.Mapping.BulkLayerCreationParams" data-throw-if-not-resolved="false"></xref> and adds it to a container such as a map.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<Layer> CreateLayers(BulkLayerCreationParams layerParams, ILayerContainerEdit container)
```
### CreateLayers(IEnumerable&lt;Uri&gt;, ILayerContainerEdit, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerFactory.yml" sourcestartlinenumber="1">Creates a readonly list of new Layer instance for each of the specified dataset paths and adds them to a container such as a map.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<Layer> CreateLayers(IEnumerable<Uri> layerUris, ILayerContainerEdit container, int index = 0)
```
### Instance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerFactory.yml" sourcestartlinenumber="1">Gets the singleton instance for ILayerFactory.</p>


```csharp
public static ILayerFactory Instance { get; }
```


