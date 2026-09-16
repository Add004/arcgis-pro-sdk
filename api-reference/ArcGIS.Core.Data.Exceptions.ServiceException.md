# ServiceException

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Exceptions.html">Exceptions</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Exceptions.ServiceException.yml" sourcestartlinenumber="1">Represents a base class for all service exceptions.</p>


## Object Signature

```csharp
public class ServiceException : GeodatabaseException, ISerializable
```


## Members

### ServiceException()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.Exceptions.ServiceException.yml" sourcestartlinenumber="1">Creates a new service exception.</p>


```csharp
public ServiceException()
```
### ServiceException(Exception)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.Exceptions.ServiceException.yml" sourcestartlinenumber="1">Creates a new service exception initialized with the input parameter.</p>


```csharp
public ServiceException(Exception innerException)
```
### ServiceException(string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.Exceptions.ServiceException.yml" sourcestartlinenumber="1">Creates a new service exception initialized with the input parameter.</p>


```csharp
public ServiceException(string errorMessage)
```
### ServiceException(string, Exception)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.Exceptions.ServiceException.yml" sourcestartlinenumber="1">Creates a new service exception initialized with the input parameters.</p>


```csharp
public ServiceException(string errorMessage, Exception innerException)
```


