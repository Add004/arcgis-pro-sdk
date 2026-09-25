# SegmentExtensionType

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.SegmentExtensionType.yml" sourcestartlinenumber="1">Describes if, how and where to extend segments. See the <xref href="ArcGIS.Core.Geometry.GeometryEngine.QueryPointAndDistance(ArcGIS.Core.Geometry.Multipart%2cArcGIS.Core.Geometry.SegmentExtensionType%2cArcGIS.Core.Geometry.MapPoint%2cArcGIS.Core.Geometry.AsRatioOrLength%2cSystem.Double%40%2cSystem.Double%40%2cArcGIS.Core.Geometry.LeftOrRightSide%40)" data-throw-if-not-resolved="false"></xref> function.</p>


## Object Signature

```csharp
public enum SegmentExtensionType
```


## Members

### ExtendEmbedded

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.SegmentExtensionType.yml" sourcestartlinenumber="1">The segment is extended by producing its embedding geometry at both endpoints. A circular
arc segment's embedding geometry is a complete circle; a line segment's embedding geometry is an infinite line.</p>


```csharp
ExtendEmbedded = 10
```
### ExtendEmbeddedAtFrom

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.SegmentExtensionType.yml" sourcestartlinenumber="1">The segment is extended by producing its embedding geometry at its 'from' point. A circular
arc segment's embedding geometry is a complete circle; a line segment's embedding geometry is an infinite line.</p>


```csharp
ExtendEmbeddedAtFrom = 2
```
### ExtendEmbeddedAtTo

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.SegmentExtensionType.yml" sourcestartlinenumber="1">The segment is extended by producing its embedding geometry at its 'to' point. A circular
arc segment's embedding geometry is a complete circle; a line segment's embedding geometry is an infinite line.</p>


```csharp
ExtendEmbeddedAtTo = 8
```
### ExtendTangentAtFrom

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.SegmentExtensionType.yml" sourcestartlinenumber="1">The segment is extended infinitely far along the line tangent to its 'from' point.</p>


```csharp
ExtendTangentAtFrom = 1
```
### ExtendTangentAtTo

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.SegmentExtensionType.yml" sourcestartlinenumber="1">The segment is extended infinitely far along the line tangent to its 'to' point.</p>


```csharp
ExtendTangentAtTo = 4
```
### ExtendTangents

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.SegmentExtensionType.yml" sourcestartlinenumber="1">The segment is extended infinitely far along lines tangent to both endpoints.</p>


```csharp
ExtendTangents = 5
```
### NoExtension

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.SegmentExtensionType.yml" sourcestartlinenumber="1">The segment is not extended.</p>


```csharp
NoExtension = 0
```


