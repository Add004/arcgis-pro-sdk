# IDisplayTable

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.IDisplayTable.yml" sourcestartlinenumber="1">Provides access to members to query and select features or rows, and access to underlying table.</p>


## Object Signature

```csharp
public interface IDisplayTable
```


## Members

### CanEditData()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IDisplayTable.yml" sourcestartlinenumber="1">Returns <code>true</code> if the data can be edited.  This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
bool CanEditData()
```
### ClearSelection()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IDisplayTable.yml" sourcestartlinenumber="1">Clears the current selection.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
void ClearSelection()
```
### DisplayExpressionInfo

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.IDisplayTable.yml" sourcestartlinenumber="1">Gets the display expression info.</p>


```csharp
CIMExpressionInfo DisplayExpressionInfo { get; }
```
### DisplayField

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.IDisplayTable.yml" sourcestartlinenumber="1">Gets the name of the attribute field that is used to identify each row or feature.</p>


```csharp
string DisplayField { get; }
```
### GetDisplayExpressions(IEnumerable&lt;long&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IDisplayTable.yml" sourcestartlinenumber="1">Gets the display expressions of the given set of objects.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
List<string> GetDisplayExpressions(IEnumerable<long> oids)
```
### GetFieldDescriptions()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IDisplayTable.yml" sourcestartlinenumber="1">Returns fields of a MapMember including joined fields, if any.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
List<FieldDescription> GetFieldDescriptions()
```
### GetSelection()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IDisplayTable.yml" sourcestartlinenumber="1">Gets the current selection of a MapMember.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
Selection GetSelection()
```
### GetTable()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IDisplayTable.yml" sourcestartlinenumber="1">Returns the underlying table or feature class.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
Table GetTable()
```
### IsEditable

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.IDisplayTable.yml" sourcestartlinenumber="1">Gets whether a MapMember is editable.</p>


```csharp
bool IsEditable { get; }
```
### IsSelectRelatedData

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.IDisplayTable.yml" sourcestartlinenumber="1">Gets whether a MapMember is set to automatically select related data.</p>


```csharp
bool IsSelectRelatedData { get; }
```
### IsSelectable

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.IDisplayTable.yml" sourcestartlinenumber="1">Gets whether a MapMember is selectable.</p>


```csharp
bool IsSelectable { get; }
```
### Search(QueryFilter, TimeRange, RangeExtent, CIMFloorFilterSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IDisplayTable.yml" sourcestartlinenumber="1">Executes a query to the underlying data source and returns rows matching the search criteria.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
RowCursor Search(QueryFilter queryFilter = null, TimeRange time = null, RangeExtent range = null, CIMFloorFilterSettings floor = null)
```
### SearchEx(QueryFilter, TimeRange, RangeExtent, CIMFloorFilterSettings, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IDisplayTable.yml" sourcestartlinenumber="1">Executes a query to the underlying data source and returns rows matching the search criteria.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
RowCursor SearchEx(QueryFilter queryFilter = null, TimeRange time = null, RangeExtent range = null, CIMFloorFilterSettings floor = null, bool useRecyclingCursor = true)
```
### Select(QueryFilter, SelectionCombinationMethod, TimeRange, RangeExtent, CIMFloorFilterSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IDisplayTable.yml" sourcestartlinenumber="1">Selects rows based upon the specified criteria and combination method.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
Selection Select(QueryFilter queryFilter = null, SelectionCombinationMethod method = SelectionCombinationMethod.New, TimeRange time = null, RangeExtent range = null, CIMFloorFilterSettings floor = null)
```
### SetDisplayExpressionInfo(CIMExpressionInfo)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IDisplayTable.yml" sourcestartlinenumber="1">Sets the display expression info with an arcade expression that will be used to identify features or rows. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
void SetDisplayExpressionInfo(CIMExpressionInfo displayExpressionInfo)
```
### SetDisplayField(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IDisplayTable.yml" sourcestartlinenumber="1">Sets the name of the attribute field that will be used to identify features or rows. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
void SetDisplayField(string displayField)
```
### SetEditable(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IDisplayTable.yml" sourcestartlinenumber="1">Enables or disables editing on a MapMember.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
void SetEditable(bool isEditable)
```
### SetFieldDescriptions(List&lt;FieldDescription&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IDisplayTable.yml" sourcestartlinenumber="1">Applies updates to the editable properties of fields.  This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
void SetFieldDescriptions(List<FieldDescription> updatedDescriptions)
```
### SetSelectRelatedData(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IDisplayTable.yml" sourcestartlinenumber="1">Toggles the SelectRelatedData of a MapMember.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
void SetSelectRelatedData(bool selectRelatedData)
```
### SetSelectable(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IDisplayTable.yml" sourcestartlinenumber="1">Toggles the selectability of a MapMember.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
void SetSelectable(bool isSelectable)
```


