# ServiceConnectionProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.ServiceConnectionProperties.yml" sourcestartlinenumber="1">Represents the properties used to connect to an ArcGIS web service.</p>


## Object Signature

```csharp
public sealed class ServiceConnectionProperties : Connector
```


## Members

### ServiceConnectionProperties(Uri)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.ServiceConnectionProperties.yml" sourcestartlinenumber="1">Initializes a new instance of the <code>ServiceConnectionProperties</code> class.</p>


```csharp
public ServiceConnectionProperties(Uri serviceURL)
```
### Password

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.ServiceConnectionProperties.yml" sourcestartlinenumber="1">The password used to connect to the service.</p>


```csharp
public string Password { get; set; }
```
### URL

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.ServiceConnectionProperties.yml" sourcestartlinenumber="1">The service URL.</p>


```csharp
public Uri URL { get; }
```
### User

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.ServiceConnectionProperties.yml" sourcestartlinenumber="1">The user used to connect to the service.</p>


```csharp
public string User { get; set; }
```
### Version

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.ServiceConnectionProperties.yml" sourcestartlinenumber="1">Transactional version to connect to. Acceptable value is a string that represents a transaction version name.</p>


```csharp
public string Version { get; set; }
```


