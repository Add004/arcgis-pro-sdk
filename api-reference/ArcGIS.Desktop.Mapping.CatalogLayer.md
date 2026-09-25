# CatalogLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.CatalogLayer.yml" sourcestartlinenumber="1">Represents a layer with a reference to a catalog dataset which contains references to
multiple datasets, packages, and/or portal items. The catalog dataset items do not have
to be related.</p>


## Object Signature

```csharp
public sealed class CatalogLayer : CompositeLayer, IMetadataInfo, IMetadataSource, ILayerContainer, ITableDefinitionQueries
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.CatalogLayer.yml" sourcestartlinenumber="1">To create a catalog layer use <xref href="ArcGIS.Desktop.Mapping.CatalogLayerCreationParams" data-throw-if-not-resolved="false"></xref> with LayerFactory.<br>
The item references, within the catalog dataset, can be visualized, filtered, and queried
dynamically in maps and scenes.</p>


## Members

### ActiveDefinitionQuery

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.CatalogLayer.yml" sourcestartlinenumber="1">Gets the active definition query.</p>


```csharp
public DefinitionQuery ActiveDefinitionQuery { get; }
```
### CanSetTime(TimeParameters)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.CatalogLayer.yml" sourcestartlinenumber="1">Gets if the mapMember supports time and if the specified time parameters are valid.
This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public override bool CanSetTime(TimeParameters timeParams)
```
### DefinitionQueries

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.CatalogLayer.yml" sourcestartlinenumber="1">Gets a list of all DefinitionQueries.</p>


```csharp
public IReadOnlyList<DefinitionQuery> DefinitionQueries { get; }
```
### DefinitionQuery

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.CatalogLayer.yml" sourcestartlinenumber="1">Gets the where clause of the active definition query of a layer or standalone table.</p>


```csharp
public string DefinitionQuery { get; }
```
### GetCatalogDataset()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.CatalogLayer.yml" sourcestartlinenumber="1">Returns the underlying <xref href="ArcGIS.Core.Data.Mapping.CatalogDataset?text=CatalogDataset" data-throw-if-not-resolved="false"></xref>
that the catalog layer is pointing to. This method must be called on the MCT. Use
QueuedTask.Run.</p>


```csharp
public CatalogDataset GetCatalogDataset()
```
### InsertDefinitionQueries(IEnumerable&lt;DefinitionQuery&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.CatalogLayer.yml" sourcestartlinenumber="1">Insert a list of <xref href="ArcGIS.Desktop.Mapping.CatalogLayer.DefinitionQuery" data-throw-if-not-resolved="false"></xref>. This method must be called on the
MCT. Use QueuedTask.Run.</p>


```csharp
public void InsertDefinitionQueries(IEnumerable<DefinitionQuery> queries)
```
### InsertDefinitionQuery(DefinitionQuery, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.CatalogLayer.yml" sourcestartlinenumber="1">Inserts a <xref href="ArcGIS.Desktop.Mapping.CatalogLayer.DefinitionQuery" data-throw-if-not-resolved="false"></xref>. If <code class="paramref">makeActive</code> is true, makes it the active definition query.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void InsertDefinitionQuery(DefinitionQuery definitionQuery, bool makeActive = false)
```
### IsValidDefinitionQuery(DefinitionQuery)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.CatalogLayer.yml" sourcestartlinenumber="1">Determines if the specified definitionQuery is valid.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Task<bool> IsValidDefinitionQuery(DefinitionQuery definitionQuery)
```
### IsValidDefinitionQuery(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.CatalogLayer.yml" sourcestartlinenumber="1">Determines if the specified SQL where clause has valid syntax.   That is; the field defined exists on the layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Task<bool> IsValidDefinitionQuery(string sql)
```
### MaxVisibleLayers

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.CatalogLayer.yml" sourcestartlinenumber="1">Gets the limit for the number of catalog dataset items that can draw in the
layer's active view.</p>


```csharp
public int MaxVisibleLayers { get; }
```
### RemoveActiveDefinitionQuery()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.CatalogLayer.yml" sourcestartlinenumber="1">Removes the active definition query. This method must be called on the MCT. Use
QueuedTask.Run.</p>


```csharp
public void RemoveActiveDefinitionQuery()
```
### RemoveAllDefinitionQueries()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.CatalogLayer.yml" sourcestartlinenumber="1">Remove all definition queries. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveAllDefinitionQueries()
```
### RemoveDefinitionQueries(IEnumerable&lt;string&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.CatalogLayer.yml" sourcestartlinenumber="1">Removes the definition queries specified by the list of names. This method must be called on
the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveDefinitionQueries(IEnumerable<string> queryNames)
```
### RemoveDefinitionQuery(int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.CatalogLayer.yml" sourcestartlinenumber="1">Removes the definition query at the specified index. This method must be called on the MCT.
Use QueuedTask.Run.</p>


```csharp
public void RemoveDefinitionQuery(int index)
```
### SetActiveDefinitionQuery(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.CatalogLayer.yml" sourcestartlinenumber="1">Sets the specified query to be the active definition query.  If the <code class="paramref">queryName</code> is null, then the active query definition
that is cleared.   This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetActiveDefinitionQuery(string queryName)
```
### SetDefinitionQuery(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.CatalogLayer.yml" sourcestartlinenumber="1">Sets the where clause of the active definition query. This method must be called
on the MCT. Use QueuedTask.Run.</p>


```csharp
public DefinitionQuery SetDefinitionQuery(string whereClause)
```
### SetMaxVisibleLayers(int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.CatalogLayer.yml" sourcestartlinenumber="1">Sets the limit for the number of catalog dataset items that can draw in the
layer's active view.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetMaxVisibleLayers(int maxVisibleLayers)
```


