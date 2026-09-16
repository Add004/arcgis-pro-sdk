# GeometryBuilderEx

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBuilderEx.yml" sourcestartlinenumber="1">An abstract base class for geometry builders.</p>


## Object Signature

```csharp
public abstract class GeometryBuilderEx
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBuilderEx.yml" sourcestartlinenumber="1">The GeometryBuilderEx classes can be created on any thread.</p>


## Members

### GeometryBuilderEx()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBuilderEx.yml" sourcestartlinenumber="1">An abstract base class for geometry builders.</p>


```csharp
protected GeometryBuilderEx()
```
### GeometryType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBuilderEx.yml" sourcestartlinenumber="1">Gets the type of geometry that will be created from this builder.</p>


```csharp
public abstract GeometryType GeometryType { get; }
```
### HasID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBuilderEx.yml" sourcestartlinenumber="1">Gets or sets a value indicating if the <xref href="ArcGIS.Core.Geometry.GeometryBuilderEx" data-throw-if-not-resolved="false"></xref> recognizes ID-values.</p>


```csharp
public abstract bool HasID { get; set; }
```
### HasM

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBuilderEx.yml" sourcestartlinenumber="1">Gets or sets a value indicating if the <xref href="ArcGIS.Core.Geometry.GeometryBuilderEx" data-throw-if-not-resolved="false"></xref> recognizes M-values.</p>


```csharp
public abstract bool HasM { get; set; }
```
### HasZ

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBuilderEx.yml" sourcestartlinenumber="1">Gets or sets a value indicating if the <xref href="ArcGIS.Core.Geometry.GeometryBuilderEx" data-throw-if-not-resolved="false"></xref> recognizes Z-values.</p>


```csharp
public abstract bool HasZ { get; set; }
```
### IsEmpty

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBuilderEx.yml" sourcestartlinenumber="1">Gets a value indicating if this instance is empty.</p>


```csharp
public abstract bool IsEmpty { get; }
```
### IsEqual(GeometryBuilderEx)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBuilderEx.yml" sourcestartlinenumber="1">Compares this instance of <xref href="ArcGIS.Core.Geometry.GeometryBuilderEx" data-throw-if-not-resolved="false"></xref> to the other for equality.</p>


```csharp
public bool IsEqual(GeometryBuilderEx other)
```
### ReplaceSpatialReference(Geometry, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBuilderEx.yml" sourcestartlinenumber="1">Replaces <xref href="ArcGIS.Core.Geometry.GeometryBuilderEx.SpatialReference" data-throw-if-not-resolved="false"></xref> of the input Geometry instance.</p>


```csharp
public static Geometry ReplaceSpatialReference(Geometry sourceGeometry, SpatialReference newSpatialReference)
```
### SetEmpty()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBuilderEx.yml" sourcestartlinenumber="1">Sets this instance to empty.</p>


```csharp
public abstract void SetEmpty()
```
### SpatialReference

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBuilderEx.yml" sourcestartlinenumber="1">Gets or sets the <xref href="ArcGIS.Core.Geometry.GeometryBuilderEx.SpatialReference" data-throw-if-not-resolved="false"></xref> instance on this builder.</p>


```csharp
public SpatialReference SpatialReference { get; set; }
```
### ToGeometry()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBuilderEx.yml" sourcestartlinenumber="1">Builds a new Geometry instance from the properties of this builder.</p>


```csharp
public abstract Geometry ToGeometry()
```


