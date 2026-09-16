# GroupTemplateBuilderMethods

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.Templates.html">Templates</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.GroupTemplateBuilderMethods.yml" sourcestartlinenumber="1">Enumeration for group template builder methods.  Used in ArcGIS.Desktop.Mapping.AddComponentTemplate</p>


## Object Signature

```csharp
public enum GroupTemplateBuilderMethods
```


## Members

### builderBufferLineToPolygon

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.GroupTemplateBuilderMethods.yml" sourcestartlinenumber="1">Buffer builder.  Available for use with a base template of geometry type polyline and a component template of geometry type polygon.
Creates a polygon feature from the base polyline feature buffered to the specified distance.</p>


```csharp
builderBufferLineToPolygon = 12
```
### builderBufferPointToPolygon

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.GroupTemplateBuilderMethods.yml" sourcestartlinenumber="1">Buffer builder. Available for use with a base template of geometry type point and a component template of geometry type polygon.
Creates a polygon feature from the base point feature buffered to the specified distance.</p>


```csharp
builderBufferPointToPolygon = 11
```
### builderBufferPolygonToPolygon

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.GroupTemplateBuilderMethods.yml" sourcestartlinenumber="1">Buffer builder.  Available for use with a base template of geometry type polygon and a component template of geometry type polygon.
Creates a polygon feature from the base polygon feature buffered to the specified distance.</p>


```csharp
builderBufferPolygonToPolygon = 13
```
### builderConnectionPoint

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.GroupTemplateBuilderMethods.yml" sourcestartlinenumber="1">Connection offset builder. Available for use with a base template of geometry type polyline and a component template of geometry type polyline.</p>


```csharp
builderConnectionPoint = 22
```
### builderOffsetLine

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.GroupTemplateBuilderMethods.yml" sourcestartlinenumber="1">Multiple single-part lines builder. Available for use with a base template of geometry type polyline and a component template of geometry type polyline.
Creates a polyline feature in the component template layer offset with the specified distance from the base polyline feature.
If no offset is specified (side = 0), a polyline feature in the component template layer is created with the same geometry as the base polygon feature.</p>


```csharp
builderOffsetLine = 9
```
### builderOffsetPrimaryLine

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.GroupTemplateBuilderMethods.yml" sourcestartlinenumber="1">Line feature builder. Available for use with a base template of geometry type polyline and a component template of geometry type polyline.
Creates a polyline feature in the component template layer offset with the specified distance from the base polyline feature.
If no offset is specified (side = 0), a polyline feature in the component template layer is created with the same geometry as the base polygon feature.</p>


```csharp
builderOffsetPrimaryLine = 10
```
### builderPointAtAllVerticesOfLine

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.GroupTemplateBuilderMethods.yml" sourcestartlinenumber="1">Point at every vertex builder. Available for use with a base template of geometry type polyline and a component template of geometry type point.
Creates point features in the component template layer offset with the specified attributes from each vertex of the base polyline feature.
If no parameters are specified, point features in the component template layer are created at each vertex of the base polyline feature.</p>


```csharp
builderPointAtAllVerticesOfLine = 7
```
### builderPointAtBeginningOfLine

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.GroupTemplateBuilderMethods.yml" sourcestartlinenumber="1">Point at beginning of line builder. Available for use with a base template of geometry type polyline and a component template of geometry type point.
Creates a point feature in the component template layer offset with the specified attributes from the beginning vertex of the base polyline feature.
If no parameters are specified, a point feature in the component template layer is created at the beginning vertex of the base polyline feature.</p>


```csharp
builderPointAtBeginningOfLine = 2
```
### builderPointAtBeginningOfRadial

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.GroupTemplateBuilderMethods.yml" sourcestartlinenumber="1">Point at beginning of line radial builder. Available for use with a base template of geometry type polyline and a component template of geometry type point.
Creates a point feature in the component template layer offset with the specified attributes from the beginning vertex of the base polyline feature.
If no parameters are specified, a point feature in the component template layer is created at the beginning vertex of the base polyline feature.</p>


```csharp
builderPointAtBeginningOfRadial = 3
```
### builderPointAtEndOfLine

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.GroupTemplateBuilderMethods.yml" sourcestartlinenumber="1">Point at end of line builder. Available for use with a base template of geometry type polyline and a component template of geometry type point.
Creates a point feature in the component template layer offset with the specified attributes from the end vertex of the base polyline feature.
If no parameters are specified, a point feature in the component template layer is created at the end vertex of the base polyline feature.</p>


```csharp
builderPointAtEndOfLine = 1
```
### builderPointAtInteriorVertices

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.GroupTemplateBuilderMethods.yml" sourcestartlinenumber="1">Point at every vertex, except start and end builder. Available for use with a base template of geometry type polyline and a component template of geometry type point.
Creates point features in the component template layer offset with the specified attributes from each vertex of the base polyline feature except the beginning and end vertices.
If no parameters are specified, point features in the component template layer are created at each vertex of the base polyline feature except the beginning and end vertices.</p>


```csharp
builderPointAtInteriorVertices = 6
```
### builderPointAtIntersectionVerticesOfLine

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.GroupTemplateBuilderMethods.yml" sourcestartlinenumber="1">Point at every intersection builder. Available for use with a base template of geometry type polyline and a component template of geometry type point.</p>


```csharp
builderPointAtIntersectionVerticesOfLine = 8
```
### builderPointAtNotBeginningOfLine

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.GroupTemplateBuilderMethods.yml" sourcestartlinenumber="1">Point at every vertex, except start builder. Available for use with a base template of geometry type polyline and a component template of geometry type point.
Creates point features in the component template layer offset with the specified attributes from each vertex of the base polyline feature except the beginning vertex.
If no parameters are specified, point features in the component template layer are created at each vertex of the base polyline feature except the beginning vertex.</p>


```csharp
builderPointAtNotBeginningOfLine = 5
```
### builderPointAtNotEndOfLine

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.GroupTemplateBuilderMethods.yml" sourcestartlinenumber="1">Point at every vertex, except end builder. Available for use with a base template of geometry type polyline and a component template of geometry type point.
Creates point features in the component template layer offset with the specified attributes from each vertex of the base polyline feature except the end vertex.
If no parameters are specified, point features in the component template layer are created at each vertex of the base polyline feature except the end vertex.</p>


```csharp
builderPointAtNotEndOfLine = 4
```
### builderPointAtPolygonCentroid

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.GroupTemplateBuilderMethods.yml" sourcestartlinenumber="1">Centroid builder. Available for use with a base template of geometry type polygon and a component template of geometry type point.
Creates a point feature at the centroid of the base polygon feature.</p>


```csharp
builderPointAtPolygonCentroid = 17
```
### builderPointAtPolygonNotStart

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.GroupTemplateBuilderMethods.yml" sourcestartlinenumber="1">Point at every vertex, except start builder.  Available for use with a base template of geometry type polygon and a component template of geometry type point.
Creates point features at every vertex of the base polygon feature except the start vertex.</p>


```csharp
builderPointAtPolygonNotStart = 16
```
### builderPointAtPolygonStart

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.GroupTemplateBuilderMethods.yml" sourcestartlinenumber="1">Point at start only builder.  Available for use with a base template of geometry type polygon and a component template of geometry type point.
Creates a point feature at the start vertex of the base polygon feature.</p>


```csharp
builderPointAtPolygonStart = 18
```
### builderPointIdentity

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.GroupTemplateBuilderMethods.yml" sourcestartlinenumber="1">Multiple point features builder. Available for use with a base template of geometry type point and a component template of geometry type point.
Creates a point feature in the component template layer with the same geometry as the base point feature.</p>


```csharp
builderPointIdentity = 0
```
### builderPolygonBoundary

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.GroupTemplateBuilderMethods.yml" sourcestartlinenumber="1">Single line feature (boundary) builder. Available for use with a base template of geometry type polygon and a component template of geometry type polyline.
Creates a polyline feature in the component template layer with the same geometry as the boundary of the base polygon feature.</p>


```csharp
builderPolygonBoundary = 19
```
### builderPolygonBoundaryTwoPoint

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.GroupTemplateBuilderMethods.yml" sourcestartlinenumber="1">Two-point line features builder. Available for use with a base template of geometry type polygon and a component template of geometry type polyline.
Creates two point polyline features in the component template layer based on the geometry of the boundary of the base polygon feature.</p>


```csharp
builderPolygonBoundaryTwoPoint = 20
```
### builderPolygonIdentity

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.GroupTemplateBuilderMethods.yml" sourcestartlinenumber="1">Multiple polygon features builder. Available for use with a base template of geometry type polygon and a component template of geometry type polygon.
Creates a polygon feature in the component template layer with the same geometry as the base polygon feature.</p>


```csharp
builderPolygonIdentity = 21
```
### builderPolygonVertices

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.GroupTemplateBuilderMethods.yml" sourcestartlinenumber="1">Point at every vertex builder.  Available for use with a base template of geometry type polygon and a component template of geometry type point.
Creates point features at every vertex of the base polygon feature.</p>


```csharp
builderPolygonVertices = 15
```
### builderTwoPointLines

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.GroupTemplateBuilderMethods.yml" sourcestartlinenumber="1">Two point line builder. Available for use with a base template of geometry type polyline and a component template of geometry type polyline.
Creates two point polyline features in the component template layer based on the geometry of the base polyline feature.</p>


```csharp
builderTwoPointLines = 14
```


