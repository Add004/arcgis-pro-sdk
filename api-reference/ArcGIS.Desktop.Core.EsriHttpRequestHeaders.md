# EsriHttpRequestHeaders

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.EsriHttpRequestHeaders.yml" sourcestartlinenumber="1">Represents the collection of Request Headers as defined in RFC 2616.</p>


## Object Signature

```csharp
public class EsriHttpRequestHeaders
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Core.EsriHttpRequestHeaders.yml" sourcestartlinenumber="1">HTTP headers provide information about the the http request.</p>


## Members

### EsriHttpRequestHeaders()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.EsriHttpRequestHeaders.yml" sourcestartlinenumber="1">Initializes a new instance of the EsriHttpRequestHeaders class.</p>


```csharp
public EsriHttpRequestHeaders()
```
### Accept

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EsriHttpRequestHeaders.yml" sourcestartlinenumber="1">Gets the collection of <xref href="System.Net.Http.Headers.MediaTypeHeaderValue" data-throw-if-not-resolved="false"></xref> values containing the list of acceptable media types for
the response. The default quality factor for each acceptable media type is &quot;q=1&quot;</p>


```csharp
public HttpHeaderValueCollection<MediaTypeWithQualityHeaderValue> Accept { get; }
```
### AcceptCharset

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EsriHttpRequestHeaders.yml" sourcestartlinenumber="1">Gets the collection of <xref href="System.Net.Http.Headers.StringWithQualityHeaderValue" data-throw-if-not-resolved="false"></xref> values indicating the quality value for the
acceptable character sets for the response. Default quality value is &quot;q=1&quot;</p>


```csharp
public HttpHeaderValueCollection<StringWithQualityHeaderValue> AcceptCharset { get; }
```
### AcceptEncoding

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EsriHttpRequestHeaders.yml" sourcestartlinenumber="1">Gets the collection of <xref href="System.Net.Http.Headers.StringWithQualityHeaderValue" data-throw-if-not-resolved="false"></xref> values indicating the quality value for
the acceptable content-codings for the response. Default quality value is &quot;q=1&quot;</p>


```csharp
public HttpHeaderValueCollection<StringWithQualityHeaderValue> AcceptEncoding { get; }
```
### AcceptLanguage

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EsriHttpRequestHeaders.yml" sourcestartlinenumber="1">Gets the collection of <xref href="System.Net.Http.Headers.StringWithQualityHeaderValue" data-throw-if-not-resolved="false"></xref> values indicating the quality value for the
acceptable set of natural languages for the response. Default quality value is &quot;q=1&quot;</p>


```csharp
public HttpHeaderValueCollection<StringWithQualityHeaderValue> AcceptLanguage { get; }
```
### CacheControl

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EsriHttpRequestHeaders.yml" sourcestartlinenumber="1">Gets or sets the caching behaviour for the response.</p>


```csharp
public CacheControlHeaderValue CacheControl { get; set; }
```
### Connection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EsriHttpRequestHeaders.yml" sourcestartlinenumber="1">Gets the value of the Connection header for the response</p>


```csharp
public HttpHeaderValueCollection<string> Connection { get; }
```
### Host

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EsriHttpRequestHeaders.yml" sourcestartlinenumber="1">Gets or sets Host header value to use in an HTTP request <i>independent from the request URI</i>. The Host property can consist of a
hostname and an optional port number.</p>


```csharp
public string Host { get; set; }
```
### Pragma

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EsriHttpRequestHeaders.yml" sourcestartlinenumber="1">Gets any optional behavior specified for the response.</p>


```csharp
public HttpHeaderValueCollection<NameValueHeaderValue> Pragma { get; }
```
### UserAgent

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.EsriHttpRequestHeaders.yml" sourcestartlinenumber="1">Gets the value of the User-agent HTTP header</p>


```csharp
public HttpHeaderValueCollection<ProductInfoHeaderValue> UserAgent { get; }
```


