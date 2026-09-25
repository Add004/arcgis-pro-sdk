# ImageServiceLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.ImageServiceLayer.yml" sourcestartlinenumber="1">Represents an image service layer.</p>


## Object Signature

```csharp
public class ImageServiceLayer : BasicRasterLayer, IMetadataInfo, IMetadataSource, ITableDefinitionQueries
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.ImageServiceLayer.yml" sourcestartlinenumber="1">The image service layer is a representation of an image service. The image service layer is drawn based on the <xref href="ArcGIS.Core.CIM.CIMRasterColorizer" data-throw-if-not-resolved="false"></xref></p>


## Members

### ActiveDefinitionQuery

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ImageServiceLayer.yml" sourcestartlinenumber="1">Gets the active definition query.</p>


```csharp
public DefinitionQuery ActiveDefinitionQuery { get; }
```
### ClearSelection()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ImageServiceLayer.yml" sourcestartlinenumber="1">Clears the current selection.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void ClearSelection()
```
### DefinitionQueries

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ImageServiceLayer.yml" sourcestartlinenumber="1">Gets a list of all DefinitionQueries.</p>


```csharp
public IReadOnlyList<DefinitionQuery> DefinitionQueries { get; }
```
### DefinitionQuery

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ImageServiceLayer.yml" sourcestartlinenumber="1">Gets the where clause of the active definition query.</p>


```csharp
public string DefinitionQuery { get; }
```
### GetCompression()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ImageServiceLayer.yml" sourcestartlinenumber="1">Gets the compression information. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Tuple<string, int> GetCompression()
```
### GetMosaicRule()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ImageServiceLayer.yml" sourcestartlinenumber="1">Gets the mosaic rule. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMMosaicRule GetMosaicRule()
```
### GetSelection()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ImageServiceLayer.yml" sourcestartlinenumber="1">Gets the current selection of the image service layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Selection GetSelection()
```
### GetTable()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ImageServiceLayer.yml" sourcestartlinenumber="1">Gets the catalog table.
This method must be called on the MCT. Use QueuedTask.Run</p>


```csharp
public Table GetTable()
```
### InsertDefinitionQueries(IEnumerable&lt;DefinitionQuery&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ImageServiceLayer.yml" sourcestartlinenumber="1">Insert a list of <xref href="ArcGIS.Desktop.Mapping.ImageServiceLayer.DefinitionQuery" data-throw-if-not-resolved="false"></xref>. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void InsertDefinitionQueries(IEnumerable<DefinitionQuery> queries)
```
### InsertDefinitionQuery(DefinitionQuery, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ImageServiceLayer.yml" sourcestartlinenumber="1">Inserts a <xref href="ArcGIS.Desktop.Mapping.ImageServiceLayer.DefinitionQuery" data-throw-if-not-resolved="false"></xref>. If <code class="paramref">makeActive</code> is true, makes it the active definition query.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void InsertDefinitionQuery(DefinitionQuery definitionQuery, bool makeActive = false)
```
### IsSelectable

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ImageServiceLayer.yml" sourcestartlinenumber="1">Gets whether the image service layer is selectable.</p>


```csharp
public bool IsSelectable { get; }
```
### IsValidDefinitionQuery(DefinitionQuery)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ImageServiceLayer.yml" sourcestartlinenumber="1">Determines if the specified definitionQuery is valid.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Task<bool> IsValidDefinitionQuery(DefinitionQuery definitionQuery)
```
### IsValidDefinitionQuery(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ImageServiceLayer.yml" sourcestartlinenumber="1">Determines if the specified SQL where clause has valid syntax.   That is; the field defined exists on the layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Task<bool> IsValidDefinitionQuery(string sql)
```
### RemoveActiveDefinitionQuery()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ImageServiceLayer.yml" sourcestartlinenumber="1">Removes the active definition query. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveActiveDefinitionQuery()
```
### RemoveAllDefinitionQueries()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ImageServiceLayer.yml" sourcestartlinenumber="1">Remove all definition queries.  This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveAllDefinitionQueries()
```
### RemoveDefinitionQueries(IEnumerable&lt;string&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ImageServiceLayer.yml" sourcestartlinenumber="1">Removes the definition queries specified by the list of names. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveDefinitionQueries(IEnumerable<string> queryNames)
```
### RemoveDefinitionQuery(int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ImageServiceLayer.yml" sourcestartlinenumber="1">Removes the definition query at the specified index. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveDefinitionQuery(int index)
```
### Select(QueryFilter, SelectionCombinationMethod, TimeRange, RangeExtent, CIMFloorFilterSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ImageServiceLayer.yml" sourcestartlinenumber="1">Selects features based upon the specified attribute and/or spatial criteria and combination method.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Selection Select(QueryFilter queryFilter = null, SelectionCombinationMethod method = SelectionCombinationMethod.New, TimeRange time = null, RangeExtent range = null, CIMFloorFilterSettings floor = null)
```
### SelectionCount

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ImageServiceLayer.yml" sourcestartlinenumber="1">Gets the number of features selected in the layer.</p>


```csharp
public int SelectionCount { get; }
```
### SetActiveDefinitionQuery(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ImageServiceLayer.yml" sourcestartlinenumber="1">Sets the definition query matching the specified <code class="paramref">queryName</code> to be the active definition query.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetActiveDefinitionQuery(string queryName)
```
### SetCompression(string, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ImageServiceLayer.yml" sourcestartlinenumber="1">Sets the compression. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetCompression(string compression, int quality)
```
### SetDefinitionQuery(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ImageServiceLayer.yml" sourcestartlinenumber="1">Sets the where clause of the active definition query.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public DefinitionQuery SetDefinitionQuery(string whereClause)
```
### SetMosaicRule(CIMMosaicRule)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ImageServiceLayer.yml" sourcestartlinenumber="1">Sets the mosaic rule. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetMosaicRule(CIMMosaicRule mosaicRule)
```
### SetSelectable(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ImageServiceLayer.yml" sourcestartlinenumber="1">Toggles the selectability of an image service layer. If the layer does not support selection (see <xref href="ArcGIS.Desktop.Mapping.ImageServiceLayer.SupportsSelection" data-throw-if-not-resolved="false"></xref>)
the value is ignored.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetSelectable(bool isSelectable)
```
### SetSelection(Selection)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ImageServiceLayer.yml" sourcestartlinenumber="1">Sets the current selection of the image service layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetSelection(Selection selection)
```
### SupportsSelection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ImageServiceLayer.yml" sourcestartlinenumber="1">Gets whether the image service layer supports selection.</p>


```csharp
public virtual bool SupportsSelection { get; }
```


