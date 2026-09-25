# Dataset

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Dataset.yml" sourcestartlinenumber="1">Represents a dataset from a specific <xref href="ArcGIS.Core.Data.Datastore" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public abstract class Dataset : CoreObjectsBase, IDisposable
```


## Members

### GetDatastore()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Dataset.yml" sourcestartlinenumber="1">Gets the data store of this dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Datastore GetDatastore()
```
### GetDefinition()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Dataset.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Definition" data-throw-if-not-resolved="false"></xref> of the dataset.</p>


```csharp
public Definition GetDefinition()
```
### GetName()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Dataset.yml" sourcestartlinenumber="1">Gets the name of the dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetName()
```
### GetPath()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Dataset.yml" sourcestartlinenumber="1">Gets the URI path to the dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Uri GetPath()
```
### GetRegistrationType()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Dataset.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.RegistrationType" data-throw-if-not-resolved="false"></xref> of a dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RegistrationType GetRegistrationType()
```
### Type

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Dataset.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.DatasetType" data-throw-if-not-resolved="false"></xref> of the dataset.</p>


```csharp
public abstract DatasetType Type { get; }
```


