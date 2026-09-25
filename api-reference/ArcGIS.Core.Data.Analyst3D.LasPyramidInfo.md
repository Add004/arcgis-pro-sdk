# LasPyramidInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Analyst3D.html">Analyst3D</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasPyramidInfo.yml" sourcestartlinenumber="1">Contains information about the state of pyramids built for a LAS dataset.</p>


## Object Signature

```csharp
public sealed class LasPyramidInfo
```


## Members

### HasPyramid

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasPyramidInfo.yml" sourcestartlinenumber="1">Gets the state of the LAS dataset's pyramids.
True indicates that pyramids exists; false indicates that there are no pyramids.</p>


```csharp
public bool HasPyramid { get; }
```
### IsPyramidUpToDate

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasPyramidInfo.yml" sourcestartlinenumber="1">Gets the status of the pyramids.
True indicates that the pyramid data is synchronized with the LAS dataset.
False indicates that the pyramid may need to be built to be updated with the LAS dataset.</p>


```csharp
public bool IsPyramidUpToDate { get; }
```
### PyramidType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasPyramidInfo.yml" sourcestartlinenumber="1">Gets the point selection type used to create the pyramids.</p>


```csharp
public LasPointSelection PyramidType { get; }
```


