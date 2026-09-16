# UpdateMMethod

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.UpdateMMethod.yml" sourcestartlinenumber="1">The method to use when calibrating M-values.
See <xref href="ArcGIS.Core.Geometry.GeometryEngine.CalibrateByMs(ArcGIS.Core.Geometry.Multipart%2cSystem.Collections.Generic.IEnumerable%7bArcGIS.Core.Geometry.MapPoint%7d%2cArcGIS.Core.Geometry.UpdateMMethod%2cSystem.Double)" data-throw-if-not-resolved="false"></xref>
and <xref href="ArcGIS.Core.Geometry.GeometryEngine.CalibrateMsByDistance(ArcGIS.Core.Geometry.Multipart%2cSystem.Collections.Generic.IEnumerable%7bArcGIS.Core.Geometry.MapPoint%7d%2cArcGIS.Core.Geometry.UpdateMMethod%2cSystem.Boolean%2cSystem.Double)" data-throw-if-not-resolved="false"></xref></p>


## Object Signature

```csharp
public enum UpdateMMethod
```


## Members

### ExtrapolateAfter

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.UpdateMMethod.yml" sourcestartlinenumber="1">Extrapolate after the input points.</p>


```csharp
ExtrapolateAfter = 4
```
### ExtrapolateBefore

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.UpdateMMethod.yml" sourcestartlinenumber="1">Extrapolate before the input points.</p>


```csharp
ExtrapolateBefore = 2
```
### Interpolate

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.UpdateMMethod.yml" sourcestartlinenumber="1">Interpolate between the input points.</p>


```csharp
Interpolate = 1
```


