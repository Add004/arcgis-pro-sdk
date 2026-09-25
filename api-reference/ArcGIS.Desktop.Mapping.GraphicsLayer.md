# GraphicsLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraphicsLayer.yml" sourcestartlinenumber="1">Graphics layers are layers that act as containers for graphics elements
that can be added to a map.</p>


## Object Signature

```csharp
public sealed class GraphicsLayer : Layer, IMetadataInfo, IMetadataSource, IElementContainer, ISuspendableObservableCollection
```


## Members

### IsSelectable

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraphicsLayer.yml" sourcestartlinenumber="1">Gets whether Graphics Layer is Selectable.</p>


```csharp
public bool IsSelectable { get; }
```
### IsSnappable

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraphicsLayer.yml" sourcestartlinenumber="1">Gets whether snapping is enabled.</p>


```csharp
public bool IsSnappable { get; }
```
### LegendStatus

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraphicsLayer.yml" sourcestartlinenumber="1">Gets the status of the legend</p>


```csharp
public override LegendStatus LegendStatus { get; protected set; }
```
### ReferenceScale

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.GraphicsLayer.yml" sourcestartlinenumber="1">Gets the layer's reference scale .</p>


```csharp
public double ReferenceScale { get; }
```


