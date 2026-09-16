# ArcGISServerConnectionFile

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.ArcGISServerConnectionFile.yml" sourcestartlinenumber="1">Represents the physical path to an ArcGIS Server connection file that ends with the <i>.ags</i> extension.</p>


## Object Signature

```csharp
public sealed class ArcGISServerConnectionFile : Connector
```


## Members

### ArcGISServerConnectionFile(Uri, string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.ArcGISServerConnectionFile.yml" sourcestartlinenumber="1">Initializes a new instance of the <code>ArcGISServerConnectionFile</code> class.</p>


```csharp
public ArcGISServerConnectionFile(Uri path, string serviceName)
```
### Path

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.ArcGISServerConnectionFile.yml" sourcestartlinenumber="1">The path to an ArcGIS Server connection file that ends with the <i>.ags</i> extension.</p>


```csharp
public Uri Path { get; }
```
### ServiceName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.ArcGISServerConnectionFile.yml" sourcestartlinenumber="1">The name of the service to connect to.</p>


```csharp
public string ServiceName { get; }
```


