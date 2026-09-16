# ICDWInterface

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Catalog.html">Catalog</a>.<a class="xref" href="ArcGIS.Desktop.Catalog.DatabaseConnections.html">DatabaseConnections</a>
- Assembly: ArcGIS.Desktop.Catalog.dll


## Object Signature

```csharp
public interface ICDWInterface
```


## Members

### GetDatasetsList()

- Kind: method


```csharp
ObservableCollection<string> GetDatasetsList()
```
### GetProjectList()

- Kind: method


```csharp
ObservableCollection<string> GetProjectList()
```
### SetClient(string)

- Kind: method


```csharp
void SetClient(string projectId = null)
```
### SetCredential(string)

- Kind: method


```csharp
void SetCredential(string value)
```
### SetUserCredentialFromRefreshToken(string, string, string)

- Kind: method


```csharp
string SetUserCredentialFromRefreshToken(string refreshToken, string clientId, string clientSecret)
```


