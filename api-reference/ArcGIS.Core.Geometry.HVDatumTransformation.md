# HVDatumTransformation

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.HVDatumTransformation.yml" sourcestartlinenumber="1">A hv (horizontal/vertical) datum transformation is used when
projecting Z-Aware geometries between two different geographic coordinate systems and two
different vertical coordinate systems. As with geographic transformations, a hv datum
transformation converts everything that needs to be changed including the units,
prime meridian, and the ellipsoid. In addition, a hv datum transformation transforms height.
Every transformation is defined in a particular forward direction, but all are reversible.
For example, suppose your Z-Aware geometry is in WGS84 with vertical coordinate system EGM2008_Geoid,
and you want to project to NAD83_2011 with vertical coordinate system NAD83_2011.
A hv datum transformation is defined to project your Z-Aware geometry from WGS84 with
vertical coordinate system EGM2008_Geoid to NAD83_2011 with vertical coordinate system NAD83_2011.
If you are projecting from NAD83_2011 with vertical coordinate system NAD83_2011 to
WGS84 with vertical coordinate system EGM2008_Geoid to NAD83_2011, you can use the reversed
form of the transformation.</p>


## Object Signature

```csharp
public sealed class HVDatumTransformation : DatumTransformation
```


## Members

### Create(int, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.HVDatumTransformation.yml" sourcestartlinenumber="1">Creates a new <xref href="ArcGIS.Core.Geometry.HVDatumTransformation" data-throw-if-not-resolved="false"></xref> instance from a well-known ID.</p>


```csharp
public static HVDatumTransformation Create(int wkid, bool transformForward = true)
```
### Create(string, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.HVDatumTransformation.yml" sourcestartlinenumber="1">Creates a <xref href="ArcGIS.Core.Geometry.HVDatumTransformation" data-throw-if-not-resolved="false"></xref> from a well-known text string.</p>


```csharp
public static HVDatumTransformation Create(string wkt, bool transformForward = true)
```
### Forward

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.HVDatumTransformation.yml" sourcestartlinenumber="1">Gets if the horizontal/vertical transformation is defed as Forward.</p>


```csharp
public override bool Forward { get; }
```
### GetInverse()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.HVDatumTransformation.yml" sourcestartlinenumber="1">Creates an inverted instance of this transformation. After the call the IsForward property is inverted.</p>


```csharp
public override DatumTransformation GetInverse()
```
### InputSpatialReference

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.HVDatumTransformation.yml" sourcestartlinenumber="1">Gets the input spatial reference of this transformation.</p>


```csharp
public override SpatialReference InputSpatialReference { get; }
```
### InputVerticalCoordinateSystem

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.HVDatumTransformation.yml" sourcestartlinenumber="1">Gets the input vertical coordinate system of this transformation.</p>


```csharp
public override VerticalCoordinateSystem InputVerticalCoordinateSystem { get; }
```
### IsForward

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.HVDatumTransformation.yml" sourcestartlinenumber="1">Gets a value indicating if this horizontal/vertical transformation is forward or inversed.</p>


```csharp
public bool IsForward { get; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.HVDatumTransformation.yml" sourcestartlinenumber="1">Gets the name of this horizontal/vertical transformation.</p>


```csharp
public string Name { get; }
```
### OutputSpatialReference

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.HVDatumTransformation.yml" sourcestartlinenumber="1">Gets the output spatial reference of this transformation.</p>


```csharp
public override SpatialReference OutputSpatialReference { get; }
```
### OutputVerticalCoordinateSystem

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.HVDatumTransformation.yml" sourcestartlinenumber="1">Gets the output vertical coordinate system of this transformation.</p>


```csharp
public override VerticalCoordinateSystem OutputVerticalCoordinateSystem { get; }
```
### Wkid

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.HVDatumTransformation.yml" sourcestartlinenumber="1">Gets the well-known ID of this horizontal/vertical transformation.</p>


```csharp
public int Wkid { get; }
```
### Wkt

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.HVDatumTransformation.yml" sourcestartlinenumber="1">Gets the well-known text of this horizontal/vertical transformation.</p>


```csharp
public string Wkt { get; }
```


