# LasPointCursor

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Analyst3D.html">Analyst3D</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasPointCursor.yml" sourcestartlinenumber="1">Represents a cursor of points from a LAS dataset.  See <xref href="ArcGIS.Core.Data.Analyst3D.LasDataset.SearchPoints(ArcGIS.Core.Data.Analyst3D.LasPointFilter%2cSystem.Double%2cSystem.Double)" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class LasPointCursor : CoreObjectsBase, IDisposable
```


## Members

### Current

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasPointCursor.yml" sourcestartlinenumber="1">Gets the current <xref href="ArcGIS.Core.Data.Analyst3D.LasPoint" data-throw-if-not-resolved="false"></xref> in this <xref href="ArcGIS.Core.Data.Analyst3D.LasPointCursor" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public LasPoint Current { get; }
```
### MoveNext()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasPointCursor.yml" sourcestartlinenumber="1">Advances to the next <xref href="ArcGIS.Core.Data.Analyst3D.LasPoint" data-throw-if-not-resolved="false"></xref> in this <xref href="ArcGIS.Core.Data.Analyst3D.LasPointCursor" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool MoveNext()
```
### MoveNextArray(Coordinate3D[], int[], int[], double[], out int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasPointCursor.yml" sourcestartlinenumber="1">Advances to the next set of <xref href="ArcGIS.Core.Data.Analyst3D.LasPoint" data-throw-if-not-resolved="false"></xref> objects in this <xref href="ArcGIS.Core.Data.Analyst3D.LasPointCursor" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool MoveNextArray(Coordinate3D[] points, int[] intensities, int[] fileIndices, double[] pointIds, out int pointCount)
```
### Reset()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasPointCursor.yml" sourcestartlinenumber="1">Resets this <xref href="ArcGIS.Core.Data.Analyst3D.LasPointCursor" data-throw-if-not-resolved="false"></xref> to its original state, i.e. to the beginning of the set it was created from.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Reset()
```


