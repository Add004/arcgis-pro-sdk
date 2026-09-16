# DatabaseClient

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.DatabaseClient.yml" sourcestartlinenumber="1">Provides a capability to execute tasks (e.g., a SQL statement) on a database management system associated with a geodatabase.</p>


## Object Signature

```csharp
public sealed class DatabaseClient
```


## Members

### ExecuteStatement(Geodatabase, string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DatabaseClient.yml" sourcestartlinenumber="1">Executes a specific <code class="paramref">statement</code> on the database management system specified by <code class="paramref">geodatabase</code>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void ExecuteStatement(Geodatabase geodatabase, string statement)
```
### GetDatabaseConnectionProperties(DatabaseConnectionFile)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DatabaseClient.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.DatabaseConnectionProperties" data-throw-if-not-resolved="false"></xref> corresponding to <code class="paramref">databaseConnectionFile</code>.</p>


```csharp
public static DatabaseConnectionProperties GetDatabaseConnectionProperties(DatabaseConnectionFile databaseConnectionFile)
```


