# AdjustedCourse

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.COGO.html">COGO</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.AdjustedCourse.yml" sourcestartlinenumber="1">Represents the adjustments to a <xref href="ArcGIS.Desktop.Editing.COGO.Course" data-throw-if-not-resolved="false"></xref> in a <xref href="ArcGIS.Desktop.Editing.COGO.Traverse" data-throw-if-not-resolved="false"></xref> after an adjustment. See <xref href="ArcGIS.Desktop.Editing.COGO.Traverse.AdjustAsync(ArcGIS.Desktop.Editing.COGO.TraverseAdjustmentMethod)" data-throw-if-not-resolved="false"></xref>,
<xref href="ArcGIS.Desktop.Editing.COGO.Traverse.AdjustmentResults" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Desktop.Editing.COGO.TraverseAdjustmentResults.AdjustedCourses" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class AdjustedCourse
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.AdjustedCourse.yml" sourcestartlinenumber="1">If a traverse has a closure error, it is automatically adjusted to eliminate and distribute the misclose among the individual traverse legs.
This class contains the adjusted dimensions and residual values for a course in the traverse.</p>


## Members

### AdjustedDirection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.AdjustedCourse.yml" sourcestartlinenumber="1">Gets the adjusted direction of the course in the traverse.  This is stored in North Azimuth decimal degrees.</p>


```csharp
public double AdjustedDirection { get; }
```
### AdjustedDistance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.AdjustedCourse.yml" sourcestartlinenumber="1">Gets the adjusted distance of the course in the traverse.</p>


```csharp
public double AdjustedDistance { get; }
```
### Direction

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.AdjustedCourse.yml" sourcestartlinenumber="1">Gets the direction of the course in the traverse. This is stored in North Azimuth decimal degrees.</p>


```csharp
public double Direction { get; }
```
### Distance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.AdjustedCourse.yml" sourcestartlinenumber="1">Gets the distance of the course in the traverse.</p>


```csharp
public double Distance { get; }
```
### ResidualDirection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.AdjustedCourse.yml" sourcestartlinenumber="1">Gets the residual direction of the course in the traverse. This is stored in Polar decimal degrees.</p>


```csharp
public double ResidualDirection { get; }
```
### ResidualDistance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.AdjustedCourse.yml" sourcestartlinenumber="1">Gets the residual distance of the course in the traverse.</p>


```csharp
public double ResidualDistance { get; }
```


