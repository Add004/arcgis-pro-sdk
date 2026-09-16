# FileSystemConnectionPath

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.FileSystemConnectionPath.yml" sourcestartlinenumber="1">Represents the physical path to a file-system data store of type <xref href="ArcGIS.Core.Data.FileSystemConnectionPath.Type" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class FileSystemConnectionPath : Connector
```


## Members

### FileSystemConnectionPath(Uri, FileSystemDatastoreType)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.FileSystemConnectionPath.yml" sourcestartlinenumber="1">Opens a file-system data store with the specified path.</p>


```csharp
public FileSystemConnectionPath(Uri path, FileSystemDatastoreType type)
```
### Path

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.FileSystemConnectionPath.yml" sourcestartlinenumber="1">The path to a directory that contains the data.</p>


```csharp
public Uri Path { get; }
```
### Type

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.FileSystemConnectionPath.yml" sourcestartlinenumber="1">The type of currently-connected file-system data store.</p>


```csharp
public FileSystemDatastoreType Type { get; }
```


