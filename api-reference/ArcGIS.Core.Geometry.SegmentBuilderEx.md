# SegmentBuilderEx

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.SegmentBuilderEx.yml" sourcestartlinenumber="1">Abstract base class for builders of all segment types to include:</p>
<ul><li>Line</li><li>Bezier curve</li><li>Elliptic Arc</li></ul><remarks>The SegmentBuilderEx methods can be called on any thread.</remarks>


## Object Signature

```csharp
public abstract class SegmentBuilderEx
```


## Members

### ConstructSegmentBuilder(Segment)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.SegmentBuilderEx.yml" sourcestartlinenumber="1">Construct a segment builder from the segment.</p>


```csharp
public static SegmentBuilderEx ConstructSegmentBuilder(Segment segment)
```
### EndPoint

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SegmentBuilderEx.yml" sourcestartlinenumber="1">Gets or sets the end point.</p>


```csharp
public virtual MapPoint EndPoint { get; set; }
```
### IsEmpty

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SegmentBuilderEx.yml" sourcestartlinenumber="1">Gets if the builder is empty.  A builder is empty if the <xref href="ArcGIS.Core.Geometry.SegmentBuilderEx.StartPoint" data-throw-if-not-resolved="false"></xref> is empty or the <xref href="ArcGIS.Core.Geometry.SegmentBuilderEx.EndPoint" data-throw-if-not-resolved="false"></xref> is empty.</p>


```csharp
public bool IsEmpty { get; }
```
### SetEmpty()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.SegmentBuilderEx.yml" sourcestartlinenumber="1">Sets the builder empty.</p>


```csharp
public void SetEmpty()
```
### SpatialReference

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SegmentBuilderEx.yml" sourcestartlinenumber="1">Gets or sets the spatial reference.</p>


```csharp
public SpatialReference SpatialReference { get; set; }
```
### StartPoint

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.SegmentBuilderEx.yml" sourcestartlinenumber="1">Gets or sets the start point.</p>


```csharp
public virtual MapPoint StartPoint { get; set; }
```
### ToSegment()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.SegmentBuilderEx.yml" sourcestartlinenumber="1">Abstract method that returns a <xref href="ArcGIS.Core.Geometry.Segment" data-throw-if-not-resolved="false"></xref> instance representing the current state of the builder.</p>


```csharp
public abstract Segment ToSegment()
```


