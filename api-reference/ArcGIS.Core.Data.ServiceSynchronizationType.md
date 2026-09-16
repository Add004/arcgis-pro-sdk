# ServiceSynchronizationType

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.ServiceSynchronizationType.yml" sourcestartlinenumber="1">Specifies which implementation of the service endpoint to call.</p>


## Object Signature

```csharp
public enum ServiceSynchronizationType
```


## Members

### Asynchronous

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.ServiceSynchronizationType.yml" sourcestartlinenumber="1">Invokes the asynchronous implementation of the service endpoint.  This version is slower than the synchronous version but is not subject to a time-out on the client.</p>


```csharp
Asynchronous = 1
```
### Synchronous

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.ServiceSynchronizationType.yml" sourcestartlinenumber="1">Invokes the synchronous implementation of the service endpoint.  This version is faster but could result in a time-out on the client.</p>


```csharp
Synchronous = 0
```


