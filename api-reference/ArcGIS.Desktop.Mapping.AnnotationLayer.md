# AnnotationLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.AnnotationLayer.yml" sourcestartlinenumber="1">Represents a layer with a collection of annotation features and their visual representation and editing (when permitted).</p>


## Object Signature

```csharp
public sealed class AnnotationLayer : BasicFeatureLayer, IMetadataInfo, IMetadataSource, IDisplayTable, ITableDefinitionQueries, IArcadeEvaluatorObject, ILayerContainer
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.AnnotationLayer.yml" sourcestartlinenumber="1">AnnotationLayer is a composite layer with one level of sublayers. It does not have any group layer inside it.</p>


## Members

### FindLayer(string, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.AnnotationLayer.yml" sourcestartlinenumber="1">Finds an annotation sub layer using a URI.</p>


```csharp
public Layer FindLayer(string layerURI, bool recursive = true)
```
### FindLayers(string, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.AnnotationLayer.yml" sourcestartlinenumber="1">Finds annotation sub layers by name.</p>


```csharp
public IReadOnlyList<Layer> FindLayers(string name, bool recursive = true)
```
### GetLayersAsFlattenedList()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.AnnotationLayer.yml" sourcestartlinenumber="1">Returns a read only list of sub layers.</p>


```csharp
public IReadOnlyList<Layer> GetLayersAsFlattenedList()
```
### GetSnapshot()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.AnnotationLayer.yml" sourcestartlinenumber="1">Gets a readonly snapshot of the sub layers.</p>


```csharp
public IReadOnlyList<Layer> GetSnapshot()
```
### Layers

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.AnnotationLayer.yml" sourcestartlinenumber="1">Gets a read-only collection of annotation sub layers from the AnnotationLayer.</p>


```csharp
public ReadOnlyObservableCollection<Layer> Layers { get; }
```
### LegendStatus

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.AnnotationLayer.yml" sourcestartlinenumber="1">Gets the status of the legend</p>


```csharp
public override LegendStatus LegendStatus { get; protected set; }
```
### ReferenceScale

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.AnnotationLayer.yml" sourcestartlinenumber="1">Reference scale for VPF Annotation.</p>


```csharp
public double ReferenceScale { get; }
```


