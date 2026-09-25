# BimFileDatasetDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.BimFileDatasetDefinition.yml" sourcestartlinenumber="1">Represents the properties of a <xref href="ArcGIS.Core.Data.BimFileDataset" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class BimFileDatasetDefinition : Definition, IDisposable
```


## Members

### DatasetType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.BimFileDatasetDefinition.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.DatasetType" data-throw-if-not-resolved="false"></xref> of the BIM dataset.</p>


```csharp
public override DatasetType DatasetType { get; }
```
### GetExtent()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.BimFileDatasetDefinition.yml" sourcestartlinenumber="1">Gets an <xref href="ArcGIS.Core.Geometry.Envelope" data-throw-if-not-resolved="false"></xref> representing the maximum extent of the data that is contained by the <xref href="ArcGIS.Core.Data.BimFileDataset" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Envelope GetExtent()
```
### GetSpatialReference()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.BimFileDatasetDefinition.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Geometry.SpatialReference" data-throw-if-not-resolved="false"></xref> for the <xref href="ArcGIS.Core.Data.BimFileDataset" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SpatialReference GetSpatialReference()
```


