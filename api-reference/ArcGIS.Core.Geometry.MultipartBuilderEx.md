# MultipartBuilderEx

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.MultipartBuilderEx.yml" sourcestartlinenumber="1">An abstract base class for creating a <xref href="ArcGIS.Core.Geometry.Polyline" data-throw-if-not-resolved="false"></xref> or a <xref href="ArcGIS.Core.Geometry.Polygon" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public abstract class MultipartBuilderEx : GeometryBuilderEx
```

## Remarks

<p>
    Use the MultipartBuilderEx class to to create and/or modify a base <xref href="ArcGIS.Core.Geometry.Multipart?text=Multipart" data-throw-if-not-resolved="false"></xref> shape.
    The builder is best suited for editing workflows where the user may be adding, inserting or removing parts of a
    Multipart geometry interactively. A Multipart is based upon the parent <xref href="ArcGIS.Core.Geometry.Geometry?text=Geometry" data-throw-if-not-resolved="false"></xref> class.
    The Geometry class is immutable which means that you can not change its shape once it is created. Hence, the
    MultipartBuilderEx provides the way to make changes when working with a Multipart. Use the 
    <xref href="ArcGIS.Core.Geometry.PolylineBuilderEx.ToGeometry" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Core.Geometry.PolygonBuilderEx.ToGeometry" data-throw-if-not-resolved="false"></xref>
    method to get the Multipart from the builder.
    </p>
<pre><code sourcefile="api/ArcGIS.Core.Geometry.MultipartBuilderEx.yml" sourcestartlinenumber="11">The MultipointBuilderEx methods can be called on any thread.
</code></pre>


## Members

### AddPart(IEnumerable&lt;Coordinate2D&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipartBuilderEx.yml" sourcestartlinenumber="1">Adds a part constructed by creating line segments from the enumeration of coordinates. The part will be added to the end
of the <xref href="ArcGIS.Core.Geometry.MultipartBuilderEx.Parts" data-throw-if-not-resolved="false"></xref> list.</p>


```csharp
public void AddPart(IEnumerable<Coordinate2D> coordinates)
```
### AddPart(IEnumerable&lt;Coordinate3D&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipartBuilderEx.yml" sourcestartlinenumber="1">Adds a part constructed by creating line segments from the enumeration of coordinates. The part will be added to the end
of the <xref href="ArcGIS.Core.Geometry.MultipartBuilderEx.Parts" data-throw-if-not-resolved="false"></xref> list.</p>


```csharp
public void AddPart(IEnumerable<Coordinate3D> coordinates)
```
### AddPart(IEnumerable&lt;MapPoint&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipartBuilderEx.yml" sourcestartlinenumber="1">Adds a part constructed by creating line segments from the enumeration of points. The part will be added to the end
of the <xref href="ArcGIS.Core.Geometry.MultipartBuilderEx.Parts" data-throw-if-not-resolved="false"></xref> list.</p>


```csharp
public void AddPart(IEnumerable<MapPoint> points)
```
### AddPart(IEnumerable&lt;Segment&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipartBuilderEx.yml" sourcestartlinenumber="1">Adds a part constructed from the enumeration of segments to the MultipartBuilderEx. The part will be added to the end
of the <xref href="ArcGIS.Core.Geometry.MultipartBuilderEx.Parts" data-throw-if-not-resolved="false"></xref> list.</p>


```csharp
public void AddPart(IEnumerable<Segment> segments)
```
### AddParts(IEnumerable&lt;IEnumerable&lt;Segment&gt;&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipartBuilderEx.yml" sourcestartlinenumber="1">Adds the parts constructed from the set of enumeration of segments to the MultipartBuilderEx.
The parts will be added to the end of the <xref href="ArcGIS.Core.Geometry.MultipartBuilderEx.Parts" data-throw-if-not-resolved="false"></xref> list.</p>


```csharp
public void AddParts(IEnumerable<IEnumerable<Segment>> parts)
```
### AddSegment(Segment, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipartBuilderEx.yml" sourcestartlinenumber="1">Adds a segment to the end of the last part of the MultipartBuilderEx. The segment will be added to the end
of the <xref href="ArcGIS.Core.Geometry.MultipartBuilderEx.Parts" data-throw-if-not-resolved="false"></xref> list.</p>


```csharp
public void AddSegment(Segment segment, bool startNewPart = false)
```
### AddSegment(SegmentBuilderEx, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipartBuilderEx.yml" sourcestartlinenumber="1">Add a segment to the MultipartBuilderEx using a segment builder. The segment will be added to the end
of the <xref href="ArcGIS.Core.Geometry.MultipartBuilderEx.Parts" data-throw-if-not-resolved="false"></xref> list.</p>


```csharp
public void AddSegment(SegmentBuilderEx segmentBuilder, bool startNewPart = false)
```
### AddSegments(IEnumerable&lt;Segment&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipartBuilderEx.yml" sourcestartlinenumber="1">Adds segments to the MultipartBuilderEx.
The segments will be added to the end of the <xref href="ArcGIS.Core.Geometry.MultipartBuilderEx.Parts" data-throw-if-not-resolved="false"></xref> list.</p>


```csharp
public void AddSegments(IEnumerable<Segment> segments, bool startNewPart = false)
```
### AddSegments(int, IEnumerable&lt;Segment&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipartBuilderEx.yml" sourcestartlinenumber="1">Adds segments to the MultipartBuilderEx.
The segments will be added to the end of the <xref href="ArcGIS.Core.Geometry.MultipartBuilderEx.Parts" data-throw-if-not-resolved="false"></xref> list.</p>


```csharp
public void AddSegments(int partIndex, IEnumerable<Segment> segments)
```
### GetSegment(int, int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipartBuilderEx.yml" sourcestartlinenumber="1">Gets the segment at the specified index.</p>


```csharp
public Segment GetSegment(int partIndex, int segmentIndex)
```
### GetSegmentCount(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipartBuilderEx.yml" sourcestartlinenumber="1">Gets the number of segments in the specified part.</p>


```csharp
public int GetSegmentCount(int partIndex)
```
### HasID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.MultipartBuilderEx.yml" sourcestartlinenumber="1">Gets or sets the HasID flag which indicates whether the geometry contains IDs.</p>


```csharp
public override bool HasID { get; set; }
```
### HasM

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.MultipartBuilderEx.yml" sourcestartlinenumber="1">Gets or sets the HasM flag which indicates whether the geometry contains Ms.</p>


```csharp
public override bool HasM { get; set; }
```
### HasZ

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.MultipartBuilderEx.yml" sourcestartlinenumber="1">Gets or sets the HasZ flag which indicates whether the geometry contains Zs.</p>


```csharp
public override bool HasZ { get; set; }
```
### InsertPart(int, IEnumerable&lt;Coordinate2D&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipartBuilderEx.yml" sourcestartlinenumber="1">Inserts a part constructed from the enumeration of coordinates to the MultipartBuilderEx. The part will be inserted into
the <xref href="ArcGIS.Core.Geometry.MultipartBuilderEx.Parts" data-throw-if-not-resolved="false"></xref> list.</p>


```csharp
public void InsertPart(int beforePartIndex, IEnumerable<Coordinate2D> coordinates)
```
### InsertPart(int, IEnumerable&lt;Coordinate3D&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipartBuilderEx.yml" sourcestartlinenumber="1">Inserts a part constructed from the enumeration of coordinates. The part will be inserted into
the <xref href="ArcGIS.Core.Geometry.MultipartBuilderEx.Parts" data-throw-if-not-resolved="false"></xref> list.</p>


```csharp
public void InsertPart(int beforePartIndex, IEnumerable<Coordinate3D> coordinates)
```
### InsertPart(int, IEnumerable&lt;MapPoint&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipartBuilderEx.yml" sourcestartlinenumber="1">Inserts a part constructed from the enumeration of points. The part will be inserted into
the <xref href="ArcGIS.Core.Geometry.MultipartBuilderEx.Parts" data-throw-if-not-resolved="false"></xref> list.</p>


```csharp
public void InsertPart(int beforePartIndex, IEnumerable<MapPoint> points)
```
### InsertPart(int, IEnumerable&lt;Segment&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipartBuilderEx.yml" sourcestartlinenumber="1">Inserts a part constructed from the enumeration of segments to the MultipartBuilderEx. The part will be inserted into
the <xref href="ArcGIS.Core.Geometry.MultipartBuilderEx.Parts" data-throw-if-not-resolved="false"></xref> list.</p>


```csharp
public void InsertPart(int beforePartIndex, IEnumerable<Segment> segments)
```
### InsertParts(int, IEnumerable&lt;IEnumerable&lt;Segment&gt;&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipartBuilderEx.yml" sourcestartlinenumber="1">Inserts parts constructed from the set of enumeration of segments to the MultipartBuilderEx.
The parts will be inserted to the <xref href="ArcGIS.Core.Geometry.MultipartBuilderEx.Parts" data-throw-if-not-resolved="false"></xref> list before the specified index.</p>


```csharp
public void InsertParts(int beforePartIndex, IEnumerable<IEnumerable<Segment>> parts)
```
### InsertSegment(int, int, Segment)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipartBuilderEx.yml" sourcestartlinenumber="1">Inserts a segment into an existing part.</p>


```csharp
public void InsertSegment(int partIndex, int beforeSegmentIndex, Segment segment)
```
### InsertSegment(int, int, SegmentBuilderEx)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipartBuilderEx.yml" sourcestartlinenumber="1">Inserts a segment into an existing part using a segment builder.</p>


```csharp
public void InsertSegment(int partIndex, int beforeSegmentIndex, SegmentBuilderEx segmentBuilder)
```
### InsertSegments(int, int, IEnumerable&lt;Segment&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipartBuilderEx.yml" sourcestartlinenumber="1">Inserts a range of segments into an existing part.</p>


```csharp
public void InsertSegments(int partIndex, int beforeSegmentIndex, IEnumerable<Segment> segments)
```
### IsEmpty

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.MultipartBuilderEx.yml" sourcestartlinenumber="1">Gets a boolean which indicates if this instance is empty or not.
This instance is empty if it has zero parts.</p>


```csharp
public override bool IsEmpty { get; }
```
### IsEqual(MultipartBuilderEx)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipartBuilderEx.yml" sourcestartlinenumber="1">Compares this instance of MultipartBuilderEx to the other for equality</p>


```csharp
public bool IsEqual(MultipartBuilderEx other)
```
### PartCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.MultipartBuilderEx.yml" sourcestartlinenumber="1">Gets the number of parts.</p>


```csharp
public int PartCount { get; }
```
### Parts

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.MultipartBuilderEx.yml" sourcestartlinenumber="1">Gets or sets the list of parts that define this builder.</p>


```csharp
public IList<List<Segment>> Parts { get; set; }
```
### RemovePart(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipartBuilderEx.yml" sourcestartlinenumber="1">Remove the part specified by <code class="paramref">partIndex</code>.</p>


```csharp
public void RemovePart(int partIndex)
```
### RemoveParts(int, int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipartBuilderEx.yml" sourcestartlinenumber="1">Removes a range of parts.</p>


```csharp
public void RemoveParts(int fromPartIndex, int toPartIndex)
```
### RemoveSegment(int, int, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipartBuilderEx.yml" sourcestartlinenumber="1">Remove the segment at the specified index from the part specified by <code class="paramref">partIndex</code>.</p>


```csharp
public void RemoveSegment(int partIndex, int segmentIndex, bool closeGap)
```
### ReplaceSegment(int, int, Segment)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipartBuilderEx.yml" sourcestartlinenumber="1">Replace the segment at the specified index from the part specified by <code class="paramref">partIndex</code>.</p>
<p></p><p></p>
<p sourcefile="api/ArcGIS.Core.Geometry.MultipartBuilderEx.yml" sourcestartlinenumber="5">Note: Values of partIndex = -1, segmentIndex = -1 replaces the last segment from the last part of the multipart.</p>


```csharp
public void ReplaceSegment(int partIndex, int segmentIndex, Segment segment)
```
### ReverseOrientation()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipartBuilderEx.yml" sourcestartlinenumber="1">Changes the direction of the parts without changing the spatial position of the parts.<br>
The start point and end point of each segment in each part are interchanged.</p>


```csharp
public void ReverseOrientation()
```
### SetEmpty()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipartBuilderEx.yml" sourcestartlinenumber="1">Sets this instance to empty by clearing the <xref href="ArcGIS.Core.Geometry.MultipartBuilderEx.Parts" data-throw-if-not-resolved="false"></xref> list.</p>


```csharp
public override void SetEmpty()
```
### SplitAtDistance(double, bool, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipartBuilderEx.yml" sourcestartlinenumber="1">Introduces a new vertex into the multipart at a specified distance from the beginning of the multipart.
For a split to happen, the split distance must be between the start and end points of the multipart.</p>


```csharp
public int SplitAtDistance(double distance, bool asRatio, bool createPart = false)
```
### SplitPartAtDistance(int, double, bool, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.MultipartBuilderEx.yml" sourcestartlinenumber="1">Introduces a new vertex to the part specified by <code class="paramref">partIndex</code> at a specified
distance from the start point of the first segment in the part. For a split to happen, the
split distance must be between the start and end points of the part.</p>


```csharp
public int SplitPartAtDistance(int partIndex, double distance, bool asRatio, bool createPart = false)
```


