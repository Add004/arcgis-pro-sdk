# NonSimpleReason

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.NonSimpleReason.yml" sourcestartlinenumber="1">Specifies the reason that a non-simple geometry is non-simple. Returned from <xref href="ArcGIS.Core.Geometry.GeometryEngine.GetNonSimpleReason(ArcGIS.Core.Geometry.Geometry%2cArcGIS.Core.Geometry.NonSimpleReason%40%2cSystem.Boolean)" data-throw-if-not-resolved="false"></xref>.
See <a href="https://github.com/esri/arcgis-pro-sdk/wiki/ProConcepts-Geometry#simplifyasfeature-and-issimpleasfeature">SimplifyAsFeature and IsSimpleAsFeature Wiki page</a>.
Note: This enumeration coincides with ArcObjects esriNonSimpleReasonEnum
<a href="https://desktop.arcgis.com/en/arcobjects/latest/net/webframe.htm#esriNonSimpleReasonEnum.htm" sourcefile="api/ArcGIS.Core.Geometry.NonSimpleReason.yml" sourcestartlinenumber="4">https://desktop.arcgis.com/en/arcobjects/latest/net/webframe.htm#esriNonSimpleReasonEnum.htm</a></p>


## Object Signature

```csharp
public enum NonSimpleReason
```


## Members

### DiscontinuousParts

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.NonSimpleReason.yml" sourcestartlinenumber="1">The geometry contains discontinuous parts.</p>


```csharp
DiscontinuousParts = 8
```
### DuplicateVertex

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.NonSimpleReason.yml" sourcestartlinenumber="1">The geometry has one or more duplicate vertices.</p>


```csharp
DuplicateVertex = 10
```
### EmptyPart

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.NonSimpleReason.yml" sourcestartlinenumber="1">The geometry contains an empty part.</p>


```csharp
EmptyPart = 6
```
### EmptyZValues

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.NonSimpleReason.yml" sourcestartlinenumber="1">The geometry is z-aware, but one or more z-values are NaN.</p>


```csharp
EmptyZValues = 9
```
### IsSimple

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.NonSimpleReason.yml" sourcestartlinenumber="1">The geometry is simple. Applies to all geometry types.</p>


```csharp
IsSimple = 0
```
### MismatchedAttributes

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.NonSimpleReason.yml" sourcestartlinenumber="1">The geometry has mismatched attributes. All of the points must have the same attribute awareness. For example,
if one point is z-aware and another point is not, then it has mismatched attributes.</p>


```csharp
MismatchedAttributes = 7
```
### RingOrientation

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.NonSimpleReason.yml" sourcestartlinenumber="1">The rings of a polygon are oriented incorrectly. Exterior rings must be oriented clockwise, and interior rings must be
oriented counterclockwise.</p>


```csharp
RingOrientation = 1
```
### SegmentOrientation

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.NonSimpleReason.yml" sourcestartlinenumber="1">Individual segments are not consistently oriented. The end point of segment(i) must be the same as the start point of segment(i + 1).</p>


```csharp
SegmentOrientation = 2
```
### SelfIntersections

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.NonSimpleReason.yml" sourcestartlinenumber="1">A path or ring intersects itself or other parts.</p>


```csharp
SelfIntersections = 4
```
### ShortSegments

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.NonSimpleReason.yml" sourcestartlinenumber="1">Some segments are shorter than allowed by the system units of the spatial reference associated with the geometry.</p>


```csharp
ShortSegments = 3
```
### UnclosedRing

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.NonSimpleReason.yml" sourcestartlinenumber="1">A ring in a polygon is not closed. The end point of the last segment in a ring must be equal to the start point of the
first segment in that ring.</p>


```csharp
UnclosedRing = 5
```
### Undetermined

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.NonSimpleReason.yml" sourcestartlinenumber="1">The non-simple reason is unknown.</p>


```csharp
Undetermined = -1
```


