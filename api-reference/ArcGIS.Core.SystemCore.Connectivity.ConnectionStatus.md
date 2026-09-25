# Connectivity.ConnectionStatus

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.SystemCore.html">SystemCore</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.SystemCore.Connectivity.ConnectionStatus.yml" sourcestartlinenumber="1">Set of values indicating connection status.  See <xref href="ArcGIS.Core.SystemCore.Connectivity.GetInternetConnectionStatus(System.Int32)" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public enum Connectivity.ConnectionStatus
```


## Members

### statusDisconnected

- Kind: field

<p sourcefile="api/ArcGIS.Core.SystemCore.Connectivity.ConnectionStatus.yml" sourcestartlinenumber="1">No connection.  Includes lack of phyical connection or airplane mode engaged.</p>


```csharp
statusDisconnected = 0
```
### statusPrivate

- Kind: field

<p sourcefile="api/ArcGIS.Core.SystemCore.Connectivity.ConnectionStatus.yml" sourcestartlinenumber="1">Connected, but without access to external internet</p>


```csharp
statusPrivate = 1
```
### statusPublic

- Kind: field

<p sourcefile="api/ArcGIS.Core.SystemCore.Connectivity.ConnectionStatus.yml" sourcestartlinenumber="1">Connected to the public internet</p>


```csharp
statusPublic = 2
```


