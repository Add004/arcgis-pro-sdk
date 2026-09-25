# TinEdgeCursor

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Analyst3D.html">Analyst3D</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEdgeCursor.yml" sourcestartlinenumber="1">Represents a cursor of edges from a TIN dataset.  See <xref href="ArcGIS.Core.Data.Analyst3D.TinDataset.SearchEdges(ArcGIS.Core.Data.Analyst3D.TinEdgeFilter)" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class TinEdgeCursor : TinCursor, IDisposable
```


## Members

### Current

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEdgeCursor.yml" sourcestartlinenumber="1">Gets the current <xref href="ArcGIS.Core.Data.Analyst3D.TinEdge" data-throw-if-not-resolved="false"></xref> in this <xref href="ArcGIS.Core.Data.Analyst3D.TinEdgeCursor" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public TinEdge Current { get; }
```
### MoveNext()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEdgeCursor.yml" sourcestartlinenumber="1">Advances to the next <xref href="ArcGIS.Core.Data.Analyst3D.TinEdge" data-throw-if-not-resolved="false"></xref> in this <xref href="ArcGIS.Core.Data.Analyst3D.TinEdgeCursor" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool MoveNext()
```
### Reset()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEdgeCursor.yml" sourcestartlinenumber="1">Resets this <xref href="ArcGIS.Core.Data.Analyst3D.TinEdgeCursor" data-throw-if-not-resolved="false"></xref> to its original state, i.e. to the beginning of the set it was created from.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Reset()
```


