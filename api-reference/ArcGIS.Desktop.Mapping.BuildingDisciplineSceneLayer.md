# BuildingDisciplineSceneLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.BuildingDisciplineSceneLayer.yml" sourcestartlinenumber="1">BuildingDisciplineSceneLayer are sublayers of a <xref href="ArcGIS.Desktop.Mapping.BuildingSceneLayer" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class BuildingDisciplineSceneLayer : CompositeLayer, IMetadataInfo, IMetadataSource, ILayerContainer
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.BuildingDisciplineSceneLayer.yml" sourcestartlinenumber="1">BuildingDisciplineSceneLayers represent each of the individual disciplines
(architectural, structural, MEP, etc) that are contained within the building and which
were derived from the original BIM data used to create the &quot;parent&quot; BuildingScenelayer<br>
BuildingDisciplineSceneLayers are never created, or exist, stand-alone. They have a composite
relationship with the BuildingScenelayer which contains them.<br>
A <xref href="ArcGIS.Desktop.Mapping.FilterDefinition" data-throw-if-not-resolved="false"></xref> is actually applied to the underlying BuildingDisciplineSceneLayers
content (within the special &quot;Full Model&quot; BuildingDisciplineSceneLayer)</p>


## Members

### GetDataConnection()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BuildingDisciplineSceneLayer.yml" sourcestartlinenumber="1">Gets a CIMDataConnection value object.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public override CIMDataConnection GetDataConnection()
```
### GetDataSourceType()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BuildingDisciplineSceneLayer.yml" sourcestartlinenumber="1">Gets the data source type.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SceneLayerDataSourceType GetDataSourceType()
```
### GetDiscipline()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BuildingDisciplineSceneLayer.yml" sourcestartlinenumber="1">Gets the discipline type.</p>


```csharp
public string GetDiscipline()
```


