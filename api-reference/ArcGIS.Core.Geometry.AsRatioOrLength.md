# AsRatioOrLength

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.AsRatioOrLength.yml" sourcestartlinenumber="1">Describes how the distance along the curve is interpreted. See the <xref href="ArcGIS.Core.Geometry.GeometryEngine.SetMsAsDistance(ArcGIS.Core.Geometry.Multipart%2cArcGIS.Core.Geometry.AsRatioOrLength)" data-throw-if-not-resolved="false"></xref>,
<xref href="ArcGIS.Core.Geometry.GeometryEngine.QueryNormal(ArcGIS.Core.Geometry.Multipart%2cArcGIS.Core.Geometry.SegmentExtensionType%2cSystem.Double%2cArcGIS.Core.Geometry.AsRatioOrLength%2cSystem.Double)" data-throw-if-not-resolved="false"></xref>, <xref href="ArcGIS.Core.Geometry.GeometryEngine.QueryPoint(ArcGIS.Core.Geometry.Multipart%2cArcGIS.Core.Geometry.SegmentExtensionType%2cSystem.Double%2cArcGIS.Core.Geometry.AsRatioOrLength)" data-throw-if-not-resolved="false"></xref>,
<xref href="ArcGIS.Core.Geometry.GeometryEngine.GetSubCurve(ArcGIS.Core.Geometry.Multipart%2cSystem.Double%2cSystem.Double%2cArcGIS.Core.Geometry.AsRatioOrLength)" data-throw-if-not-resolved="false"></xref> functions as examples.</p>


## Object Signature

```csharp
public enum AsRatioOrLength
```


## Members

### AsLength

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.AsRatioOrLength.yml" sourcestartlinenumber="1">The distance is returned as length from the start point of the curve.</p>


```csharp
AsLength = 1
```
### AsRatio

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.AsRatioOrLength.yml" sourcestartlinenumber="1">The distance is returned as a ratio of the length of the curve.</p>


```csharp
AsRatio = 0
```


