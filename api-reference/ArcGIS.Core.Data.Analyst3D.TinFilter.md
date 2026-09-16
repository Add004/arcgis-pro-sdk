# TinFilter

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Analyst3D.html">Analyst3D</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinFilter.yml" sourcestartlinenumber="1">An abstract base class that provides a set of parameters to filter for TIN elements. See <xref href="ArcGIS.Core.Data.Analyst3D.TinNodeFilter" data-throw-if-not-resolved="false"></xref>,
<xref href="ArcGIS.Core.Data.Analyst3D.TinEdgeFilter" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Core.Data.Analyst3D.TinTriangleFilter" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public abstract class TinFilter
```


## Members

### DataElementsOnly

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinFilter.yml" sourcestartlinenumber="1">Gets and sets whether the filter should return elements classified as &quot;inside&quot; only.  Default value is false.</p>


```csharp
public bool DataElementsOnly { get; set; }
```
### FilterEnvelope

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinFilter.yml" sourcestartlinenumber="1">Gets and sets an envelope filter.   Default value is null meaning that the envelope searched is the TIN's data area, See <xref href="ArcGIS.Core.Data.Analyst3D.TinDataset.GetDataArea" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public Envelope FilterEnvelope { get; set; }
```
### FilterType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinFilter.yml" sourcestartlinenumber="1">Gets and sets the filter type.   Default value is <xref href="ArcGIS.Core.Data.Analyst3D.TinFilterType.All" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public TinFilterType FilterType { get; set; }
```


