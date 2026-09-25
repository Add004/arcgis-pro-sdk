# PolylineBuilderEx

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.PolylineBuilderEx.yml" sourcestartlinenumber="1">A builder for creating a <xref href="ArcGIS.Core.Geometry.Polyline?text=polyline" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class PolylineBuilderEx : MultipartBuilderEx
```

## Remarks

<p>
    Use the PolylineBuilderEx class to to create and/or modify a <xref href="ArcGIS.Core.Geometry.Polyline?text=Polyline" data-throw-if-not-resolved="false"></xref> shape. The builder is best suited 
    for editing workflows where the user may be adding, inserting or removing parts of a Polyline geometry interactively. A Polyline
    are based upon the parent <xref href="ArcGIS.Core.Geometry.Geometry?text=Geometry" data-throw-if-not-resolved="false"></xref> class. The Geometry class is immutable which means that you can not change
    its shape once it is created. Hence, the PolylineBuilderEx provides the way to make changes when working with a Polyline. Use the 
    <xref href="ArcGIS.Core.Geometry.PolylineBuilderEx.ToGeometry?text=PolylineBuilderEx.ToGeometry" data-throw-if-not-resolved="false"></xref> method to get the Polyline geometry from the builder.
    </p>
<p></p>
<pre><code sourcefile="api/ArcGIS.Core.Geometry.PolylineBuilderEx.yml" sourcestartlinenumber="10">Most of the PolylineBuilderEx methods can be called on any thread. If a method must be called on the MCT thread, it is noted in the summary.
&lt;img src=&quot;images/ArcGIS.Core.Geometry/MultiPart.png&quot; alt=&quot;Multipart Polyline&quot; /&gt;
</code></pre>


## Members

### PolylineBuilderEx(Envelope)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.PolylineBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the <xref href="ArcGIS.Core.Geometry.PolylineBuilderEx" data-throw-if-not-resolved="false"></xref> class from the input envelope.</p>


```csharp
public PolylineBuilderEx(Envelope envelope)
```
### PolylineBuilderEx(MapPoint, double, double, double, ArcOrientation, ClothoidCreateMethod, double, CurveDensifyMethod, double, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.PolylineBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the <xref href="ArcGIS.Core.Geometry.PolylineBuilderEx" data-throw-if-not-resolved="false"></xref> class that is a linear approximation to a clothoid. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public PolylineBuilderEx(MapPoint startPoint, double startTangentDirection, double startRadius, double endRadius, ArcOrientation orientation, ClothoidCreateMethod createMethod, double lengthOrAngle, CurveDensifyMethod densifyMethod, double curveDensity, SpatialReference spatialReference = null)
```
### PolylineBuilderEx(Multipoint)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.PolylineBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the <xref href="ArcGIS.Core.Geometry.PolylineBuilderEx" data-throw-if-not-resolved="false"></xref> class from the input multipoint.</p>


```csharp
public PolylineBuilderEx(Multipoint multipoint)
```
### PolylineBuilderEx(Polygon)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.PolylineBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the <xref href="ArcGIS.Core.Geometry.PolylineBuilderEx" data-throw-if-not-resolved="false"></xref> class from the parts of a polygon.</p>


```csharp
public PolylineBuilderEx(Polygon polygon)
```
### PolylineBuilderEx(Polyline)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.PolylineBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the <xref href="ArcGIS.Core.Geometry.PolylineBuilderEx" data-throw-if-not-resolved="false"></xref> class from the input polyline.</p>


```csharp
public PolylineBuilderEx(Polyline polyline)
```
### PolylineBuilderEx(PolylineBuilderEx)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.PolylineBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the <xref href="ArcGIS.Core.Geometry.PolylineBuilderEx" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public PolylineBuilderEx(PolylineBuilderEx polylineBuilderEx)
```
### PolylineBuilderEx(Segment, AttributeFlags, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.PolylineBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the <xref href="ArcGIS.Core.Geometry.PolylineBuilderEx" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public PolylineBuilderEx(Segment segment, AttributeFlags attributes, SpatialReference spatialReference = null)
```
### PolylineBuilderEx(SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.PolylineBuilderEx.yml" sourcestartlinenumber="1">Creates an empty instance of the <xref href="ArcGIS.Core.Geometry.PolylineBuilderEx" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public PolylineBuilderEx(SpatialReference spatialReference = null)
```
### PolylineBuilderEx(IEnumerable&lt;Coordinate2D&gt;, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.PolylineBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the <xref href="ArcGIS.Core.Geometry.PolylineBuilderEx" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public PolylineBuilderEx(IEnumerable<Coordinate2D> coordinates, SpatialReference spatialReference = null)
```
### PolylineBuilderEx(IEnumerable&lt;Coordinate3D&gt;, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.PolylineBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the <xref href="ArcGIS.Core.Geometry.PolylineBuilderEx" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public PolylineBuilderEx(IEnumerable<Coordinate3D> coordinates, SpatialReference spatialReference = null)
```
### PolylineBuilderEx(IEnumerable&lt;MapPoint&gt;, AttributeFlags, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.PolylineBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the <xref href="ArcGIS.Core.Geometry.PolylineBuilderEx" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public PolylineBuilderEx(IEnumerable<MapPoint> points, AttributeFlags attributes, SpatialReference spatialReference = null)
```
### PolylineBuilderEx(IEnumerable&lt;Polyline&gt;, AttributeFlags, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.PolylineBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the <xref href="ArcGIS.Core.Geometry.PolylineBuilderEx" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public PolylineBuilderEx(IEnumerable<Polyline> polylines, AttributeFlags attributes, SpatialReference spatialReference = null)
```
### PolylineBuilderEx(IEnumerable&lt;Segment&gt;, AttributeFlags, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.PolylineBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the <xref href="ArcGIS.Core.Geometry.PolylineBuilderEx" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public PolylineBuilderEx(IEnumerable<Segment> segments, AttributeFlags attributes, SpatialReference spatialReference = null)
```
### PolylineBuilderEx(IEnumerable&lt;IEnumerable&lt;Segment&gt;&gt;, AttributeFlags, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.PolylineBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the <xref href="ArcGIS.Core.Geometry.PolylineBuilderEx" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public PolylineBuilderEx(IEnumerable<IEnumerable<Segment>> parts, AttributeFlags attributes, SpatialReference spatialReference = null)
```
### CreatePolyline(Envelope, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.PolylineBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.Polyline" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Polyline CreatePolyline(Envelope envelope, SpatialReference spatialReference = null)
```
### CreatePolyline(MapPoint, double, double, double, ArcOrientation, ClothoidCreateMethod, double, CurveDensifyMethod, double, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.PolylineBuilderEx.yml" sourcestartlinenumber="1">Creates new instance of the <xref href="ArcGIS.Core.Geometry.Polyline" data-throw-if-not-resolved="false"></xref> class that is a linear approximation to a clothoid.</p>


```csharp
public static Polyline CreatePolyline(MapPoint startPoint, double startTangentDirection, double startRadius, double endRadius, ArcOrientation orientation, ClothoidCreateMethod createMethod, double lengthOrAngle, CurveDensifyMethod densifyMethod, double curveDensity, SpatialReference spatialReference = null)
```
### CreatePolyline(Multipoint, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.PolylineBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.Polyline" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Polyline CreatePolyline(Multipoint multipoint, SpatialReference spatialReference = null)
```
### CreatePolyline(Polygon, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.PolylineBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.Polyline" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Polyline CreatePolyline(Polygon polygon, SpatialReference spatialReference = null)
```
### CreatePolyline(Polyline, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.PolylineBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.Polyline" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Polyline CreatePolyline(Polyline polyline, SpatialReference spatialReference = null)
```
### CreatePolyline(PolylineBuilderEx, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.PolylineBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.Polyline" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Polyline CreatePolyline(PolylineBuilderEx polylineBuilderEx, SpatialReference spatialReference = null)
```
### CreatePolyline(Segment, AttributeFlags, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.PolylineBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.Polyline" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Polyline CreatePolyline(Segment segment, AttributeFlags attributes, SpatialReference spatialReference = null)
```
### CreatePolyline(Segment, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.PolylineBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.Polyline" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Polyline CreatePolyline(Segment segment, SpatialReference spatialReference = null)
```
### CreatePolyline(SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.PolylineBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.Polyline" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Polyline CreatePolyline(SpatialReference spatialReference = null)
```
### CreatePolyline(IEnumerable&lt;Coordinate2D&gt;, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.PolylineBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.Polyline" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Polyline CreatePolyline(IEnumerable<Coordinate2D> coordinates, SpatialReference spatialReference = null)
```
### CreatePolyline(IEnumerable&lt;Coordinate3D&gt;, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.PolylineBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.Polyline" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Polyline CreatePolyline(IEnumerable<Coordinate3D> coordinates, SpatialReference spatialReference = null)
```
### CreatePolyline(IEnumerable&lt;MapPoint&gt;, AttributeFlags, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.PolylineBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.Polyline" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Polyline CreatePolyline(IEnumerable<MapPoint> points, AttributeFlags attributes, SpatialReference spatialReference = null)
```
### CreatePolyline(IEnumerable&lt;MapPoint&gt;, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.PolylineBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.Polyline" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Polyline CreatePolyline(IEnumerable<MapPoint> points, SpatialReference spatialReference = null)
```
### CreatePolyline(IEnumerable&lt;Polyline&gt;, AttributeFlags, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.PolylineBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.Polyline" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Polyline CreatePolyline(IEnumerable<Polyline> polylines, AttributeFlags attributes, SpatialReference spatialReference = null)
```
### CreatePolyline(IEnumerable&lt;Polyline&gt;, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.PolylineBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.Polyline" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Polyline CreatePolyline(IEnumerable<Polyline> polylines, SpatialReference spatialReference = null)
```
### CreatePolyline(IEnumerable&lt;Segment&gt;, AttributeFlags, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.PolylineBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.Polyline" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Polyline CreatePolyline(IEnumerable<Segment> segments, AttributeFlags attributes, SpatialReference spatialReference = null)
```
### CreatePolyline(IEnumerable&lt;Segment&gt;, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.PolylineBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.Polyline" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Polyline CreatePolyline(IEnumerable<Segment> segments, SpatialReference spatialReference = null)
```
### CreatePolyline(IEnumerable&lt;IEnumerable&lt;Segment&gt;&gt;, AttributeFlags, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.PolylineBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.Polyline" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Polyline CreatePolyline(IEnumerable<IEnumerable<Segment>> parts, AttributeFlags attributes, SpatialReference spatialReference = null)
```
### CreatePolyline(IEnumerable&lt;IEnumerable&lt;Segment&gt;&gt;, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.PolylineBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.Polyline" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Polyline CreatePolyline(IEnumerable<IEnumerable<Segment>> parts, SpatialReference spatialReference = null)
```
### FromEsriShape(byte[], SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.PolylineBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of a <xref href="ArcGIS.Core.Geometry.Polyline" data-throw-if-not-resolved="false"></xref> class from an Esri shape buffer.</p>


```csharp
public static Polyline FromEsriShape(byte[] esriShapeBuffer, SpatialReference spatialReference = null)
```
### FromJson(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.PolylineBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of a <xref href="ArcGIS.Core.Geometry.Polyline" data-throw-if-not-resolved="false"></xref> class from a JSON string representation.</p>


```csharp
public static Polyline FromJson(string jsonString)
```
### FromXml(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.PolylineBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of a <xref href="ArcGIS.Core.Geometry.Polyline" data-throw-if-not-resolved="false"></xref> class from an XML string representation.</p>


```csharp
public static Polyline FromXml(string xmlString)
```
### GeometryType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.PolylineBuilderEx.yml" sourcestartlinenumber="1">Gets the type of geometry that will be created from this builder. Always returns <xref href="ArcGIS.Core.Geometry.GeometryType.Polyline" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public override GeometryType GeometryType { get; }
```
### IsEqual(PolylineBuilderEx)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.PolylineBuilderEx.yml" sourcestartlinenumber="1">Compares this instance of <xref href="ArcGIS.Core.Geometry.PolylineBuilderEx" data-throw-if-not-resolved="false"></xref> to the other for equality.</p>


```csharp
public bool IsEqual(PolylineBuilderEx other)
```
### QueryClothoidParameters(MapPoint, MapPoint, double, double, double, ArcOrientation, ClothoidCreateMethod, double, out MapPoint, out double, out double, out double, out double, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.PolylineBuilderEx.yml" sourcestartlinenumber="1">Queries parameters to be used when creating an instance <xref href="ArcGIS.Core.Geometry.Polyline" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Core.Geometry.PolylineBuilderEx" data-throw-if-not-resolved="false"></xref> class that is a linear approximation to a clothoid. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void QueryClothoidParameters(MapPoint queryPoint, MapPoint startPoint, double startTangentDirection, double startRadius, double endRadius, ArcOrientation orientation, ClothoidCreateMethod createMethod, double lengthOrAngle, out MapPoint pointOnPath, out double radiusOut, out double tangentDirectionOut, out double lengthOut, out double angleOut, SpatialReference spatialReference = null)
```
### ToGeometry()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.PolylineBuilderEx.yml" sourcestartlinenumber="1">Returns a <xref href="ArcGIS.Core.Geometry.Polyline" data-throw-if-not-resolved="false"></xref> instance representing the current state of the builder.</p>


```csharp
public override Polyline ToGeometry()
```


