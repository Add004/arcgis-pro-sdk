# SpatialRelationship

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.SpatialRelationship.yml" sourcestartlinenumber="1">Specifies the spatial relationship.</p>


## Object Signature

```csharp
public enum SpatialRelationship
```

## Remarks

<ul><li>Intersects - Returns a feature if any spatial relationship is found.</li><li>EnvelopeIntersects - Returns a feature if the envelope of the two shapes intersect.</li><li>Contains - Returns a feature if its shape is wholly contained within the search geometry. Valid of all shape type combinations.</li><li>Crosses - Returns a feature if the intersection of the interiors of the two shapes is not empty and has a lower dimension that the maximum dimension of
        the two shapes. Two lines that share an endpoint do not cross. Valid for polyline/polyline, polyline/Area, multipoint/Area, and multipoint/polyline shape type
        combinations.</li><li>IndexIntersects uses the underlying index grid of the target feature class which is faster than using the envelope of the features, and is often used
        to return features for display purposes.</li><li>Overlaps - Returns a feature if the intersection of the two shapes results in an object of the same dimension, but different from both of the shapes.
        Applies to Area/Area, polyline/polyline, and multipoint/multipoint shape type combinations.</li><li>Touches - Returns a feature if the two shapes share a common boundary. However, the intersection of the interiors of the two shapes must be empty. In
        the point/polyline case, the point may touch an endpoint only of the polyline. Applies to all combinations except for point/point.</li><li>Within - Returns a feature if its shape wholly contains the search geometry. Valid for all shape type combinations.</li></ul>


## Members

### Contains

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.SpatialRelationship.yml" sourcestartlinenumber="1">The filter geometry wholly contains within it a feature from the target feature class.</p>


```csharp
Contains = 8
```
### Crosses

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.SpatialRelationship.yml" sourcestartlinenumber="1">The filter geometry crosses a feature from the target feature class.</p>


```csharp
Crosses = 6
```
### EnvelopeIntersects

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.SpatialRelationship.yml" sourcestartlinenumber="1">The envelope of the filter geometry intersects with the envelope of a feature in the target feature class.</p>


```csharp
EnvelopeIntersects = 2
```
### IndexIntersects

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.SpatialRelationship.yml" sourcestartlinenumber="1">The envelope of the filter geometry intersects with the index entry for a feature in the target feature class.</p>


```csharp
IndexIntersects = 3
```
### Intersects

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.SpatialRelationship.yml" sourcestartlinenumber="1">The filter geometry intersects a feature from the target feature class.</p>


```csharp
Intersects = 1
```
### Overlaps

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.SpatialRelationship.yml" sourcestartlinenumber="1">The filter geometry overlaps a feature in the target feature class.</p>


```csharp
Overlaps = 5
```
### Relation

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.SpatialRelationship.yml" sourcestartlinenumber="1">The filter geometry is involved in an interior-boundary-exterior relationship with a feature from the target feature class.</p>


```csharp
Relation = 9
```
### Touches

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.SpatialRelationship.yml" sourcestartlinenumber="1">The filter geometry touches a feature in the target feature class.</p>


```csharp
Touches = 4
```
### Undefined

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.SpatialRelationship.yml" sourcestartlinenumber="1">No defined spatial relationship.</p>


```csharp
Undefined = 0
```
### Within

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.SpatialRelationship.yml" sourcestartlinenumber="1">The filter geometry is within a feature in the target feature class.</p>


```csharp
Within = 7
```


