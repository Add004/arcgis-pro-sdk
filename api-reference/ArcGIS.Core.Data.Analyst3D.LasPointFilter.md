# LasPointFilter

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Analyst3D.html">Analyst3D</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasPointFilter.yml" sourcestartlinenumber="1">Provides a set of parameters to filter for LAS points in <xref href="ArcGIS.Core.Data.Analyst3D.LasDataset.SearchPoints(ArcGIS.Core.Data.Analyst3D.LasPointFilter%2cSystem.Double%2cSystem.Double)" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class LasPointFilter
```


## Members

### LasPointFilter()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasPointFilter.yml" sourcestartlinenumber="1">Create an instance of <xref href="ArcGIS.Core.Data.Analyst3D.LasPointFilter" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public LasPointFilter()
```
### ClassCodes

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasPointFilter.yml" sourcestartlinenumber="1">Gets and sets the list of class codes to filter.    Default value is null.</p>


```csharp
public List<int> ClassCodes { get; set; }
```
### FilterGeometry

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasPointFilter.yml" sourcestartlinenumber="1">Gets and sets a geometry filter. It may be set to an <xref href="ArcGIS.Core.Geometry.Envelope" data-throw-if-not-resolved="false"></xref> or a <xref href="ArcGIS.Core.Geometry.Polygon" data-throw-if-not-resolved="false"></xref>.
Default value is null.</p>


```csharp
public Geometry FilterGeometry { get; set; }
```
### KeyPoints

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasPointFilter.yml" sourcestartlinenumber="1">Gets and sets whether key points are filtered.  Default value is true.</p>


```csharp
public bool KeyPoints { get; set; }
```
### OverlapPoints

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasPointFilter.yml" sourcestartlinenumber="1">Gets and sets whether overlap points are filtered.  Default value is true.</p>


```csharp
public bool OverlapPoints { get; set; }
```
### Returns

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasPointFilter.yml" sourcestartlinenumber="1">Gets and sets the list of returns to filter.   Default value is null.</p>


```csharp
public List<LasReturnType> Returns { get; set; }
```
### SyntheticPoints

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasPointFilter.yml" sourcestartlinenumber="1">Gets and sets whether synthetic points are filtered.  Default value is true.</p>


```csharp
public bool SyntheticPoints { get; set; }
```
### WithheldPoints

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasPointFilter.yml" sourcestartlinenumber="1">Gets and sets whether withheld points are filtered. Default value is false.</p>


```csharp
public bool WithheldPoints { get; set; }
```


