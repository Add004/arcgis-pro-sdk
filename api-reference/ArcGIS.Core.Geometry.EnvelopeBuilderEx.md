# EnvelopeBuilderEx

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">A builder for creating an <xref href="ArcGIS.Core.Geometry.Envelope" data-throw-if-not-resolved="false"></xref> whose methods can be called on any thread.</p>


## Object Signature

```csharp
public sealed class EnvelopeBuilderEx : GeometryBuilderEx
```

## Remarks

<pre><code sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">        Use the EnvelopeBuilderEx class to to create and/or modify an &lt;xref href=&quot;ArcGIS.Core.Geometry.Envelope&quot; data-throw-if-not-resolved=&quot;false&quot;&gt;&lt;/xref&gt; shape. An Envelope
        is based upon the parent &lt;xref href=&quot;ArcGIS.Core.Geometry.Geometry?text=Geometry&quot; data-throw-if-not-resolved=&quot;false&quot;&gt;&lt;/xref&gt; class. The Geometry class is immutable which means that you can not change
        its shape once it is created. Hence, the EnvelopeBuilderEx provides the way to make changes when working with an Envelope. Use the 
        &lt;xref href=&quot;ArcGIS.Core.Geometry.EnvelopeBuilderEx.ToGeometry&quot; data-throw-if-not-resolved=&quot;false&quot;&gt;&lt;/xref&gt; method to get the Envelope geometry from the builder.

        &lt;p&gt;
        An &lt;xref href=&quot;ArcGIS.Core.Geometry.Envelope&quot; data-throw-if-not-resolved=&quot;false&quot;&gt;&lt;/xref&gt; is an axis-aligned box described by the coordinates
        of the lower left corner and the coordinates of the upper right corner.
        &lt;/p&gt;&lt;p&gt;
        The EnvelopeBuilderEx methods can be called on any thread.
</code></pre>
<p></p>


## Members

### EnvelopeBuilderEx(Coordinate2D, Coordinate2D, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the EnvelopeBuilderEx class.</p>


```csharp
public EnvelopeBuilderEx(Coordinate2D minCoord, Coordinate2D maxCoord, SpatialReference spatialReference = null)
```
### EnvelopeBuilderEx(Coordinate3D, Coordinate3D, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the EnvelopeBuilderEx class.</p>


```csharp
public EnvelopeBuilderEx(Coordinate3D minCoord, Coordinate3D maxCoord, SpatialReference spatialReference = null)
```
### EnvelopeBuilderEx(Envelope)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the EnvelopeBuilderEx class.</p>


```csharp
public EnvelopeBuilderEx(Envelope envelope)
```
### EnvelopeBuilderEx(EnvelopeBuilderEx)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the <xref href="ArcGIS.Core.Geometry.EnvelopeBuilderEx" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public EnvelopeBuilderEx(EnvelopeBuilderEx envelopeBuilderEx)
```
### EnvelopeBuilderEx(MapPoint, MapPoint, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the EnvelopeBuilderEx class.</p>


```csharp
public EnvelopeBuilderEx(MapPoint minPoint, MapPoint maxPoint, SpatialReference spatialReference = null)
```
### EnvelopeBuilderEx(SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Creates a new empty instance of the EnvelopeBuilderEx class.</p>


```csharp
public EnvelopeBuilderEx(SpatialReference spatialReference = null)
```
### EnvelopeBuilderEx(double, double, double, double, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the EnvelopeBuilderEx class.</p>


```csharp
public EnvelopeBuilderEx(double xMin, double yMin, double xMax, double yMax, SpatialReference spatialReference = null)
```
### Center

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Gets or sets the center point of this instance.</p>


```csharp
public MapPoint Center { get; set; }
```
### CenterCoordinate

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Gets or sets the center point of this instance formatted as a <xref href="ArcGIS.Core.Geometry.Coordinate2D" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public Coordinate2D CenterCoordinate { get; set; }
```
### CreateEnvelope(Coordinate2D, Coordinate2D, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.Envelope" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Envelope CreateEnvelope(Coordinate2D minCoord, Coordinate2D maxCoord, SpatialReference spatialReference = null)
```
### CreateEnvelope(Coordinate3D, Coordinate3D, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.Envelope" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Envelope CreateEnvelope(Coordinate3D minCoord, Coordinate3D maxCoord, SpatialReference spatialReference = null)
```
### CreateEnvelope(Envelope, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.Envelope" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Envelope CreateEnvelope(Envelope envelope, SpatialReference spatialReference = null)
```
### CreateEnvelope(EnvelopeBuilderEx, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.Envelope" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Envelope CreateEnvelope(EnvelopeBuilderEx envelopeBuilderEx, SpatialReference spatialReference = null)
```
### CreateEnvelope(MapPoint, MapPoint, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.Envelope" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Envelope CreateEnvelope(MapPoint minPoint, MapPoint maxPoint, SpatialReference spatialReference = null)
```
### CreateEnvelope(SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.Envelope" data-throw-if-not-resolved="false"></xref> class. The new instance is empty.</p>


```csharp
public static Envelope CreateEnvelope(SpatialReference spatialReference = null)
```
### CreateEnvelope(double, double, double, double, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.Envelope" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static Envelope CreateEnvelope(double xMin, double yMin, double xMax, double yMax, SpatialReference spatialReference = null)
```
### Depth

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Gets the depth of this instance.</p>


```csharp
public double Depth { get; }
```
### Expand(double, double, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Moves the X and Y coordinates of the envelope sides toward or away from each other to scale the size of the envelope.</p>


```csharp
public void Expand(double dx, double dy, bool asRatio)
```
### Expand(double, double, double, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Moves the X, Y and Z coordinates of the envelope sides toward or away from each other to scale the size of the envelope.</p>


```csharp
public void Expand(double dx, double dy, double dz, bool asRatio)
```
### FromEsriShape(byte[], SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the <xref href="ArcGIS.Core.Geometry.Envelope" data-throw-if-not-resolved="false"></xref> class from an Esri shape buffer.</p>


```csharp
public static Envelope FromEsriShape(byte[] esriShapeBuffer, SpatialReference spatialReference = null)
```
### FromJson(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the <xref href="ArcGIS.Core.Geometry.Envelope" data-throw-if-not-resolved="false"></xref> class from an ArcGIS JSON geometry representation.</p>


```csharp
public static Envelope FromJson(string jsonString)
```
### FromXml(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the <xref href="ArcGIS.Core.Geometry.Envelope" data-throw-if-not-resolved="false"></xref> class from an ArcGIS XML string representation.</p>


```csharp
public static Envelope FromXml(string xmlString)
```
### GeometryType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Gets the type of geometry that will be created from this builder. Always returns <xref href="ArcGIS.Core.Geometry.GeometryType.Envelope" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public override GeometryType GeometryType { get; }
```
### HasID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Gets or sets a value indicating if the <xref href="ArcGIS.Core.Geometry.EnvelopeBuilderEx" data-throw-if-not-resolved="false"></xref> recognizes ID-values also known as ID-awareness.</p>


```csharp
public override bool HasID { get; set; }
```
### HasM

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Gets or sets a value indicating if the <xref href="ArcGIS.Core.Geometry.EnvelopeBuilderEx" data-throw-if-not-resolved="false"></xref> recognizes M-values also known as M-awareness.</p>


```csharp
public override bool HasM { get; set; }
```
### HasZ

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Gets or sets a value indicating if the <xref href="ArcGIS.Core.Geometry.EnvelopeBuilderEx" data-throw-if-not-resolved="false"></xref> recognizes Z-values also known as Z-awareness.</p>


```csharp
public override bool HasZ { get; set; }
```
### Height

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Gets the height of this instance.</p>


```csharp
public double Height { get; }
```
### IDMax

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Gets or sets the ID maximum of this instance.</p>


```csharp
public int IDMax { get; set; }
```
### IDMin

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Gets or sets the ID minimum of this instance.</p>


```csharp
public int IDMin { get; set; }
```
### Intersection(Envelope)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Intersects the <code class="paramref">envelope</code> with the EnvelopeBuilderEx.</p>


```csharp
public void Intersection(Envelope envelope)
```
### Intersects(Envelope)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Checks if the input <xref href="ArcGIS.Core.Geometry.Envelope" data-throw-if-not-resolved="false"></xref> intersects the EnvelopeBuilderEx.</p>


```csharp
public bool Intersects(Envelope envelope)
```
### IsEmpty

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Gets a boolean indicating if the geometry of this builder is empty.</p>


```csharp
public override bool IsEmpty { get; }
```
### IsEqual(EnvelopeBuilderEx)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Compares this instance of <xref href="ArcGIS.Core.Geometry.EnvelopeBuilderEx" data-throw-if-not-resolved="false"></xref> to the other for equality.</p>


```csharp
public bool IsEqual(EnvelopeBuilderEx other)
```
### MMax

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Gets or sets the M maximum of this instance.</p>


```csharp
public double MMax { get; set; }
```
### MMin

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Gets or sets the M minimum of this instance.</p>


```csharp
public double MMin { get; set; }
```
### SetCoords(Envelope)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Sets the coordinates from the input envelope.</p>


```csharp
public void SetCoords(Envelope envelope)
```
### SetEmpty()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Sets the geometry of this builder to empty.</p>


```csharp
public override void SetEmpty()
```
### SetIDCoords(int, int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Sets the ID-coordinates, that is, IDMin and IDMax. Also sets HasID = true.</p>


```csharp
public void SetIDCoords(int id1, int id2)
```
### SetMCoords(double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Sets the M-coordinates, that is, MMin and MMax. Also sets HasM = true.</p>


```csharp
public void SetMCoords(double m1, double m2)
```
### SetXYCoords(Coordinate2D, Coordinate2D)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Sets the xy-coordinates, that is, XMin, YMin, XMax, YMax.</p>


```csharp
public void SetXYCoords(Coordinate2D coordinate1, Coordinate2D coordinate2)
```
### SetZCoords(double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Sets the Z-coordinates, that is, ZMin and ZMax. Also sets HasZ = true.</p>


```csharp
public void SetZCoords(double z1, double z2)
```
### ToGeometry()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Returns an <xref href="ArcGIS.Core.Geometry.Envelope" data-throw-if-not-resolved="false"></xref> instance representing the current state of the builder.</p>


```csharp
public override Envelope ToGeometry()
```
### Union(Envelope)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Unions the <code class="paramref">envelope</code> with the EnvelopeBuilderEx.</p>


```csharp
public void Union(Envelope envelope)
```
### Width

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Gets the width of this instance.</p>


```csharp
public double Width { get; }
```
### XMax

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Gets or sets the X maximum of this instance.</p>


```csharp
public double XMax { get; set; }
```
### XMin

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Gets or sets the X minimum of this instance.</p>


```csharp
public double XMin { get; set; }
```
### YMax

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Gets or sets the Y maximum of this instance.</p>


```csharp
public double YMax { get; set; }
```
### YMin

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Gets or sets the Y minimum of this instance.</p>


```csharp
public double YMin { get; set; }
```
### ZMax

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Gets or sets the Z maximum of this instance.</p>


```csharp
public double ZMax { get; set; }
```
### ZMin

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">Gets or sets the Z minimum of this instance.</p>


```csharp
public double ZMin { get; set; }
```


