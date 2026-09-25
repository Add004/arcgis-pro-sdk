# CompositeLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.CompositeLayer.yml" sourcestartlinenumber="1">Represents an abstract class for a read-only collection of layers.</p>


## Object Signature

```csharp
public abstract class CompositeLayer : Layer, IMetadataInfo, IMetadataSource, ILayerContainer
```


## Members

### CompositeLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.CompositeLayer.yml" sourcestartlinenumber="1">Default constructor</p>


```csharp
protected CompositeLayer()
```
### FindLayer(string, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.CompositeLayer.yml" sourcestartlinenumber="1">Finds a layer using a URI.</p>


```csharp
public virtual Layer FindLayer(string layerURI, bool recursive = true)
```
### FindLayers(string, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.CompositeLayer.yml" sourcestartlinenumber="1">Finds layers by name.</p>


```csharp
public virtual IReadOnlyList<Layer> FindLayers(string name, bool recursive = true)
```
### GetLayersAsFlattenedList()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.CompositeLayer.yml" sourcestartlinenumber="1">Returns a read only flat list of layers where nested groups are not preserved.</p>


```csharp
public virtual IReadOnlyList<Layer> GetLayersAsFlattenedList()
```
### GetSnapshot()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.CompositeLayer.yml" sourcestartlinenumber="1">Gets a readonly snapshot of the layers.</p>


```csharp
public virtual IReadOnlyList<Layer> GetSnapshot()
```
### Layers

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.CompositeLayer.yml" sourcestartlinenumber="1">Gets a read-only collection of layers from the composite layer.</p>


```csharp
public virtual ReadOnlyObservableCollection<Layer> Layers { get; }
```
### LegendStatus

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.CompositeLayer.yml" sourcestartlinenumber="1">Gets the status of the legend</p>


```csharp
public override LegendStatus LegendStatus { get; protected set; }
```


