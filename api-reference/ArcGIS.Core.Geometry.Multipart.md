# Multipart

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.Multipart.yml" sourcestartlinenumber="1">An abstract base class for multipart geometry types.</p>


## Object Signature

```csharp
public abstract class Multipart : Geometry
```

## Remarks

<p>
    A Multipart is based upon the parent <xref href="ArcGIS.Core.Geometry.Geometry?text=Geometry" data-throw-if-not-resolved="false"></xref> class. The Geometry class is immutable which means that you can not change
    its shape once it is created. If you need to modify a Multipart once it has been created, use the MultipartBuilderEx
    class instead. The MultipartBuilderEx.ToGeometry method will provide you with the base Geometry object. 
    </p>


## Members

### Area

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Multipart.yml" sourcestartlinenumber="1">Gets the area of this instance.</p>


```csharp
public abstract double Area { get; }
```
### Copy2DCoordinatesToList()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Multipart.yml" sourcestartlinenumber="1">Gets a copy of all the coordinates in all parts as a read-only list of 2D coordinates.</p>


```csharp
public IReadOnlyList<Coordinate2D> Copy2DCoordinatesToList()
```
### Copy3DCoordinatesToList()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Multipart.yml" sourcestartlinenumber="1">Gets a copy of all the coordinates in all parts as a read-only list of 3D coordinates.</p>


```csharp
public IReadOnlyList<Coordinate3D> Copy3DCoordinatesToList()
```
### Extent

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Multipart.yml" sourcestartlinenumber="1">Gets the minimum enclosing envelope of this instance.</p>


```csharp
public override Envelope Extent { get; }
```
### GetAllSegments(ref ICollection&lt;Segment&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Multipart.yml" sourcestartlinenumber="1">Gets all the segments in this instance.</p>


```csharp
public void GetAllSegments(ref ICollection<Segment> segments)
```
### HasCurves

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Multipart.yml" sourcestartlinenumber="1">Gets a boolean value indicating whether or not the multipart contains segments other than straight line segments.</p>


```csharp
public bool HasCurves { get; }
```
### IsEmpty

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Multipart.yml" sourcestartlinenumber="1">Gets a value indicating whether or not this instance is empty.</p>


```csharp
public override bool IsEmpty { get; }
```
### IsEqual(Multipart)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Multipart.yml" sourcestartlinenumber="1">Compares two <xref href="ArcGIS.Core.Geometry.Multipart" data-throw-if-not-resolved="false"></xref> for equality. This will check the <xref href="ArcGIS.Core.Geometry.SpatialReference" data-throw-if-not-resolved="false"></xref>,
attribute awareness (HasZ, HasM, HasID), and coordinates for a match.</p>


```csharp
public bool IsEqual(Multipart multipart)
```
### IsEqual(Multipart, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Multipart.yml" sourcestartlinenumber="1">Compares two multiparts for equality while considering the given tolerance.</p>


```csharp
public bool IsEqual(Multipart multipart, double tolerance)
```
### Length

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Multipart.yml" sourcestartlinenumber="1">Gets the 2D length of this instance.</p>


```csharp
public override double Length { get; }
```
### Length3D

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Multipart.yml" sourcestartlinenumber="1">Gets the 3D length of this instance.</p>


```csharp
public virtual double Length3D { get; }
```
### PartCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Multipart.yml" sourcestartlinenumber="1">Gets the number of parts in this instance.</p>


```csharp
public int PartCount { get; }
```
### Parts

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Multipart.yml" sourcestartlinenumber="1">Gets the parts in this instance.</p>


```csharp
public virtual ReadOnlyPartCollection Parts { get; }
```
### PointCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Multipart.yml" sourcestartlinenumber="1">Gets the count of all points in all parts for this instance.</p>


```csharp
public override int PointCount { get; }
```
### Points

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Multipart.yml" sourcestartlinenumber="1">Gets a collection of points representing the vertices of all the parts.</p>


```csharp
public ReadOnlyPointCollection Points { get; }
```
### ToEsriShape()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Multipart.yml" sourcestartlinenumber="1">Converts this Multipart into an Esri shape formatted binary byte buffer.</p>


```csharp
public override byte[] ToEsriShape()
```
### ToEsriShape(ref byte[])

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Multipart.yml" sourcestartlinenumber="1">Converts this Multipart into an Esri shape formatted binary byte buffer and returns the size of the shapeBuffer.</p>


```csharp
public override long ToEsriShape(ref byte[] shapeBuffer)
```


