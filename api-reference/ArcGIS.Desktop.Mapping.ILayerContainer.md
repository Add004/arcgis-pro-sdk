# ILayerContainer

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.ILayerContainer.yml" sourcestartlinenumber="1">Provides read-only access to layers inside the layer container.</p>


## Object Signature

```csharp
public interface ILayerContainer
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.ILayerContainer.yml" sourcestartlinenumber="1">A layer container could be a map, a group layer or a composite layer that implements ILayerContainer</p>


## Members

### FindLayer(string, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ILayerContainer.yml" sourcestartlinenumber="1">Finds a layer using a URI.</p>


```csharp
Layer FindLayer(string layerURI, bool recursive = true)
```
### FindLayers(string, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ILayerContainer.yml" sourcestartlinenumber="1">Finds layers by name.</p>


```csharp
IReadOnlyList<Layer> FindLayers(string name, bool recursive = true)
```
### GetLayersAsFlattenedList()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ILayerContainer.yml" sourcestartlinenumber="1">Returns a read only flat list of layers where nested groups are not preserved.</p>


```csharp
IReadOnlyList<Layer> GetLayersAsFlattenedList()
```
### GetSnapshot()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ILayerContainer.yml" sourcestartlinenumber="1">Returns a read-only snapshot of the layers in the container.</p>


```csharp
IReadOnlyList<Layer> GetSnapshot()
```
### Layers

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ILayerContainer.yml" sourcestartlinenumber="1">Gets a read-only collection of layers from the container.</p>


```csharp
ReadOnlyObservableCollection<Layer> Layers { get; }
```


