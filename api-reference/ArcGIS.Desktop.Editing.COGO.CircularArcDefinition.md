# CircularArcDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.COGO.html">COGO</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.CircularArcDefinition.yml" sourcestartlinenumber="1">Defines the parameters for a circular arc in the context of a traverse.</p>


## Object Signature

```csharp
public sealed class CircularArcDefinition : BaseCurveDefinition
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.CircularArcDefinition.yml" sourcestartlinenumber="1">A non tangent arc must be defined with a <xref href="ArcGIS.Desktop.Editing.COGO.BaseCurveDefinition.Radius" data-throw-if-not-resolved="false"></xref> and one of the following <xref href="ArcGIS.Desktop.Editing.COGO.BaseCurveDefinition.ChordLength" data-throw-if-not-resolved="false"></xref>,
<xref href="ArcGIS.Desktop.Editing.COGO.BaseCurveDefinition.CentralAngle" data-throw-if-not-resolved="false"></xref>, <xref href="ArcGIS.Desktop.Editing.COGO.BaseCurveDefinition.ArcLength" data-throw-if-not-resolved="false"></xref>.
It must also have a direction defined by one of <xref href="ArcGIS.Desktop.Editing.COGO.CircularArcDefinition.ChordDirection" data-throw-if-not-resolved="false"></xref>, <xref href="ArcGIS.Desktop.Editing.COGO.CircularArcDefinition.TangentDirection" data-throw-if-not-resolved="false"></xref>, <xref href="ArcGIS.Desktop.Editing.COGO.CircularArcDefinition.RadialDirection" data-throw-if-not-resolved="false"></xref>.</p>
<p></p>
<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.CircularArcDefinition.yml" sourcestartlinenumber="7">Once the arc parameters have been defined, use the <xref href="ArcGIS.Desktop.Editing.COGO.COGOLineBuilder.CreateCOGOCircularArc(ArcGIS.Desktop.Editing.COGO.CircularArcDefinition)" data-throw-if-not-resolved="false"></xref> method to create
a <xref href="ArcGIS.Desktop.Editing.COGO.COGOLine" data-throw-if-not-resolved="false"></xref>.  Once a line has been created, use <xref href="ArcGIS.Desktop.Editing.COGO.Traverse.AddCourse(ArcGIS.Desktop.Editing.COGO.COGOLine)" data-throw-if-not-resolved="false"></xref> to
add it to a traverse.</p>


## Members

### CircularArcDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.CircularArcDefinition.yml" sourcestartlinenumber="1">Default constructor.</p>


```csharp
public CircularArcDefinition()
```
### CalculateChordDirection()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.CircularArcDefinition.yml" sourcestartlinenumber="1">Calculates the chord direction for the arc. The value is returned in North Azimuth decimal degrees.</p>


```csharp
public double CalculateChordDirection()
```
### CalculateRadialDirection()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.CircularArcDefinition.yml" sourcestartlinenumber="1">Calculates the radial direction for the arc. The value is returned in North Azimuth decimal degrees.</p>


```csharp
public double CalculateRadialDirection()
```
### CalculateTangentDirection()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.CircularArcDefinition.yml" sourcestartlinenumber="1">Calculates the tangent direction for the arc.The value is returned in North Azimuth decimal degrees.</p>


```csharp
public double CalculateTangentDirection()
```
### CanCalculateChordDirection()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.CircularArcDefinition.yml" sourcestartlinenumber="1">Determines if the chord direction can be calculated from the arc definition.</p>


```csharp
public bool CanCalculateChordDirection()
```
### CanCalculateRadialDirection()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.CircularArcDefinition.yml" sourcestartlinenumber="1">Determines if the radial direction can be calculated from the arc definition.</p>


```csharp
public bool CanCalculateRadialDirection()
```
### CanCalculateTangentDirection()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.CircularArcDefinition.yml" sourcestartlinenumber="1">Determines if the tangent direction can be calculated from the arc definition.</p>


```csharp
public bool CanCalculateTangentDirection()
```
### ChordDirection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.CircularArcDefinition.yml" sourcestartlinenumber="1">Gets and sets the chord direction.</p>


```csharp
public double? ChordDirection { get; set; }
```
### IsDefinedByChordDirection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.CircularArcDefinition.yml" sourcestartlinenumber="1">Gets if the circular arc definition is defined by a chord direction.</p>


```csharp
public bool IsDefinedByChordDirection { get; }
```
### IsDefinedByRadialDirection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.CircularArcDefinition.yml" sourcestartlinenumber="1">Gets if the circular arc definition is defined by a radial direction.</p>


```csharp
public bool IsDefinedByRadialDirection { get; }
```
### IsDefinedByTangentDirection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.CircularArcDefinition.yml" sourcestartlinenumber="1">Gets if the circular arc definition is defined by a tangent direction.</p>


```csharp
public bool IsDefinedByTangentDirection { get; }
```
### IsValid()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.CircularArcDefinition.yml" sourcestartlinenumber="1">Gets if the curve definition is valid. That is, if the minimum set of values are defined.</p>


```csharp
public bool IsValid()
```
### RadialDirection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.CircularArcDefinition.yml" sourcestartlinenumber="1">Gets and sets the radial direction.</p>


```csharp
public double? RadialDirection { get; set; }
```
### TangentDirection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.CircularArcDefinition.yml" sourcestartlinenumber="1">Gets and sets the tangent direction.</p>


```csharp
public double? TangentDirection { get; set; }
```


