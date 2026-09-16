# GeographicTransformation

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.GeographicTransformation.yml" sourcestartlinenumber="1">A geographic transformation is used when
projecting geometries between two different geographic coordinate systems. A geographic
transformation converts everything that needs to be changed including the units,
prime meridian, and the ellipsoid. Every transformation is defined in a particular forward
direction, say from GCS A to GCS B, but all are reversible. For example, a geographic
transformation may be defined to convert from NAD27 to WGS84. If you are projecting from
WGS84 to NAD27, you can use the reversed form of the transformation.</p>


## Object Signature

```csharp
public sealed class GeographicTransformation : DatumTransformation
```


## Members

### Create(int, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeographicTransformation.yml" sourcestartlinenumber="1">Creates a <xref href="ArcGIS.Core.Geometry.GeographicTransformation" data-throw-if-not-resolved="false"></xref> instance from a well-known ID.</p>


```csharp
public static GeographicTransformation Create(int wkid, bool transformForward = true)
```
### Create(string, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeographicTransformation.yml" sourcestartlinenumber="1">Creates a <xref href="ArcGIS.Core.Geometry.GeographicTransformation" data-throw-if-not-resolved="false"></xref> instance from a well-known text string.</p>


```csharp
public static GeographicTransformation Create(string wkt, bool transformForward = true)
```
### CreateNull(SpatialReference, SpatialReference, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeographicTransformation.yml" sourcestartlinenumber="1">Creates a <xref href="ArcGIS.Core.Geometry.GeographicTransformation" data-throw-if-not-resolved="false"></xref> instance representing the 'null' method for a pair of spatial references.</p>


```csharp
public static GeographicTransformation CreateNull(SpatialReference input, SpatialReference output, bool transformForward = true)
```
### Forward

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeographicTransformation.yml" sourcestartlinenumber="1">Gets if the geographic transformation is defed as Forward.</p>


```csharp
public override bool Forward { get; }
```
### GetInverse()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeographicTransformation.yml" sourcestartlinenumber="1">Creates an inverted instance of this transformation. The inverted instance has its IsForward property inverted
and input and output spatial references are switched.</p>


```csharp
public override DatumTransformation GetInverse()
```
### GridDatasetName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeographicTransformation.yml" sourcestartlinenumber="1">Gets the name of the grid dataset used by this transformation, if applicable.
If the transformation does not use a grid dataset, this property will be null.</p>


```csharp
public string GridDatasetName { get; }
```
### InputSpatialReference

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeographicTransformation.yml" sourcestartlinenumber="1">Gets the input spatial reference of this transformation.</p>


```csharp
public override SpatialReference InputSpatialReference { get; }
```
### IsForward

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeographicTransformation.yml" sourcestartlinenumber="1">Gets a value indicating if the geographic transformation is forward or inversed.</p>


```csharp
public bool IsForward { get; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeographicTransformation.yml" sourcestartlinenumber="1">Gets the name of the geographic transformation.</p>


```csharp
public string Name { get; }
```
### OutputSpatialReference

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeographicTransformation.yml" sourcestartlinenumber="1">Gets the output spatial reference of this transformation.</p>


```csharp
public override SpatialReference OutputSpatialReference { get; }
```
### Wkid

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeographicTransformation.yml" sourcestartlinenumber="1">Gets the well-known ID of the geographic transformation.</p>


```csharp
public int Wkid { get; }
```
### Wkt

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeographicTransformation.yml" sourcestartlinenumber="1">Gets the well-known text of the geographic transformation.</p>


```csharp
public string Wkt { get; }
```


