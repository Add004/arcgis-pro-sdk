# CompositeFeatureLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.CompositeFeatureLayer.yml" sourcestartlinenumber="1">Represents an abstract class for Composite Feature Layers.
Composite Feature Layers are fully fledged Feature Layers that can also have their own sublayers.</p>


## Object Signature

```csharp
public abstract class CompositeFeatureLayer : FeatureLayer, IMetadataInfo, IMetadataSource, IDisplayTable, ITableDefinitionQueries, IArcadeEvaluatorObject, ILayerContainer
```


## Members

### CompositeFeatureLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.CompositeFeatureLayer.yml" sourcestartlinenumber="1">Default constructor</p>


```csharp
protected CompositeFeatureLayer()
```
### FindLayer(string, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.CompositeFeatureLayer.yml" sourcestartlinenumber="1">Finds a layer using a URI.</p>


```csharp
public Layer FindLayer(string layerURI, bool recursive = true)
```
### FindLayers(string, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.CompositeFeatureLayer.yml" sourcestartlinenumber="1">Finds layers by name.</p>


```csharp
public IReadOnlyList<Layer> FindLayers(string name, bool recursive = true)
```
### GetIsFeatureDrawOrderSupported()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.CompositeFeatureLayer.yml" sourcestartlinenumber="1">Gets whether or not feature drawing order is supported on the layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public override bool GetIsFeatureDrawOrderSupported()
```
### GetLayersAsFlattenedList()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.CompositeFeatureLayer.yml" sourcestartlinenumber="1">Returns a read only flat list of layers where nested groups are not preserved.</p>


```csharp
public IReadOnlyList<Layer> GetLayersAsFlattenedList()
```
### GetSnapshot()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.CompositeFeatureLayer.yml" sourcestartlinenumber="1">Gets a readonly snapshot of the layers.</p>


```csharp
public IReadOnlyList<Layer> GetSnapshot()
```
### Layers

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.CompositeFeatureLayer.yml" sourcestartlinenumber="1">Gets a read-only collection of layers from the composite layer.</p>


```csharp
public ReadOnlyObservableCollection<Layer> Layers { get; }
```


