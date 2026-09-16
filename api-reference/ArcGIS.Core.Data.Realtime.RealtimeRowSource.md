# RealtimeRowSource

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Realtime.html">Realtime</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeRowSource.yml" sourcestartlinenumber="1">Specifies the type of a <xref href="ArcGIS.Core.Data.Realtime.RealtimeRow" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public enum RealtimeRowSource
```


## Members

### EventDelete

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeRowSource.yml" sourcestartlinenumber="1">The <xref href="ArcGIS.Core.Data.Realtime.RealtimeRow" data-throw-if-not-resolved="false"></xref> was created as a result of a Delete event.</p>


```csharp
EventDelete = 2
```
### EventInsert

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeRowSource.yml" sourcestartlinenumber="1">The <xref href="ArcGIS.Core.Data.Realtime.RealtimeRow" data-throw-if-not-resolved="false"></xref> was created as a result of an Insert event.</p>


```csharp
EventInsert = 1
```
### PreExisting

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeRowSource.yml" sourcestartlinenumber="1">The <xref href="ArcGIS.Core.Data.Realtime.RealtimeRow" data-throw-if-not-resolved="false"></xref> represents a database row that already existed when the query operation was executed.</p>


```csharp
PreExisting = 3
```


