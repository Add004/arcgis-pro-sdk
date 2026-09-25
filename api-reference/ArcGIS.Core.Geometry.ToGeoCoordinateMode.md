# ToGeoCoordinateMode

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.ToGeoCoordinateMode.yml" sourcestartlinenumber="1">Determines how to handle the geographic coordinate system of the spatial reference.  Certain older geographic coordinate systems will cause one of the letters
of the string to be shifted.  This process makes it easier to identify coordinates that are based on a non-WGS84 datum.</p>


## Object Signature

```csharp
public enum ToGeoCoordinateMode
```


## Members

### Default

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.ToGeoCoordinateMode.yml" sourcestartlinenumber="1">The default conversion mode for all types.</p>


```csharp
Default = 0
```
### MgrsNewStyle

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.ToGeoCoordinateMode.yml" sourcestartlinenumber="1">Treats all spheroids as new, like WGS 1984, when creating or reading a military grid string.
The 180 longitude falls into zone 60.</p>


```csharp
MgrsNewStyle = 18
```
### MgrsNewWith180InZone01

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.ToGeoCoordinateMode.yml" sourcestartlinenumber="1">Treats all spheroids as new, like WGS 1984, when creating or reading a military grid string.
The 180 longitude falls into zone 01.</p>


```csharp
MgrsNewWith180InZone01 = 27
```
### MgrsOldStyle

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.ToGeoCoordinateMode.yml" sourcestartlinenumber="1">Treats all spheroids as old, like Bessel 1841, when creating or reading a military grid string.
The 180 longitude falls into zone 60.</p>


```csharp
MgrsOldStyle = 19
```
### MgrsOldWith180InZone01

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.ToGeoCoordinateMode.yml" sourcestartlinenumber="1">Treats all spheroids as old, like Bessel 1841, when creating or reading a military grid string.
The 180 longitude falls into zone 01.</p>


```csharp
MgrsOldWith180InZone01 = 28
```
### UtmNorthSouth

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.ToGeoCoordinateMode.yml" sourcestartlinenumber="1">Uses North/South latitude indicators. Non-standard. Default is recommended.</p>


```csharp
UtmNorthSouth = 34
```


