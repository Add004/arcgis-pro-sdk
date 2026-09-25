# TinTriangleCursor

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Analyst3D.html">Analyst3D</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinTriangleCursor.yml" sourcestartlinenumber="1">Represents a cursor of triangles from a TIN dataset.  See <xref href="ArcGIS.Core.Data.Analyst3D.TinDataset.SearchTriangles(ArcGIS.Core.Data.Analyst3D.TinTriangleFilter)" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class TinTriangleCursor : TinCursor, IDisposable
```


## Members

### Current

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinTriangleCursor.yml" sourcestartlinenumber="1">Gets the current <xref href="ArcGIS.Core.Data.Analyst3D.TinTriangle" data-throw-if-not-resolved="false"></xref> in this <xref href="ArcGIS.Core.Data.Analyst3D.TinTriangleCursor" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public TinTriangle Current { get; }
```
### MoveNext()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinTriangleCursor.yml" sourcestartlinenumber="1">Advances to the next <xref href="ArcGIS.Core.Data.Analyst3D.TinTriangle" data-throw-if-not-resolved="false"></xref> in this <xref href="ArcGIS.Core.Data.Analyst3D.TinTriangleCursor" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool MoveNext()
```
### Reset()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinTriangleCursor.yml" sourcestartlinenumber="1">Resets this <xref href="ArcGIS.Core.Data.Analyst3D.TinTriangleCursor" data-throw-if-not-resolved="false"></xref> to its original state, i.e. to the beginning of the set it was created from.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Reset()
```


