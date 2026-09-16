# StreamingConnectionState

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Realtime.html">Realtime</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Realtime.StreamingConnectionState.yml" sourcestartlinenumber="1">Specifies the state of the real-time (streaming) connection.</p>


## Object Signature

```csharp
public enum StreamingConnectionState
```


## Members

### Closed

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Realtime.StreamingConnectionState.yml" sourcestartlinenumber="1">Connection is closed, will not receive streaming features.</p>


```csharp
Closed = 5
```
### Connecting

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Realtime.StreamingConnectionState.yml" sourcestartlinenumber="1">Trying to connect.</p>


```csharp
Connecting = 2
```
### Failed

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Realtime.StreamingConnectionState.yml" sourcestartlinenumber="1">Failed to connect.</p>


```csharp
Failed = 4
```
### Open

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Realtime.StreamingConnectionState.yml" sourcestartlinenumber="1">Connection is open to receive streaming features.</p>


```csharp
Open = 3
```
### Ready

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Realtime.StreamingConnectionState.yml" sourcestartlinenumber="1">Ready to make connection.</p>


```csharp
Ready = 1
```
### Unknown

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Realtime.StreamingConnectionState.yml" sourcestartlinenumber="1">Unknown.</p>


```csharp
Unknown = 0
```


