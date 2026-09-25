# ReadOnlyPartCollection

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.ReadOnlyPartCollection.yml" sourcestartlinenumber="1">A Read-only collection of <xref href="ArcGIS.Core.Geometry.ReadOnlySegmentCollection" data-throw-if-not-resolved="false"></xref> parts used by
<xref href="ArcGIS.Core.Geometry.Polyline" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Core.Geometry.Polygon" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class ReadOnlyPartCollection : IReadOnlyCollection<ReadOnlySegmentCollection>, IEnumerable<ReadOnlySegmentCollection>, IEnumerable
```


## Members

### Count

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.ReadOnlyPartCollection.yml" sourcestartlinenumber="1">Gets the number of elements contained in the <xref href="System.Collections.Generic.ICollection%601" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public int Count { get; }
```
### GetEnumerator()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.ReadOnlyPartCollection.yml" sourcestartlinenumber="1">Returns an enumerator that iterates through the collection.</p>


```csharp
public IEnumerator<ReadOnlySegmentCollection> GetEnumerator()
```
### this[int]

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.ReadOnlyPartCollection.yml" sourcestartlinenumber="1">Gets the element at the specified index.</p>


```csharp
public ReadOnlySegmentCollection this[int index] { get; }
```
### SpatialReference

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.ReadOnlyPartCollection.yml" sourcestartlinenumber="1">Gets or sets the <xref href="ArcGIS.Core.Geometry.SpatialReference?text=SpatialReference" data-throw-if-not-resolved="false"></xref> used for this read-only part collection.</p>


```csharp
public SpatialReference SpatialReference { get; set; }
```


