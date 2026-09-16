# SubtypeGroupTable

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll


## Object Signature

```csharp
public sealed class SubtypeGroupTable : StandaloneTable, IMetadataInfo, IMetadataSource, IDisplayTable, ITableDefinitionQueries, IArcadeEvaluatorObject, IStandaloneTableContainer
```


## Members

### SubtypeGroupTable()

- Kind: constructor


```csharp
public SubtypeGroupTable()
```
### Add(StandaloneTable)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SubtypeGroupTable.yml" sourcestartlinenumber="1">Adds a table to the collection inside an exclusive lock.</p>


```csharp
public void Add(StandaloneTable table)
```
### FindStandaloneTable(int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SubtypeGroupTable.yml" sourcestartlinenumber="1">Finds tables by ID.</p>


```csharp
public StandaloneTable FindStandaloneTable(int tableID)
```
### FindStandaloneTable(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SubtypeGroupTable.yml" sourcestartlinenumber="1">Finds a StandaloneTable using a URI. Child group layers are also searched.</p>


```csharp
public StandaloneTable FindStandaloneTable(string tableURI)
```
### FindStandaloneTables(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SubtypeGroupTable.yml" sourcestartlinenumber="1">Finds StandaloneTables by name. Child group layers are also searched.</p>


```csharp
public IReadOnlyList<StandaloneTable> FindStandaloneTables(string name)
```
### GetSnapshot()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SubtypeGroupTable.yml" sourcestartlinenumber="1">Returns a read-only snapshot of the tables in the container.</p>


```csharp
public IReadOnlyList<StandaloneTable> GetSnapshot()
```
### Insert(IList&lt;int&gt;, IList&lt;StandaloneTable&gt;, IList&lt;int&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SubtypeGroupTable.yml" sourcestartlinenumber="1">Inserts several tables into the collection at once, inside an exclusive lock.</p>


```csharp
public void Insert(IList<int> indices, IList<StandaloneTable> tables, IList<int> currentIndices)
```
### Insert(int, StandaloneTable)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SubtypeGroupTable.yml" sourcestartlinenumber="1">Inserts a table into the collection at a specified position, inside an exclusive lock.</p>


```csharp
public void Insert(int index, StandaloneTable table)
```
### IsExpanded

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SubtypeGroupTable.yml" sourcestartlinenumber="1">Gets whether the group table is expanded or collapsed in the TOC.</p>


```csharp
public bool IsExpanded { get; }
```
### Move(IList&lt;StandaloneTable&gt;, IList&lt;int&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SubtypeGroupTable.yml" sourcestartlinenumber="1">Moves a series of tables inside an exclusive lock.</p>


```csharp
public void Move(IList<StandaloneTable> tables, IList<int> indices)
```
### Remove(IEnumerable&lt;StandaloneTable&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SubtypeGroupTable.yml" sourcestartlinenumber="1">Removes a series of tables from the collection inside an exclusive lock.</p>


```csharp
public void Remove(IEnumerable<StandaloneTable> tables)
```
### StandaloneTables

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SubtypeGroupTable.yml" sourcestartlinenumber="1">Gets a read-only collection of StandaloneTables from the container.</p>


```csharp
public ReadOnlyObservableCollection<StandaloneTable> StandaloneTables { get; }
```


