# FeatureSceneLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureSceneLayer.yml" sourcestartlinenumber="1">FeatureSceneLayers currently support the I3S Point and 3D Object layer types.
Points must be based off 3D point data and 3D Objects must be based off multipatches.</p>


## Object Signature

```csharp
public sealed class FeatureSceneLayer : CompositeLayer, IMetadataInfo, IMetadataSource, ILayerContainer, ITableDefinitionQueries
```


## Members

### ActiveDefinitionQuery

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureSceneLayer.yml" sourcestartlinenumber="1">Gets the active definition query.</p>


```csharp
public DefinitionQuery ActiveDefinitionQuery { get; }
```
### AddLabelClass(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureSceneLayer.yml" sourcestartlinenumber="1">Adds a label class to the layer's label class collection.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void AddLabelClass(string labelClassName)
```
### CanLabel

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureSceneLayer.yml" sourcestartlinenumber="1">Gets whether the feature scene layer supports labeling.</p>


```csharp
public bool CanLabel { get; }
```
### ClearSelection()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureSceneLayer.yml" sourcestartlinenumber="1">Clears the current selection. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void ClearSelection()
```
### DefinitionQueries

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureSceneLayer.yml" sourcestartlinenumber="1">Gets a list of all DefinitionQueries.</p>


```csharp
public IReadOnlyList<DefinitionQuery> DefinitionQueries { get; }
```
### DefinitionQuery

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureSceneLayer.yml" sourcestartlinenumber="1">Gets the where clause of the active definition query of a layer or standalone table.</p>


```csharp
public string DefinitionQuery { get; }
```
### FeatureSceneLayerType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureSceneLayer.yml" sourcestartlinenumber="1">Gets the scene layer type.</p>


```csharp
public FeatureSceneLayerType FeatureSceneLayerType { get; }
```
### GetDataSourceType()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureSceneLayer.yml" sourcestartlinenumber="1">Gets the data source type.</p>


```csharp
public SceneLayerDataSourceType GetDataSourceType()
```
### GetFeatureClass()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureSceneLayer.yml" sourcestartlinenumber="1">Gets the associated feature class. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public FeatureClass GetFeatureClass()
```
### GetFieldDescriptions()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureSceneLayer.yml" sourcestartlinenumber="1">Returns a list of field descriptions. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public List<FieldDescription> GetFieldDescriptions()
```
### GetRenderer()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureSceneLayer.yml" sourcestartlinenumber="1">Returns the renderer used to draw the feature scene layer
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMRenderer GetRenderer()
```
### GetSelection()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureSceneLayer.yml" sourcestartlinenumber="1">Gets the current selection.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Selection GetSelection()
```
### HasAssociatedFeatureService

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureSceneLayer.yml" sourcestartlinenumber="1">Gets whether the feature scene layer has an associated feature service.</p>


```csharp
public bool HasAssociatedFeatureService { get; }
```
### HideSelectedFeatures()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureSceneLayer.yml" sourcestartlinenumber="1">Creates an exclusion set based on the currently selected features.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void HideSelectedFeatures()
```
### InsertDefinitionQueries(IEnumerable&lt;DefinitionQuery&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureSceneLayer.yml" sourcestartlinenumber="1">Insert a list of <xref href="ArcGIS.Desktop.Mapping.FeatureSceneLayer.DefinitionQuery" data-throw-if-not-resolved="false"></xref>. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void InsertDefinitionQueries(IEnumerable<DefinitionQuery> queries)
```
### InsertDefinitionQuery(DefinitionQuery, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureSceneLayer.yml" sourcestartlinenumber="1">Inserts a <xref href="ArcGIS.Desktop.Mapping.FeatureSceneLayer.DefinitionQuery" data-throw-if-not-resolved="false"></xref>. If <code class="paramref">makeActive</code> is true, makes it the active definition query.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void InsertDefinitionQuery(DefinitionQuery definitionQuery, bool makeActive = false)
```
### IsEditable

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureSceneLayer.yml" sourcestartlinenumber="1">Gets whether the feature scene layer is editable.</p>


```csharp
public bool IsEditable { get; }
```
### IsLabelVisible

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureSceneLayer.yml" sourcestartlinenumber="1">Gets whether labels are drawing</p>


```csharp
public bool IsLabelVisible { get; }
```
### IsSelectable

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureSceneLayer.yml" sourcestartlinenumber="1">Gets whether the feature scene layer is selectable.</p>


```csharp
public bool IsSelectable { get; }
```
### IsSnappable

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureSceneLayer.yml" sourcestartlinenumber="1">Gets whether the feature scene layer is snappable.</p>


```csharp
public bool IsSnappable { get; }
```
### IsValidDefinitionQuery(DefinitionQuery)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureSceneLayer.yml" sourcestartlinenumber="1">Determines if the specified definitionQuery is valid.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Task<bool> IsValidDefinitionQuery(DefinitionQuery definitionQuery)
```
### IsValidDefinitionQuery(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureSceneLayer.yml" sourcestartlinenumber="1">Determines if the specified SQL where clause has valid syntax.   That is; the field defined exists on the layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Task<bool> IsValidDefinitionQuery(string sql)
```
### LabelClasses

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureSceneLayer.yml" sourcestartlinenumber="1">Gets the available label classes for the feature scene layer.</p>


```csharp
public ReadOnlyObservableCollection<LabelClass> LabelClasses { get; }
```
### LegendStatus

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureSceneLayer.yml" sourcestartlinenumber="1">Gets the status of the legend</p>


```csharp
public override LegendStatus LegendStatus { get; protected set; }
```
### RemoveActiveDefinitionQuery()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureSceneLayer.yml" sourcestartlinenumber="1">Removes the active definition query. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveActiveDefinitionQuery()
```
### RemoveAllDefinitionQueries()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureSceneLayer.yml" sourcestartlinenumber="1">Remove all definition queries.  This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveAllDefinitionQueries()
```
### RemoveDefinitionQueries(IEnumerable&lt;string&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureSceneLayer.yml" sourcestartlinenumber="1">Removes the definition queries specified by the list of names. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveDefinitionQueries(IEnumerable<string> queryNames)
```
### RemoveDefinitionQuery(int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureSceneLayer.yml" sourcestartlinenumber="1">Removes the definition query at the specified index. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveDefinitionQuery(int index)
```
### RemoveLabelClass(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureSceneLayer.yml" sourcestartlinenumber="1">Removes a label class from the layer's label class collection.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveLabelClass(string labelClassName)
```
### Search(QueryFilter)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureSceneLayer.yml" sourcestartlinenumber="1">Search for features based upon the specified attribute and/or spatial criteria.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RowCursor Search(QueryFilter queryFilter = null)
```
### SearchEx(QueryFilter, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureSceneLayer.yml" sourcestartlinenumber="1">Search for features based upon the specified attribute and/or spatial criteria.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RowCursor SearchEx(QueryFilter queryFilter = null, bool useRecyclingCursor = true)
```
### Select(QueryFilter, SelectionCombinationMethod)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureSceneLayer.yml" sourcestartlinenumber="1">Selects features based upon the specified attribute and/or spatial criteria and combination method.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Selection Select(QueryFilter queryFilter = null, SelectionCombinationMethod method = SelectionCombinationMethod.New)
```
### SelectionCount

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureSceneLayer.yml" sourcestartlinenumber="1">Gets the number of selected features.</p>


```csharp
public int SelectionCount { get; }
```
### SetActiveDefinitionQuery(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureSceneLayer.yml" sourcestartlinenumber="1">Sets the specified query to be the active definition query.  If the <code class="paramref">queryName</code> is null, then the active query definition
that is cleared.   This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetActiveDefinitionQuery(string queryName)
```
### SetDefinitionQuery(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureSceneLayer.yml" sourcestartlinenumber="1">Sets the where clause of the active definition query.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public DefinitionQuery SetDefinitionQuery(string whereClause)
```
### SetRenderer(CIMRenderer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureSceneLayer.yml" sourcestartlinenumber="1">Specifies the feature scene layer's renderer object which determines how the layer draws.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetRenderer(CIMRenderer renderer)
```
### SetSelection(Selection)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureSceneLayer.yml" sourcestartlinenumber="1">Sets the current selection. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetSelection(Selection selection)
```
### ShapeType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureSceneLayer.yml" sourcestartlinenumber="1">Gets the feature scene layer's shape type.</p>


```csharp
public esriGeometryType ShapeType { get; }
```
### ShowHiddenFeatures()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureSceneLayer.yml" sourcestartlinenumber="1">Removes all features from the current exclusion set.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void ShowHiddenFeatures()
```


