# ReadOnlyPointCollection

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.ReadOnlyPointCollection.yml" sourcestartlinenumber="1">A read-only collection of <xref href="ArcGIS.Core.Geometry.MapPoint?text=MapPoints" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class ReadOnlyPointCollection : IReadOnlyCollection<MapPoint>, IEnumerable<MapPoint>, IEnumerable
```


## Members

### Copy2DCoordinatesToList()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.ReadOnlyPointCollection.yml" sourcestartlinenumber="1">Gets a copy of all the MapPoints in the list as a read-only list of 2D coordinates.</p>


```csharp
public IReadOnlyList<Coordinate2D> Copy2DCoordinatesToList()
```
### Copy2DCoordinatesToList(int, int, ref ICollection&lt;Coordinate2D&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.ReadOnlyPointCollection.yml" sourcestartlinenumber="1">Copies the MapPoints in this list to the given list of 2D coordinates.</p>


```csharp
public void Copy2DCoordinatesToList(int startIndex, int pointCount, ref ICollection<Coordinate2D> coordinates)
```
### Copy3DCoordinatesToList()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.ReadOnlyPointCollection.yml" sourcestartlinenumber="1">Gets a copy of all the MapPoints in the list as a read-only list of 3D coordinates.</p>


```csharp
public IReadOnlyList<Coordinate3D> Copy3DCoordinatesToList()
```
### Copy3DCoordinatesToList(int, int, ref ICollection&lt;Coordinate3D&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.ReadOnlyPointCollection.yml" sourcestartlinenumber="1">Copies the MapPoints in this list to the given list of 3D coordinates.</p>


```csharp
public void Copy3DCoordinatesToList(int startIndex, int pointCount, ref ICollection<Coordinate3D> coordinates)
```
### CopyPointsToList(int, int, ref ICollection&lt;MapPoint&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.ReadOnlyPointCollection.yml" sourcestartlinenumber="1">Copies the MapPoints in this list to the given list of MapPoints.</p>


```csharp
public void CopyPointsToList(int startIndex, int pointCount, ref ICollection<MapPoint> points)
```
### Count

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.ReadOnlyPointCollection.yml" sourcestartlinenumber="1">Gets the number of elements contained in the <xref href="System.Collections.Generic.ICollection%601" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public int Count { get; }
```
### GetEnumerator()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.ReadOnlyPointCollection.yml" sourcestartlinenumber="1">Returns an enumerator that iterates through the collection.</p>


```csharp
public IEnumerator<MapPoint> GetEnumerator()
```
### this[int]

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.ReadOnlyPointCollection.yml" sourcestartlinenumber="1">Gets the element at the specified index.</p>


```csharp
public MapPoint this[int index] { get; }
```
### SpatialReference

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.ReadOnlyPointCollection.yml" sourcestartlinenumber="1">Gets or sets the <xref href="ArcGIS.Core.Geometry.SpatialReference?text=SpatialReference" data-throw-if-not-resolved="false"></xref> used for this read-only point collection.</p>


```csharp
public SpatialReference SpatialReference { get; set; }
```


