# GeometryBagBuilderEx

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBagBuilderEx.yml" sourcestartlinenumber="1">Builder for creating a <xref href="ArcGIS.Core.Geometry.GeometryBag?text=GeometryBag" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class GeometryBagBuilderEx : GeometryBuilderEx
```

## Remarks

<p>
    Use the GeometryBagBuilderEx class to to create a <xref href="ArcGIS.Core.Geometry.GeometryBag?text=GeometryBag" data-throw-if-not-resolved="false"></xref> shape. A GeometryBag
    is based upon the parent <xref href="ArcGIS.Core.Geometry.Geometry?text=Geometry" data-throw-if-not-resolved="false"></xref> class. Use the 
    <xref href="ArcGIS.Core.Geometry.GeometryBagBuilderEx.ToGeometry?text=GeometryBagBuilderEx.ToGeometry" data-throw-if-not-resolved="false"></xref> method to get the GeometryBag geometry from the builder.
    </p>
<p>
    The spatial reference of the GeometryBagBuilderEx is transferred to the GeometryBag and any geometries it contains after calling
    <xref href="ArcGIS.Core.Geometry.GeometryBagBuilderEx.ToGeometry?text=GeometryBagBuilderEx.ToGeometry" data-throw-if-not-resolved="false"></xref>. 
    However, the spatial reference of the added geometry is ignored, and is not transferred to the GeometryBagBuilderEx. Adding a
    geometry that is not in the domain of the spatial reference could lead to unexpected results.
    </p>
<p>
    An Envelope is converted to a Polygon when a GeometryBag is created by calling <xref href="ArcGIS.Core.Geometry.GeometryBagBuilderEx.ToGeometry?text=GeometryBagBuilderEx.ToGeometry" data-throw-if-not-resolved="false"></xref>.
    As a result, when retrieving an Envelope from a GeometryBag, it will be a Polygon.</p>


## Members

### GeometryBagBuilderEx(GeometryBag)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBagBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the <xref href="ArcGIS.Core.Geometry.GeometryBagBuilderEx" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public GeometryBagBuilderEx(GeometryBag geometryBag)
```
### GeometryBagBuilderEx(GeometryBagBuilderEx)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBagBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the <xref href="ArcGIS.Core.Geometry.GeometryBagBuilderEx" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public GeometryBagBuilderEx(GeometryBagBuilderEx geometryBagBuilderEx)
```
### GeometryBagBuilderEx(SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBagBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the <xref href="ArcGIS.Core.Geometry.GeometryBagBuilderEx" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public GeometryBagBuilderEx(SpatialReference spatialReference = null)
```
### GeometryBagBuilderEx(IEnumerable&lt;Geometry&gt;, AttributeFlags, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBagBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the <xref href="ArcGIS.Core.Geometry.GeometryBagBuilderEx" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public GeometryBagBuilderEx(IEnumerable<Geometry> geometries, AttributeFlags attributeFlags, SpatialReference spatialReference = null)
```
### GeometryBagBuilderEx(IEnumerable&lt;Geometry&gt;, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBagBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of the <xref href="ArcGIS.Core.Geometry.GeometryBagBuilderEx" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public GeometryBagBuilderEx(IEnumerable<Geometry> geometries, SpatialReference spatialReference = null)
```
### AddGeometries(IEnumerable&lt;Geometry&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBagBuilderEx.yml" sourcestartlinenumber="1">Adds the given list of geometries to the end of the list of geometries in this GeometryBag.</p>


```csharp
public void AddGeometries(IEnumerable<Geometry> geometries)
```
### AddGeometry(Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBagBuilderEx.yml" sourcestartlinenumber="1">Adds the given geometry to the end of the list of geometries in this GeometryBag.</p>


```csharp
public void AddGeometry(Geometry geometry)
```
### CreateGeometryBag(GeometryBag, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBagBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.GeometryBag" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static GeometryBag CreateGeometryBag(GeometryBag geometryBag, SpatialReference spatialReference = null)
```
### CreateGeometryBag(GeometryBagBuilderEx, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBagBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.GeometryBag" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static GeometryBag CreateGeometryBag(GeometryBagBuilderEx geometryBagBuilderEx, SpatialReference spatialReference = null)
```
### CreateGeometryBag(SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBagBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new empty instance of the <xref href="ArcGIS.Core.Geometry.GeometryBag" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static GeometryBag CreateGeometryBag(SpatialReference spatialReference = null)
```
### CreateGeometryBag(IEnumerable&lt;Geometry&gt;, AttributeFlags, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBagBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.GeometryBag" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static GeometryBag CreateGeometryBag(IEnumerable<Geometry> geometries, AttributeFlags attributeFlags, SpatialReference spatialReference = null)
```
### CreateGeometryBag(IEnumerable&lt;Geometry&gt;, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBagBuilderEx.yml" sourcestartlinenumber="1">Convenience method to create a new instance of the <xref href="ArcGIS.Core.Geometry.GeometryBag" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public static GeometryBag CreateGeometryBag(IEnumerable<Geometry> geometries, SpatialReference spatialReference = null)
```
### FromJson(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBagBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of a <xref href="ArcGIS.Core.Geometry.GeometryBag" data-throw-if-not-resolved="false"></xref> class from a JSON string representation.</p>


```csharp
public static GeometryBag FromJson(string jsonString)
```
### FromXml(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBagBuilderEx.yml" sourcestartlinenumber="1">Creates a new instance of a <xref href="ArcGIS.Core.Geometry.GeometryBag" data-throw-if-not-resolved="false"></xref> class from an XML string representation.</p>


```csharp
public static GeometryBag FromXml(string xmlString)
```
### Geometries

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBagBuilderEx.yml" sourcestartlinenumber="1">Gets or sets the list of geometries that define this builder.</p>


```csharp
public IList<Geometry> Geometries { get; set; }
```
### GeometryCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBagBuilderEx.yml" sourcestartlinenumber="1">Gets the number of geometries.</p>


```csharp
public int GeometryCount { get; }
```
### GeometryType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBagBuilderEx.yml" sourcestartlinenumber="1">Gets the geometry type.  Always returns <xref href="ArcGIS.Core.Geometry.GeometryType.GeometryBag" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public override GeometryType GeometryType { get; }
```
### HasID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBagBuilderEx.yml" sourcestartlinenumber="1">Gets or sets the HasID flag which indicates whether the geometry bag contains IDs.</p>


```csharp
public override bool HasID { get; set; }
```
### HasM

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBagBuilderEx.yml" sourcestartlinenumber="1">Gets or sets the HasM flag which indicates whether the geometry bag contains Ms.</p>


```csharp
public override bool HasM { get; set; }
```
### HasZ

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBagBuilderEx.yml" sourcestartlinenumber="1">Gets or sets the HasZ flag which indicates whether the geometry bag contains Zs.</p>


```csharp
public override bool HasZ { get; set; }
```
### InsertGeometries(int, IEnumerable&lt;Geometry&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBagBuilderEx.yml" sourcestartlinenumber="1">Inserts the given list of geometries before the specified index.</p>


```csharp
public void InsertGeometries(int index, IEnumerable<Geometry> geometries)
```
### InsertGeometry(int, Geometry)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBagBuilderEx.yml" sourcestartlinenumber="1">Inserts the given geometry before the specified index.</p>


```csharp
public void InsertGeometry(int index, Geometry geometry)
```
### IsEmpty

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBagBuilderEx.yml" sourcestartlinenumber="1">Gets a boolean which indicates if this instance is empty or not.
This instance is empty if it has zero geometries.</p>


```csharp
public override bool IsEmpty { get; }
```
### IsEqual(GeometryBagBuilderEx)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBagBuilderEx.yml" sourcestartlinenumber="1">Compares this instance of <xref href="ArcGIS.Core.Geometry.GeometryBagBuilderEx" data-throw-if-not-resolved="false"></xref> to the other for equality.</p>


```csharp
public bool IsEqual(GeometryBagBuilderEx other)
```
### RemoveGeometry(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBagBuilderEx.yml" sourcestartlinenumber="1">Remove the geometry specified by the given index.</p>


```csharp
public void RemoveGeometry(int index)
```
### SetEmpty()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBagBuilderEx.yml" sourcestartlinenumber="1">Sets this instance to empty by clearing the <xref href="ArcGIS.Core.Geometry.GeometryBagBuilderEx.Geometries" data-throw-if-not-resolved="false"></xref> list.</p>


```csharp
public override void SetEmpty()
```
### ToGeometry()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBagBuilderEx.yml" sourcestartlinenumber="1">Returns a <xref href="ArcGIS.Core.Geometry.GeometryBag" data-throw-if-not-resolved="false"></xref> instance representing the current state of the builder.</p>


```csharp
public override GeometryBag ToGeometry()
```


