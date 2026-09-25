# RealtimeTableDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Realtime.html">Realtime</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeTableDefinition.yml" sourcestartlinenumber="1">Represents the schema and properties of a <xref href="ArcGIS.Core.Data.Realtime.RealtimeTable" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public abstract class RealtimeTableDefinition : TableDefinition, IDisposable
```


## Members

### GetSupportedFilterFields()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeTableDefinition.yml" sourcestartlinenumber="1">Gets a list of fields that can be used in defintion query <xref href="ArcGIS.Core.Data.Realtime.RealtimeTable.SetFilterWhereClause(System.String)" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<string> GetSupportedFilterFields()
```
### GetTrackIDField()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeTableDefinition.yml" sourcestartlinenumber="1">Gets the track ID field name.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetTrackIDField()
```
### GetTrackType()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeTableDefinition.yml" sourcestartlinenumber="1">Gets a value indicating the nature of the tracking data present in this table.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public TrackType GetTrackType()
```
### HasTrackIDField()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeTableDefinition.yml" sourcestartlinenumber="1">Gets a value indicating whether this table has a field whose values are used to group rows in tracks.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool HasTrackIDField()
```


