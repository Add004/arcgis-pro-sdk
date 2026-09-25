# SpatialQueryFilter

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.SpatialQueryFilter.yml" sourcestartlinenumber="1">Represents the spatial component of a filter used when querying a <xref href="ArcGIS.Core.Data.FeatureClass" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class SpatialQueryFilter : QueryFilter
```


## Members

### SpatialQueryFilter()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.SpatialQueryFilter.yml" sourcestartlinenumber="1">Represents the spatial component of a filter used when querying a <xref href="ArcGIS.Core.Data.FeatureClass" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public SpatialQueryFilter()
```
### FilterGeometry

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.SpatialQueryFilter.yml" sourcestartlinenumber="1">Gets and sets the geometry to use for the spatial filter.</p>


```csharp
public Geometry FilterGeometry { get; set; }
```
### SearchOrder

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.SpatialQueryFilter.yml" sourcestartlinenumber="1">Gets and sets the SearchOrder to be used by the query.</p>


```csharp
public SearchOrder SearchOrder { get; set; }
```
### SpatialRelationship

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.SpatialQueryFilter.yml" sourcestartlinenumber="1">Gets and sets the SpatialRelationship to use for the spatial filter.</p>


```csharp
public SpatialRelationship SpatialRelationship { get; set; }
```
### SpatialRelationshipDescription

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.SpatialQueryFilter.yml" sourcestartlinenumber="1">The DE-9IM matrix relation encoded as a string.
This property is only applicable if the SpatialRelationship is <xref href="ArcGIS.Core.Data.SpatialRelationship.Relation" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public string SpatialRelationshipDescription { get; set; }
```


