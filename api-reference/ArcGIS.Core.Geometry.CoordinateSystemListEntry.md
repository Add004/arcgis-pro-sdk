# CoordinateSystemListEntry

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.CoordinateSystemListEntry.yml" sourcestartlinenumber="1">Provides the well-known ID (WKID), name and category (or region) of a particular coordinate system.</p>


## Object Signature

```csharp
public sealed class CoordinateSystemListEntry
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Geometry.CoordinateSystemListEntry.yml" sourcestartlinenumber="1">Returned in a read-only list from <xref href="ArcGIS.Core.Geometry.GeometryEngine.GetPredefinedCoordinateSystemList(ArcGIS.Core.Geometry.CoordinateSystemFilter)" data-throw-if-not-resolved="false"></xref>.
A coordinate system list entry can have more than one level in a category. If there is more than one level in a category,
categories are hierarchical. For example:</p>
<ul><li>Two level category followed by the name of the coordinate system: Geographic Coordinate Systems/World/WGS 1984</li><li>Three level category followed by the name of the coordinate system: Geographic Coordinate Systems/Solar System/Venus/Venus 2000</li></ul>


## Members

### Category

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.CoordinateSystemListEntry.yml" sourcestartlinenumber="1">Gets the category of the coordinate system. The category is a string separated by forward slashes.
When there is more than one category (or region), the ordering is hierarchical.
In other words, the categories in the list are ordered by area from largest to smallest.</p>


```csharp
public string Category { get; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.CoordinateSystemListEntry.yml" sourcestartlinenumber="1">Gets the name of the coordinate system.
When there is more than one category name (or regions), the ordering is hierarchical.
In other words, the categories in the list are ordered by area from largest to smallest.</p>


```csharp
public string Name { get; }
```
### Wkid

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.CoordinateSystemListEntry.yml" sourcestartlinenumber="1">Gets the well-known ID of the coordinate system.</p>


```csharp
public int Wkid { get; }
```


