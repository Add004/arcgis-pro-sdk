# COGOLine

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.COGO.html">COGO</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.COGOLine.yml" sourcestartlinenumber="1">Represents a COGO line.</p>


## Object Signature

```csharp
public sealed class COGOLine
```


## Members

### ArcLength

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.COGOLine.yml" sourcestartlinenumber="1">Gets the arc length value.  Can be null;  see <xref href="ArcGIS.Desktop.Editing.COGO.COGOLine.IsDefinedByArcLength" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public double? ArcLength { get; }
```
### COGOLineGeometryType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.COGOLine.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Desktop.Editing.COGO.COGOLine.COGOLineGeometryType" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public COGOLineGeometryType COGOLineGeometryType { get; }
```
### CentralAngle

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.COGOLine.yml" sourcestartlinenumber="1">Gets the central angle value.  Can be null;  see <xref href="ArcGIS.Desktop.Editing.COGO.COGOLine.IsDefinedByCentralAngle" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public double? CentralAngle { get; }
```
### DeflectionAngle

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.COGOLine.yml" sourcestartlinenumber="1">Gets the deflection angle of the COGO line if it's defined with one.</p>


```csharp
public double? DeflectionAngle { get; }
```
### Direction

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.COGOLine.yml" sourcestartlinenumber="1">Gets the direction value.  If <xref href="ArcGIS.Desktop.Editing.COGO.COGOLine.IsStraightLine" data-throw-if-not-resolved="false"></xref>, then this is the direction of the line.
If <xref href="ArcGIS.Desktop.Editing.COGO.COGOLine.IsCircularArc" data-throw-if-not-resolved="false"></xref>, then this is the direction of the chord line, tangent or the radial.</p>


```csharp
public double? Direction { get; }
```
### Distance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.COGOLine.yml" sourcestartlinenumber="1">Gets the distance value. If <xref href="ArcGIS.Desktop.Editing.COGO.COGOLine.IsStraightLine" data-throw-if-not-resolved="false"></xref>, then this is the distance between end points of the line.
If <xref href="ArcGIS.Desktop.Editing.COGO.COGOLine.IsCircularArc" data-throw-if-not-resolved="false"></xref>, then this is the distance along the chord line between the end points.</p>


```csharp
public double? Distance { get; }
```
### IsCircularArc

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.COGOLine.yml" sourcestartlinenumber="1">Gets if the COGO line is a circular arc.</p>


```csharp
public bool IsCircularArc { get; }
```
### IsDefinedByArcLength

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.COGOLine.yml" sourcestartlinenumber="1">Gets if the <xref href="ArcGIS.Desktop.Editing.COGO.COGOLine.ArcLength" data-throw-if-not-resolved="false"></xref> is defined.</p>


```csharp
public bool IsDefinedByArcLength { get; }
```
### IsDefinedByCentralAngle

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.COGOLine.yml" sourcestartlinenumber="1">Gets if the <xref href="ArcGIS.Desktop.Editing.COGO.COGOLine.CentralAngle" data-throw-if-not-resolved="false"></xref> is defined.</p>


```csharp
public bool IsDefinedByCentralAngle { get; }
```
### IsDefinedByChordDirection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.COGOLine.yml" sourcestartlinenumber="1">Gets if the COGOLine is defined with a chord direction.  This is applicable if the COGOLine is a circular arc. See <xref href="ArcGIS.Desktop.Editing.COGO.COGOLine.IsCircularArc" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public bool IsDefinedByChordDirection { get; }
```
### IsDefinedByChordLength

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.COGOLine.yml" sourcestartlinenumber="1">Gets if the <xref href="ArcGIS.Desktop.Editing.COGO.COGOLine.Distance" data-throw-if-not-resolved="false"></xref> is defined as a chord length. This is applicable if the COGOLine is a circular arc. See <xref href="ArcGIS.Desktop.Editing.COGO.COGOLine.IsCircularArc" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public bool IsDefinedByChordLength { get; }
```
### IsDefinedByRadialDirection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.COGOLine.yml" sourcestartlinenumber="1">Gets if the COGOLine is defined with a radial direction.  This is applicable if the COGOLine is a circular arc. See <xref href="ArcGIS.Desktop.Editing.COGO.COGOLine.IsCircularArc" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public bool IsDefinedByRadialDirection { get; }
```
### IsDefinedByTangentDirection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.COGOLine.yml" sourcestartlinenumber="1">Gets if the COGOLine is defined with a tangent direction.  This is applicable if the COGOLine is a circular arc. See <xref href="ArcGIS.Desktop.Editing.COGO.COGOLine.IsCircularArc" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public bool IsDefinedByTangentDirection { get; }
```
### IsStraightLine

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.COGOLine.yml" sourcestartlinenumber="1">Gets if the COGO line is a straight line.</p>


```csharp
public bool IsStraightLine { get; }
```
### Radius

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.COGOLine.yml" sourcestartlinenumber="1">Gets the radius value. A negative radius indicates a counter clockwise arc.</p>


```csharp
public double? Radius { get; }
```
### ToCircularArcDefinition()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.COGOLine.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Desktop.Editing.COGO.CircularArcDefinition" data-throw-if-not-resolved="false"></xref> for this COGOLine.</p>


```csharp
public CircularArcDefinition ToCircularArcDefinition()
```


