# LasPointDisplayFilterType

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointDisplayFilterType.yml" sourcestartlinenumber="1">Coarse grained filter for display of points in a LAS dataset layer.  See <xref href="ArcGIS.Desktop.Mapping.LasDatasetLayer.SetDisplayFilter(ArcGIS.Desktop.Mapping.LasPointDisplayFilterType)" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public enum LasPointDisplayFilterType
```


## Members

### AllPoints

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointDisplayFilterType.yml" sourcestartlinenumber="1">Display all points.</p>


```csharp
AllPoints = 0
```
### FirstReturnPoints

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointDisplayFilterType.yml" sourcestartlinenumber="1">Display only the first-return points. See <xref href="ArcGIS.Core.Data.Analyst3D.LasReturnType.Return1" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
FirstReturnPoints = 3
```
### Ground

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointDisplayFilterType.yml" sourcestartlinenumber="1">Display only the points flagged as ground points.</p>


```csharp
Ground = 1
```
### NonGround

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointDisplayFilterType.yml" sourcestartlinenumber="1">Display all the points that are not flagged as ground points.</p>


```csharp
NonGround = 2
```


