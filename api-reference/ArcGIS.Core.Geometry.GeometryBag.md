# GeometryBag

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBag.yml" sourcestartlinenumber="1">A class representing a GeometryBag.   To create a geometry bag use the <xref href="ArcGIS.Core.Geometry.GeometryBagBuilderEx" data-throw-if-not-resolved="false"></xref> object.</p>


## Object Signature

```csharp
public sealed class GeometryBag : Geometry
```

## Remarks

<p>
     A GeometryBag is a heterogeneous collection of <xref href="ArcGIS.Core.Geometry.Geometry?text=Geometry" data-throw-if-not-resolved="false"></xref> objects. A GeometryBag is based upon the parent <xref href="ArcGIS.Core.Geometry.Geometry?text=Geometry" data-throw-if-not-resolved="false"></xref> class. The Geometry class is immutable which means that you can not change
     its shape once it is created. </p>


## Members

### Extent

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBag.yml" sourcestartlinenumber="1">Gets the minimum enclosing envelope of this instance.</p>


```csharp
public override Envelope Extent { get; }
```
### Geometries

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBag.yml" sourcestartlinenumber="1">Gets a list of geometries in this GeometryBag.</p>


```csharp
public IReadOnlyList<Geometry> Geometries { get; }
```
### GeometryType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBag.yml" sourcestartlinenumber="1">Gets the geometry type. Always returns <xref href="ArcGIS.Core.Geometry.GeometryType.GeometryBag" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public override GeometryType GeometryType { get; }
```
### IsEmpty

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBag.yml" sourcestartlinenumber="1">Gets a value indicating whether or not this instance is empty.</p>


```csharp
public override bool IsEmpty { get; }
```
### IsEqual(GeometryBag)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBag.yml" sourcestartlinenumber="1">Compares two <xref href="ArcGIS.Core.Geometry.GeometryBag" data-throw-if-not-resolved="false"></xref> for equality. This will
check that the <xref href="ArcGIS.Core.Geometry.SpatialReference" data-throw-if-not-resolved="false"></xref>, attribute awareness (HasZ, HasM, HasID), and the content of
<xref href="ArcGIS.Core.Geometry.GeometryBag.Geometries" data-throw-if-not-resolved="false"></xref> match. The order of parts must match too.</p>


```csharp
public bool IsEqual(GeometryBag geomteryBag)
```
### IsEqual(GeometryBag, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBag.yml" sourcestartlinenumber="1">Compares two geometry bags for equality while considering the given tolerance.</p>


```csharp
public bool IsEqual(GeometryBag geometryBag, double tolerance)
```
### PartCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBag.yml" sourcestartlinenumber="1">Gets the number of parts (geometries) in this instance.</p>


```csharp
public int PartCount { get; }
```
### PointCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBag.yml" sourcestartlinenumber="1">Gets the count of all points in all parts for this instance.</p>


```csharp
public override int PointCount { get; }
```
### ToEsriShape()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBag.yml" sourcestartlinenumber="1">Converts this GeometryBag into an Esri shape formatted binary byte buffer.</p>


```csharp
public override byte[] ToEsriShape()
```
### ToEsriShape(ref byte[])

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBag.yml" sourcestartlinenumber="1">Converts this GeometryBag into an Esri shape formatted binary byte buffer and returns the size of the shapeBuffer.</p>


```csharp
public override long ToEsriShape(ref byte[] shapeBuffer)
```


