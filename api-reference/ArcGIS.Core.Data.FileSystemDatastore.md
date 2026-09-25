# FileSystemDatastore

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.FileSystemDatastore.yml" sourcestartlinenumber="1">Represents a file system-based data store; e.g., a folder that contains shapefiles.</p>


## Object Signature

```csharp
public sealed class FileSystemDatastore : Datastore, IDisposable
```


## Members

### FileSystemDatastore(FileSystemConnectionPath)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.FileSystemDatastore.yml" sourcestartlinenumber="1">Opens a folder that contains datasets of type <xref href="ArcGIS.Core.Data.FileSystemConnectionPath.Type" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public FileSystemDatastore(FileSystemConnectionPath connectionPath)
```
### GetConnector()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.FileSystemDatastore.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Connector" data-throw-if-not-resolved="false"></xref> associated with the currently opened file-system data store.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public override Connector GetConnector()
```
### GetDefinition&lt;T&gt;(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.FileSystemDatastore.yml" sourcestartlinenumber="1">Gets a specific <xref href="ArcGIS.Core.Data.Definition" data-throw-if-not-resolved="false"></xref> instance associated with <code class="paramref">name</code> of type <code class="typeparamref">T</code>
in the file-system data store.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public T GetDefinition<T>(string name) where T : Definition
```
### OpenDataset&lt;T&gt;(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.FileSystemDatastore.yml" sourcestartlinenumber="1">Gets a specific <xref href="ArcGIS.Core.Data.Dataset" data-throw-if-not-resolved="false"></xref> instance associated with <code class="paramref">name</code> of type <code class="typeparamref">T</code>
in the file-system data store. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public T OpenDataset<T>(string name) where T : Dataset
```


