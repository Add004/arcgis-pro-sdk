# FeatureClass

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.FeatureClass.yml" sourcestartlinenumber="1">Represents a table with a spatial column.</p>


## Object Signature

```csharp
public class FeatureClass : Table, IDisposable
```


## Members

### CreateRow(RowBuffer)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.FeatureClass.yml" sourcestartlinenumber="1">Creates a new feature in the feature class with a system assigned object ID.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Feature CreateRow(RowBuffer featureBuffer)
```
### Get3DObjectFields()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.FeatureClass.yml" sourcestartlinenumber="1">Gets a set of field names if this table is a 3D object feature layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public HashSet<string> Get3DObjectFields()
```
### GetDefinition()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.FeatureClass.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.FeatureClassDefinition" data-throw-if-not-resolved="false"></xref> of this dataset.</p>


```csharp
public FeatureClassDefinition GetDefinition()
```
### GetExtent()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.FeatureClass.yml" sourcestartlinenumber="1">Gets an <xref href="ArcGIS.Core.Geometry.Envelope" data-throw-if-not-resolved="false"></xref> representing the maximum extent of the data that has been stored in the <xref href="ArcGIS.Core.Data.FeatureClass" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Envelope GetExtent()
```
### GetFeatureDataset()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.FeatureClass.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.FeatureDataset" data-throw-if-not-resolved="false"></xref> in which this feature class is contained.
This method must be called on the MCT. Use QueuedTask.Run</p>


```csharp
public FeatureDataset GetFeatureDataset()
```
### Is3DObjectFeatureClass()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.FeatureClass.yml" sourcestartlinenumber="1">Gets a value indicating whether this table is a 3D object feature layer.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool Is3DObjectFeatureClass()
```
### IsFeatureCacheSupported()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.FeatureClass.yml" sourcestartlinenumber="1">Gets a value indicating whether this feature class supports feature cache.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool IsFeatureCacheSupported()
```
### Type

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.FeatureClass.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.DatasetType" data-throw-if-not-resolved="false"></xref> of this derived dataset.</p>


```csharp
public override DatasetType Type { get; }
```


