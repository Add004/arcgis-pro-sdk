# Selection

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Selection.yml" sourcestartlinenumber="1">Represents a selection of rows based on IDs or global IDs from a geodatabase table.</p>


## Object Signature

```csharp
public sealed class Selection : CoreObjectsBase, IDisposable
```


## Members

### Add(IEnumerable&lt;Guid&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Selection.yml" sourcestartlinenumber="1">Adds a list of rows by global IDs to the selection. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Add(IEnumerable<Guid> globalIDs)
```
### Add(IEnumerable&lt;long&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Selection.yml" sourcestartlinenumber="1">Adds a list of rows by object IDs to the selection. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Add(IEnumerable<long> objectIDs)
```
### Combine(Selection, SetOperation)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Selection.yml" sourcestartlinenumber="1">Combines this selection with another selection using the specified <xref href="ArcGIS.Core.Data.SetOperation" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Selection Combine(Selection otherSelection, SetOperation setOperation)
```
### GetCount()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Selection.yml" sourcestartlinenumber="1">Gets the count of how many items are currently contained in the selection.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public long GetCount()
```
### GetGlobalIDs()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Selection.yml" sourcestartlinenumber="1">Gets a <xref href="System.Collections.Generic.IReadOnlyList%601" data-throw-if-not-resolved="false"></xref> of currently selected global IDs.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<Guid> GetGlobalIDs()
```
### GetObjectIDs()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Selection.yml" sourcestartlinenumber="1">Gets a <xref href="System.Collections.Generic.IReadOnlyList%601" data-throw-if-not-resolved="false"></xref> of currently selected object IDs.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<long> GetObjectIDs()
```
### Remove(IEnumerable&lt;Guid&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Selection.yml" sourcestartlinenumber="1">Removes a list of rows from the selection based on global IDs. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Remove(IEnumerable<Guid> globalIDs)
```
### Remove(IEnumerable&lt;long&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Selection.yml" sourcestartlinenumber="1">Removes a list of rows from the selection based on object IDs. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Remove(IEnumerable<long> objectIDs)
```
### Search(QueryFilter, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Selection.yml" sourcestartlinenumber="1">Search and retrieve specific rows in this <xref href="ArcGIS.Core.Data.Selection" data-throw-if-not-resolved="false"></xref> that satisfy the criteria set in the <code class="paramref">queryFilter</code>.
If no query filter is set, all rows will be retrieved. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RowCursor Search(QueryFilter queryFilter = null, bool useRecyclingCursor = true)
```
### Select(QueryFilter, SelectionOption)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Selection.yml" sourcestartlinenumber="1">Creates a selection of specific rows in this <xref href="ArcGIS.Core.Data.Selection" data-throw-if-not-resolved="false"></xref> that satisfy the criteria set in the <code class="paramref">queryFilter</code>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Selection Select(QueryFilter queryFilter = null, SelectionOption selectionOption = SelectionOption.Normal)
```
### SelectionType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Selection.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.SelectionType" data-throw-if-not-resolved="false"></xref> of this instance of selection.</p>


```csharp
public SelectionType SelectionType { get; }
```


