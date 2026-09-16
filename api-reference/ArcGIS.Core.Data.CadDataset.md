# CadDataset

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.CadDataset.yml" sourcestartlinenumber="1">Represents a CAD dataset.</p>


## Object Signature

```csharp
public sealed class CadDataset : Dataset, IDisposable
```


## Members

### GetDefinition()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.CadDataset.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.CadDatasetDefinition" data-throw-if-not-resolved="false"></xref> of this CAD dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CadDatasetDefinition GetDefinition()
```
### GetExtent()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.CadDataset.yml" sourcestartlinenumber="1">Gets an <xref href="ArcGIS.Core.Geometry.Envelope" data-throw-if-not-resolved="false"></xref> representing the maximum extent of the data that has been stored in the <xref href="ArcGIS.Core.Data.CadDataset" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Envelope GetExtent()
```
### OpenDataset&lt;T&gt;(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.CadDataset.yml" sourcestartlinenumber="1">Gets a specific <xref href="ArcGIS.Core.Data.Dataset" data-throw-if-not-resolved="false"></xref> instance associated with <code class="paramref">name</code> of type <code class="typeparamref">T</code>
in the CAD dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public T OpenDataset<T>(string name) where T : Dataset
```
### Reload()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.CadDataset.yml" sourcestartlinenumber="1">Reloads the CAD dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Reload()
```
### Type

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.CadDataset.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.DatasetType" data-throw-if-not-resolved="false"></xref> of this CAD dataset.</p>


```csharp
public override DatasetType Type { get; }
```


