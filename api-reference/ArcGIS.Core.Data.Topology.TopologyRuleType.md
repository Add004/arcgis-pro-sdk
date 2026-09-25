# TopologyRuleType

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Topology.html">Topology</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyRuleType.yml" sourcestartlinenumber="1">Specifies the types of topology rules.</p>


## Object Signature

```csharp
public enum TopologyRuleType
```


## Members

### AreaAreaCoverEachOther

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyRuleType.yml" sourcestartlinenumber="1">The rule is an 2 areas cover each other rule.</p>


```csharp
AreaAreaCoverEachOther = 5
```
### AreaBoundaryCoveredByAreaBoundary

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyRuleType.yml" sourcestartlinenumber="1">The rule is an area boundary covered by line rule.</p>


```csharp
AreaBoundaryCoveredByAreaBoundary = 38
```
### AreaBoundaryCoveredByLine

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyRuleType.yml" sourcestartlinenumber="1">The rule is an area boundary covered by line rule.</p>


```csharp
AreaBoundaryCoveredByLine = 37
```
### AreaContainOnePoint

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyRuleType.yml" sourcestartlinenumber="1">The rule is one point must be found in each area.</p>


```csharp
AreaContainOnePoint = 16
```
### AreaContainPoint

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyRuleType.yml" sourcestartlinenumber="1">The rule is an area contain point rule.</p>


```csharp
AreaContainPoint = 43
```
### AreaCoveredByArea

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyRuleType.yml" sourcestartlinenumber="1">The rule is an area covered by area rule.</p>


```csharp
AreaCoveredByArea = 7
```
### AreaCoveredByAreaClass

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyRuleType.yml" sourcestartlinenumber="1">The rule is an area covered by area class rule.</p>


```csharp
AreaCoveredByAreaClass = 4
```
### AreaNoGaps

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyRuleType.yml" sourcestartlinenumber="1">The rule is an area-no gap rule.</p>


```csharp
AreaNoGaps = 1
```
### AreaNoOverlap

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyRuleType.yml" sourcestartlinenumber="1">The rule is an area-no overlap rule.</p>


```csharp
AreaNoOverlap = 3
```
### AreaNoOverlapArea

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyRuleType.yml" sourcestartlinenumber="1">The rule is an area covered by area rule.</p>


```csharp
AreaNoOverlapArea = 8
```
### FeatureLargerThanClusterTolerance

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyRuleType.yml" sourcestartlinenumber="1">The rule is a feature to be deleted is smaller than the cluster tolerance rule.</p>


```csharp
FeatureLargerThanClusterTolerance = 0
```
### LineCoveredByAreaBoundary

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyRuleType.yml" sourcestartlinenumber="1">The rule is a line covered by area boundary rule.</p>


```csharp
LineCoveredByAreaBoundary = 10
```
### LineCoveredByLineClass

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyRuleType.yml" sourcestartlinenumber="1">The rule is a line covered by line class rule.</p>


```csharp
LineCoveredByLineClass = 26
```
### LineEndpointCoveredByPoint

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyRuleType.yml" sourcestartlinenumber="1">The rule is a line endpoint covered by point rule.</p>


```csharp
LineEndpointCoveredByPoint = 42
```
### LineInsideArea

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyRuleType.yml" sourcestartlinenumber="1">The rule is a line must be inside area rule.</p>


```csharp
LineInsideArea = 11
```
### LineNoDangles

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyRuleType.yml" sourcestartlinenumber="1">The rule is a line-no dangles rule.</p>


```csharp
LineNoDangles = 21
```
### LineNoIntersectLine

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyRuleType.yml" sourcestartlinenumber="1">The rule is a line must not intersect with line rule.</p>


```csharp
LineNoIntersectLine = 45
```
### LineNoIntersectOrInteriorTouch

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyRuleType.yml" sourcestartlinenumber="1">The rule is a line-no intersect or interior touch rule.</p>


```csharp
LineNoIntersectOrInteriorTouch = 41
```
### LineNoIntersectOrInteriorTouchLine

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyRuleType.yml" sourcestartlinenumber="1">The rule is a line must not intersect or touch interior of line rule.</p>


```csharp
LineNoIntersectOrInteriorTouchLine = 46
```
### LineNoIntersection

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyRuleType.yml" sourcestartlinenumber="1">The rule is a line-no intersection rule.</p>


```csharp
LineNoIntersection = 20
```
### LineNoMultipart

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyRuleType.yml" sourcestartlinenumber="1">The rule is a line cannot be multipart rule.</p>


```csharp
LineNoMultipart = 44
```
### LineNoOverlap

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyRuleType.yml" sourcestartlinenumber="1">The rule is a line-no overlap rule.</p>


```csharp
LineNoOverlap = 19
```
### LineNoOverlapLine

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyRuleType.yml" sourcestartlinenumber="1">The rule is a line-no overlap line rule.</p>


```csharp
LineNoOverlapLine = 28
```
### LineNoPseudos

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyRuleType.yml" sourcestartlinenumber="1">The rule is a line with no pseudo-nodes rule.</p>


```csharp
LineNoPseudos = 22
```
### LineNoSelfIntersect

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyRuleType.yml" sourcestartlinenumber="1">The rule is a line-no self intersect rule.</p>


```csharp
LineNoSelfIntersect = 40
```
### LineNoSelfOverlap

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyRuleType.yml" sourcestartlinenumber="1">The rule is a line-no self overlap rule.</p>


```csharp
LineNoSelfOverlap = 39
```
### PointCoincidePoint

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyRuleType.yml" sourcestartlinenumber="1">The rule is a point must be coincident with point rule.</p>


```csharp
PointCoincidePoint = 35
```
### PointCoveredByAreaBoundary

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyRuleType.yml" sourcestartlinenumber="1">The rule is a point covered by area boundary rule.</p>


```csharp
PointCoveredByAreaBoundary = 13
```
### PointCoveredByLine

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyRuleType.yml" sourcestartlinenumber="1">The rule is a point covered by line rule.</p>


```csharp
PointCoveredByLine = 29
```
### PointCoveredByLineEndpoint

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyRuleType.yml" sourcestartlinenumber="1">The rule is a point covered by line endpoint rule.</p>


```csharp
PointCoveredByLineEndpoint = 31
```
### PointDisjoint

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyRuleType.yml" sourcestartlinenumber="1">The rule is a point must be disjoint rule.</p>


```csharp
PointDisjoint = 34
```
### PointProperlyInsideArea

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyRuleType.yml" sourcestartlinenumber="1">The rule is a point properly inside area rule.</p>


```csharp
PointProperlyInsideArea = 15
```


