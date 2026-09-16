# Database

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Database.yml" sourcestartlinenumber="1">Represents the gateway to connect to a relational database, which may or may not be a geodatabase (please see remarks).<br>
Given a specific <xref href="ArcGIS.Core.Data.QueryDescription" data-throw-if-not-resolved="false"></xref> object, the <b>Database</b> data store can be used to
open a <b>single</b> database table, or a <b>query layer</b> that is created from one or more database tables.</p>


## Object Signature

```csharp
public sealed class Database : Datastore, IDisposable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.Database.yml" sourcestartlinenumber="1">Although the <b>Database</b> data store can be used to access a geodatabase, this practice is not recommended.  Instead,
<xref href="ArcGIS.Core.Data.Geodatabase" data-throw-if-not-resolved="false"></xref> should be used instead.  The main reason is that internally, the implementation
of a <b>Geodatabase</b> table is different from that of a <b>Database</b>.  There are certain operations in this class
that require the table to be originally opened from a <b>Database</b>.  If this precondition is not met, there will be a<br>
runtime exception (<xref href="ArcGIS.Core.Data.Database.GetQueryDescription(ArcGIS.Core.Data.Table)" data-throw-if-not-resolved="false"></xref>).</p>


## Members

### Database(DatabaseConnectionFile)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.Database.yml" sourcestartlinenumber="1">Opens an enterprise database with the specified connection file.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Database(DatabaseConnectionFile databaseConnectionFile)
```
### Database(DatabaseConnectionProperties)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.Database.yml" sourcestartlinenumber="1">Opens an enterprise database with the specified connection properties.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Database(DatabaseConnectionProperties databaseConnectionProperties)
```
### Database(SQLiteConnectionPath)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.Database.yml" sourcestartlinenumber="1">Opens a SQLite database with the specified connection path.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Database(SQLiteConnectionPath sqliteConnectionPath)
```
### CalculateExtent(FeatureClass)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Database.yml" sourcestartlinenumber="1">Calculates the extent for the spatial <b>single table</b> or <b>query layer</b> specified by <code class="paramref">featureClass</code>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void CalculateExtent(FeatureClass featureClass)
```
### GetConnector()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Database.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.DatabaseConnectionProperties" data-throw-if-not-resolved="false"></xref> associated with the currently opened database.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public override Connector GetConnector()
```
### GetDefinition(QueryDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Database.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.TableDefinition" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Core.Data.FeatureClassDefinition" data-throw-if-not-resolved="false"></xref> (if
<xref href="ArcGIS.Core.Data.QueryDescription.IsSpatialQuery" data-throw-if-not-resolved="false"></xref> in <code class="paramref">queryDescription</code> returns <b>true</b>) whose
<xref href="ArcGIS.Core.Data.Table" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Core.Data.FeatureClass" data-throw-if-not-resolved="false"></xref> is associated with <code class="paramref">queryDescription</code>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public TableDefinition GetDefinition(QueryDescription queryDescription)
```
### GetQueryDescription(Table)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Database.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.QueryDescription" data-throw-if-not-resolved="false"></xref> object associated with <code class="paramref">table</code>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public QueryDescription GetQueryDescription(Table table)
```
### GetQueryDescription(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Database.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.QueryDescription" data-throw-if-not-resolved="false"></xref> object associated with the single (i.e., standalone) table specified by
<code class="paramref">tableName</code> in the currently opened database.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public QueryDescription GetQueryDescription(string tableName)
```
### GetQueryDescription(string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Database.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.QueryDescription" data-throw-if-not-resolved="false"></xref> object associated with the <b>query layer</b> that is created from one or<br>
more database table(s) as specified by <code class="paramref">queryStatement</code>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public QueryDescription GetQueryDescription(string queryStatement, string queryLayerName)
```
### GetTableNames()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Database.yml" sourcestartlinenumber="1">Gets the fully qualified name of all the tables that exist in the currently opened database.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<string> GetTableNames()
```
### OpenTable(QueryDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Database.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Table" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Core.Data.FeatureClass" data-throw-if-not-resolved="false"></xref> (if it is spatially enabled) associated
with <code class="paramref">queryDescription</code>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Table OpenTable(QueryDescription queryDescription)
```


