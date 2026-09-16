# CoordinateSystemFilter

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.CoordinateSystemFilter.yml" sourcestartlinenumber="1">Coordinate System Filter. Use a filter as input to <xref href="ArcGIS.Core.Geometry.GeometryEngine.GetPredefinedCoordinateSystemList(ArcGIS.Core.Geometry.CoordinateSystemFilter)" data-throw-if-not-resolved="false"></xref>.
Can be used as a bit mask to get multiple coordinate system types in one list.</p>


## Object Signature

```csharp
[Flags]
public enum CoordinateSystemFilter
```


## Members

### GeographicCoordinateSystem

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.CoordinateSystemFilter.yml" sourcestartlinenumber="1">Geographic Coordinate System</p>


```csharp
GeographicCoordinateSystem = 1
```
### ProjectedCoordinateSystem

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.CoordinateSystemFilter.yml" sourcestartlinenumber="1">Projected Coordinate System</p>


```csharp
ProjectedCoordinateSystem = 2
```
### VerticalCoordinateSystem

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.CoordinateSystemFilter.yml" sourcestartlinenumber="1">Vertical Coordinate System</p>


```csharp
VerticalCoordinateSystem = 8
```


