# TinEdgeFilter

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Analyst3D.html">Analyst3D</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEdgeFilter.yml" sourcestartlinenumber="1">Encapsulates a set of parameters for filtering edges in <xref href="ArcGIS.Core.Data.Analyst3D.TinDataset.SearchEdges(ArcGIS.Core.Data.Analyst3D.TinEdgeFilter)" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class TinEdgeFilter : TinFilter
```


## Members

### TinEdgeFilter()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEdgeFilter.yml" sourcestartlinenumber="1">Create an instance of <xref href="ArcGIS.Core.Data.Analyst3D.TinEdgeFilter" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public TinEdgeFilter()
```
### EdgeType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEdgeFilter.yml" sourcestartlinenumber="1">Gets and sets the edge type to filter by.  Used only when <xref href="ArcGIS.Core.Data.Analyst3D.TinEdgeFilter.FilterByEdgeType" data-throw-if-not-resolved="false"></xref> is true. Default is <xref href="ArcGIS.Core.Data.Analyst3D.TinEdgeType.RegularEdge" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public TinEdgeType EdgeType { get; set; }
```
### FilterByEdgeType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEdgeFilter.yml" sourcestartlinenumber="1">Gets and sets whether the <xref href="ArcGIS.Core.Data.Analyst3D.TinEdgeFilter.EdgeType" data-throw-if-not-resolved="false"></xref> property is used in the filter. Default value is false.</p>


```csharp
public bool FilterByEdgeType { get; set; }
```
### SingleEdge

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinEdgeFilter.yml" sourcestartlinenumber="1">Gets and sets whether single or double edges are returned. Default value is true.</p>


```csharp
public bool SingleEdge { get; set; }
```


