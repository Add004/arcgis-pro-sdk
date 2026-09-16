# SpatialReference

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReference.yml" sourcestartlinenumber="1">Class representing a spatial reference.</p>


## Object Signature

```csharp
public sealed class SpatialReference
```

## Remarks

<p>
    Each spatial reference can be represented by either a
    well-known ID (WKID), or a well-known text (WKT). Spatial References define the spatial properties of a geometry,
    for instance the coordinate system it uses. There are 2 broad classes of coordinate systems - Geographic &amp; Projected.
    A Geographic Coordinate system uses a 3-dimensional spherical surface to define locations on the earth. A Projected
    Coordinate system on the other hand uses a flat, 2-dimensional surface. More information about spatial references
    and coordinate systems is available
    <a href="http://desktop.arcgis.com/en/arcmap/latest/map/projections/what-are-map-projections.htm" target="_blank">here</a>.
    </p>
<p>It is very important to associate spatial data, such as geometry objects, with corresponding spatial references.</p>


## Members

### AreEqual(SpatialReference, SpatialReference, bool, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReference.yml" sourcestartlinenumber="1">Determines if two spatial references are equal.</p>


```csharp
public static bool AreEqual(SpatialReference sr1, SpatialReference sr2, bool ignoreUnknown = false, bool checkResolution = false)
```
### CentralMeridian

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReference.yml" sourcestartlinenumber="1">Gets the central meridian of the projected coordinate system.</p>


```csharp
public double CentralMeridian { get; }
```
### Datum

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReference.yml" sourcestartlinenumber="1">Gets the horizontal datum of this spatial reference.</p>


```csharp
public Datum Datum { get; }
```
### Domain

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReference.yml" sourcestartlinenumber="1">Gets the square domain extent of the spatial reference.</p>


```csharp
public Envelope Domain { get; }
```
### FalseM

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReference.yml" sourcestartlinenumber="1">Gets the false M.</p>


```csharp
public double FalseM { get; }
```
### FalseX

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReference.yml" sourcestartlinenumber="1">Gets the false X.</p>


```csharp
public double FalseX { get; }
```
### FalseY

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReference.yml" sourcestartlinenumber="1">Gets the false Y.</p>


```csharp
public double FalseY { get; }
```
### FalseZ

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReference.yml" sourcestartlinenumber="1">Gets the false Z.</p>


```csharp
public double FalseZ { get; }
```
### Gcs

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReference.yml" sourcestartlinenumber="1">Gets the underlying geographic coordinate system for this instance.
If this instance is a geographic coordinate system,
a pointer to this instance is returned.</p>


```csharp
public SpatialReference Gcs { get; }
```
### GcsWkid

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReference.yml" sourcestartlinenumber="1">Gets the geographic coordinate system well-known ID.</p>


```csharp
public int GcsWkid { get; }
```
### GcsWkt

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReference.yml" sourcestartlinenumber="1">Gets the geographic coordinate system well-known text.</p>


```csharp
public string GcsWkt { get; }
```
### GetConvergenceAngle(Coordinate2D)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReference.yml" sourcestartlinenumber="1">Gets the grid convergence for this spatial reference at the given point.</p>


```csharp
public double GetConvergenceAngle(Coordinate2D coordinate)
```
### GetGCSHorizon()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReference.yml" sourcestartlinenumber="1">Gets the horizon of the geographic coordinate system.</p>


```csharp
public Envelope GetGCSHorizon()
```
### GetPCSHorizon(out bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReference.yml" sourcestartlinenumber="1">Gets the horizon of the projected coordinate system.</p>


```csharp
public Polygon GetPCSHorizon(out bool isInclusive)
```
### GetWkt2(WktFormatMode)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReference.yml" sourcestartlinenumber="1">Gets the well-known text (2) for this instance.</p>


```csharp
public string GetWkt2(WktFormatMode wktFormatMode)
```
### HasVcs

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReference.yml" sourcestartlinenumber="1">Gets if a vertical coordinate system has been defined.</p>


```csharp
public bool HasVcs { get; }
```
### IsEqual(SpatialReference, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReference.yml" sourcestartlinenumber="1">Determines if this instance is the same as the <code class="paramref">other</code> spatial reference.</p>


```csharp
public bool IsEqual(SpatialReference other, bool ignoreUnknown = false)
```
### IsGeographic

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReference.yml" sourcestartlinenumber="1">Gets if this is a geographic coordinate system.</p>


```csharp
public bool IsGeographic { get; }
```
### IsHighPrecision

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReference.yml" sourcestartlinenumber="1">Gets the HighPrecision flag of this instance.</p>


```csharp
public bool IsHighPrecision { get; }
```
### IsImage

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReference.yml" sourcestartlinenumber="1">Gets if this is an image coordinate system.</p>


```csharp
public bool IsImage { get; }
```
### IsPannable

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReference.yml" sourcestartlinenumber="1">Gets if this instance is pannable.</p>


```csharp
public bool IsPannable { get; }
```
### IsProjected

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReference.yml" sourcestartlinenumber="1">Gets if this is a projected coordinate system.</p>


```csharp
public bool IsProjected { get; }
```
### IsUnknown

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReference.yml" sourcestartlinenumber="1">Gets if this is the unknown coordinate system.</p>


```csharp
public bool IsUnknown { get; }
```
### LatestWkid

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReference.yml" sourcestartlinenumber="1">Gets the latest well-known ID for this instance.</p>


```csharp
public int LatestWkid { get; }
```
### LeftLongitude

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReference.yml" sourcestartlinenumber="1">Gets the left longitude value of the geographic coordinate system.</p>


```csharp
public double LeftLongitude { get; }
```
### MScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReference.yml" sourcestartlinenumber="1">Gets the M Scale.</p>


```csharp
public double MScale { get; }
```
### MTolerance

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReference.yml" sourcestartlinenumber="1">Gets the M Tolerance.</p>


```csharp
public double MTolerance { get; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReference.yml" sourcestartlinenumber="1">Gets the name of the spatial reference.</p>


```csharp
public string Name { get; }
```
### PositiveDirection

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReference.yml" sourcestartlinenumber="1">Gets the positive direction of the vertical coordinate system.</p>


```csharp
public PositiveDirection PositiveDirection { get; }
```
### ProjectionName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReference.yml" sourcestartlinenumber="1">Gets the name of the underlying projection of the spatial reference. Returns an empty string if <xref href="ArcGIS.Core.Geometry.SpatialReference.IsProjected?text=IsProjected" data-throw-if-not-resolved="false"></xref> is false.</p>


```csharp
public string ProjectionName { get; }
```
### RightLongitude

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReference.yml" sourcestartlinenumber="1">Gets the right longitude value of the geographic coordinate system.</p>


```csharp
public double RightLongitude { get; }
```
### ToJson()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReference.yml" sourcestartlinenumber="1">Converts this spatial reference instance into an ArcGIS JSON spatial reference representation.</p>


```csharp
public string ToJson()
```
### ToXml()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReference.yml" sourcestartlinenumber="1">Converts this spatial reference instance into an ArcGIS XML spatial reference representation.</p>


```csharp
public string ToXml()
```
### Unit

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReference.yml" sourcestartlinenumber="1">Gets the units that the spatial reference xy-coordinates are in.</p>


```csharp
public Unit Unit { get; }
```
### VcsWkid

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReference.yml" sourcestartlinenumber="1">Gets the vertical coordinate system well-known ID.</p>


```csharp
public int VcsWkid { get; }
```
### VcsWkt

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReference.yml" sourcestartlinenumber="1">Gets the vertical coordinate system well-known text.</p>


```csharp
public string VcsWkt { get; }
```
### VerticalShift

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReference.yml" sourcestartlinenumber="1">Gets the vertical shift of the vertical coordinate system.</p>


```csharp
public double VerticalShift { get; }
```
### Wkid

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReference.yml" sourcestartlinenumber="1">Gets the well-known ID for this instance.</p>


```csharp
public int Wkid { get; }
```
### Wkt

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReference.yml" sourcestartlinenumber="1">Gets the well-known text for this instance.</p>


```csharp
public string Wkt { get; }
```
### XYResolution

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReference.yml" sourcestartlinenumber="1">Gets the XY Resolution.</p>


```csharp
public double XYResolution { get; }
```
### XYScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReference.yml" sourcestartlinenumber="1">Gets the XY Scale.</p>


```csharp
public double XYScale { get; }
```
### XYTolerance

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReference.yml" sourcestartlinenumber="1">Gets the XY Tolerance.</p>


```csharp
public double XYTolerance { get; }
```
### ZScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReference.yml" sourcestartlinenumber="1">Gets the Z Scale.</p>


```csharp
public double ZScale { get; }
```
### ZTolerance

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReference.yml" sourcestartlinenumber="1">Gets the Z Tolerance.</p>


```csharp
public double ZTolerance { get; }
```
### ZUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReference.yml" sourcestartlinenumber="1">Gets the units that the spatial reference z-coordinates are in.</p>


```csharp
public Unit ZUnit { get; }
```


