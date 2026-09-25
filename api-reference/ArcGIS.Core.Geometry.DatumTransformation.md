# DatumTransformation

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.DatumTransformation.yml" sourcestartlinenumber="1">An abstract class for datum transformations. Currently, a datum transformation can be a <xref href="ArcGIS.Core.Geometry.GeographicTransformation" data-throw-if-not-resolved="false"></xref>,
a <xref href="ArcGIS.Core.Geometry.CompositeGeographicTransformation" data-throw-if-not-resolved="false"></xref>, a <xref href="ArcGIS.Core.Geometry.HVDatumTransformation" data-throw-if-not-resolved="false"></xref> or a <xref href="ArcGIS.Core.Geometry.CompositeHVDatumTransformation" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public abstract class DatumTransformation
```


## Members

### DatumTransformation()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Geometry.DatumTransformation.yml" sourcestartlinenumber="1">An abstract class for datum transformations. Currently, a datum transformation can be a <xref href="ArcGIS.Core.Geometry.GeographicTransformation" data-throw-if-not-resolved="false"></xref>,
a <xref href="ArcGIS.Core.Geometry.CompositeGeographicTransformation" data-throw-if-not-resolved="false"></xref>, a <xref href="ArcGIS.Core.Geometry.HVDatumTransformation" data-throw-if-not-resolved="false"></xref> or a <xref href="ArcGIS.Core.Geometry.CompositeHVDatumTransformation" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
protected DatumTransformation()
```
### CreateFromJson(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.DatumTransformation.yml" sourcestartlinenumber="1">Creates a <xref href="ArcGIS.Core.Geometry.CompositeGeographicTransformation" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Core.Geometry.CompositeHVDatumTransformation" data-throw-if-not-resolved="false"></xref> from the input JSON string.</p>


```csharp
public static DatumTransformation CreateFromJson(string jsonString)
```
### Forward

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.DatumTransformation.yml" sourcestartlinenumber="1">Gets if the transformation is defined as Forward.</p>


```csharp
public virtual bool Forward { get; }
```
### GetInverse()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.DatumTransformation.yml" sourcestartlinenumber="1">Creates an inverted instance of this transformation. The inverted instance has its IsForward property inverted.</p>


```csharp
public abstract DatumTransformation GetInverse()
```
### InputSpatialReference

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.DatumTransformation.yml" sourcestartlinenumber="1">Gets the input spatial reference of this transformation.</p>


```csharp
public virtual SpatialReference InputSpatialReference { get; }
```
### InputVerticalCoordinateSystem

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.DatumTransformation.yml" sourcestartlinenumber="1">Gets the input vertical coordinate system of this transformation.</p>


```csharp
public virtual VerticalCoordinateSystem InputVerticalCoordinateSystem { get; }
```
### OutputSpatialReference

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.DatumTransformation.yml" sourcestartlinenumber="1">Gets the output spatial reference of this transformation.</p>


```csharp
public virtual SpatialReference OutputSpatialReference { get; }
```
### OutputVerticalCoordinateSystem

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.DatumTransformation.yml" sourcestartlinenumber="1">Gets the output vertical coordinate system of this transformation.</p>


```csharp
public virtual VerticalCoordinateSystem OutputVerticalCoordinateSystem { get; }
```
### ToJson()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.DatumTransformation.yml" sourcestartlinenumber="1">Returns the JSON representation of this transformation;</p>


```csharp
public virtual string ToJson()
```
### _inputSR

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.DatumTransformation.yml" sourcestartlinenumber="1">An abstract class for datum transformations. Currently, a datum transformation can be a <xref href="ArcGIS.Core.Geometry.GeographicTransformation" data-throw-if-not-resolved="false"></xref>,
a <xref href="ArcGIS.Core.Geometry.CompositeGeographicTransformation" data-throw-if-not-resolved="false"></xref>, a <xref href="ArcGIS.Core.Geometry.HVDatumTransformation" data-throw-if-not-resolved="false"></xref> or a <xref href="ArcGIS.Core.Geometry.CompositeHVDatumTransformation" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
protected SpatialReference _inputSR
```
### _inputVCS

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.DatumTransformation.yml" sourcestartlinenumber="1">An abstract class for datum transformations. Currently, a datum transformation can be a <xref href="ArcGIS.Core.Geometry.GeographicTransformation" data-throw-if-not-resolved="false"></xref>,
a <xref href="ArcGIS.Core.Geometry.CompositeGeographicTransformation" data-throw-if-not-resolved="false"></xref>, a <xref href="ArcGIS.Core.Geometry.HVDatumTransformation" data-throw-if-not-resolved="false"></xref> or a <xref href="ArcGIS.Core.Geometry.CompositeHVDatumTransformation" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
protected VerticalCoordinateSystem _inputVCS
```
### _outputSR

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.DatumTransformation.yml" sourcestartlinenumber="1">An abstract class for datum transformations. Currently, a datum transformation can be a <xref href="ArcGIS.Core.Geometry.GeographicTransformation" data-throw-if-not-resolved="false"></xref>,
a <xref href="ArcGIS.Core.Geometry.CompositeGeographicTransformation" data-throw-if-not-resolved="false"></xref>, a <xref href="ArcGIS.Core.Geometry.HVDatumTransformation" data-throw-if-not-resolved="false"></xref> or a <xref href="ArcGIS.Core.Geometry.CompositeHVDatumTransformation" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
protected SpatialReference _outputSR
```
### _outputVCS

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.DatumTransformation.yml" sourcestartlinenumber="1">An abstract class for datum transformations. Currently, a datum transformation can be a <xref href="ArcGIS.Core.Geometry.GeographicTransformation" data-throw-if-not-resolved="false"></xref>,
a <xref href="ArcGIS.Core.Geometry.CompositeGeographicTransformation" data-throw-if-not-resolved="false"></xref>, a <xref href="ArcGIS.Core.Geometry.HVDatumTransformation" data-throw-if-not-resolved="false"></xref> or a <xref href="ArcGIS.Core.Geometry.CompositeHVDatumTransformation" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
protected VerticalCoordinateSystem _outputVCS
```
### lockThis

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.DatumTransformation.yml" sourcestartlinenumber="1">An abstract class for datum transformations. Currently, a datum transformation can be a <xref href="ArcGIS.Core.Geometry.GeographicTransformation" data-throw-if-not-resolved="false"></xref>,
a <xref href="ArcGIS.Core.Geometry.CompositeGeographicTransformation" data-throw-if-not-resolved="false"></xref>, a <xref href="ArcGIS.Core.Geometry.HVDatumTransformation" data-throw-if-not-resolved="false"></xref> or a <xref href="ArcGIS.Core.Geometry.CompositeHVDatumTransformation" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
protected object lockThis
```


