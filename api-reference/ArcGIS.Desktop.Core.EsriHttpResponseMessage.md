# EsriHttpResponseMessage

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.EsriHttpResponseMessage.yml" sourcestartlinenumber="1">Provides a class representing HTTP response message.</p>


## Object Signature

```csharp
public class EsriHttpResponseMessage
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Core.EsriHttpResponseMessage.yml" sourcestartlinenumber="1">HTTP response messages are received by the client from the server after an HTTP request messages is sent.</p>


## Members

### EsriHttpResponseMessage()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.EsriHttpResponseMessage.yml" sourcestartlinenumber="1">Initializes a new instance of the EsriHttpResponseMessage class.</p>


```csharp
public EsriHttpResponseMessage()
```
### EsriHttpResponseMessage(long)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.EsriHttpResponseMessage.yml" sourcestartlinenumber="1">Initializes a new instance of the EsriHttpResponseMessage class with a specific StatusCode.</p>


```csharp
public EsriHttpResponseMessage(long status_code)
```
### Content

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EsriHttpResponseMessage.yml" sourcestartlinenumber="1">Gets or sets the content of a HTTP response message.</p>


```csharp
public HttpContent Content { get; set; }
```
### EnsureSuccessStatusCode()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.EsriHttpResponseMessage.yml" sourcestartlinenumber="1">Throws an exception if the IsSuccessStatusCode property for the HTTP response is false.</p>


```csharp
public EsriHttpResponseMessage EnsureSuccessStatusCode()
```
### Headers

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EsriHttpResponseMessage.yml" sourcestartlinenumber="1">Gets or sets the collection of HTTP response headers.</p>


```csharp
public HttpResponseHeaders Headers { get; set; }
```
### IsSuccessStatusCode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EsriHttpResponseMessage.yml" sourcestartlinenumber="1">Gets a value that indicates if the HTTP response was successful.</p>


```csharp
public bool IsSuccessStatusCode { get; }
```
### StatusCode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EsriHttpResponseMessage.yml" sourcestartlinenumber="1">Gets or sets the status code of the HTTP response.</p>


```csharp
public HttpStatusCode StatusCode { get; set; }
```


