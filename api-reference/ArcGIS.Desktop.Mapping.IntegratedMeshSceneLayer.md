# IntegratedMeshSceneLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.IntegratedMeshSceneLayer.yml" sourcestartlinenumber="1">Class for visualizing accurate representations of infrastructure and natural landscapes.</p>


## Object Signature

```csharp
public sealed class IntegratedMeshSceneLayer : CompositeLayer, IMetadataInfo, IMetadataSource, ILayerContainer, ITableDefinitionQueries
```


## Members

### ActiveDefinitionQuery

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.IntegratedMeshSceneLayer.yml" sourcestartlinenumber="1">Gets the active definition query.</p>


```csharp
public DefinitionQuery ActiveDefinitionQuery { get; }
```
### CanLabel

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.IntegratedMeshSceneLayer.yml" sourcestartlinenumber="1">Gets whether the integrated mesh scene layer supports labeling.</p>


```csharp
public bool CanLabel { get; }
```
### DefinitionQueries

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.IntegratedMeshSceneLayer.yml" sourcestartlinenumber="1">Gets a list of all DefinitionQueries.</p>


```csharp
public IReadOnlyList<DefinitionQuery> DefinitionQueries { get; }
```
### DefinitionQuery

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.IntegratedMeshSceneLayer.yml" sourcestartlinenumber="1">Gets the where clause of the active definition query.</p>


```csharp
public string DefinitionQuery { get; }
```
### GetDataSourceType()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IntegratedMeshSceneLayer.yml" sourcestartlinenumber="1">Gets the data source type.</p>


```csharp
public SceneLayerDataSourceType GetDataSourceType()
```
### GetRenderer()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IntegratedMeshSceneLayer.yml" sourcestartlinenumber="1">Returns the renderer used to draw the integrated mesh scene layer
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMRenderer GetRenderer()
```
### HasAttributes

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.IntegratedMeshSceneLayer.yml" sourcestartlinenumber="1">Gets whether the integrated mesh scene layer has attributes.</p>


```csharp
public bool HasAttributes { get; }
```
### InsertDefinitionQueries(IEnumerable&lt;DefinitionQuery&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IntegratedMeshSceneLayer.yml" sourcestartlinenumber="1">Insert a list of <xref href="ArcGIS.Desktop.Mapping.IntegratedMeshSceneLayer.DefinitionQuery" data-throw-if-not-resolved="false"></xref>. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void InsertDefinitionQueries(IEnumerable<DefinitionQuery> queries)
```
### InsertDefinitionQuery(DefinitionQuery, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IntegratedMeshSceneLayer.yml" sourcestartlinenumber="1">Inserts a <xref href="ArcGIS.Desktop.Mapping.IntegratedMeshSceneLayer.DefinitionQuery" data-throw-if-not-resolved="false"></xref>. If <code class="paramref">makeActive</code> is true, makes it the active definition query.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void InsertDefinitionQuery(DefinitionQuery definitionQuery, bool makeActive = false)
```
### IsEditable

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.IntegratedMeshSceneLayer.yml" sourcestartlinenumber="1">Gets whether the integrated mesh scene layer is editable.</p>


```csharp
public bool IsEditable { get; }
```
### IsLabelVisible

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.IntegratedMeshSceneLayer.yml" sourcestartlinenumber="1">Gets whether labels are drawing</p>


```csharp
public bool IsLabelVisible { get; }
```
### IsSelectable

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.IntegratedMeshSceneLayer.yml" sourcestartlinenumber="1">Gets whether the integrated mesh scene layer is selectable.</p>


```csharp
public bool IsSelectable { get; }
```
### IsSnappable

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.IntegratedMeshSceneLayer.yml" sourcestartlinenumber="1">Gets whether the integrated mesh scene layer is snappable.</p>


```csharp
public bool IsSnappable { get; }
```
### IsValidDefinitionQuery(DefinitionQuery)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IntegratedMeshSceneLayer.yml" sourcestartlinenumber="1">Determines if the specified definitionQuery is valid.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Task<bool> IsValidDefinitionQuery(DefinitionQuery definitionQuery)
```
### IsValidDefinitionQuery(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IntegratedMeshSceneLayer.yml" sourcestartlinenumber="1">Determines if the specified SQL where clause has valid syntax.   That is; the field defined exists on the layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Task<bool> IsValidDefinitionQuery(string sql)
```
### LegendStatus

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.IntegratedMeshSceneLayer.yml" sourcestartlinenumber="1">Gets the status of the legend</p>


```csharp
public override LegendStatus LegendStatus { get; protected set; }
```
### RemoveActiveDefinitionQuery()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IntegratedMeshSceneLayer.yml" sourcestartlinenumber="1">Removes the active definition query. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveActiveDefinitionQuery()
```
### RemoveAllDefinitionQueries()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IntegratedMeshSceneLayer.yml" sourcestartlinenumber="1">Remove all definition queries.  This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveAllDefinitionQueries()
```
### RemoveDefinitionQueries(IEnumerable&lt;string&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IntegratedMeshSceneLayer.yml" sourcestartlinenumber="1">Removes the definition queries specified by the list of names. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveDefinitionQueries(IEnumerable<string> queryNames)
```
### RemoveDefinitionQuery(int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IntegratedMeshSceneLayer.yml" sourcestartlinenumber="1">Removes the definition query at the specified index. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveDefinitionQuery(int index)
```
### SetActiveDefinitionQuery(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IntegratedMeshSceneLayer.yml" sourcestartlinenumber="1">Sets the definition query matching the specified <code class="paramref">queryName</code> to be the active definition query.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetActiveDefinitionQuery(string queryName)
```
### SetDefinitionQuery(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IntegratedMeshSceneLayer.yml" sourcestartlinenumber="1">Sets the where clause of the active definition query.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public DefinitionQuery SetDefinitionQuery(string whereClause)
```
### SetRenderer(CIMRenderer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IntegratedMeshSceneLayer.yml" sourcestartlinenumber="1">Specifies the integrated mesh scene layer's renderer object which determines how the layer draws.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetRenderer(CIMRenderer renderer)
```
### ShapeType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.IntegratedMeshSceneLayer.yml" sourcestartlinenumber="1">Gets the integrated mesh scene layer's shape type.</p>


```csharp
public esriGeometryType ShapeType { get; }
```


