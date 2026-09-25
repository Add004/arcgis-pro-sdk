# MinorOrMajor

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.MinorOrMajor.yml" sourcestartlinenumber="1">Indicates whether the arc is a minor or major arc. An arc is minor if the central angle
is less than PI radians (180 degrees) and major otherwise.  Used with <xref href="ArcGIS.Core.Geometry.EllipticArcBuilderEx.CreateCircularArc(ArcGIS.Core.Geometry.MapPoint%2cSystem.Double%2cSystem.Double%2cSystem.Double%2cArcGIS.Core.Geometry.ArcOrientation%2cArcGIS.Core.Geometry.MinorOrMajor%2cArcGIS.Core.Geometry.SpatialReference)" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public enum MinorOrMajor
```


## Members

### Major

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.MinorOrMajor.yml" sourcestartlinenumber="1">An arc is a major arc if the central angle is greater than or equal to PI radians  (180 degrees)</p>


```csharp
Major = 0
```
### Minor

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.MinorOrMajor.yml" sourcestartlinenumber="1">An arc is a minor arc if the central angle is less than PI radians (180 degrees)</p>


```csharp
Minor = 1
```


