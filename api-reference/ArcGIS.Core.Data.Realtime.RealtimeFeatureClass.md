# RealtimeFeatureClass

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Realtime.html">Realtime</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeFeatureClass.yml" sourcestartlinenumber="1">Represents a real-time table with a spatial column.</p>


## Object Signature

```csharp
public sealed class RealtimeFeatureClass : FeatureClass, IDisposable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeFeatureClass.yml" sourcestartlinenumber="1">Streaming does not start automatically. Call <xref href="ArcGIS.Core.Data.Realtime.RealtimeFeatureClass.StartStreaming" data-throw-if-not-resolved="false"></xref> explicitly to start receiving feature stream.</p>


## Members

### GetDatastore()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeFeatureClass.yml" sourcestartlinenumber="1">Gets the data store of this dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RealtimeDatastore GetDatastore()
```
### GetDefinition()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeFeatureClass.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Realtime.RealtimeFeatureClassDefinition" data-throw-if-not-resolved="false"></xref> of this dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RealtimeFeatureClassDefinition GetDefinition()
```
### GetExpirationMaxAge()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeFeatureClass.yml" sourcestartlinenumber="1">Gets the expiration maximum age for features.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public TimeSpan GetExpirationMaxAge()
```
### GetExpirationMaxCount()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeFeatureClass.yml" sourcestartlinenumber="1">Gets the expiration maximum feature count.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public ulong GetExpirationMaxCount()
```
### GetExpirationMethod()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeFeatureClass.yml" sourcestartlinenumber="1">Gets the expiration method currently being used for this table.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RowExpirationMethod GetExpirationMethod()
```
### GetFilterWhereClause()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeFeatureClass.yml" sourcestartlinenumber="1">Gets the filter that is set to this table.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetFilterWhereClause()
```
### GetStreamingConnectionState()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeFeatureClass.yml" sourcestartlinenumber="1">Gets the streaming connection state.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public StreamingConnectionState GetStreamingConnectionState()
```
### SearchAndSubscribe(QueryFilter, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeFeatureClass.yml" sourcestartlinenumber="1">Searches the feature class for existing rows using the query criteria and then subscribes to receive row events.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RealtimeCursor SearchAndSubscribe(QueryFilter queryFilter, bool useRecyclingCursor)
```
### SetExpirationMaxAge(TimeSpan)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeFeatureClass.yml" sourcestartlinenumber="1">Sets the expiration maximum age for features.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetExpirationMaxAge(TimeSpan expirationMaxAge)
```
### SetExpirationMaxCount(ulong)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeFeatureClass.yml" sourcestartlinenumber="1">Gets the expiration maximum feature count.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetExpirationMaxCount(ulong expirationMaxCount)
```
### SetExpirationMethod(RowExpirationMethod)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeFeatureClass.yml" sourcestartlinenumber="1">Sets the expiration method to the table.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetExpirationMethod(RowExpirationMethod rowExpirationMethod)
```
### SetFilterWhereClause(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeFeatureClass.yml" sourcestartlinenumber="1">Sets a filter on this table so that only features matching this filter will be streamed by the service.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetFilterWhereClause(string filterWhereClause)
```
### StartStreaming()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeFeatureClass.yml" sourcestartlinenumber="1">Sets the feature class to a state where it starts listening to broadcasts from a real-time service
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void StartStreaming()
```
### StopStreaming()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeFeatureClass.yml" sourcestartlinenumber="1">Stops listening to streams from a real-time service.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void StopStreaming()
```
### Subscribe(QueryFilter, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeFeatureClass.yml" sourcestartlinenumber="1">Subscribe to receive row events. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RealtimeCursor Subscribe(QueryFilter queryFilter, bool useRecyclingCursor)
```
### Truncate()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeFeatureClass.yml" sourcestartlinenumber="1">Removes all features.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Truncate()
```


