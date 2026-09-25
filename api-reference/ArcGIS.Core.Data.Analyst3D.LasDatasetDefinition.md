# LasDatasetDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Analyst3D.html">Analyst3D</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasDatasetDefinition.yml" sourcestartlinenumber="1">Represents the properties of a <xref href="ArcGIS.Core.Data.Analyst3D.LasDataset" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class LasDatasetDefinition : Definition, IDisposable
```


## Members

### AreStatisticsUpToDate()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasDatasetDefinition.yml" sourcestartlinenumber="1">Gets if the LAS dataset has statistics and they are up to date.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool AreStatisticsUpToDate()
```
### DatasetType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasDatasetDefinition.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.DatasetType" data-throw-if-not-resolved="false"></xref> of the LAS dataset.  Returns <xref href="ArcGIS.Core.Data.DatasetType.LasDataset" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public override DatasetType DatasetType { get; }
```
### GetExtent()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasDatasetDefinition.yml" sourcestartlinenumber="1">Gets an <xref href="ArcGIS.Core.Geometry.Envelope" data-throw-if-not-resolved="false"></xref> representing the maximum extent of the data that is contained by the <xref href="ArcGIS.Core.Data.Analyst3D.LasDataset" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Envelope GetExtent()
```
### GetFileCount()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasDatasetDefinition.yml" sourcestartlinenumber="1">Gets the number of files in this LAS dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int GetFileCount()
```
### GetPointCount()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasDatasetDefinition.yml" sourcestartlinenumber="1">Gets the number of points in this LAS dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int GetPointCount()
```
### GetSpatialReference()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasDatasetDefinition.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Geometry.SpatialReference" data-throw-if-not-resolved="false"></xref> for the <xref href="ArcGIS.Core.Data.Analyst3D.LasDataset" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SpatialReference GetSpatialReference()
```
### GetSurfaceConstraintCount()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasDatasetDefinition.yml" sourcestartlinenumber="1">Gets the number of surface constraints in this LAS dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int GetSurfaceConstraintCount()
```
### HasStatistics()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasDatasetDefinition.yml" sourcestartlinenumber="1">Gets if the LAS dataset has statistics.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool HasStatistics()
```
### UsesRelativePath()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasDatasetDefinition.yml" sourcestartlinenumber="1">Gets if the datasources in the LAS dataset are stored with relative path.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool UsesRelativePath()
```


