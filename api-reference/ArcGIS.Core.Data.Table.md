# Table

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Table.yml" sourcestartlinenumber="1">Represents a table from the geodatabase.</p>


## Object Signature

```csharp
public class Table : Dataset, IDisposable
```


## Members

### CalculateStatistics(TableStatisticsDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Table.yml" sourcestartlinenumber="1">Performs common statistics functions on one or more fields in this table or feature class.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<TableStatisticsResult> CalculateStatistics(TableStatisticsDescription tableStatisticsDescription)
```
### CreateInsertCursor()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Table.yml" sourcestartlinenumber="1">Creates an <xref href="ArcGIS.Core.Data.InsertCursor" data-throw-if-not-resolved="false"></xref> instance in memory.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public InsertCursor CreateInsertCursor()
```
### CreateRow(RowBuffer)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Table.yml" sourcestartlinenumber="1">Creates a new row in the table with a system assigned object ID.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Row CreateRow(RowBuffer rowBuffer)
```
### CreateRowBuffer()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Table.yml" sourcestartlinenumber="1">Creates a new row buffer instance in memory.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RowBuffer CreateRowBuffer()
```
### CreateRowBuffer(Row)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Table.yml" sourcestartlinenumber="1">Creates a new row buffer instance in memory.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RowBuffer CreateRowBuffer(Row row)
```
### CreateRowBuffer(Subtype)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Table.yml" sourcestartlinenumber="1">Creates a new row buffer instance in memory.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RowBuffer CreateRowBuffer(Subtype subtype)
```
### CreateUpdateCursor(QueryFilter, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Table.yml" sourcestartlinenumber="1">Creates an <xref href="ArcGIS.Core.Data.UpdateCursor" data-throw-if-not-resolved="false"></xref> instance in memory.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public UpdateCursor CreateUpdateCursor(QueryFilter queryFilter, bool useRecyclingCursor)
```
### DeleteRows(QueryFilter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Table.yml" sourcestartlinenumber="1">Deletes the rows in the database selected by the specified query.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void DeleteRows(QueryFilter queryFilter)
```
### Differences(Table, DifferenceType, QueryFilter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Table.yml" sourcestartlinenumber="1">Gets a <xref href="ArcGIS.Core.Data.DifferenceCursor" data-throw-if-not-resolved="false"></xref> that can be used to retrieve rows based on the specified <code class="paramref">differenceType</code>.
Differences can be obtained for transactional, multi-branch or historical versions.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public DifferenceCursor Differences(Table targetTable, DifferenceType differenceType, QueryFilter queryFilter = null)
```
### Differences(Table, DifferenceType, QueryFilter, ServiceSynchronizationType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Table.yml" sourcestartlinenumber="1">Gets a <xref href="ArcGIS.Core.Data.DifferenceCursor" data-throw-if-not-resolved="false"></xref> that can be used to retrieve rows based on the specified <code class="paramref">differenceType</code>.
Differences can be obtained for transactional, multi-branch or historical versions.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public DifferenceCursor Differences(Table targetTable, DifferenceType differenceType, QueryFilter queryFilter, ServiceSynchronizationType serviceSynchronizationType)
```
### GetArchiveTable()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Table.yml" sourcestartlinenumber="1">Gets the archive table associated with this table or feature class if it is archived-enabled.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Table GetArchiveTable()
```
### GetContingentValues(RowBuffer, string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Table.yml" sourcestartlinenumber="1">Gets the possible contingent values for the given field name based on the values of the row buffer.</p>


```csharp
public IReadOnlyDictionary<FieldGroup, IReadOnlyList<ContingentValue>> GetContingentValues(RowBuffer rowBuffer, string fieldName)
```
### GetControllerDatasets()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Table.yml" sourcestartlinenumber="1">Gets a <xref href="System.Collections.Generic.IReadOnlyList%601" data-throw-if-not-resolved="false"></xref> of controller datasets of a specific <xref href="ArcGIS.Core.Data.Dataset" data-throw-if-not-resolved="false"></xref> type
that this table or feature class participates in.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<Dataset> GetControllerDatasets()
```
### GetCount()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Table.yml" sourcestartlinenumber="1">Gets the count of how many rows are currently in this <xref href="ArcGIS.Core.Data.Table" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public long GetCount()
```
### GetCount(QueryFilter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Table.yml" sourcestartlinenumber="1">Gets the count of how many rows are currently in this <xref href="ArcGIS.Core.Data.Table" data-throw-if-not-resolved="false"></xref> that satisfy the criteria set
in the <code class="paramref">queryFilter</code>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public long GetCount(QueryFilter queryFilter)
```
### GetDefinition()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Table.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.TableDefinition" data-throw-if-not-resolved="false"></xref> of this dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public TableDefinition GetDefinition()
```
### GetID()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Table.yml" sourcestartlinenumber="1">Gets the ID associated with this table.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public long GetID()
```
### GetJoin()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Table.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Join" data-throw-if-not-resolved="false"></xref> object from which this <code>joined table</code> was created.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Join GetJoin()
```
### IsArchiveEnabled()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Table.yml" sourcestartlinenumber="1">Gets a value indicating whether this table is archive-enabled.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool IsArchiveEnabled()
```
### IsAttachmentEnabled()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Table.yml" sourcestartlinenumber="1">Gets a value indicating whether this table supports attachments.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool IsAttachmentEnabled()
```
### IsControllerDatasetSupported()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Table.yml" sourcestartlinenumber="1">Gets a value indicating whether this <code>Table</code> supports the concept of controller datasets.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool IsControllerDatasetSupported()
```
### IsJoinedTable()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Table.yml" sourcestartlinenumber="1">Gets a value indicating whether this <code>Table</code> was obtained as a result of joining a <xref href="ArcGIS.Core.Data.Table" data-throw-if-not-resolved="false"></xref> or a
<xref href="ArcGIS.Core.Data.FeatureClass" data-throw-if-not-resolved="false"></xref> with another <xref href="ArcGIS.Core.Data.Table" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Core.Data.FeatureClass" data-throw-if-not-resolved="false"></xref>
from the same or different <xref href="ArcGIS.Core.Data.Datastore" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool IsJoinedTable()
```
### RelateTo(Table, VirtualRelationshipClassDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Table.yml" sourcestartlinenumber="1">Creates a <b>virtual</b> relationship class with the current table as the origin table/feature class and the <code class="paramref">destinationTable</code>
as the destination table/feature class.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RelationshipClass RelateTo(Table destinationTable, VirtualRelationshipClassDescription description)
```
### Search(QueryFilter, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Table.yml" sourcestartlinenumber="1">Searches and retrieves specific rows in this <xref href="ArcGIS.Core.Data.Table" data-throw-if-not-resolved="false"></xref> that satisfy the criteria set in the <code class="paramref">queryFilter</code>.
If no query filter is set, all rows will be retrieved.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RowCursor Search(QueryFilter queryFilter = null, bool useRecyclingCursor = true)
```
### Select(QueryFilter, SelectionType, SelectionOption)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Table.yml" sourcestartlinenumber="1">Creates a selection of specific rows in this <xref href="ArcGIS.Core.Data.Table" data-throw-if-not-resolved="false"></xref> that satisfy the criteria set in the <code class="paramref">queryFilter</code>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Selection Select(QueryFilter queryFilter, SelectionType selectionType, SelectionOption selectionOption)
```
### Sort(TableSortDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Table.yml" sourcestartlinenumber="1">Sorts data from this table or feature class.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RowCursor Sort(TableSortDescription tableSortDescription)
```
### Type

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Table.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.DatasetType" data-throw-if-not-resolved="false"></xref> of this derived dataset.</p>


```csharp
public override DatasetType Type { get; }
```
### Validate(QueryFilter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Table.yml" sourcestartlinenumber="1">Indicates whether the row(s) in <code class="paramref">filter</code> is violating any rules.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyDictionary<long, string> Validate(QueryFilter filter)
```
### Validate(Selection)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Table.yml" sourcestartlinenumber="1">Indicates whether the row(s) in <code class="paramref">selection</code> is violating any rules.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyDictionary<long, string> Validate(Selection selection)
```
### Validate(IEnumerable&lt;Row&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Table.yml" sourcestartlinenumber="1">Indicates whether the row(s) in <code class="paramref">rows</code> is violating any rules.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyDictionary<long, string> Validate(IEnumerable<Row> rows)
```
### ValidateContingencies(RowBuffer)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Table.yml" sourcestartlinenumber="1">Validate contingency constraints to distinguish between valid and invalid contingencies.</p>


```csharp
public ContingencyValidationResult ValidateContingencies(RowBuffer rowBuffer)
```


