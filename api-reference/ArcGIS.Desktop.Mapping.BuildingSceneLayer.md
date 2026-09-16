# BuildingSceneLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.BuildingSceneLayer.yml" sourcestartlinenumber="1">Class to represent the 3D model aspect of Building Information Modeling (BIM).</p>


## Object Signature

```csharp
public sealed class BuildingSceneLayer : CompositeLayer, IMetadataInfo, IMetadataSource, ILayerContainer
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.BuildingSceneLayer.yml" sourcestartlinenumber="1">BuildingSceneLayers are typically derived from BIM data extracted from
Autodesk revit files.<br>BuildingSceneLayers are a <xref href="ArcGIS.Desktop.Mapping.CompositeLayer" data-throw-if-not-resolved="false"></xref>. They
contain two top-level child layers:<br>
o A <xref href="ArcGIS.Desktop.Mapping.FeatureSceneLayer" data-throw-if-not-resolved="false"></xref> providing an &quot;Overview&quot; (think of it as a simplified
rendering of the building exterior).<br>
o A <xref href="ArcGIS.Desktop.Mapping.BuildingDisciplineSceneLayer" data-throw-if-not-resolved="false"></xref> providing the &quot;Full Model&quot; which includes all
of the building disciplines extracted from the original BIM.</p>


## Members

### ClearActiveFilter()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BuildingSceneLayer.yml" sourcestartlinenumber="1">Clears the active filter.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void ClearActiveFilter()
```
### CreateDefaultFilter()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BuildingSceneLayer.yml" sourcestartlinenumber="1">Creates a filter definition with default values.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public FilterDefinition CreateDefaultFilter()
```
### CreateFilter(FilterDefinition)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BuildingSceneLayer.yml" sourcestartlinenumber="1">Create a new filter.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void CreateFilter(FilterDefinition filterDefinition)
```
### GetActiveFilter()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BuildingSceneLayer.yml" sourcestartlinenumber="1">Gets the active filter.</p>


```csharp
public FilterDefinition GetActiveFilter()
```
### GetAvailableFieldsAndValues()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BuildingSceneLayer.yml" sourcestartlinenumber="1">Gets all available fields and their corresponding values for a building scene layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Dictionary<string, List<string>> GetAvailableFieldsAndValues()
```
### GetDataSourceType()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BuildingSceneLayer.yml" sourcestartlinenumber="1">Gets the data source type.</p>


```csharp
public SceneLayerDataSourceType GetDataSourceType()
```
### GetFilter(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BuildingSceneLayer.yml" sourcestartlinenumber="1">Gets a filter for the given filter id
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public FilterDefinition GetFilter(string filterID)
```
### GetFilterTypes(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BuildingSceneLayer.yml" sourcestartlinenumber="1">Returns a list of currently defined filter types.</p>


```csharp
public List<string> GetFilterTypes(string filterID)
```
### GetFilters()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BuildingSceneLayer.yml" sourcestartlinenumber="1">Returns a list of defined filters.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public List<FilterDefinition> GetFilters()
```
### HasFilter(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BuildingSceneLayer.yml" sourcestartlinenumber="1">Determines whether a filter exists with the given filter ID.</p>


```csharp
public bool HasFilter(string filterID)
```
### RemoveAllFilters()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BuildingSceneLayer.yml" sourcestartlinenumber="1">Removes all the filters. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveAllFilters()
```
### RemoveFilter(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BuildingSceneLayer.yml" sourcestartlinenumber="1">Removes the filter with the given filter id.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveFilter(string filterID)
```
### SetActiveFilter(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BuildingSceneLayer.yml" sourcestartlinenumber="1">Sets the active filter to be the filter with the given filter id
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetActiveFilter(string filterID)
```
### SetFilterTypes(string, List&lt;string&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BuildingSceneLayer.yml" sourcestartlinenumber="1">Sets the filter types shown for each filter block with the given filter id and a list of included filter types.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetFilterTypes(string filterID, List<string> includedTypes)
```
### UpdateFilter(FilterDefinition)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BuildingSceneLayer.yml" sourcestartlinenumber="1">Update a filter.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void UpdateFilter(FilterDefinition filterDefinition)
```


