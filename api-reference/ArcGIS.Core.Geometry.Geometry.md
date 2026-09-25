# Geometry

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.Geometry.yml" sourcestartlinenumber="1">An abstract base class for objects that define geometric shapes. Geometry objects can be used
as geometry definitions for rendering data.</p>


## Object Signature

```csharp
public abstract class Geometry
```


## Members

### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Geometry.yml" sourcestartlinenumber="1">Clones this geometry instance. As geometry objects are immutable and hence never change, the clone returned will be this object rather than a copy of
this instance.</p>


```csharp
public Geometry Clone()
```
### Dimension

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Geometry.yml" sourcestartlinenumber="1">Gets the dimension of the geometry.</p>


```csharp
public int Dimension { get; }
```
### Extent

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Geometry.yml" sourcestartlinenumber="1">Gets the minimum enclosing envelope of the instance. Returns null if this geometry has IsEmpty = true.</p>


```csharp
public abstract Envelope Extent { get; }
```
### GeometryType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Geometry.yml" sourcestartlinenumber="1">Gets the geometry type of the instance.</p>


```csharp
public abstract GeometryType GeometryType { get; }
```
### HasID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Geometry.yml" sourcestartlinenumber="1">Gets a value indicating if the geometry has ID.</p>


```csharp
public bool HasID { get; }
```
### HasM

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Geometry.yml" sourcestartlinenumber="1">Gets a value indicating if the geometry has M.</p>


```csharp
public bool HasM { get; }
```
### HasZ

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Geometry.yml" sourcestartlinenumber="1">Gets a value indicating if the geometry has Z.</p>


```csharp
public bool HasZ { get; }
```
### IsEmpty

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Geometry.yml" sourcestartlinenumber="1">Gets a value indicating whether or not the geometry is empty.</p>


```csharp
public abstract bool IsEmpty { get; }
```
### IsEqual(Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Geometry.yml" sourcestartlinenumber="1">Compares two <xref href="ArcGIS.Core.Geometry.Geometry" data-throw-if-not-resolved="false"></xref> for equality. Compares <xref href="ArcGIS.Core.Geometry.Geometry.GeometryType" data-throw-if-not-resolved="false"></xref>, <xref href="ArcGIS.Core.Geometry.Geometry.SpatialReference" data-throw-if-not-resolved="false"></xref>, and coordinates for equality.</p>


```csharp
public bool IsEqual(Geometry other)
```
### IsEqual(Geometry, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Geometry.yml" sourcestartlinenumber="1">Compares two geometries for equality while considering the given tolerance.</p>


```csharp
public bool IsEqual(Geometry other, double tolerance)
```
### IsKnownMSimple

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Geometry.yml" sourcestartlinenumber="1">Indicates whether this geometry is known to be M-simple. A geometry is M-simple if all the M-values are not NaN.
False will be returned if <xref href="ArcGIS.Core.Geometry.GeometryEngine.IsMSimple(ArcGIS.Core.Geometry.Geometry)" data-throw-if-not-resolved="false"></xref> has never been called.</p>


```csharp
public bool IsKnownMSimple { get; }
```
### IsKnownSimple

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Geometry.yml" sourcestartlinenumber="1">Indicates whether this geometry is known to be topologically consistent according to the geometry type for storage in a database.</p>


```csharp
public bool IsKnownSimple { get; }
```
### IsKnownSimpleOgc

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Geometry.yml" sourcestartlinenumber="1">Indicates whether this geometry is known to be topologically consistent according to the Open Geospatial Consortium (OGC) validation specification.</p>


```csharp
public bool IsKnownSimpleOgc { get; }
```
### Length

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Geometry.yml" sourcestartlinenumber="1">Gets the length of this geometry</p>


```csharp
public virtual double Length { get; }
```
### PointCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Geometry.yml" sourcestartlinenumber="1">Gets the number of points that comprise this geometry.</p>


```csharp
public abstract int PointCount { get; }
```
### SpatialReference

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Geometry.yml" sourcestartlinenumber="1">Gets the spatial reference of this instance.</p>


```csharp
public SpatialReference SpatialReference { get; }
```
### ToEsriShape()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Geometry.yml" sourcestartlinenumber="1">Returns this geometry as an Esri shape formatted binary byte buffer.</p>


```csharp
public abstract byte[] ToEsriShape()
```
### ToEsriShape(ref byte[])

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Geometry.yml" sourcestartlinenumber="1">Converts this geometry into an Esri shape formatted binary byte buffer and returns the size of the shapeBuffer.</p>


```csharp
public abstract long ToEsriShape(ref byte[] shapeBuffer)
```
### ToJson(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Geometry.yml" sourcestartlinenumber="1">Serializes this geometry instance into an ArcGIS JSON geometry representation.</p>


```csharp
public string ToJson(bool skipSR = false)
```
### ToXml()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Geometry.yml" sourcestartlinenumber="1">Serializes this geometry instance into an ArcGIS XML geometry representation.</p>


```csharp
public string ToXml()
```


