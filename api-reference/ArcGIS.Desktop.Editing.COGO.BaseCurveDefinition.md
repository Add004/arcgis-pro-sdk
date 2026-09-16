# BaseCurveDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.COGO.html">COGO</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.BaseCurveDefinition.yml" sourcestartlinenumber="1">Represents the abstract base class for curve definitions.  See <xref href="ArcGIS.Desktop.Editing.COGO.CircularArcDefinition" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Desktop.Editing.COGO.TangentCurveDefinition" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public abstract class BaseCurveDefinition
```


## Members

### ArcLength

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.BaseCurveDefinition.yml" sourcestartlinenumber="1">Gets and sets the arc length value.</p>


```csharp
public double? ArcLength { get; set; }
```
### CalculateArcLength()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.BaseCurveDefinition.yml" sourcestartlinenumber="1">Calculates the arc length for the curve.</p>


```csharp
public double CalculateArcLength()
```
### CalculateCentralAngle()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.BaseCurveDefinition.yml" sourcestartlinenumber="1">Calculates the central angle for the curve.  The value is returned in decimal degrees.</p>


```csharp
public double CalculateCentralAngle()
```
### CalculateChordLength()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.BaseCurveDefinition.yml" sourcestartlinenumber="1">Calculates the chord length for the curve.</p>


```csharp
public double CalculateChordLength()
```
### CanCalculateArcLength()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.BaseCurveDefinition.yml" sourcestartlinenumber="1">Determines if the arc length can be calculated from the curve definition.</p>


```csharp
public bool CanCalculateArcLength()
```
### CanCalculateCentralAngle()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.BaseCurveDefinition.yml" sourcestartlinenumber="1">Determines if the central angle can be calculated from the curve definition.</p>


```csharp
public bool CanCalculateCentralAngle()
```
### CanCalculateChordLength()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.BaseCurveDefinition.yml" sourcestartlinenumber="1">Determines if the chord length can be calculated from the curve definition.</p>


```csharp
public bool CanCalculateChordLength()
```
### CentralAngle

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.BaseCurveDefinition.yml" sourcestartlinenumber="1">Gets and sets the central angle value.  An angle more than 180 degrees indicates a major arc.</p>


```csharp
public double? CentralAngle { get; set; }
```
### ChordLength

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.BaseCurveDefinition.yml" sourcestartlinenumber="1">Gets and sets the chord length value. A negative chord length indicates a major arc.</p>


```csharp
public double? ChordLength { get; set; }
```
### IsDefinedByArcLength

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.BaseCurveDefinition.yml" sourcestartlinenumber="1">Gets if the curve definition is defined by an arc length.</p>


```csharp
public bool IsDefinedByArcLength { get; }
```
### IsDefinedByCentralAngle

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.BaseCurveDefinition.yml" sourcestartlinenumber="1">Gets if the curve definition is defined by a central angle.</p>


```csharp
public bool IsDefinedByCentralAngle { get; }
```
### IsDefinedByChordLength

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.BaseCurveDefinition.yml" sourcestartlinenumber="1">Gets if the curve definition is defined by a chord length.</p>


```csharp
public bool IsDefinedByChordLength { get; }
```
### IsDefinedByRadius

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.BaseCurveDefinition.yml" sourcestartlinenumber="1">Gets if the curve definition is defined by a radius.</p>


```csharp
public bool IsDefinedByRadius { get; }
```
### Radius

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.BaseCurveDefinition.yml" sourcestartlinenumber="1">Gets and sets the radius value.  A negative radius indicates a counter clockwise curve.</p>


```csharp
public double? Radius { get; set; }
```


