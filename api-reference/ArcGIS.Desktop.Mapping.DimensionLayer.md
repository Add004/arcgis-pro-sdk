# DimensionLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.DimensionLayer.yml" sourcestartlinenumber="1">Represents a DimensionLayer.</p>


## Object Signature

```csharp
public sealed class DimensionLayer : BasicFeatureLayer, IMetadataInfo, IMetadataSource, IDisplayTable, ITableDefinitionQueries, IArcadeEvaluatorObject
```


## Members

### IsSnappable

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.DimensionLayer.yml" sourcestartlinenumber="1">Gets whether snapping is enabled.</p>


```csharp
public bool IsSnappable { get; }
```
### SetSnappable(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.DimensionLayer.yml" sourcestartlinenumber="1">Enables or disables snapping on the feature layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetSnappable(bool isSnappable)
```


