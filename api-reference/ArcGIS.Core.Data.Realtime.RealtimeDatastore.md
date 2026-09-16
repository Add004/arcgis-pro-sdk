# RealtimeDatastore

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Realtime.html">Realtime</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeDatastore.yml" sourcestartlinenumber="1">Represents a repository for real-time data.</p>


## Object Signature

```csharp
public sealed class RealtimeDatastore : Datastore, IDisposable
```


## Members

### RealtimeDatastore(RealtimeServiceConnectionProperties)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeDatastore.yml" sourcestartlinenumber="1">Opens a real-time datastore with a <xref href="ArcGIS.Core.Data.Realtime.RealtimeServiceConnectionProperties" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RealtimeDatastore(RealtimeServiceConnectionProperties connectionProperties)
```
### GetConnector()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeDatastore.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Connector" data-throw-if-not-resolved="false"></xref> associated with the currently opened realtime datastore.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public override Connector GetConnector()
```
### GetDefinition(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeDatastore.yml" sourcestartlinenumber="1">Gets a <xref href="ArcGIS.Core.Data.TableDefinition" data-throw-if-not-resolved="false"></xref> instance associated with <code class="paramref">name</code>
in the real-time data store.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public TableDefinition GetDefinition(string name)
```
### GetFilterSQLSyntax()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeDatastore.yml" sourcestartlinenumber="1">Gets the gateway to access information about the SQL syntax supported in the filter.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SQLSyntax GetFilterSQLSyntax()
```
### GetTableNames()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeDatastore.yml" sourcestartlinenumber="1">Gets the name of all the tables that exist in the currently opened realtime data store.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<string> GetTableNames()
```
### OpenTable(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeDatastore.yml" sourcestartlinenumber="1">Gets a <xref href="ArcGIS.Core.Data.Realtime.RealtimeTable" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Core.Data.Realtime.RealtimeFeatureClass" data-throw-if-not-resolved="false"></xref> instance associated with <code class="paramref">name</code>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Table OpenTable(string name)
```


