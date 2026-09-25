# LinkChartFeatureLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.LinkChartFeatureLayer.yml" sourcestartlinenumber="1">Represents a Link Chart Feature Layer.</p>


## Object Signature

```csharp
public sealed class LinkChartFeatureLayer : CompositeFeatureLayer, IMetadataInfo, IMetadataSource, IDisplayTable, ITableDefinitionQueries, IArcadeEvaluatorObject, ILayerContainer
```


## Members

### GetTypeName()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LinkChartFeatureLayer.yml" sourcestartlinenumber="1">Gets the object type name that the link chart feature layer represents.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetTypeName()
```
### IsEntity

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LinkChartFeatureLayer.yml" sourcestartlinenumber="1">Gets if the link chart feature layer represents an entity in the Knowledge Graph.</p>


```csharp
public bool IsEntity { get; }
```
### IsRelationship

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LinkChartFeatureLayer.yml" sourcestartlinenumber="1">Gets if the link chart feature layer represents a relationship in the Knowledge Graph.</p>


```csharp
public bool IsRelationship { get; }
```


