# TinNodeSourceType

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Analyst3D.html">Analyst3D</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinNodeSourceType.yml" sourcestartlinenumber="1">TIN node source types.  See <xref href="ArcGIS.Core.Data.Analyst3D.TinNode.Source" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public enum TinNodeSourceType
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinNodeSourceType.yml" sourcestartlinenumber="1">TINs do not persist node source information. It is only maintained while the TIN is in edit mode.
This means that after a TIN has been saved to disk, all nodes, except for super nodes, become Unknown.</p>


## Members

### Densified

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinNodeSourceType.yml" sourcestartlinenumber="1">Densified node.  Added by the triangulator along a breakline so that it may be Delaunay conforming.</p>


```csharp
Densified = 8
```
### Intersection

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinNodeSourceType.yml" sourcestartlinenumber="1">Intersection of two or more enforced lines.   Added by the triangulator where breaklines intersect.</p>


```csharp
Intersection = 32
```
### Original

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinNodeSourceType.yml" sourcestartlinenumber="1">Original input node.  A point or breakline vertex handed to the triangulator as user data.</p>


```csharp
Original = 4
```
### SuperNode

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinNodeSourceType.yml" sourcestartlinenumber="1">Super node. One of 4 nodes added far outside the declared data extent when a TIN is first created.</p>


```csharp
SuperNode = 2
```
### Unknown

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.TinNodeSourceType.yml" sourcestartlinenumber="1">Unknown source.</p>


```csharp
Unknown = 1
```


