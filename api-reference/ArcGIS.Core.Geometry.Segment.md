# Segment

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.Segment.yml" sourcestartlinenumber="1">Abstract class representing a start and end point and how they are connected. The most common is a straight line <xref href="ArcGIS.Core.Geometry.LineSegment" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public abstract class Segment
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Geometry.Segment.yml" sourcestartlinenumber="1">Segments are used as the building blocks of the parts of <xref href="ArcGIS.Core.Geometry.Polygon" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Core.Geometry.Polyline" data-throw-if-not-resolved="false"></xref> classes.</p>


## Members

### EndCoordinate

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Segment.yml" sourcestartlinenumber="1">Gets the end point as a <xref href="ArcGIS.Core.Geometry.Coordinate2D" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public Coordinate2D EndCoordinate { get; }
```
### EndPoint

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Segment.yml" sourcestartlinenumber="1">Gets the end point.</p>


```csharp
public MapPoint EndPoint { get; }
```
### IsCurve

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Segment.yml" sourcestartlinenumber="1">Gets if this segment is a curve.</p>


```csharp
public abstract bool IsCurve { get; }
```
### IsEqual(Segment)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Segment.yml" sourcestartlinenumber="1">Compares two <xref href="ArcGIS.Core.Geometry.Segment" data-throw-if-not-resolved="false"></xref> for equality.  Compares <xref href="ArcGIS.Core.Geometry.Segment.SegmentType" data-throw-if-not-resolved="false"></xref>, <xref href="ArcGIS.Core.Geometry.Segment.SpatialReference" data-throw-if-not-resolved="false"></xref>, and coordinates for equality.</p>


```csharp
public bool IsEqual(Segment other)
```
### IsEqual(Segment, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Segment.yml" sourcestartlinenumber="1">Compares two segments for equality while considering the given tolerance.</p>


```csharp
public bool IsEqual(Segment other, double tolerance)
```
### Length

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Segment.yml" sourcestartlinenumber="1">Gets the length.</p>


```csharp
public abstract double Length { get; }
```
### SegmentType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Segment.yml" sourcestartlinenumber="1">Gets the segment type.</p>


```csharp
public abstract SegmentType SegmentType { get; }
```
### SpatialReference

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Segment.yml" sourcestartlinenumber="1">Gets the spatial reference.</p>


```csharp
public SpatialReference SpatialReference { get; }
```
### StartCoordinate

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Segment.yml" sourcestartlinenumber="1">Gets the start point as a <xref href="ArcGIS.Core.Geometry.Coordinate2D" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public Coordinate2D StartCoordinate { get; }
```
### StartPoint

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Segment.yml" sourcestartlinenumber="1">Gets the start point.</p>


```csharp
public MapPoint StartPoint { get; }
```


