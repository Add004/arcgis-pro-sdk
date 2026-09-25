# EsriHttpClient

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.EsriHttpClient.yml" sourcestartlinenumber="1">Provides a class for perfroming HTTP communication with a resource identified by a Uniform Resource Identifier (URI).</p>


## Object Signature

```csharp
public class EsriHttpClient
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Core.EsriHttpClient.yml" sourcestartlinenumber="1">This class provides functions to communicate with the server/portal. If you are signed in, security tokens are automatically appended to HTTP requests and renewed when necessary.</p>


## Members

### EsriHttpClient()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.EsriHttpClient.yml" sourcestartlinenumber="1">Initializes a new instance of the EsriHttpClient class.</p>


```csharp
public EsriHttpClient()
```
### AllowRedirect

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EsriHttpClient.yml" sourcestartlinenumber="1">Gets or sets a value that indicates whether the request should follow redirection responses.</p>


```csharp
public bool AllowRedirect { get; set; }
```
### BaseAddress

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EsriHttpClient.yml" sourcestartlinenumber="1">Gets or sets the base address of the Uniform Resource Identifier (URI) of the Internet resource used when sending requests.</p>


```csharp
public Uri BaseAddress { get; set; }
```
### DefaultRequestHeaders

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EsriHttpClient.yml" sourcestartlinenumber="1">Gets or sets the headers which should be sent with each request.</p>


```csharp
public EsriHttpRequestHeaders DefaultRequestHeaders { get; set; }
```
### Delete(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.EsriHttpClient.yml" sourcestartlinenumber="1">Sends a DELETE request to the specified Uri as a synchronous operation.</p>


```csharp
public EsriHttpResponseMessage Delete(string requestUri)
```
### DeleteAsync(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.EsriHttpClient.yml" sourcestartlinenumber="1">Sends a DELETE request to the specified Uri as an asynchronous operation.</p>


```csharp
public Task<EsriHttpResponseMessage> DeleteAsync(string requestUri)
```
### Get(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.EsriHttpClient.yml" sourcestartlinenumber="1">Sends a GET request to the specified Uri as a synchronous operation.</p>


```csharp
public EsriHttpResponseMessage Get(string requestUri)
```
### GetAsFile(string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.EsriHttpClient.yml" sourcestartlinenumber="1">Downloads the resource as a file identified by the specified Uri synchronously.</p>


```csharp
public bool GetAsFile(string requestUri, string filePathToDownload)
```
### GetAsFileAsync(string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.EsriHttpClient.yml" sourcestartlinenumber="1">Downloads the resource as a file identified by the specified Uri asynchronously.</p>


```csharp
public Task<bool> GetAsFileAsync(string requestUri, string filePathToDownload)
```
### GetAsync(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.EsriHttpClient.yml" sourcestartlinenumber="1">Sends a GET request to the specified Uri as an asynchronous operation.</p>


```csharp
public Task<EsriHttpResponseMessage> GetAsync(string requestUri)
```
### MaxResponseContentBufferSizeInBytes

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EsriHttpClient.yml" sourcestartlinenumber="1">Gets or sets the maximum number of bytes to buffer when reading the response content.</p>


```csharp
public int MaxResponseContentBufferSizeInBytes { get; set; }
```
### OverwriteFile

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EsriHttpClient.yml" sourcestartlinenumber="1">Gets or sets a value that indicates if the file should be overwritten if already present while uploading/downloading files.</p>


```csharp
public bool OverwriteFile { get; set; }
```
### Post(string, HttpContent)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.EsriHttpClient.yml" sourcestartlinenumber="1">Sends a POST request to the specified Uri as a synchronous operation.</p>


```csharp
public EsriHttpResponseMessage Post(string requestUri, HttpContent content)
```
### PostAsync(string, HttpContent)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.EsriHttpClient.yml" sourcestartlinenumber="1">Sends a POST request to the specified Uri as an asynchronous operation.</p>


```csharp
public Task<EsriHttpResponseMessage> PostAsync(string requestUri, HttpContent content)
```
### Put(string, HttpContent)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.EsriHttpClient.yml" sourcestartlinenumber="1">Sends a PUT request to the specified Uri as a synchronous operation.</p>


```csharp
public EsriHttpResponseMessage Put(string requestUri, HttpContent content)
```
### PutAsync(string, HttpContent)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.EsriHttpClient.yml" sourcestartlinenumber="1">Sends a PUT request to the specified Uri as an asynchronous operation.</p>


```csharp
public Task<EsriHttpResponseMessage> PutAsync(string requestUri, HttpContent content)
```
### ShowDialogs

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EsriHttpClient.yml" sourcestartlinenumber="1">Gets or sets a value which controls if the APIs are allowed to pop-up any dialogs if required.</p>


```csharp
public bool ShowDialogs { get; set; }
```
### Timeout

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EsriHttpClient.yml" sourcestartlinenumber="1">Gets or sets the timespan to wait before the request times out.</p>


```csharp
public TimeSpan Timeout { get; set; }
```
### Upload(UploadDefinition)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.EsriHttpClient.yml" sourcestartlinenumber="1">Uploads an item to the specified Uri identifying a portal/server as a synchronous operation.</p>


```csharp
public Tuple<bool, string> Upload(UploadDefinition uploadDefinition)
```
### UploadAsync(UploadDefinition)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.EsriHttpClient.yml" sourcestartlinenumber="1">Uploads an item to the specified Uri in the upload definition asynchronously.</p>


```csharp
public Task<Tuple<bool, string>> UploadAsync(UploadDefinition uploadDefinition)
```


