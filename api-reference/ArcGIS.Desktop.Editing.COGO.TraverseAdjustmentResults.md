# TraverseAdjustmentResults

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.COGO.html">COGO</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.TraverseAdjustmentResults.yml" sourcestartlinenumber="1">Represents the results of a traverse adjustment. See <xref href="ArcGIS.Desktop.Editing.COGO.Traverse.AdjustAsync(ArcGIS.Desktop.Editing.COGO.TraverseAdjustmentMethod)" data-throw-if-not-resolved="false"></xref> to
perform an adjustment and then <xref href="ArcGIS.Desktop.Editing.COGO.Traverse.AdjustmentResults" data-throw-if-not-resolved="false"></xref> to obtain the results.</p>


## Object Signature

```csharp
public sealed class TraverseAdjustmentResults
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.TraverseAdjustmentResults.yml" sourcestartlinenumber="1">The traverse adjustment results consists of the residual and adjusted values for each course in the traverse. See <xref href="ArcGIS.Desktop.Editing.COGO.TraverseAdjustmentResults.AdjustedCourses" data-throw-if-not-resolved="false"></xref>.</p>


## Members

### AdjustedCoordinates

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.TraverseAdjustmentResults.yml" sourcestartlinenumber="1">Gets the list of adjusted coordinate locations in the traverse.</p>


```csharp
public IReadOnlyList<Coordinate3D> AdjustedCoordinates { get; }
```
### AdjustedCourses

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.TraverseAdjustmentResults.yml" sourcestartlinenumber="1">Gets the residual and adjusted values for each course in the traverse.</p>


```csharp
public IReadOnlyList<AdjustedCourse> AdjustedCourses { get; }
```
### DirectionalResiduals

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.TraverseAdjustmentResults.yml" sourcestartlinenumber="1">Gets the residual directions for each course in the traverse. Each direction is in North Azimuth decimal degrees.</p>


```csharp
public IReadOnlyList<double> DirectionalResiduals { get; }
```
### DistanceResiduals

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.TraverseAdjustmentResults.yml" sourcestartlinenumber="1">Gets the residual distances for each course in the traverse.</p>


```csharp
public IReadOnlyList<double> DistanceResiduals { get; }
```


