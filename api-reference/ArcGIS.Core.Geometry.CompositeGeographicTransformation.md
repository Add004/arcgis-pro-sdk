# CompositeGeographicTransformation

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.CompositeGeographicTransformation.yml" sourcestartlinenumber="1">A composite geographic transformation class is an ordered list of <xref href="ArcGIS.Core.Geometry.GeographicTransformation" data-throw-if-not-resolved="false"></xref> classes.
The geographic transformations are applied in the order they are stored.</p>


## Object Signature

```csharp
public sealed class CompositeGeographicTransformation : DatumTransformation
```


## Members

### Count

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.CompositeGeographicTransformation.yml" sourcestartlinenumber="1">Gets the number of single transformations in this composite transformation.</p>


```csharp
public int Count { get; }
```
### Create(IEnumerable&lt;GeographicTransformation&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.CompositeGeographicTransformation.yml" sourcestartlinenumber="1">Creates a new <xref href="ArcGIS.Core.Geometry.CompositeGeographicTransformation" data-throw-if-not-resolved="false"></xref> instance that contains the list of GeographicTransformation instances.</p>


```csharp
public static CompositeGeographicTransformation Create(IEnumerable<GeographicTransformation> geoTransformations)
```
### Create(int, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.CompositeGeographicTransformation.yml" sourcestartlinenumber="1">Creates a new <xref href="ArcGIS.Core.Geometry.GeographicTransformation" data-throw-if-not-resolved="false"></xref> instance with the given well-known ID and direction, and adds to it a new CompositeGeographicTransformation instance.</p>


```csharp
public static CompositeGeographicTransformation Create(int wkid, bool transformForward = true)
```
### Create(string, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.CompositeGeographicTransformation.yml" sourcestartlinenumber="1">Creates a new <xref href="ArcGIS.Core.Geometry.GeographicTransformation" data-throw-if-not-resolved="false"></xref> instance with the given well-known text and direction, and adds it to a new CompositeGeographicTransformation instance.</p>


```csharp
public static CompositeGeographicTransformation Create(string wkt, bool transformForward = true)
```
### GetInverse()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.CompositeGeographicTransformation.yml" sourcestartlinenumber="1">Creates an inverted instance of this tranformation. The inverted instance has inverted order of <xref href="ArcGIS.Core.Geometry.GeographicTransformation" data-throw-if-not-resolved="false"></xref> instances,
and each geographic transformation has its IsForward property inverted.</p>


```csharp
public override DatumTransformation GetInverse()
```
### this[int]

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.CompositeGeographicTransformation.yml" sourcestartlinenumber="1">Gets the single transformation at the specified index.</p>


```csharp
public GeographicTransformation this[int index] { get; }
```
### ToJson()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.CompositeGeographicTransformation.yml" sourcestartlinenumber="1">Returns the JSON representation of this transformation.</p>


```csharp
public override string ToJson()
```
### Transformations

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.CompositeGeographicTransformation.yml" sourcestartlinenumber="1">Gets the list of transformations in this composite transformation.</p>


```csharp
public IList<GeographicTransformation> Transformations { get; }
```


