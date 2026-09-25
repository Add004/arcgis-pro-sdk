# ShapeDescription

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.DDL.html">DDL</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.DDL.ShapeDescription.yml" sourcestartlinenumber="1">Represents a mechanism to create a Shape <xref href="ArcGIS.Core.Data.Field" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class ShapeDescription : Description
```


## Members

### ShapeDescription(FeatureClassDefinition)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.ShapeDescription.yml" sourcestartlinenumber="1">Creates a description object of the shape <xref href="ArcGIS.Core.Data.Field" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public ShapeDescription(FeatureClassDefinition featureClassDefinition)
```
### ShapeDescription(GeometryType, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.ShapeDescription.yml" sourcestartlinenumber="1">Creates a description object of the shape <xref href="ArcGIS.Core.Data.Field" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public ShapeDescription(GeometryType geometryType, SpatialReference spatialReference)
```
### ShapeDescription(string, GeometryType, SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.ShapeDescription.yml" sourcestartlinenumber="1">Creates a description object of the shape <xref href="ArcGIS.Core.Data.Field" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public ShapeDescription(string name, GeometryType geometryType, SpatialReference spatialReference)
```
### GeometryType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.ShapeDescription.yml" sourcestartlinenumber="1">The <xref href="ArcGIS.Core.Geometry.GeometryType" data-throw-if-not-resolved="false"></xref> of the <xref href="ArcGIS.Core.Data.FeatureClass" data-throw-if-not-resolved="false"></xref> to create.</p>


```csharp
public GeometryType GeometryType { get; }
```
### HasM

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.ShapeDescription.yml" sourcestartlinenumber="1">Indicates whether or not the <xref href="ArcGIS.Core.Data.FeatureClass" data-throw-if-not-resolved="false"></xref> to create has M values.</p>


```csharp
public bool HasM { get; set; }
```
### HasZ

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.ShapeDescription.yml" sourcestartlinenumber="1">Indicates whether or not the <xref href="ArcGIS.Core.Data.FeatureClass" data-throw-if-not-resolved="false"></xref> to create has Z values.</p>


```csharp
public bool HasZ { get; set; }
```
### SpatialReference

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.ShapeDescription.yml" sourcestartlinenumber="1">The <xref href="ArcGIS.Core.Geometry.SpatialReference" data-throw-if-not-resolved="false"></xref> of the <xref href="ArcGIS.Core.Data.FeatureClass" data-throw-if-not-resolved="false"></xref> to create.</p>


```csharp
public SpatialReference SpatialReference { get; }
```


