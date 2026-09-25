# CDWInterface

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Catalog.html">Catalog</a>.<a class="xref" href="ArcGIS.Desktop.Catalog.DatabaseConnections.html">DatabaseConnections</a>
- Assembly: ArcGIS.Desktop.Catalog.dll


## Object Signature

```csharp
public class CDWInterface : ViewModelBase, ICDWInterface
```


## Members

### CDWInterface()

- Kind: constructor


```csharp
public CDWInterface()
```
### AuthenticationType

- Kind: property


```csharp
public int AuthenticationType { get; set; }
```
### BigQueryProjectIDs

- Kind: property


```csharp
public ObservableCollection<string> BigQueryProjectIDs { get; set; }
```
### GetDatasetsList()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Catalog.DatabaseConnections.CDWInterface.yml" sourcestartlinenumber="1">Get Google BigQuery dataset list</p>


```csharp
public ObservableCollection<string> GetDatasetsList()
```
### GetProjectList()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Catalog.DatabaseConnections.CDWInterface.yml" sourcestartlinenumber="1">Get Google BigQuery project list</p>


```csharp
public ObservableCollection<string> GetProjectList()
```
### LoadFromParquetFile(string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Catalog.DatabaseConnections.CDWInterface.yml" sourcestartlinenumber="1">Load Parquet file to Google BigQuery database</p>


```csharp
public int LoadFromParquetFile(string tableName, string tablePath)
```
### SetClient(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Catalog.DatabaseConnections.CDWInterface.yml" sourcestartlinenumber="1">Set Google Client with or without projectid for C# API</p>


```csharp
public void SetClient(string projectId = null)
```
### SetCredential(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Catalog.DatabaseConnections.CDWInterface.yml" sourcestartlinenumber="1">Set Google Credential for C# client API</p>


```csharp
public void SetCredential(string value)
```
### SetDefaultDataset(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Catalog.DatabaseConnections.CDWInterface.yml" sourcestartlinenumber="1">Set default dataset name</p>


```csharp
public void SetDefaultDataset(string defaultDataset = null)
```
### SetRefreshToken(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Catalog.DatabaseConnections.CDWInterface.yml" sourcestartlinenumber="1">Set default dataset name</p>


```csharp
public void SetRefreshToken(string defaultDataset = null)
```
### SetUserCredentialFromRefreshToken(string, string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Catalog.DatabaseConnections.CDWInterface.yml" sourcestartlinenumber="1">Set Google user credential using OAuth refresh token flow</p>


```csharp
public string SetUserCredentialFromRefreshToken(string refreshToken, string clientId, string clientSecret)
```


