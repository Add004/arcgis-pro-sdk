# StandaloneTable

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Represents a table without geometries that can be added to your map.</p>


## Object Signature

```csharp
public class StandaloneTable : MapMember, IMetadataInfo, IMetadataSource, IDisplayTable, ITableDefinitionQueries, IArcadeEvaluatorObject
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">It can be used in conjunction with the layers. The data in a StandaloneTable does not display in your map, but is listed in the table of contents. You can work with this data as you would work with any tabular information of geographic features. For example, you can view the table, add new fields, create graphs, and join it to other tables or layers.</p>


## Members

### ActiveDefinitionQuery

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Gets the active definition query.</p>


```csharp
public DefinitionQuery ActiveDefinitionQuery { get; }
```
### CanEditData()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Returns <code>true</code> if the data can be edited.</p>


```csharp
public bool CanEditData()
```
### CanReplaceDataSource(Table)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Check if the standalone table's data source can be replace with this table.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool CanReplaceDataSource(Table table)
```
### CanSetTime(TimeParameters)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Gets if the mapMember supports time filtering and if the specified time parameters are valid.
This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public override bool CanSetTime(TimeParameters timeParams)
```
### ClearSelection()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Clears the current selection.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void ClearSelection()
```
### DefinitionQueries

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Gets a list of all DefinitionQueries.</p>


```csharp
public IReadOnlyList<DefinitionQuery> DefinitionQueries { get; }
```
### DefinitionQuery

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Gets the where clause of the active definition query.</p>


```csharp
public string DefinitionQuery { get; }
```
### DisplayExpressionInfo

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Gets the display expression info.</p>


```csharp
public CIMExpressionInfo DisplayExpressionInfo { get; }
```
### DisplayField

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Gets the name of the attribute field that is used to identify each row or feature.</p>


```csharp
public string DisplayField { get; }
```
### FindAndReplaceWorkspacePath(string, string, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Performs a find and replace of workspace path for the table.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void FindAndReplaceWorkspacePath(string findWorkspacePath, string replaceWorkspacePath, bool validate = true)
```
### GetCanEditMetadata()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Gets whether the StandaloneTable metadata can be edited or not. This method must be called on the MCT.
Use QueuedTask.Run.</p>


```csharp
public override bool GetCanEditMetadata()
```
### GetDefinition()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Returns the standalone table's CIM definition.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public virtual CIMStandaloneTable GetDefinition()
```
### GetDisplayExpressions(IEnumerable&lt;long&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Gets the display expressions of the given set of objects.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public List<string> GetDisplayExpressions(IEnumerable<long> oids)
```
### GetFieldDescriptions()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Returns fields of the standalone table including joined fields, if any.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public List<FieldDescription> GetFieldDescriptions()
```
### GetMetadata()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Gets the StandaloneTable metadata. This method must be called on the MCT.
Use QueuedTask.Run.</p>


```csharp
public override string GetMetadata()
```
### GetSelection()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Gets the current selection of the table.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Selection GetSelection()
```
### GetTable()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Returns the underlying table.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Table GetTable()
```
### HasJoins

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Gets whether the StandaloneTable has any joins</p>


```csharp
public bool HasJoins { get; }
```
### HasRelates

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Gets whether the StandaloneTable has any relates</p>


```csharp
public bool HasRelates { get; }
```
### InsertDefinitionQueries(IEnumerable&lt;DefinitionQuery&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Insert a list of <xref href="ArcGIS.Desktop.Mapping.StandaloneTable.DefinitionQuery" data-throw-if-not-resolved="false"></xref>. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void InsertDefinitionQueries(IEnumerable<DefinitionQuery> queries)
```
### InsertDefinitionQuery(DefinitionQuery, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Inserts a <xref href="ArcGIS.Desktop.Mapping.StandaloneTable.DefinitionQuery" data-throw-if-not-resolved="false"></xref>. If <code class="paramref">makeActive</code> is true, makes it the active definition query.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void InsertDefinitionQuery(DefinitionQuery definitionQuery, bool makeActive = false)
```
### IsEditable

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Gets whether the standalone table is editable.</p>


```csharp
public bool IsEditable { get; }
```
### IsSelectRelatedData

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Gets whether the standalone table is set to automatically select related data.</p>


```csharp
public bool IsSelectRelatedData { get; }
```
### IsSelectable

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Gets whether a MapMember is selectable.</p>


```csharp
public bool IsSelectable { get; }
```
### IsSubtypeTable

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Gets whether the standalone table is a member of <xref href="ArcGIS.Desktop.Mapping.SubtypeGroupTable" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public bool IsSubtypeTable { get; }
```
### IsValidDefinitionQuery(DefinitionQuery)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Determines if the specified definitionQuery is valid.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Task<bool> IsValidDefinitionQuery(DefinitionQuery definitionQuery)
```
### IsValidDefinitionQuery(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Determines if the specified SQL where clause has valid syntax.   That is; the field defined exists on the table.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Task<bool> IsValidDefinitionQuery(string sql)
```
### Parent

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Gets the parent of the StandaloneTable. It is either the group layer it belongs to, or the map for tables that do not belong in any group layers.</p>


```csharp
public IStandaloneTableContainer Parent { get; }
```
### RemoveActiveDefinitionQuery()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Removes the active definition query. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveActiveDefinitionQuery()
```
### RemoveAllDefinitionQueries()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Remove all definition queries.  This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveAllDefinitionQueries()
```
### RemoveDefinitionQueries(IEnumerable&lt;string&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Removes the definition queries specified by the list of names. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveDefinitionQueries(IEnumerable<string> queryNames)
```
### RemoveDefinitionQuery(int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Removes the definition query at the specified index. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveDefinitionQuery(int index)
```
### ReplaceDataSource(Table)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Replace the standalone table's data source.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void ReplaceDataSource(Table table)
```
### Search(QueryFilter, TimeRange, RangeExtent, CIMFloorFilterSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Executes a query to the underlying data source and returns rows matching the search criteria.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RowCursor Search(QueryFilter queryFilter = null, TimeRange time = null, RangeExtent range = null, CIMFloorFilterSettings floor = null)
```
### SearchEx(QueryFilter, TimeRange, RangeExtent, CIMFloorFilterSettings, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Executes a query to the underlying data source and returns rows matching the search criteria.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RowCursor SearchEx(QueryFilter queryFilter = null, TimeRange time = null, RangeExtent range = null, CIMFloorFilterSettings floor = null, bool useRecyclingCursor = true)
```
### Select(QueryFilter, SelectionCombinationMethod, TimeRange, RangeExtent, CIMFloorFilterSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Selects rows based upon the specified criteria and combination method.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Selection Select(QueryFilter queryFilter = null, SelectionCombinationMethod method = SelectionCombinationMethod.New, TimeRange time = null, RangeExtent range = null, CIMFloorFilterSettings floor = null)
```
### SelectionCount

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Gets the number of rows selected in the standalone table.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int SelectionCount { get; }
```
### SetActiveDefinitionQuery(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Sets the definition query matching the specified <code class="paramref">queryName</code> to be the active definition query.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetActiveDefinitionQuery(string queryName)
```
### SetDefinition(CIMStandaloneTable)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Updates the standalone table's CIM definition.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public virtual void SetDefinition(CIMStandaloneTable table)
```
### SetDefinitionQuery(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Sets the where clause of the active definition query.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public DefinitionQuery SetDefinitionQuery(string whereClause)
```
### SetDisplayExpressionInfo(CIMExpressionInfo)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Sets the display expression info with an arcade expression that will be used to identify features or rows. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDisplayExpressionInfo(CIMExpressionInfo displayExpressionInfo)
```
### SetDisplayField(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Sets the name of the attribute field that will be used to identify features or rows. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDisplayField(string displayField)
```
### SetEditable(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Enables or disables editing on a standalone table.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetEditable(bool isEditable)
```
### SetFieldDescriptions(List&lt;FieldDescription&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Applies updates to the editable properties of fields.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetFieldDescriptions(List<FieldDescription> updatedDescriptions)
```
### SetMetadata(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Sets the StandaloneTable metadata. This method must be called on the MCT.
Use QueuedTask.Run.</p>


```csharp
public override void SetMetadata(string metadataXml)
```
### SetSelectRelatedData(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Toggles the SelectRelatedData of a MapMember.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetSelectRelatedData(bool selectRelatedData)
```
### SetSelectable(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Toggles the selectability.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetSelectable(bool isSelectable)
```
### SetSelection(Selection)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Sets the current selection of the table.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetSelection(Selection selection)
```
### SubtypeValue

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTable.yml" sourcestartlinenumber="1">Gets the subtype value that is used in the standalone table definition.</p>


```csharp
public int SubtypeValue { get; }
```


