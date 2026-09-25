# BimFileDataset

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.BimFileDataset.yml" sourcestartlinenumber="1">Represents a BIM file dataset.</p>


## Object Signature

```csharp
public sealed class BimFileDataset : Dataset, IDisposable
```


## Members

### GetDefinition()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.BimFileDataset.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.BimFileDatasetDefinition" data-throw-if-not-resolved="false"></xref> of this BIM file dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public BimFileDatasetDefinition GetDefinition()
```
### GetExtent()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.BimFileDataset.yml" sourcestartlinenumber="1">Gets an <xref href="ArcGIS.Core.Geometry.Envelope" data-throw-if-not-resolved="false"></xref> representing the maximum extent of the data that has been stored in the <xref href="ArcGIS.Core.Data.BimFileDataset" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Envelope GetExtent()
```
### OpenDataset&lt;T&gt;(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.BimFileDataset.yml" sourcestartlinenumber="1">Gets a specific <xref href="ArcGIS.Core.Data.Dataset" data-throw-if-not-resolved="false"></xref> instance associated with <code class="paramref">name</code> of type <code class="typeparamref">T</code>
in the BIM file dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public T OpenDataset<T>(string name) where T : Dataset
```
### Reload()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.BimFileDataset.yml" sourcestartlinenumber="1">Reloads the BIM file.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Reload()
```
### Type

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.BimFileDataset.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.DatasetType" data-throw-if-not-resolved="false"></xref> of this BIM file dataset.</p>


```csharp
public override DatasetType Type { get; }
```
### Upgrade()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.BimFileDataset.yml" sourcestartlinenumber="1">Upgrades the BIM file to the latest supported file version. This operation is not supported for IFC files.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Upgrade()
```


