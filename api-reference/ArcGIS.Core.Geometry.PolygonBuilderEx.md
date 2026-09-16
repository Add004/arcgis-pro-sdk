# PolygonBuilderEx

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.PolygonBuilderEx.yml" sourcestartlinenumber="1">A builder for creating a <xref href="ArcGIS.Core.Geometry.Polygon?text=polygon" data-throw-if-not-resolved="false"></xref> whose methods can be called on any thread.</p>


## Object Signature

```csharp
public sealed class PolygonBuilderEx : MultipartBuilderEx
```

## Remarks

<p>
    Use the PolygonBuilderEx class to to create and/or modify a <xref href="ArcGIS.Core.Geometry.Polygon?text=Polygon" data-throw-if-not-resolved="false"></xref> shape. The builder is best suited 
    for editing workflows where the user may be adding, inserting or removing parts of a Polygon geometry interactively. A Polygon
    are based upon the parent <xref href="ArcGIS.Core.Geometry.Geometry?text=Geometry" data-throw-if-not-resolved="false"></xref> class. The Geometry class is immutable which means that you can not change
    its shape once it is created. Hence, the PolygonBuilderEx provides the way to make changes when working with a Polygon. Use the 
    <xref href="ArcGIS.Core.Geometry.PolygonBuilderEx.ToGeometry?text=PolygonBuilderEx.ToGeometry" data-throw-if-not-resolved="false"></xref> method to get the Polygon geometry from the builder.
    </p>
<p>
    A polygon is defined by a collection of rings. Each ring is a collection of contiguous segments such that the start point and the end point of each <xref href="ArcGIS.Core.Geometry.Segment" data-throw-if-not-resolved="false"></xref>
    are the same (that is, it is a closed ring). If a polygon has more than one ring, the rings may be separate from one another or they may nest inside one another, but 
    they should not overlap. Access the rings of a polygon using the <xref href="ArcGIS.Core.Geometry.Multipart.Parts" data-throw-if-not-resolved="false"></xref> method.
    </p>
<p>
    Note: For a polygon to be topologically correct, exterior rings should be clockwise and interior rings should be counterclockwise. If there is ever a doubt 
    about the topological correctness of a polygon, call the <xref href="ArcGIS.Core.Geometry.GeometryEngine.SimplifyAsFeature(ArcGIS.Core.Geometry.Geometry%2cSystem.Boolean)?text=GeometryEngine.SimplifyAsFeature" data-throw-if-not-resolved="false"></xref> 
    method to correct any issues. 
    </p>
<pre><code sourcefile="api/ArcGIS.Core.Geometry.PolygonBuilderEx.yml" sourcestartlinenumber="19">Most of the PolygonBuilderEx methods can be called on any thread. If a method must be called on the MCT thread, it is noted in the summary.
&lt;img src=&quot;images/ArcGIS.Core.Geometry/MultiPart.png&quot; alt=&quot;Multipart Polygon&quot; /&gt;
</code></pre>


## Members

### PolygonBuilderEx(Envelope)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.PolygonBuilderEx.yml" sourcestartlinenumber="1">Initializes a new instance of the <xref href="ArcGIS.Core.Geometry.PolygonBuilderEx" data-throw-if-not-resolved="false"></xref> class from the input envelope.</p>


```csharp
public PolygonBuilderEx(Envelope envelope)
```
### PolygonBuilderEx(Multipoint)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.PolygonBuilderEx.yml" sourcestartlinenumber="1">Initializes a new instance of the <xref href="ArcGIS.Core.Geometry.PolygonBuilderEx" data-throw-if-not-resolved="false"></xref> class from the input multipoint.</p>


```csharp
public PolygonBuilderEx(Multipoint multipoint)
```
### PolygonBuilderEx(Polygon)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.PolygonBuilderEx.yml" sourcestartlinenumber="1">Initializes a new instance of the <xref href="ArcGIS.Core.Geometry.PolygonBuilderEx" data-throw-if-not-resolved="false"></xref> class from the input polygon.</p>


```csharp
public PolygonBuilderEx(Polygon polygon)
```
### PolygonBuilderEx(PolygonBuilderEx)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.PolygonBuilderEx.yml" sourcestartlinenumber="1">Initializes a new instance of the <xref href="ArcGIS.Core.Geometry.PolygonBuilderEx" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public PolygonBuilderEx(PolygonBuilderEx polygonBuilderEx)
```
### PolygonBuilderEx(Polyline)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.PolygonBuilderEx.yml" sourcestartlinenumber="1">Initializes a new instance of the <xref href="ArcGIS.Core.Geometry.PolygonBuilderEx" data-throw-if-not-resolved="false"></xref> class from the parts of a polyline.</p>


```csharp
public PolygonBuilderEx(Polyline polyline)
```
### PolygonBuilderEx(SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.PolygonBuilderEx.yml" sourcestartlinenumber="1">Initializes an empty instance of the <xref href="ArcGIS.Core.Geometry.PolygonBuilderEx" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public PolygonBuilderEx(SpatialReference spatialReference = null)
```
### PolygonBuilderEx(IEnumerable&lt;Coordinate2D&gt;, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.PolygonBuilderEx.yml" sourcestartlinenumber="1">Initializes a new instance of the <xref href="ArcGIS.Core.Geometry.PolygonBuilderEx" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public PolygonBuilderEx(IEnumerable<Coordinate2D> coordinate2Ds, SpatialReference spatialReference = null)
```
### PolygonBuilderEx(IEnumerable&lt;Coordinate3D&gt;, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.PolygonBuilderEx.yml" sourcestartlinenumber="1">Initializes a new instance of the <xref href="ArcGIS.Core.Geometry.PolygonBuilderEx" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public PolygonBuilderEx(IEnumerable<Coordinate3D> coordinate3Ds, SpatialReference spatialReference = null)
```
### PolygonBuilderEx(IEnumerable&lt;MapPoint&gt;, AttributeFlags, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.PolygonBuilderEx.yml" sourcestartlinenumber="1">Initializes a new instance of the <xref href="ArcGIS.Core.Geometry.PolygonBuilderEx" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public PolygonBuilderEx(IEnumerable<MapPoint> points, AttributeFlags attributes, SpatialReference spatialReference = null)
```
### PolygonBuilderEx(IEnumerable&lt;Polygon&gt;, AttributeFlags, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.PolygonBuilderEx.yml" sourcestartlinenumber="1">Initializes a new instance of the <xref href="ArcGIS.Core.Geometry.PolygonBuilderEx" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public PolygonBuilderEx(IEnumerable<Polygon> polygons, AttributeFlags attributes, SpatialReference spatialReference = null)
```
### PolygonBuilderEx(IEnumerable&lt;Segment&gt;, AttributeFlags, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.PolygonBuilderEx.yml" sourcestartlinenumber="1">Initializes a new instance of the <xref href="ArcGIS.Core.Geometry.PolygonBuilderEx" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public PolygonBuilderEx(IEnumerable<Segment> segments, AttributeFlags attributes, SpatialReference spatialReference = null)
```
### PolygonBuilderEx(IEnumerable&lt;IEnumerable&lt;Segment&gt;&gt;, AttributeFlags, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.PolygonBuilderEx.yml" sourcestartlinenumber="1">Initializes a new instance of the <xref href="ArcGIS.Core.Geometry.PolygonBuilderEx" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public PolygonBuilderEx(IEnumerable<IEnumerable<Segment>> parts, AttributeFlags attributes, SpatialReference spatialReference = null)
```
### CreatePolygon(Envelope, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.PolygonBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.Polygon" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Polygon CreatePolygon(Envelope envelope, SpatialReference spatialReference = null)
```
### CreatePolygon(Multipoint, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.PolygonBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.Polygon" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Polygon CreatePolygon(Multipoint multipoint, SpatialReference spatialReference = null)
```
### CreatePolygon(Polygon, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.PolygonBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.Polygon" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Polygon CreatePolygon(Polygon polygon, SpatialReference spatialReference = null)
```
### CreatePolygon(PolygonBuilderEx, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.PolygonBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.Polygon" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Polygon CreatePolygon(PolygonBuilderEx polygonBuilderEx, SpatialReference spatialReference = null)
```
### CreatePolygon(Polyline, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.PolygonBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.Polygon" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Polygon CreatePolygon(Polyline polyline, SpatialReference spatialReference = null)
```
### CreatePolygon(SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.PolygonBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.Polygon" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Polygon CreatePolygon(SpatialReference spatialReference = null)
```
### CreatePolygon(IEnumerable&lt;Coordinate2D&gt;, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.PolygonBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.Polygon" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Polygon CreatePolygon(IEnumerable<Coordinate2D> coordinate2Ds, SpatialReference spatialReference = null)
```
### CreatePolygon(IEnumerable&lt;Coordinate3D&gt;, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.PolygonBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.Polygon" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Polygon CreatePolygon(IEnumerable<Coordinate3D> coordinate3Ds, SpatialReference spatialReference = null)
```
### CreatePolygon(IEnumerable&lt;MapPoint&gt;, AttributeFlags, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.PolygonBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.Polygon" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Polygon CreatePolygon(IEnumerable<MapPoint> points, AttributeFlags attributes, SpatialReference spatialReference = null)
```
### CreatePolygon(IEnumerable&lt;MapPoint&gt;, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.PolygonBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.Polygon" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Polygon CreatePolygon(IEnumerable<MapPoint> points, SpatialReference spatialReference = null)
```
### CreatePolygon(IEnumerable&lt;Polygon&gt;, AttributeFlags, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.PolygonBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.Polygon" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Polygon CreatePolygon(IEnumerable<Polygon> polygons, AttributeFlags attributes, SpatialReference spatialReference = null)
```
### CreatePolygon(IEnumerable&lt;Polygon&gt;, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.PolygonBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.Polygon" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Polygon CreatePolygon(IEnumerable<Polygon> polygons, SpatialReference spatialReference = null)
```
### CreatePolygon(IEnumerable&lt;Segment&gt;, AttributeFlags, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.PolygonBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.Polygon" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Polygon CreatePolygon(IEnumerable<Segment> segments, AttributeFlags attributes, SpatialReference spatialReference = null)
```
### CreatePolygon(IEnumerable&lt;Segment&gt;, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.PolygonBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.Polygon" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Polygon CreatePolygon(IEnumerable<Segment> segments, SpatialReference spatialReference = null)
```
### CreatePolygon(IEnumerable&lt;IEnumerable&lt;Segment&gt;&gt;, AttributeFlags, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.PolygonBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.Polygon" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Polygon CreatePolygon(IEnumerable<IEnumerable<Segment>> parts, AttributeFlags attributes, SpatialReference spatialReference = null)
```
### CreatePolygon(IEnumerable&lt;IEnumerable&lt;Segment&gt;&gt;, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.PolygonBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.Polygon" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Polygon CreatePolygon(IEnumerable<IEnumerable<Segment>> parts, SpatialReference spatialReference = null)
```
### FromEsriShape(byte[], SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.PolygonBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of a <xref href="ArcGIS.Core.Geometry.Polygon" data-throw-if-not-resolved="false"></xref> class from an Esri shape buffer.</p>


```csharp
public static Polygon FromEsriShape(byte[] esriShapeBuffer, SpatialReference spatialReference = null)
```
### FromJson(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.PolygonBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of a <xref href="ArcGIS.Core.Geometry.Polygon" data-throw-if-not-resolved="false"></xref> class from a JSON string representation.</p>


```csharp
public static Polygon FromJson(string jsonString)
```
### FromXml(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.PolygonBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of a <xref href="ArcGIS.Core.Geometry.Polygon" data-throw-if-not-resolved="false"></xref> class from an XML string representation.</p>


```csharp
public static Polygon FromXml(string xmlString)
```
### GeometryType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.PolygonBuilderEx.yml" sourcestartlinenumber="1">Gets the type of geometry that will be created from this builder. Always returns <xref href="ArcGIS.Core.Geometry.GeometryType.Polygon" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public override GeometryType GeometryType { get; }
```
### IsEqual(PolygonBuilderEx)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.PolygonBuilderEx.yml" sourcestartlinenumber="1">Compares this instance of <xref href="ArcGIS.Core.Geometry.PolygonBuilderEx" data-throw-if-not-resolved="false"></xref> to the other for equality.</p>


```csharp
public bool IsEqual(PolygonBuilderEx other)
```
### ToGeometry()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.PolygonBuilderEx.yml" sourcestartlinenumber="1">Returns a <xref href="ArcGIS.Core.Geometry.Polygon" data-throw-if-not-resolved="false"></xref> instance representing the current state of the builder.</p>


```csharp
public override Polygon ToGeometry()
```


