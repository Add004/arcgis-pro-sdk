# CompositeHVDatumTransformation

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.CompositeHVDatumTransformation.yml" sourcestartlinenumber="1">A composite hv (horizontal/vertical) datum transformation class is an ordered list of <xref href="ArcGIS.Core.Geometry.HVDatumTransformation" data-throw-if-not-resolved="false"></xref> classes.
The hv datum transformations are applied in the order they are stored.</p>


## Object Signature

```csharp
public sealed class CompositeHVDatumTransformation : DatumTransformation
```


## Members

### Count

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.CompositeHVDatumTransformation.yml" sourcestartlinenumber="1">Gets the number of single transformations in this composite transformation.</p>


```csharp
public int Count { get; }
```
### Create(IEnumerable&lt;HVDatumTransformation&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.CompositeHVDatumTransformation.yml" sourcestartlinenumber="1">Creates a new <xref href="ArcGIS.Core.Geometry.CompositeHVDatumTransformation" data-throw-if-not-resolved="false"></xref> instance that contains the list of <xref href="ArcGIS.Core.Geometry.HVDatumTransformation" data-throw-if-not-resolved="false"></xref> instances.</p>


```csharp
public static CompositeHVDatumTransformation Create(IEnumerable<HVDatumTransformation> hvTransformations)
```
### Create(int, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.CompositeHVDatumTransformation.yml" sourcestartlinenumber="1">Creates a new <xref href="ArcGIS.Core.Geometry.HVDatumTransformation" data-throw-if-not-resolved="false"></xref> instance with the given well-known ID and direction, and adds to it a new CompositeHVDatumTransformation instance.</p>


```csharp
public static CompositeHVDatumTransformation Create(int wkid, bool transformForward = true)
```
### Create(string, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.CompositeHVDatumTransformation.yml" sourcestartlinenumber="1">Creates a new <xref href="ArcGIS.Core.Geometry.HVDatumTransformation" data-throw-if-not-resolved="false"></xref> instance with the given well-known text and direction, and adds it to a new CompositeHVDatumTransformation instance.</p>


```csharp
public static CompositeHVDatumTransformation Create(string wkt, bool transformForward = true)
```
### CreateFromXml(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.CompositeHVDatumTransformation.yml" sourcestartlinenumber="1">Creates a new <xref href="ArcGIS.Core.Geometry.CompositeHVDatumTransformation" data-throw-if-not-resolved="false"></xref> from the given XML.</p>


```csharp
public static CompositeHVDatumTransformation CreateFromXml(string xmlString)
```
### CreateNull(SpatialReference, SpatialReference, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.CompositeHVDatumTransformation.yml" sourcestartlinenumber="1">Creates a new <xref href="ArcGIS.Core.Geometry.CompositeHVDatumTransformation" data-throw-if-not-resolved="false"></xref> instance representing the 'null' method for a pair of spatial references.</p>


```csharp
public static CompositeHVDatumTransformation CreateNull(SpatialReference inputSR, SpatialReference outputSR, bool transformForward = true)
```
### GetInverse()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.CompositeHVDatumTransformation.yml" sourcestartlinenumber="1">Creates an inverted instance of this HVDatumTransformation. The inverted instance has inverted order of
<xref href="ArcGIS.Core.Geometry.HVDatumTransformation" data-throw-if-not-resolved="false"></xref> instances, and each hv datum transformation has its IsForward property inverted.</p>


```csharp
public override DatumTransformation GetInverse()
```
### this[int]

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.CompositeHVDatumTransformation.yml" sourcestartlinenumber="1">Gets the single transformation at the specified index.</p>


```csharp
public HVDatumTransformation this[int index] { get; }
```
### ToJson()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.CompositeHVDatumTransformation.yml" sourcestartlinenumber="1">Returns the JSON representation of this transformation.</p>


```csharp
public override string ToJson()
```
### ToXml()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.CompositeHVDatumTransformation.yml" sourcestartlinenumber="1">Returns the XML representation of this composite transformation.</p>


```csharp
public string ToXml()
```
### Transformations

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.CompositeHVDatumTransformation.yml" sourcestartlinenumber="1">Gets the list of transformations in this composite transformation.</p>


```csharp
public IList<HVDatumTransformation> Transformations { get; }
```


