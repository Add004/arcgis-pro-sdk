# Datastore

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Datastore.yml" sourcestartlinenumber="1">Represents a data repository.</p>


## Object Signature

```csharp
public abstract class Datastore : CoreObjectsBase, IDisposable
```


## Members

### AreDatastorePropertiesSupported()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Datastore.yml" sourcestartlinenumber="1">Gets a value indicating whether this datastore supports datastore properties.</p>


```csharp
public bool AreDatastorePropertiesSupported()
```
### GetConnectionString()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Datastore.yml" sourcestartlinenumber="1">Gets the connection string associated with the currently opened data store (e.g., an enterprise geodatabase).
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetConnectionString()
```
### GetConnector()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Datastore.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Connector" data-throw-if-not-resolved="false"></xref> associated with the currently opened data store.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public abstract Connector GetConnector()
```
### GetDatastoreProperties()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Datastore.yml" sourcestartlinenumber="1">Gets the datastore properties of the datastore.</p>


```csharp
public DatastoreProperties GetDatastoreProperties()
```
### GetPath()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Datastore.yml" sourcestartlinenumber="1">Gets the path to the currently opened data store (e.g., an enterprise geodatabase .sde connection file).
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Uri GetPath()
```
### GetSQLSyntax()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Datastore.yml" sourcestartlinenumber="1">Gets the gateway to access information about the SQL syntax and other functionality supported by this <xref href="ArcGIS.Core.Data.Datastore" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SQLSyntax GetSQLSyntax()
```
### HasEdits()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Datastore.yml" sourcestartlinenumber="1">Determines whether the currently opened data store (e.g., an enterprise geodatabase) has any pending edits which have not been saved.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool HasEdits()
```


