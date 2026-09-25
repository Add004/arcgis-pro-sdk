# FeatureDataset

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.FeatureDataset.yml" sourcestartlinenumber="1">Represents a feature dataset from a geodatabase.</p>


## Object Signature

```csharp
public sealed class FeatureDataset : Dataset, IDisposable
```


## Members

### GetDefinition()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.FeatureDataset.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.FeatureDatasetDefinition" data-throw-if-not-resolved="false"></xref> of this dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public FeatureDatasetDefinition GetDefinition()
```
### GetDefinition&lt;T&gt;(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.FeatureDataset.yml" sourcestartlinenumber="1">Gets a specific <xref href="ArcGIS.Core.Data.Definition" data-throw-if-not-resolved="false"></xref> instance associated with <code class="paramref">name</code> of type <code class="typeparamref">T</code>
in the feature dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public T GetDefinition<T>(string name) where T : Definition
```
### GetDefinitions&lt;T&gt;()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.FeatureDataset.yml" sourcestartlinenumber="1">Gets an <xref href="System.Collections.Generic.IReadOnlyList%601" data-throw-if-not-resolved="false"></xref> of specific <xref href="ArcGIS.Core.Data.Definition" data-throw-if-not-resolved="false"></xref>
instances associated with each dataset of type <code class="typeparamref">T</code>
in the feature dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<T> GetDefinitions<T>() where T : Definition
```
### GetExtent()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.FeatureDataset.yml" sourcestartlinenumber="1">Gets an <xref href="ArcGIS.Core.Geometry.Envelope" data-throw-if-not-resolved="false"></xref> representing the maximum extent of the data that has been stored in the <xref href="ArcGIS.Core.Data.FeatureDataset" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Envelope GetExtent()
```
### OpenDataset&lt;T&gt;(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.FeatureDataset.yml" sourcestartlinenumber="1">Gets a specific <xref href="ArcGIS.Core.Data.Dataset" data-throw-if-not-resolved="false"></xref> instance associated with <code class="paramref">name</code> of type <code class="typeparamref">T</code>
in the feature dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public T OpenDataset<T>(string name) where T : Dataset
```
### Type

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.FeatureDataset.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.DatasetType" data-throw-if-not-resolved="false"></xref> of this derived dataset.</p>


```csharp
public override DatasetType Type { get; }
```


