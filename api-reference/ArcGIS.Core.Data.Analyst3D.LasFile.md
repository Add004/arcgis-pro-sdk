# LasFile

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Analyst3D.html">Analyst3D</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasFile.yml" sourcestartlinenumber="1">Represents a LAS file.  See <xref href="ArcGIS.Core.Data.Analyst3D.LasDataset.GetFiles" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class LasFile
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasFile.yml" sourcestartlinenumber="1">A <xref href="ArcGIS.Core.Data.Analyst3D.LasDataset" data-throw-if-not-resolved="false"></xref> can reference one or more LAS or Optimized LAS (ZLAS) files.</p>


## Members

### FileName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasFile.yml" sourcestartlinenumber="1">Gets the file name (with file extension).</p>


```csharp
public string FileName { get; }
```
### FilePath

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasFile.yml" sourcestartlinenumber="1">Gets the file path.</p>


```csharp
public string FilePath { get; }
```
### MajorVersion

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasFile.yml" sourcestartlinenumber="1">Gets the file major version.</p>


```csharp
public int MajorVersion { get; }
```
### MinorVersion

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasFile.yml" sourcestartlinenumber="1">Gets the file minor version.</p>


```csharp
public int MinorVersion { get; }
```
### PointCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasFile.yml" sourcestartlinenumber="1">Gets the number of points in the file.</p>


```csharp
public double PointCount { get; }
```
### PointFormat

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasFile.yml" sourcestartlinenumber="1">Gets the point format.</p>


```csharp
public int PointFormat { get; }
```
### ZMax

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasFile.yml" sourcestartlinenumber="1">Gets the maximum z-value of points in the file.</p>


```csharp
public double ZMax { get; }
```
### ZMin

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Analyst3D.LasFile.yml" sourcestartlinenumber="1">Gets the minimum Z-value of points in the file.</p>


```csharp
public double ZMin { get; }
```


