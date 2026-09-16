# DatabaseConnectionFile

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.DatabaseConnectionFile.yml" sourcestartlinenumber="1">Represents the physical path to a connection file that ends with the <b>.sde</b> extension used for connecting to an enterprise database or geodatabase.</p>


## Object Signature

```csharp
public class DatabaseConnectionFile : Connector
```


## Members

### DatabaseConnectionFile(Uri)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DatabaseConnectionFile.yml" sourcestartlinenumber="1">Initializes a new instance of the <code>DatabaseConnectionFile</code> class.</p>


```csharp
public DatabaseConnectionFile(Uri path)
```
### Path

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DatabaseConnectionFile.yml" sourcestartlinenumber="1">The path to a database connection file that ends with the <b>.sde</b> extension.</p>


```csharp
public Uri Path { get; }
```


