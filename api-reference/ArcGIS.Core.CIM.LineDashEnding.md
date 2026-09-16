# LineDashEnding

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.LineDashEnding.yml" sourcestartlinenumber="1">Determines how the strokes with dash patterns and other patterns (tiled pictures, placement effects) are handled at the end points of the line geometry's segments.</p>


## Object Signature

```csharp
public enum LineDashEnding
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.LineDashEnding.yml" sourcestartlinenumber="1">If more than one pattern exists (for example, a dashed simple stroke, a hash stroke, and a marker stroke) then the longest pattern's length is affected directly by this option and the rest of the stroke patterns are resized proportionately to match.</p>


## Members

### Custom

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.LineDashEnding.yml" sourcestartlinenumber="1">Custom - the pattern is fit to the length of the feature by adjusting the gaps slightly.</p>


```csharp
Custom = 5
```
### FullGap

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.LineDashEnding.yml" sourcestartlinenumber="1">Full Gap - a space equal to the gap value will be placed on either side of control points.</p>


```csharp
FullGap = 4
```
### FullPattern

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.LineDashEnding.yml" sourcestartlinenumber="1">Full Pattern - a full dash will be placed on either side of control points.</p>


```csharp
FullPattern = 3
```
### HalfGap

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.LineDashEnding.yml" sourcestartlinenumber="1">Half Gap - a space equal to the half the gap value will be placed on either side of control points.</p>


```csharp
HalfGap = 2
```
### HalfPattern

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.LineDashEnding.yml" sourcestartlinenumber="1">Half Pattern -  a half dash will be placed on either side of control points.</p>


```csharp
HalfPattern = 1
```
### NoConstraint

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.LineDashEnding.yml" sourcestartlinenumber="1">No Constraint - no constraint is applied to how the dash is placed.</p>


```csharp
NoConstraint = 0
```


