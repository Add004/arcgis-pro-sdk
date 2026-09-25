# MosaicLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.MosaicLayer.yml" sourcestartlinenumber="1">Represents a mosaic layer.</p>


## Object Signature

```csharp
public sealed class MosaicLayer : CompositeLayer, IMetadataInfo, IMetadataSource, ILayerContainer, ITableDefinitionQueries
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.MosaicLayer.yml" sourcestartlinenumber="1">The mosaic layer is a composite layer which is a representation of a mosaic dataset.
The mosaic layer is drawn based on the <xref href="ArcGIS.Core.CIM.CIMRasterColorizer" data-throw-if-not-resolved="false"></xref>.</p>


## Members

### ActiveDefinitionQuery

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MosaicLayer.yml" sourcestartlinenumber="1">Gets the active definition query.</p>


```csharp
public DefinitionQuery ActiveDefinitionQuery { get; }
```
### CanSetTime(TimeParameters)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MosaicLayer.yml" sourcestartlinenumber="1">Gets if the mapMember supports time and if the specified time parameters are valid.
This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public override bool CanSetTime(TimeParameters timeParams)
```
### DefinitionQueries

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MosaicLayer.yml" sourcestartlinenumber="1">Gets a list of all DefinitionQueries.</p>


```csharp
public IReadOnlyList<DefinitionQuery> DefinitionQueries { get; }
```
### DefinitionQuery

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MosaicLayer.yml" sourcestartlinenumber="1">Gets the where clause of the active definition query.</p>


```csharp
public string DefinitionQuery { get; }
```
### GetBoundaryLayer()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MosaicLayer.yml" sourcestartlinenumber="1">Gets the boundary sub-layer. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public FeatureMosaicSubLayer GetBoundaryLayer()
```
### GetFootprintLayer()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MosaicLayer.yml" sourcestartlinenumber="1">Gets the footprint sub-layer. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public FeatureMosaicSubLayer GetFootprintLayer()
```
### GetImageLayer()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MosaicLayer.yml" sourcestartlinenumber="1">Gets the image sub-layer. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public ImageMosaicSubLayer GetImageLayer()
```
### GetSeamlineLayer()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MosaicLayer.yml" sourcestartlinenumber="1">Gets the seamline sub-layer (if generated). This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public FeatureMosaicSubLayer GetSeamlineLayer()
```
### InsertDefinitionQueries(IEnumerable&lt;DefinitionQuery&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MosaicLayer.yml" sourcestartlinenumber="1">Insert a list of <xref href="ArcGIS.Desktop.Mapping.MosaicLayer.DefinitionQuery" data-throw-if-not-resolved="false"></xref>. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void InsertDefinitionQueries(IEnumerable<DefinitionQuery> queries)
```
### InsertDefinitionQuery(DefinitionQuery, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MosaicLayer.yml" sourcestartlinenumber="1">Inserts a <xref href="ArcGIS.Desktop.Mapping.MosaicLayer.DefinitionQuery" data-throw-if-not-resolved="false"></xref>. If <code class="paramref">makeActive</code> is true, makes it the active definition query.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void InsertDefinitionQuery(DefinitionQuery definitionQuery, bool makeActive = false)
```
### IsValidDefinitionQuery(DefinitionQuery)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MosaicLayer.yml" sourcestartlinenumber="1">Determines if the specified definitionQuery is valid.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Task<bool> IsValidDefinitionQuery(DefinitionQuery definitionQuery)
```
### IsValidDefinitionQuery(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MosaicLayer.yml" sourcestartlinenumber="1">Determines if the specified SQL where clause has valid syntax.   That is; the field defined exists on the layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Task<bool> IsValidDefinitionQuery(string sql)
```
### RemoveActiveDefinitionQuery()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MosaicLayer.yml" sourcestartlinenumber="1">Removes the active definition query. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveActiveDefinitionQuery()
```
### RemoveAllDefinitionQueries()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MosaicLayer.yml" sourcestartlinenumber="1">Remove all definition queries.  This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveAllDefinitionQueries()
```
### RemoveDefinitionQueries(IEnumerable&lt;string&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MosaicLayer.yml" sourcestartlinenumber="1">Removes the definition queries specified by the list of names. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveDefinitionQueries(IEnumerable<string> queryNames)
```
### RemoveDefinitionQuery(int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MosaicLayer.yml" sourcestartlinenumber="1">Removes the definition query at the specified index. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveDefinitionQuery(int index)
```
### SetActiveDefinitionQuery(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MosaicLayer.yml" sourcestartlinenumber="1">Sets the definition query matching the specified <code class="paramref">queryName</code> to be the active definition query.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetActiveDefinitionQuery(string queryName)
```
### SetDefinitionQuery(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MosaicLayer.yml" sourcestartlinenumber="1">Sets the where clause of the active definition query.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public DefinitionQuery SetDefinitionQuery(string whereClause)
```


