# MultipointBuilderEx

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">A builder for creating a <xref href="ArcGIS.Core.Geometry.Multipoint" data-throw-if-not-resolved="false"></xref> whose methods can be called on any thread.</p>


## Object Signature

```csharp
public sealed class MultipointBuilderEx : GeometryBuilderEx
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Use the MultipointBuilderEx class to to create a Multipoint geometry.
Use the <xref href="ArcGIS.Core.Geometry.MultipointBuilderEx.ToGeometry" data-throw-if-not-resolved="false"></xref>method to get the Multipoint geometry from the builder.</p>
<pre><code sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="4">        &lt;p&gt;&lt;/p&gt;

        The MultipointBuilderEx methods can be called on any thread.
</code></pre>


## Members

### MultipointBuilderEx(MapPoint)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the <xref href="ArcGIS.Core.Geometry.MultipointBuilderEx" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public MultipointBuilderEx(MapPoint point)
```
### MultipointBuilderEx(Multipart)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the <xref href="ArcGIS.Core.Geometry.MultipointBuilderEx" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public MultipointBuilderEx(Multipart multipart)
```
### MultipointBuilderEx(Multipoint)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the <xref href="ArcGIS.Core.Geometry.MultipointBuilderEx" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public MultipointBuilderEx(Multipoint multipoint)
```
### MultipointBuilderEx(MultipointBuilderEx)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the <xref href="ArcGIS.Core.Geometry.MultipointBuilderEx" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public MultipointBuilderEx(MultipointBuilderEx multipointBuilderEx)
```
### MultipointBuilderEx(SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Creates an empty instance of the <xref href="ArcGIS.Core.Geometry.MultipointBuilderEx" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public MultipointBuilderEx(SpatialReference spatialReference = null)
```
### MultipointBuilderEx(IEnumerable&lt;Coordinate2D&gt;, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the <xref href="ArcGIS.Core.Geometry.MultipointBuilderEx" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public MultipointBuilderEx(IEnumerable<Coordinate2D> coordinate2Ds, SpatialReference spatialReference = null)
```
### MultipointBuilderEx(IEnumerable&lt;Coordinate3D&gt;, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the <xref href="ArcGIS.Core.Geometry.MultipointBuilderEx" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public MultipointBuilderEx(IEnumerable<Coordinate3D> coordinate3Ds, SpatialReference spatialReference = null)
```
### MultipointBuilderEx(IEnumerable&lt;MapPoint&gt;, AttributeFlags, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the <xref href="ArcGIS.Core.Geometry.MultipointBuilderEx" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public MultipointBuilderEx(IEnumerable<MapPoint> mapPoints, AttributeFlags attributes, SpatialReference spatialReference = null)
```
### AddPoint(Coordinate2D)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Add a <xref href="ArcGIS.Core.Geometry.Coordinate2D" data-throw-if-not-resolved="false"></xref> to the list of points.</p>


```csharp
public void AddPoint(Coordinate2D coordinate2D)
```
### AddPoint(Coordinate3D)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Add a <xref href="ArcGIS.Core.Geometry.Coordinate3D" data-throw-if-not-resolved="false"></xref> to the list of points.</p>


```csharp
public void AddPoint(Coordinate3D coordinate3D)
```
### AddPoint(MapPoint)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Add a <xref href="ArcGIS.Core.Geometry.MapPoint" data-throw-if-not-resolved="false"></xref> to the list of points.</p>


```csharp
public void AddPoint(MapPoint point)
```
### AddPoints(IEnumerable&lt;Coordinate2D&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Add an enumeration of points to the list of points.</p>


```csharp
public void AddPoints(IEnumerable<Coordinate2D> coordinate2Ds)
```
### AddPoints(IEnumerable&lt;Coordinate3D&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Aadd an enumeration of points to the list of points.</p>


```csharp
public void AddPoints(IEnumerable<Coordinate3D> coordinate3Ds)
```
### AddPoints(IEnumerable&lt;MapPoint&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Add an enumeration of points to the list of points.</p>


```csharp
public void AddPoints(IEnumerable<MapPoint> points)
```
### AddPoints(IEnumerable&lt;Segment&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Add the vertices of the segments in the enumeration to the list of points.</p>


```csharp
public void AddPoints(IEnumerable<Segment> segments)
```
### Coordinate2Ds

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Gets or sets the list of coordinates that define this geometry.</p>


```csharp
public IList<Coordinate2D> Coordinate2Ds { get; set; }
```
### CreateMultipoint(MapPoint, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create an instance of the <xref href="ArcGIS.Core.Geometry.Multipoint" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Multipoint CreateMultipoint(MapPoint point, SpatialReference spatialReference = null)
```
### CreateMultipoint(Multipart, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create an instance of the <xref href="ArcGIS.Core.Geometry.Multipoint" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Multipoint CreateMultipoint(Multipart multipart, SpatialReference spatialReference = null)
```
### CreateMultipoint(Multipoint, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create an instance of the <xref href="ArcGIS.Core.Geometry.Multipoint" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Multipoint CreateMultipoint(Multipoint multipoint, SpatialReference spatialReference = null)
```
### CreateMultipoint(MultipointBuilderEx, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create an instance of the <xref href="ArcGIS.Core.Geometry.Multipoint" data-throw-if-not-resolved="false"></xref> class from the specified multipoint builder.</p>


```csharp
public static Multipoint CreateMultipoint(MultipointBuilderEx multipointBuilderEx, SpatialReference spatialReference = null)
```
### CreateMultipoint(SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create an empty instance of the <xref href="ArcGIS.Core.Geometry.Multipoint" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Multipoint CreateMultipoint(SpatialReference spatialReference = null)
```
### CreateMultipoint(IEnumerable&lt;Coordinate2D&gt;, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create an instance of the <xref href="ArcGIS.Core.Geometry.Multipoint" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Multipoint CreateMultipoint(IEnumerable<Coordinate2D> coordinate2Ds, SpatialReference spatialReference = null)
```
### CreateMultipoint(IEnumerable&lt;Coordinate3D&gt;, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create an instance of the <xref href="ArcGIS.Core.Geometry.Multipoint" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Multipoint CreateMultipoint(IEnumerable<Coordinate3D> coordinate3Ds, SpatialReference spatialReference = null)
```
### CreateMultipoint(IEnumerable&lt;MapPoint&gt;, AttributeFlags, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create an instance of the <xref href="ArcGIS.Core.Geometry.Multipoint" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Multipoint CreateMultipoint(IEnumerable<MapPoint> points, AttributeFlags attributes, SpatialReference spatialReference = null)
```
### CreateMultipoint(IEnumerable&lt;MapPoint&gt;, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create an instance of the <xref href="ArcGIS.Core.Geometry.Multipoint" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Multipoint CreateMultipoint(IEnumerable<MapPoint> points, SpatialReference spatialReference = null)
```
### FromEsriShape(byte[], SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of a <xref href="ArcGIS.Core.Geometry.Multipoint" data-throw-if-not-resolved="false"></xref> class from an Esri shape buffer.</p>


```csharp
public static Multipoint FromEsriShape(byte[] esriShapeBuffer, SpatialReference spatialReference = null)
```
### FromJson(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of a <xref href="ArcGIS.Core.Geometry.Multipoint" data-throw-if-not-resolved="false"></xref> class from a JSON representation.</p>


```csharp
public static Multipoint FromJson(string jsonString)
```
### FromXml(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of a <xref href="ArcGIS.Core.Geometry.Multipoint" data-throw-if-not-resolved="false"></xref> class from an XML string representation.</p>


```csharp
public static Multipoint FromXml(string xmlString)
```
### GeometryType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Gets the type of geometry that will be created from this builder. Always returns <xref href="ArcGIS.Core.Geometry.GeometryType.Multipoint" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public override GeometryType GeometryType { get; }
```
### GetPoint(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Geometry.MapPoint" data-throw-if-not-resolved="false"></xref> at the specified point index.</p>


```csharp
public MapPoint GetPoint(int pointIndex)
```
### HasID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Gets or sets a value indicating if this instance recognizes ID-values, also known as ID-awareness.</p>


```csharp
public override bool HasID { get; set; }
```
### HasM

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Gets or sets a value indicating if this instance recognizes M-values, also known as M-awareness.</p>


```csharp
public override bool HasM { get; set; }
```
### HasZ

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Gets or sets a value indicating if this instance recognizes Z-values, also known as Z-awareness.</p>


```csharp
public override bool HasZ { get; set; }
```
### IDs

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Gets or sets the list of ID-values.</p>


```csharp
public IList<int> IDs { get; set; }
```
### InsertPoint(int, Coordinate2D)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Insert a <xref href="ArcGIS.Core.Geometry.Coordinate2D" data-throw-if-not-resolved="false"></xref> at the specified index to the list of points.</p>


```csharp
public void InsertPoint(int index, Coordinate2D coordinate2D)
```
### InsertPoint(int, Coordinate3D)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Insert a <xref href="ArcGIS.Core.Geometry.Coordinate3D" data-throw-if-not-resolved="false"></xref> at the specified index to the list of points.</p>


```csharp
public void InsertPoint(int index, Coordinate3D coordinate3D)
```
### InsertPoint(int, MapPoint)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Insert a <xref href="ArcGIS.Core.Geometry.MapPoint" data-throw-if-not-resolved="false"></xref> at the specified index to the list of points.</p>


```csharp
public void InsertPoint(int index, MapPoint point)
```
### InsertPoints(int, IEnumerable&lt;Coordinate2D&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Insert a range of points at the specified index.</p>


```csharp
public void InsertPoints(int index, IEnumerable<Coordinate2D> coordinate2Ds)
```
### InsertPoints(int, IEnumerable&lt;Coordinate3D&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Insert a range of points at the specified index.</p>


```csharp
public void InsertPoints(int index, IEnumerable<Coordinate3D> coordinate3Ds)
```
### InsertPoints(int, IEnumerable&lt;MapPoint&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Insert a range of points at the specified index.</p>


```csharp
public void InsertPoints(int index, IEnumerable<MapPoint> points)
```
### InsertPoints(int, IEnumerable&lt;Segment&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Insert the vertices of the segments in the enumeration to the list of points at the specified index.</p>


```csharp
public void InsertPoints(int index, IEnumerable<Segment> segments)
```
### IsEmpty

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Gets a value which determines if this instance is empty. This instance is empty if <xref href="ArcGIS.Core.Geometry.MultipointBuilderEx.Coordinate2Ds" data-throw-if-not-resolved="false"></xref>.Count = 0.</p>


```csharp
public override bool IsEmpty { get; }
```
### IsEqual(MultipointBuilderEx)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Compares this instance of <xref href="ArcGIS.Core.Geometry.MultipointBuilderEx" data-throw-if-not-resolved="false"></xref> to the other for equality.</p>


```csharp
public bool IsEqual(MultipointBuilderEx other)
```
### Ms

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Gets or sets the list of M-values.</p>


```csharp
public IList<double> Ms { get; set; }
```
### PointCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Gets the number of points in this instance.</p>


```csharp
public int PointCount { get; }
```
### RemovePoint(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Remove a point at the specified index.</p>


```csharp
public void RemovePoint(int index)
```
### RemovePoints(int, int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Remove a range of points.</p>


```csharp
public void RemovePoints(int fromIndex, int toIndex)
```
### SetEmpty()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Sets this instance to empty.</p>


```csharp
public override void SetEmpty()
```
### SetPoint(int, Coordinate2D)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Update the point at the specified index.</p>


```csharp
public void SetPoint(int index, Coordinate2D coordinate2D)
```
### SetPoint(int, Coordinate3D)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Update the point at the specified index.</p>


```csharp
public void SetPoint(int index, Coordinate3D coordinate3D)
```
### SetPoint(int, MapPoint)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Update the point at the specified index.</p>


```csharp
public void SetPoint(int index, MapPoint point)
```
### SetPoint(int, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Update the point at the specified index with the specified coordinates.</p>


```csharp
public void SetPoint(int index, double x, double y)
```
### ToGeometry()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Returns a <xref href="ArcGIS.Core.Geometry.Multipoint" data-throw-if-not-resolved="false"></xref> instance representing the current state of the builder.</p>


```csharp
public override Multipoint ToGeometry()
```
### Zs

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">Gets or sets the list of Z-values.</p>


```csharp
public IList<double> Zs { get; set; }
```


