# ConnectionStatus

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.ConnectionStatus.yml" sourcestartlinenumber="1">Specifies MapMember's connection status.</p>


## Object Signature

```csharp
public enum ConnectionStatus
```


## Members

### Broken

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.ConnectionStatus.yml" sourcestartlinenumber="1">Failed to make the connection to the data source.</p>


```csharp
Broken = 2
```
### Connected

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.ConnectionStatus.yml" sourcestartlinenumber="1">Connected.</p>


```csharp
Connected = 1
```
### Disconnected

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.ConnectionStatus.yml" sourcestartlinenumber="1">Data source is valid, but currently disconnected. This can occur while the data source's schema is being modified by a geoprocessing tool.</p>


```csharp
Disconnected = 3
```
### Unattempted

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.ConnectionStatus.yml" sourcestartlinenumber="1">No attempt was made to connect.</p>


```csharp
Unattempted = 0
```


