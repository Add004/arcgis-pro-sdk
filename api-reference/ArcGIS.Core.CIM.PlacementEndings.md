# PlacementEndings

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.PlacementEndings.yml" sourcestartlinenumber="1">Options for how markers are placed at extremities and control points.</p>


## Object Signature

```csharp
public enum PlacementEndings
```


## Members

### Custom

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.PlacementEndings.yml" sourcestartlinenumber="1">Will fit the pattern to the length of the features by adjusting the gaps slightly.</p>


```csharp
Custom = 4
```
### NoConstraint

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.PlacementEndings.yml" sourcestartlinenumber="1">No constraint on how the markers are placed.</p>


```csharp
NoConstraint = 0
```
### WithFullGap

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.PlacementEndings.yml" sourcestartlinenumber="1">A space equal to the placement template will be placed at the control point.</p>


```csharp
WithFullGap = 2
```
### WithHalfGap

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.PlacementEndings.yml" sourcestartlinenumber="1">A space equal to half the placement template will be placed at the control point.</p>


```csharp
WithHalfGap = 3
```
### WithMarkers

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.PlacementEndings.yml" sourcestartlinenumber="1">A marker is placed at the control point.</p>


```csharp
WithMarkers = 1
```


