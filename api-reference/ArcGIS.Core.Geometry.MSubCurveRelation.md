# MSubCurveRelation

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.MSubCurveRelation.yml" sourcestartlinenumber="1">Information about where an M-value falls relative to a multipart. Use with <xref href="ArcGIS.Core.Geometry.GeometryEngine.GetSubCurveBetweenMsEx(ArcGIS.Core.Geometry.Multipart%2cSystem.Double%2cSystem.Double%2cArcGIS.Core.Geometry.MSubCurveRelation%40%2cArcGIS.Core.Geometry.MSubCurveRelation%40)" data-throw-if-not-resolved="false"></xref> method.</p>


## Object Signature

```csharp
public enum MSubCurveRelation
```


## Members

### MAboveMax

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.MSubCurveRelation.yml" sourcestartlinenumber="1">The M-value is greater than the multipart's maximum M-value.</p>


```csharp
MAboveMax = 3
```
### MBelowMin

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.MSubCurveRelation.yml" sourcestartlinenumber="1">The M-value is less than the multipart's minimum M-value.</p>


```csharp
MBelowMin = 2
```
### MBetweenMinMax

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.MSubCurveRelation.yml" sourcestartlinenumber="1">The M-value is between the multipart's minimum and maximum M-values.</p>


```csharp
MBetweenMinMax = 1
```
### MRelationMIsNaN

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.MSubCurveRelation.yml" sourcestartlinenumber="1">The M-value is NaN.</p>


```csharp
MRelationMIsNaN = 48
```
### MRelationSubCurveEmpty

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.MSubCurveRelation.yml" sourcestartlinenumber="1">The multipart is empty.</p>


```csharp
MRelationSubCurveEmpty = 16
```
### MRelationSubCurveHasNoMs

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.MSubCurveRelation.yml" sourcestartlinenumber="1">The multipart's HasM property is true, but no M-values are set.</p>


```csharp
MRelationSubCurveHasNoMs = 32
```
### MRelationUndetermined

- Kind: field

<p sourcefile="api/ArcGIS.Core.Geometry.MSubCurveRelation.yml" sourcestartlinenumber="1">The relationship between the M-value and the multipart could not be determined.</p>


```csharp
MRelationUndetermined = 0
```


