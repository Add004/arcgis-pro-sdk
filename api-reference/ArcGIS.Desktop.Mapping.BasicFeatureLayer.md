# BasicFeatureLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Represents the abstract base class for layers with a collection of features and their visual representation and editing (when permitted).</p>


## Object Signature

```csharp
public abstract class BasicFeatureLayer : Layer, IMetadataInfo, IMetadataSource, IDisplayTable, ITableDefinitionQueries, IArcadeEvaluatorObject
```


## Members

### BasicFeatureLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Represents the abstract base class for layers with a collection of features and their visual representation and editing (when permitted).</p>


```csharp
protected BasicFeatureLayer()
```
### ActiveDefinitionQuery

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Gets the active definition query.</p>


```csharp
public DefinitionQuery ActiveDefinitionQuery { get; }
```
### CanEditData()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Returns <code>true</code> if the data can be edited.</p>


```csharp
public bool CanEditData()
```
### CanSetFeatureBlendingMode(BlendingMode)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Check if the per feature blending mode can be set on this layer.</p>


```csharp
public bool CanSetFeatureBlendingMode(BlendingMode mode)
```
### ClearSelection()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Clears the current selection.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void ClearSelection()
```
### DefinitionQueries

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Gets a list of all DefinitionQueries.</p>


```csharp
public IReadOnlyList<DefinitionQuery> DefinitionQueries { get; }
```
### DefinitionQuery

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Gets the where clause of the active definition query.</p>


```csharp
public string DefinitionQuery { get; }
```
### DisplayExpressionInfo

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Gets the display expression info.</p>


```csharp
public CIMExpressionInfo DisplayExpressionInfo { get; }
```
### DisplayField

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Gets the name of the attribute field that is used to identify each row or feature.</p>


```csharp
public string DisplayField { get; }
```
### FeatureBlendingMode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Gets the per feature blend mode of a basic feature layer.</p>


```csharp
public BlendingMode FeatureBlendingMode { get; }
```
### FeatureCacheType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Gets the layer's feature cache type.</p>


```csharp
public FeatureCacheType FeatureCacheType { get; }
```
### GetCustomSelectionProperties()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Gets the custom selection properties in use for this layer; that is the flag indicating if a custom selection color is used along
with the custom selection color and a flag indication if a custom selection fill color is used along with the custom selection fill color (if the layer is a polygon layer).
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public (bool useCustomSelectionColor, CIMColor customSelectionColor, bool useCustomSelectionFillColor, CIMColor customSelectionFillColor) GetCustomSelectionProperties()
```
### GetDisplayExpressions(IEnumerable&lt;long&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Gets the display expressions of the given set of objects.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public List<string> GetDisplayExpressions(IEnumerable<long> oids)
```
### GetDrawingOutline(long, MapView, DrawingOutlineType)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Get the outline geometry for the corresponding feature identified by the object id.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Geometry GetDrawingOutline(long oid, MapView view, DrawingOutlineType outlineType)
```
### GetFeatureOutline(MapView, FeatureOutlineType)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Get an outline geometry created from the geometries of the set of input features.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Geometry GetFeatureOutline(MapView view, FeatureOutlineType outlineType)
```
### GetFieldDescriptions()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Returns fields of the layer including joined fields, if any.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public List<FieldDescription> GetFieldDescriptions()
```
### GetSelection()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Gets the current selection of the basic feature layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Selection GetSelection()
```
### GetTable()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Returns the underlying feature class as Table type.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Table GetTable()
```
### InsertDefinitionQueries(IEnumerable&lt;DefinitionQuery&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Insert a list of <xref href="ArcGIS.Desktop.Mapping.BasicFeatureLayer.DefinitionQuery" data-throw-if-not-resolved="false"></xref>. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void InsertDefinitionQueries(IEnumerable<DefinitionQuery> queries)
```
### InsertDefinitionQuery(DefinitionQuery, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Inserts a <xref href="ArcGIS.Desktop.Mapping.BasicFeatureLayer.DefinitionQuery" data-throw-if-not-resolved="false"></xref>. If <code class="paramref">makeActive</code> is true, makes it the active definition query.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void InsertDefinitionQuery(DefinitionQuery definitionQuery, bool makeActive = false)
```
### IsEditable

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Gets whether a layer is editable.</p>


```csharp
public bool IsEditable { get; }
```
### IsSelectRelatedData

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Gets whether a basic feature layer is set to automatically select related data.</p>


```csharp
public bool IsSelectRelatedData { get; }
```
### IsSelectable

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Gets whether the basic feature layer is selectable.</p>


```csharp
public bool IsSelectable { get; }
```
### IsValidDefinitionQuery(DefinitionQuery)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Determines if the specified definitionQuery is valid.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Task<bool> IsValidDefinitionQuery(DefinitionQuery definitionQuery)
```
### IsValidDefinitionQuery(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Determines if the specified SQL where clause has valid syntax.   That is; the field defined exists on the layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Task<bool> IsValidDefinitionQuery(string sql)
```
### RemoveActiveDefinitionQuery()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Removes the active definition query. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveActiveDefinitionQuery()
```
### RemoveAllDefinitionQueries()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Remove all definition queries.  This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveAllDefinitionQueries()
```
### RemoveDefinitionQueries(IEnumerable&lt;string&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Removes the definition queries specified by the list of names. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveDefinitionQueries(IEnumerable<string> queryNames)
```
### RemoveDefinitionQuery(int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Removes the definition query at the specified index. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveDefinitionQuery(int index)
```
### Search(QueryFilter, TimeRange, RangeExtent, CIMFloorFilterSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Executes a spatial or attribute query to the underlying data source and returns features matching the search criteria.
For stream layer, you should call <xref href="ArcGIS.Core.Data.Realtime.RealtimeFeatureClass.StopStreaming" data-throw-if-not-resolved="false"></xref> for predictable result.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RowCursor Search(QueryFilter queryFilter = null, TimeRange time = null, RangeExtent range = null, CIMFloorFilterSettings floor = null)
```
### SearchEx(QueryFilter, TimeRange, RangeExtent, CIMFloorFilterSettings, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Executes a query to the underlying data source and returns rows matching the search criteria.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RowCursor SearchEx(QueryFilter queryFilter = null, TimeRange time = null, RangeExtent range = null, CIMFloorFilterSettings floor = null, bool useRecyclingCursor = true)
```
### Select(QueryFilter, SelectionCombinationMethod, TimeRange, RangeExtent, CIMFloorFilterSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Selects features based upon the specified attribute and/or spatial criteria and combination method.
For stream layer, you should call <xref href="ArcGIS.Core.Data.Realtime.RealtimeFeatureClass.StopStreaming" data-throw-if-not-resolved="false"></xref> for predictable result.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Selection Select(QueryFilter queryFilter = null, SelectionCombinationMethod method = SelectionCombinationMethod.New, TimeRange time = null, RangeExtent range = null, CIMFloorFilterSettings floor = null)
```
### SelectionCount

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Gets the number of features selected in the layer.</p>


```csharp
public int SelectionCount { get; }
```
### SetActiveDefinitionQuery(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Sets the definition query matching the specified <code class="paramref">queryName</code> to be the active definition query.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetActiveDefinitionQuery(string queryName)
```
### SetCustomSelectionColor(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Sets the layer to display its selection in the specified color. Use null to specify that the layer should display its selection in
the default selection color defined in <xref href="ArcGIS.Desktop.Core.SelectionOptions.SelectionColor" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetCustomSelectionColor(CIMColor color)
```
### SetCustomSelectionColor(CIMColor, CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Sets the layer to display its selection in the specified color.  If the layer is a polygon layer, also set the selection color for polygon interiors.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetCustomSelectionColor(CIMColor color, CIMColor fillColor)
```
### SetDefinitionQuery(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Sets the where clause of the active definition query.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public DefinitionQuery SetDefinitionQuery(string whereClause)
```
### SetDisplayExpressionInfo(CIMExpressionInfo)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Sets the display expression info with an arcade expression that will be used to identify features or rows. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDisplayExpressionInfo(CIMExpressionInfo displayExpressionInfo)
```
### SetDisplayField(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Sets the name of the attribute field that will be used to identify features or rows. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDisplayField(string displayField)
```
### SetEditable(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Enables or disables editing on a basic feature layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetEditable(bool isEditable)
```
### SetFeatureBlendingMode(BlendingMode)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Sets the per feature blending mode.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetFeatureBlendingMode(BlendingMode mode)
```
### SetFieldDescriptions(List&lt;FieldDescription&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Applies updates to the editable properties of fields.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetFieldDescriptions(List<FieldDescription> updatedDescriptions)
```
### SetSelectRelatedData(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Toggles the <xref href="ArcGIS.Desktop.Mapping.BasicFeatureLayer.IsSelectRelatedData" data-throw-if-not-resolved="false"></xref> of a BasicFeatureLayer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetSelectRelatedData(bool selectRelatedData)
```
### SetSelectable(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Toggles the selectability of a basic feature layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetSelectable(bool isSelectable)
```
### SetSelection(Selection)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Sets the current selection of the basic feature layer.<br>
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetSelection(Selection selection)
```
### SetUseDefaultSelectionColor()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Sets the layer to use the default selection color to display its selection.  The default selection color is defined in the Selection options.  See
<xref href="ArcGIS.Desktop.Core.SelectionOptions.SelectionColor" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetUseDefaultSelectionColor()
```
### ShapeType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Gets the geometry type of the layer.</p>


```csharp
public virtual esriGeometryType ShapeType { get; }
```
### SupportsCustomSelectionProperties()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BasicFeatureLayer.yml" sourcestartlinenumber="1">Gets if the layer type supports custom selection properties; specifically if the layer can display its selection in a custom color.</p>


```csharp
public bool SupportsCustomSelectionProperties()
```
### _shapeType

- Kind: field


```csharp
protected esriGeometryType _shapeType
```


