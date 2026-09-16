# ISignOnHandler

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.SystemCore.html">SystemCore</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.SystemCore.ISignOnHandler.yml" sourcestartlinenumber="1">CoreHost applications implement an ISignOnHandler to receive callbacks from the system
whenever authentication is required for a portal or arcgis online.</p>


## Object Signature

```csharp
[Guid("FA6F071D-42DE-45B7-B89F-1DA18401C7C9")]
[InterfaceType(ComInterfaceType.InterfaceIsIUnknown)]
public interface ISignOnHandler
```

## Remarks

<p sourcefile="api/ArcGIS.Core.SystemCore.ISignOnHandler.yml" sourcestartlinenumber="1">The primary scenario for authentication is when a CoreHost application is
instantiating a connection to a federated Feature Service DB that is secured.</p>


## Members

### GenerateCredentials(ref SIGNONHANDLERINFO)

- Kind: method

<p sourcefile="api/ArcGIS.Core.SystemCore.ISignOnHandler.yml" sourcestartlinenumber="1">GenerateCredentials will be called by the system when authentication is required against
a portal or online. This method is for use in CoreHost applications only</p>


```csharp
void GenerateCredentials(ref SIGNONHANDLERINFO info)
```


