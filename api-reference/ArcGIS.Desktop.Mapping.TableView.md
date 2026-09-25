# TableView

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Represents a view of a table.</p>


## Object Signature

```csharp
public sealed class TableView
```


## Members

### Active

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Gets the active table view.</p>


```csharp
public static TableView Active { get; }
```
### ActiveFieldIndex

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Gets the zero based index of the active field in the table.  Can be -1 if there are no fields.</p>


```csharp
public int ActiveFieldIndex { get; }
```
### ActiveObjectId

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Gets the ObjectID of the active row in the table.</p>
<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="3">The value of the row can be null, when the table does not have object ids,
the active row is the new row, or the data for the row has not been loaded.</p>


```csharp
public long? ActiveObjectId { get; }
```
### ActiveRowIndex

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Gets the zero based index of the active row in the table.  Can be -1 if there is no active row.</p>


```csharp
public int ActiveRowIndex { get; }
```
### AddField()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Displays the Add Field GP tool.</p>


```csharp
public void AddField()
```
### BringIntoView(int, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Scroll the table grid to the desired row and field and set the active cell.</p>


```csharp
public Task BringIntoView(int rowIndex, int fieldIndex = -1)
```
### CalculateField()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Shows the Calculate Field GP dialog.</p>


```csharp
public void CalculateField()
```
### CalculateFieldToolbar()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Shows the Calculate Field toolbar control.</p>


```csharp
public void CalculateFieldToolbar()
```
### CalculateGeometry()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Shows the Calculate Geometry dialog.</p>


```csharp
public void CalculateGeometry()
```
### CanAddField

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Determines if the Add Field GP tool can be displayed.</p>


```csharp
public bool CanAddField { get; }
```
### CanCalculateField

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Determines if the table control can display the Calculate Field GP dialog.</p>


```csharp
public bool CanCalculateField { get; }
```
### CanCalculateFieldToolbar

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Determines if the table control can display the Calculate Field toolbar control.</p>


```csharp
public bool CanCalculateFieldToolbar { get; }
```
### CanCalculateGeometry

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Determines if the table control can display the Calculate Geometry dialog.</p>


```csharp
public bool CanCalculateGeometry { get; }
```
### CanClearHighlighted

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Determines if the table view can clear its highlight. The table view must be showing the Selected Records view.</p>


```csharp
public bool CanClearHighlighted { get; }
```
### CanClearSelection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Determines if the table view can clear its selection.</p>


```csharp
public bool CanClearSelection { get; }
```
### CanCopySelectedRows

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Determines if the table view can copy the selected rows.</p>


```csharp
public bool CanCopySelectedRows { get; }
```
### CanCustomSort

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Determines if the table view can display the custom sort dialog.</p>


```csharp
public bool CanCustomSort { get; }
```
### CanDeleteField

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Determines if the active field of the table view can be deleted.</p>


```csharp
public bool CanDeleteField { get; }
```
### CanDeleteHighlighted

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Determines if the table can delete the highlighted rows.   The table view must be showing the Selected Records view.</p>


```csharp
public bool CanDeleteHighlighted { get; }
```
### CanDeleteSelected

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Determines if the table view can delete the selected rows.</p>


```csharp
public bool CanDeleteSelected { get; }
```
### CanExport

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Determines if the table view can export its attributes.</p>


```csharp
public bool CanExport { get; }
```
### CanFind

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Determines if the table view can display the Find control.</p>


```csharp
public bool CanFind { get; }
```
### CanFindAndReplace

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Determines if the table view can display the Find and replace control.</p>


```csharp
public bool CanFindAndReplace { get; }
```
### CanGetHighlightedObjectIds

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Gets if the objectIds of the highlighted rows can be retrieved. The table view must be showing the Selected Records view.</p>


```csharp
public bool CanGetHighlightedObjectIds { get; }
```
### CanGoTo

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Determines if the table view can display the Go to row number control.</p>


```csharp
public bool CanGoTo { get; }
```
### CanHideSelectedFields

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Determines if the table view's selected fields can be hidden.</p>


```csharp
public bool CanHideSelectedFields { get; }
```
### CanHighlight

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Gets if rows can be highlighted in the table view.  The table view must be showing the Selected Records view.</p>


```csharp
public bool CanHighlight { get; }
```
### CanPanToHighlighted

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Determines if the table can pan to the highlighted rows.   The table view must be showing the Selected Records view.</p>


```csharp
public bool CanPanToHighlighted { get; }
```
### CanPanToSelected

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Determines if the table view can pan to the selected rows.</p>


```csharp
public bool CanPanToSelected { get; }
```
### CanRefresh

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Determines if the table view can refresh its content.</p>


```csharp
public bool CanRefresh { get; }
```
### CanResetFieldOrder

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Resets the field order in the table view.</p>


```csharp
public bool CanResetFieldOrder { get; }
```
### CanSelect

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Determines if the table view can select rows.</p>


```csharp
public bool CanSelect { get; }
```
### CanSelectAll

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Determines if the table view can select all of its rows.</p>


```csharp
public bool CanSelectAll { get; }
```
### CanSelectByAttributes

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Determines if the table control can display the Select By Attributes GP tool.</p>


```csharp
public bool CanSelectByAttributes { get; }
```
### CanShowAllFields

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Determines if the table view can show all fields.</p>


```csharp
public bool CanShowAllFields { get; }
```
### CanSortAscending

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Determines if the table view can sort the active field.</p>


```csharp
public bool CanSortAscending { get; }
```
### CanSortDescending

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Determines if the table view can sort the active field.</p>


```csharp
public bool CanSortDescending { get; }
```
### CanSwitchHighlight

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Determines if the table view can switch its highlight. The table view must be showing the Selected Records view.</p>


```csharp
public bool CanSwitchHighlight { get; }
```
### CanSwitchSelection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Determines if the table view can switch its selection.</p>


```csharp
public bool CanSwitchSelection { get; }
```
### CanToggleFieldAlias

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Determines if the table view can toggle the field name and alias.</p>


```csharp
public bool CanToggleFieldAlias { get; }
```
### CanToggleRowHighlight

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Determines if the table view can toggle the highlight of the active row.  The table view must be showing the Selected Records view.</p>


```csharp
public bool CanToggleRowHighlight { get; }
```
### CanToggleRowSelection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Determines if the table view can toggle the selection of the active row.</p>


```csharp
public bool CanToggleRowSelection { get; }
```
### CanToggleSubtypeDomainDescriptions

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Determines if the table view can toggle between the subtype and domain descriptions and codes</p>


```csharp
public bool CanToggleSubtypeDomainDescriptions { get; }
```
### CanZoomToHighlighted

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Determines if the table can zoom to the highlighted rows.   The table view must be showing the Selected Records view.</p>


```csharp
public bool CanZoomToHighlighted { get; }
```
### CanZoomToSelected

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Determines if the table view can zoom to the selected rows.</p>


```csharp
public bool CanZoomToSelected { get; }
```
### ClearAllFrozenFieldsAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Clears all the frozen fields.</p>


```csharp
public Task ClearAllFrozenFieldsAsync()
```
### ClearHighlighted()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Clears the current highlight of the table view.</p>


```csharp
public void ClearHighlighted()
```
### ClearSelection()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Clears the current selection of the table view.</p>


```csharp
public void ClearSelection()
```
### CopySelectedRows()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Copies the selected rows in the table view.</p>


```csharp
public void CopySelectedRows()
```
### CustomSort()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Shows the custom field sort dialog.</p>


```csharp
public void CustomSort()
```
### DeleteField()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Deletes the active field of the table view.</p>


```csharp
public void DeleteField()
```
### DeleteHighlighted()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Deletes the highlighted rows.</p>


```csharp
public void DeleteHighlighted()
```
### DeleteSelected()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Deletes the selected rows in the table view.</p>


```csharp
public void DeleteSelected()
```
### Export()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Shows the Export Table GP tool for exporting the attributes of the table view.</p>


```csharp
public void Export()
```
### Find()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Shows the Find control.</p>


```csharp
public void Find()
```
### FindAndReplace()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Shows the Find and Replace control.</p>


```csharp
public void FindAndReplace()
```
### GetActivePageObjectIds()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Get the object ids of all active pages. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<long> GetActivePageObjectIds()
```
### GetAllObjectIds()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Gets all the sorted object ids from the data source. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<long> GetAllObjectIds()
```
### GetField(int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Gets the field at the given index.</p>


```csharp
public FieldDescription GetField(int index)
```
### GetFieldIndex(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Gets the index of the field with the given name.</p>


```csharp
public int GetFieldIndex(string fieldName)
```
### GetFields()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Gets a read-only list of <xref href="ArcGIS.Desktop.Mapping.FieldDescription" data-throw-if-not-resolved="false"></xref> representing the columns in the table.</p>


```csharp
public IReadOnlyList<FieldDescription> GetFields()
```
### GetFrozenFields()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Gets the set of frozen fields in the table view.</p>


```csharp
public IReadOnlyList<string> GetFrozenFields()
```
### GetHiddenFields()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Gets the set of hidden fields in the table view.</p>


```csharp
public IReadOnlyList<string> GetHiddenFields()
```
### GetHighlightedObjectIds()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Gets all the highlighted object ids from the data source.</p>


```csharp
public IReadOnlyList<long> GetHighlightedObjectIds()
```
### GetObjectIdAsync(int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Gets the object id for a row in the current <xref href="ArcGIS.Desktop.Editing.Controls.TableControl.ViewMode" data-throw-if-not-resolved="false"></xref> of the table.</p>


```csharp
public Task<long> GetObjectIdAsync(int rowIndex)
```
### GetRowCountAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Loads the row count from the data source.</p>


```csharp
public Task<long> GetRowCountAsync()
```
### GetRowIndex(long, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Gets the index of a row in the current <xref href="ArcGIS.Desktop.Editing.Controls.TableControl.ViewMode" data-throw-if-not-resolved="false"></xref> of the table.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int GetRowIndex(long objectId, bool activePageSearch)
```
### GetRowIndexAsync(long, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Gets the index of a row in the current <xref href="ArcGIS.Desktop.Editing.Controls.TableControl.ViewMode" data-throw-if-not-resolved="false"></xref> of the table.</p>


```csharp
public Task<int> GetRowIndexAsync(long objectId, bool activePageSearch)
```
### GetSelectedFields()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Gets the set of selected fields in the table view.</p>


```csharp
public IReadOnlyList<string> GetSelectedFields()
```
### GetSelectedObjectIds()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Gets all the selected object ids from the data source. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<long> GetSelectedObjectIds()
```
### GetSelectedRowIndexes()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Gets the indexes of all the selected rows. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<long> GetSelectedRowIndexes()
```
### GoTo()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Shows the Go to row number control.</p>


```csharp
public void GoTo()
```
### HideSelectedFields()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Hides the selected fields of the table view.</p>


```csharp
public void HideSelectedFields()
```
### Highlight(IEnumerable&lt;long&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Highlights rows in the table view.</p>


```csharp
public Task Highlight(IEnumerable<long> ids, bool idsAreObjectIds)
```
### Highlight(long, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Highlights a row in the table view.</p>


```csharp
public Task Highlight(long id, bool idIsObjectId)
```
### IsReady

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Gets a value that indicates whether the TableView can be accessed.
<remarks>This property is false while the table view processes major operations like initializing.</remarks></p>


```csharp
public bool IsReady { get; }
```
### IsRowCountKnown

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Gets the IsRowCountKnown property indicating the table view knows the count of rows in the data source.</p>


```csharp
public bool IsRowCountKnown { get; }
```
### Item

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Gets the item source of the table view. Use <xref href="ArcGIS.Desktop.Core.ItemFactory.CanGetDataset(ArcGIS.Desktop.Core.Item)" data-throw-if-not-resolved="false"></xref>
and <xref href="ArcGIS.Desktop.Core.ItemFactory.GetDataset(ArcGIS.Desktop.Core.Item)" data-throw-if-not-resolved="false"></xref> to retrieve the data.</p>


```csharp
public Item Item { get; }
```
### MapMember

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Gets the Layer or StandaloneTable source of the table view.</p>


```csharp
public MapMember MapMember { get; }
```
### PanToHighlighted()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Pans to the highlighted rows.</p>


```csharp
public void PanToHighlighted()
```
### PanToSelected()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Pans to the selected rows in the table view.</p>


```csharp
public void PanToSelected()
```
### Refresh()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Refreshes the content of the table view.</p>


```csharp
public void Refresh()
```
### ResetFieldOrder()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Resets the field order in the table view.</p>


```csharp
public void ResetFieldOrder()
```
### RowCount

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Gets the number of rows in the data source. If the IsRowCountKnown is true, then this is a total count.</p>


```csharp
public long RowCount { get; }
```
### RowsPerPage

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Gets the number of rows the table view is requesting, from the data source, for each page.</p>


```csharp
public long RowsPerPage { get; }
```
### Select(IEnumerable&lt;long&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Selects rows in the table view. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Select(IEnumerable<long> ids, bool idsAreObjectIds)
```
### Select(long, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Selects a row in the table view. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Select(long id, bool idIsObjectId)
```
### SelectAll()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Selects all the rows in the table view.</p>


```csharp
public void SelectAll()
```
### SelectByAttributes()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Shows the Select By Attributes GP tool..</p>


```csharp
public void SelectByAttributes()
```
### SetActiveField(int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Sets the active field in the table view.</p>


```csharp
public void SetActiveField(int fieldIndex)
```
### SetActiveField(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Sets the active field in the table view.</p>


```csharp
public void SetActiveField(string fieldName)
```
### SetFieldOrderAsync(List&lt;string&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Sets the field order in the table view according to the specified set of field names.</p>


```csharp
public Task SetFieldOrderAsync(List<string> fieldNames)
```
### SetFrozenFieldsAsync(List&lt;string&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Sets the specified fields to be frozen in the table view.  Frozen fields are promoted to be the first visible fields in the table view
and stay visible as the table view is scrolled horizontally. A divider bar is placed between the frozen fields and the remaining fields
in the table. The specified list of fields are added to any existing fields that are already frozen.</p>


```csharp
public Task SetFrozenFieldsAsync(List<string> fieldNames)
```
### SetHiddenFields(List&lt;string&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Sets the specified fields to be hidden in the table view UI.  The specified list of fields are added to any existing fields that
are already hidden. To display all fields use <xref href="ArcGIS.Desktop.Mapping.TableView.ShowAllFields" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public void SetHiddenFields(List<string> fieldNames)
```
### SetSelectedFields(List&lt;string&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Sets the specified fields to be selected in the table view.</p>


```csharp
public void SetSelectedFields(List<string> fieldNames)
```
### SetViewMode(TableViewMode)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Sets the view mode of the table view.</p>


```csharp
public Task SetViewMode(TableViewMode viewMode)
```
### SetZoomLevel(int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Set the zoom level for the table view. The allowed values are 50 to 400.</p>


```csharp
public void SetZoomLevel(int zoomLevel)
```
### ShowAllFields()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Shows all fields on the table view.</p>


```csharp
public void ShowAllFields()
```
### ShowFieldAlias

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Gets and sets the current state of displaying the field alias.</p>


```csharp
public bool ShowFieldAlias { get; set; }
```
### ShowSubtypeDomainDescriptions

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Gets and sets the current state of displaying subtype and domain descriptions.</p>


```csharp
public bool ShowSubtypeDomainDescriptions { get; set; }
```
### SortAscending()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Sorts the values of the active field from lowest to highest.</p>


```csharp
public void SortAscending()
```
### SortAsync(IReadOnlyDictionary&lt;string, FieldSortInfo&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Sorts the attributes in the table view.</p>


```csharp
public Task<bool> SortAsync(IReadOnlyDictionary<string, FieldSortInfo> sortFields)
```
### SortDescending()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Sorts the values of the active field from highest to lowest.</p>


```csharp
public void SortDescending()
```
### SwitchHighlight()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Switch the current highlight of the table view.</p>


```csharp
public void SwitchHighlight()
```
### SwitchSelection()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Switch the current selection of the table view.</p>


```csharp
public void SwitchSelection()
```
### ToggleFieldAlias()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Toggles between the field name and alias on the column headers of the table view.</p>


```csharp
public void ToggleFieldAlias()
```
### ToggleRowHighlight()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Toggles the highlight of the active row of the table view.</p>


```csharp
public void ToggleRowHighlight()
```
### ToggleRowSelection()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Toggles the selection of the active row of the table view.</p>


```csharp
public void ToggleRowSelection()
```
### ToggleSubtypeDomainDescriptionsAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Toggles between the subtype and domain descriptions and codes in the columns of the table view.</p>


```csharp
public Task ToggleSubtypeDomainDescriptionsAsync()
```
### ViewMode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Gets the view mode of the table view.</p>


```csharp
public TableViewMode ViewMode { get; }
```
### ZoomLevel

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Gets the zoom level for the table view.</p>


```csharp
public int ZoomLevel { get; }
```
### ZoomToHighlighted()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Zooms to the highlighted rows.</p>


```csharp
public void ZoomToHighlighted()
```
### ZoomToSelected()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TableView.yml" sourcestartlinenumber="1">Zooms to the selected rows in the table view.</p>


```csharp
public void ZoomToSelected()
```


