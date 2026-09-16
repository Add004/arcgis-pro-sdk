# ISharingModule

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll


## Object Signature

```csharp
public interface ISharingModule
```


## Members

### CreateSharingSessionAsync(bool)

- Kind: method


```csharp
Task<bool> CreateSharingSessionAsync(bool cacheActiveSharingSession)
```
### DoesServerItemExistAsync(string, string, string, int, string, string, string, string)

- Kind: method


```csharp
Task<bool> DoesServerItemExistAsync(string name = "", string title = "", string folder = "", int itemType = 0, string serviceSubType = "", string itemID = "", string createDate = "", string accessAndSecurity = "")
```
### GetPortalFoldersAsync(int, Progressor, int)

- Kind: method


```csharp
Task<string[]> GetPortalFoldersAsync(int repositoryID, Progressor progressor, int connectionID = -1)
```
### GetServerValueAsync(int, string, string, string, bool, Progressor)

- Kind: method


```csharp
Task<object> GetServerValueAsync(int repositoryID, string connectionID, string valueName, string categoryName, bool useCache, Progressor progressor = null)
```
### GetSharingUtilities()

- Kind: method


```csharp
ISharingUtilities GetSharingUtilities()
```
### GetUniqueNameAsync(string, string, int)

- Kind: method


```csharp
Task<string> GetUniqueNameAsync(string rootName = "", string folder = "", int itemType = 0)
```
### SetCachedSharingSessionToActive()

- Kind: method


```csharp
bool SetCachedSharingSessionToActive()
```
### UpdatePortalConnectionsAsync()

- Kind: method


```csharp
Task UpdatePortalConnectionsAsync()
```


