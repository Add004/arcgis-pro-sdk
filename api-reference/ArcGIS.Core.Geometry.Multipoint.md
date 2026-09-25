# Multipoint

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.Multipoint.yml" sourcestartlinenumber="1">A Multipoint is a ordered collection of <xref href="ArcGIS.Core.Geometry.MapPoint?text=map+points" data-throw-if-not-resolved="false"></xref>. To create a multipoint use the
<xref href="ArcGIS.Core.Geometry.MultipointBuilderEx" data-throw-if-not-resolved="false"></xref> object.</p>


## Object Signature

```csharp
public sealed class Multipoint : Geometry
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Geometry.Multipoint.yml" sourcestartlinenumber="1">A Multipoint is a one-dimensional geometry object which can be used to store a collection
of point-based information.</p>
<pre><code sourcefile="api/ArcGIS.Core.Geometry.Multipoint.yml" sourcestartlinenumber="4">       &lt;p&gt;
       The interior of a multipoint is the set of points in the collection, the boundary is the empty set, and the exterior is the set of points that are not in the collection.
       &lt;/p&gt;&lt;p&gt;
       A Multipoint is based upon the parent &lt;xref href=&quot;ArcGIS.Core.Geometry.Geometry?text=Geometry&quot; data-throw-if-not-resolved=&quot;false&quot;&gt;&lt;/xref&gt; class. The Geometry class is immutable which means that you can not change
       its shape once it is created. If you need to modify a Multipoint once it has been created, use the &lt;xref href=&quot;ArcGIS.Core.Geometry.MultipointBuilderEx?text=MultipointBuilderEx&quot; data-throw-if-not-resolved=&quot;false&quot;&gt;&lt;/xref&gt;
       class instead. The &lt;xref href=&quot;ArcGIS.Core.Geometry.MultipointBuilderEx.ToGeometry?text=MultipointBuilderEx.ToGeometry&quot; data-throw-if-not-resolved=&quot;false&quot;&gt;&lt;/xref&gt; method will provide you with the Multipoint object. 
       &lt;/p&gt;
</code></pre>


## Members

### Copy2DCoordinatesToList()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Multipoint.yml" sourcestartlinenumber="1">Gets a copy of all the points as a read-only list of 2D coordinates.</p>


```csharp
public IReadOnlyList<Coordinate2D> Copy2DCoordinatesToList()
```
### Copy3DCoordinatesToList()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Multipoint.yml" sourcestartlinenumber="1">Gets a copy of all the points as a read-only list of 3D coordinates.</p>


```csharp
public IReadOnlyList<Coordinate3D> Copy3DCoordinatesToList()
```
### Extent

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Multipoint.yml" sourcestartlinenumber="1">Gets the minimum enclosing envelope of this instance.</p>


```csharp
public override Envelope Extent { get; }
```
### GeometryType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Multipoint.yml" sourcestartlinenumber="1">Gets the geometry type. Always returns <xref href="ArcGIS.Core.Geometry.GeometryType.Multipoint" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public override GeometryType GeometryType { get; }
```
### IsEmpty

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Multipoint.yml" sourcestartlinenumber="1">Gets a value indicating whether or not this instance is empty.</p>


```csharp
public override bool IsEmpty { get; }
```
### IsEqual(Multipoint)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Multipoint.yml" sourcestartlinenumber="1">Compares two <xref href="ArcGIS.Core.Geometry.Multipoint" data-throw-if-not-resolved="false"></xref> for equality. This will check the <xref href="ArcGIS.Core.Geometry.SpatialReference" data-throw-if-not-resolved="false"></xref>,
attribute awareness (HasZ, HasM, HasID), and coordinates for a match.</p>


```csharp
public bool IsEqual(Multipoint multiPoint)
```
### IsEqual(Multipoint, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Multipoint.yml" sourcestartlinenumber="1">Compares two <xref href="ArcGIS.Core.Geometry.Multipoint" data-throw-if-not-resolved="false"></xref> instances for equality using a tolerance.</p>


```csharp
public bool IsEqual(Multipoint multipoint, double tolerance)
```
### PointCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Multipoint.yml" sourcestartlinenumber="1">Gets the count of points in this instance.</p>


```csharp
public override int PointCount { get; }
```
### Points

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Multipoint.yml" sourcestartlinenumber="1">Gets the collection of points.</p>


```csharp
public ReadOnlyPointCollection Points { get; }
```
### ToEsriShape()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Multipoint.yml" sourcestartlinenumber="1">Returns this Multipoint as an Esri shape formatted binary byte buffer.</p>


```csharp
public override byte[] ToEsriShape()
```
### ToEsriShape(ref byte[])

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Multipoint.yml" sourcestartlinenumber="1">Converts this Multipoint into an Esri shape formatted binary byte buffer and returns the size of the shapeBuffer.</p>


```csharp
public override long ToEsriShape(ref byte[] shapeBuffer)
```


