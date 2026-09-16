# ITableDefinitionQueries

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.ITableDefinitionQueries.yml" sourcestartlinenumber="1">Defines required properties and methods for interacting with definition filters.</p>


## Object Signature

```csharp
public interface ITableDefinitionQueries
```


## Members

### ActiveDefinitionQuery

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ITableDefinitionQueries.yml" sourcestartlinenumber="1">Gets the active definition query.</p>


```csharp
DefinitionQuery ActiveDefinitionQuery { get; }
```
### DefinitionQueries

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ITableDefinitionQueries.yml" sourcestartlinenumber="1">Gets a list of all DefinitionQueries.</p>


```csharp
IReadOnlyList<DefinitionQuery> DefinitionQueries { get; }
```
### DefinitionQuery

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ITableDefinitionQueries.yml" sourcestartlinenumber="1">Gets the where clause of the active definition query.</p>


```csharp
string DefinitionQuery { get; }
```
### InsertDefinitionQueries(IEnumerable&lt;DefinitionQuery&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ITableDefinitionQueries.yml" sourcestartlinenumber="1">Insert a list of definition queries. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
void InsertDefinitionQueries(IEnumerable<DefinitionQuery> queries)
```
### InsertDefinitionQuery(DefinitionQuery, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ITableDefinitionQueries.yml" sourcestartlinenumber="1">Inserts a <xref href="ArcGIS.Desktop.Mapping.ITableDefinitionQueries.DefinitionQuery" data-throw-if-not-resolved="false"></xref>. If <code class="paramref">makeActive</code> is true, makes it the active definition query.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
void InsertDefinitionQuery(DefinitionQuery definitionQuery, bool makeActive = false)
```
### IsValidDefinitionQuery(DefinitionQuery)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ITableDefinitionQueries.yml" sourcestartlinenumber="1">Determines if the specified definitionQuery is valid.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
Task<bool> IsValidDefinitionQuery(DefinitionQuery definitionQuery)
```
### IsValidDefinitionQuery(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ITableDefinitionQueries.yml" sourcestartlinenumber="1">Determines if the specified SQL where clause has valid syntax.<br>
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
Task<bool> IsValidDefinitionQuery(string sql)
```
### RemoveActiveDefinitionQuery()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ITableDefinitionQueries.yml" sourcestartlinenumber="1">Removes the active definition query. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
void RemoveActiveDefinitionQuery()
```
### RemoveAllDefinitionQueries()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ITableDefinitionQueries.yml" sourcestartlinenumber="1">Remove all definition queries.  This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
void RemoveAllDefinitionQueries()
```
### RemoveDefinitionQueries(IEnumerable&lt;string&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ITableDefinitionQueries.yml" sourcestartlinenumber="1">Removes the definition queries specified by the list of names. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
void RemoveDefinitionQueries(IEnumerable<string> queryNames)
```
### RemoveDefinitionQuery(int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ITableDefinitionQueries.yml" sourcestartlinenumber="1">Removes the definition query at the specified index. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
void RemoveDefinitionQuery(int index)
```
### SetActiveDefinitionQuery(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ITableDefinitionQueries.yml" sourcestartlinenumber="1">Sets the definition query matching the specified <code class="paramref">queryName</code> to be the active definition query.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
void SetActiveDefinitionQuery(string queryName)
```
### SetDefinitionQuery(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ITableDefinitionQueries.yml" sourcestartlinenumber="1">Sets the where clause of the active definition query.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
DefinitionQuery SetDefinitionQuery(string whereClause)
```


