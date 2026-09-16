# LasDataset

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Analyst3D.html">Analyst3D</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasDataset.yml" sourcestartlinenumber="1">Represents a LAS dataset.</p>


## Object Signature

```csharp
public sealed class LasDataset : Dataset, IDisposable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasDataset.yml" sourcestartlinenumber="1">The LAS dataset is a stand-alone file that resides in a folder and references lidar data in the LAS format
with optional surface constraint features that define surface characteristics.
The LAS dataset can reference one or more LAS or Optimized LAS (ZLAS) files.</p>


## Members

### EstimatePointCount(Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasDataset.yml" sourcestartlinenumber="1">Estimates the number of points within the specified area of interest.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double EstimatePointCount(Geometry geometry)
```
### EstimatePointSpacing(Envelope)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasDataset.yml" sourcestartlinenumber="1">Gets the minimum, maximum, and mean point spacing estimates based on the LAS files whose extents intersect the envelope.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public (double minSpacing, double maxSpacing, double meanSpacing) EstimatePointSpacing(Envelope envelope)
```
### GetDefinition()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasDataset.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Analyst3D.LasDatasetDefinition" data-throw-if-not-resolved="false"></xref> of this LAS dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public LasDatasetDefinition GetDefinition()
```
### GetExtent()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasDataset.yml" sourcestartlinenumber="1">Gets an <xref href="ArcGIS.Core.Geometry.Envelope" data-throw-if-not-resolved="false"></xref> representing the maximum extent of the data that has been stored in this LAS dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Envelope GetExtent()
```
### GetFileCounts()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasDataset.yml" sourcestartlinenumber="1">Gets the number of LAS and ZLAS files in this LAS dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public (int lasFileCount, int zLasFileCount) GetFileCounts()
```
### GetFiles()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasDataset.yml" sourcestartlinenumber="1">Gets the list of <xref href="ArcGIS.Core.Data.Analyst3D.LasFile" data-throw-if-not-resolved="false"></xref> used in this LAS dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<LasFile> GetFiles()
```
### GetName()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasDataset.yml" sourcestartlinenumber="1">Gets the dataset's name.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetName()
```
### GetPointByID(double, Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasDataset.yml" sourcestartlinenumber="1">Gets the points specified by the point ID.  Because the LAS dataset can reference multiple LAS files, more than one point
with the specified point ID can be found.
If a geometry is specified, then only this spatial area is searched.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<LasPoint> GetPointByID(double pointID, Geometry geometry = null)
```
### GetPointByID(int, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasDataset.yml" sourcestartlinenumber="1">Gets the point specified by the file index and point ID.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public LasPoint GetPointByID(int fileIndex, double pointID)
```
### GetPointCount()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasDataset.yml" sourcestartlinenumber="1">Gets the number of points in this LAS dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double GetPointCount()
```
### GetPyramidInfo()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasDataset.yml" sourcestartlinenumber="1">Retrieves the pyramid info from a LAS Dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public LasPyramidInfo GetPyramidInfo()
```
### GetSizeInBytes()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasDataset.yml" sourcestartlinenumber="1">Gets the dataset's size in bytes.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double GetSizeInBytes()
```
### GetSurfaceConstraintCount()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasDataset.yml" sourcestartlinenumber="1">Gets the number of surface constraints used in this LAS dataset.  Also see <xref href="ArcGIS.Core.Data.Analyst3D.LasDataset.GetSurfaceConstraints" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int GetSurfaceConstraintCount()
```
### GetSurfaceConstraints()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasDataset.yml" sourcestartlinenumber="1">Gets the list of <xref href="ArcGIS.Core.Data.Analyst3D.SurfaceConstraint" data-throw-if-not-resolved="false"></xref> used in this LAS dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<SurfaceConstraint> GetSurfaceConstraints()
```
### GetUncompressedSizeInBytes()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasDataset.yml" sourcestartlinenumber="1">Gets the dataset's uncompressed size in bytes.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public double GetUncompressedSizeInBytes()
```
### GetUniqueClassCodes()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasDataset.yml" sourcestartlinenumber="1">Gets the set of classification codes used in this LAS dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<int> GetUniqueClassCodes()
```
### GetUniqueReturns()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasDataset.yml" sourcestartlinenumber="1">Gets the set of returns used in this LAS dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<LasReturnType> GetUniqueReturns()
```
### GetVersion()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasDataset.yml" sourcestartlinenumber="1">Gets the major and minor version of the LAS dataset.  Also retrieves the point format.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public (int majorVersion, int minorVersion, int pointFormat) GetVersion()
```
### SearchPoints(LasPointFilter, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasDataset.yml" sourcestartlinenumber="1">Retrieves the points in the LAS dataset that satisfy the criteria set in the <code class="paramref">filter</code>.
If no filter is set, all points will be retrieved.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public LasPointCursor SearchPoints(LasPointFilter filter, double thinningFactor = 1, double zFactor = 1)
```
### Type

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasDataset.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.DatasetType" data-throw-if-not-resolved="false"></xref> of this LAS dataset.  Returns <xref href="ArcGIS.Core.Data.DatasetType.LasDataset" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public override DatasetType Type { get; }
```


