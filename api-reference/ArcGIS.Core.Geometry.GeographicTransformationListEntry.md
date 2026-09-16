# GeographicTransformationListEntry

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.GeographicTransformationListEntry.yml" sourcestartlinenumber="1">Provides the name, well-known ID (WKID), and WKIDs of the spatial references from which and to which the data will be projected.</p>


## Object Signature

```csharp
public sealed class GeographicTransformationListEntry
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Geometry.GeographicTransformationListEntry.yml" sourcestartlinenumber="1">Returned in a read-only list from <xref href="ArcGIS.Core.Geometry.GeometryEngine.GetPredefinedGeographicTransformationList" data-throw-if-not-resolved="false"></xref>.</p>


## Members

### FromSRWkid

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeographicTransformationListEntry.yml" sourcestartlinenumber="1">Gets the well-known ID of the spatial reference from which the data will be projected.</p>


```csharp
public int FromSRWkid { get; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeographicTransformationListEntry.yml" sourcestartlinenumber="1">Gets the name of the geographic transformation.</p>


```csharp
public string Name { get; }
```
### ToSRWkid

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeographicTransformationListEntry.yml" sourcestartlinenumber="1">Gets the well-known ID of the spatial reference to which the data will be projected.</p>


```csharp
public int ToSRWkid { get; }
```
### Wkid

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeographicTransformationListEntry.yml" sourcestartlinenumber="1">Gets the well-known ID of the geographic transformation.</p>


```csharp
public int Wkid { get; }
```


