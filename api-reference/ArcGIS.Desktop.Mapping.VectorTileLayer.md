# VectorTileLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.VectorTileLayer.yml" sourcestartlinenumber="1">Represents a vector tile layer.</p>


## Object Signature

```csharp
public sealed class VectorTileLayer : Layer, IMetadataInfo, IMetadataSource
```


## Members

### GetStyleJSON()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.VectorTileLayer.yml" sourcestartlinenumber="1">Returns the JSON of the vector tile layer style.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetStyleJSON()
```
### LegendStatus

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.VectorTileLayer.yml" sourcestartlinenumber="1">Gets the status of the legend</p>


```csharp
public override LegendStatus LegendStatus { get; protected set; }
```
### SetStyleJSON(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.VectorTileLayer.yml" sourcestartlinenumber="1">Sets the style JSON of the vector tile layer style.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetStyleJSON(string styleJSON)
```


