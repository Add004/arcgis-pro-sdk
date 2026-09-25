# ServerConnectionManager

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Catalog.html">Catalog</a>
- Assembly: ArcGIS.Desktop.Catalog.dll

<p sourcefile="api/ArcGIS.Desktop.Catalog.ServerConnectionManager.yml" sourcestartlinenumber="1">This utility class is used to create or manage server connections.</p>


## Object Signature

```csharp
public class ServerConnectionManager
```


## Members

### ServerConnectionManager()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Catalog.ServerConnectionManager.yml" sourcestartlinenumber="1">This utility class is used to create or manage server connections.</p>


```csharp
public ServerConnectionManager()
```
### CreateAGSServerConnectionFile(string, string, string, string, bool, bool, ConnectionMode)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Catalog.ServerConnectionManager.yml" sourcestartlinenumber="1">Creates a new ArcGIS Server connection file. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static Item CreateAGSServerConnectionFile(string agsFilePath, string serverUrl, string userName = "", string password = "", bool saveToWCM = true, bool saveToFile = false, ConnectionMode connMode = 0)
```


