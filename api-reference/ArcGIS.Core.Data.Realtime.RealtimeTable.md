# RealtimeTable

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Realtime.html">Realtime</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeTable.yml" sourcestartlinenumber="1">Represents a real-time table.</p>


## Object Signature

```csharp
public sealed class RealtimeTable : Table, IDisposable
```


## Members

### GetDatastore()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeTable.yml" sourcestartlinenumber="1">Gets the data store of this dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RealtimeDatastore GetDatastore()
```
### GetDefinition()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeTable.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Realtime.RealtimeTableDefinition" data-throw-if-not-resolved="false"></xref> of this dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RealtimeTableDefinition GetDefinition()
```
### GetExpirationMaxAge()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeTable.yml" sourcestartlinenumber="1">Gets the expiration maximum age for rows.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public TimeSpan GetExpirationMaxAge()
```
### GetExpirationMaxCount()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeTable.yml" sourcestartlinenumber="1">Gets the expiration maximum row count.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public ulong GetExpirationMaxCount()
```
### GetExpirationMethod()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeTable.yml" sourcestartlinenumber="1">Gets the expiration method currently being used for this table.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RowExpirationMethod GetExpirationMethod()
```
### GetFilterWhereClause()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeTable.yml" sourcestartlinenumber="1">Gets the filter that is set to this table.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetFilterWhereClause()
```
### GetStreamingConnectionState()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeTable.yml" sourcestartlinenumber="1">Gets the streaming connection state.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public StreamingConnectionState GetStreamingConnectionState()
```
### SearchAndSubscribe(QueryFilter, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeTable.yml" sourcestartlinenumber="1">Searches the table for existing rows using the query criteria and then subscribes to receive row events.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RealtimeCursor SearchAndSubscribe(QueryFilter queryFilter, bool useRecyclingCursor)
```
### SetExpirationMaxAge(TimeSpan)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeTable.yml" sourcestartlinenumber="1">Sets the expiration maximum age for rows.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetExpirationMaxAge(TimeSpan expirationMaxAge)
```
### SetExpirationMaxCount(ulong)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeTable.yml" sourcestartlinenumber="1">Gets the expiration maximum row count.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetExpirationMaxCount(ulong expirationMaxCount)
```
### SetExpirationMethod(RowExpirationMethod)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeTable.yml" sourcestartlinenumber="1">Sets the expiration method to the table.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetExpirationMethod(RowExpirationMethod rowExpirationMethod)
```
### SetFilterWhereClause(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeTable.yml" sourcestartlinenumber="1">Sets a filter this table so that only rows matching this filter will be streamed by the service.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetFilterWhereClause(string filterWhereClause)
```
### StartStreaming()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeTable.yml" sourcestartlinenumber="1">Sets the row class to a state where it starts listening to broadcasts from a real-time service
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void StartStreaming()
```
### StopStreaming()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeTable.yml" sourcestartlinenumber="1">Stops listening to streams from a real-time service.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void StopStreaming()
```
### Subscribe(QueryFilter, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeTable.yml" sourcestartlinenumber="1">Subscribe to receive row events. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RealtimeCursor Subscribe(QueryFilter queryFilter, bool useRecyclingCursor)
```
### Truncate()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeTable.yml" sourcestartlinenumber="1">Removes all rows.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Truncate()
```


