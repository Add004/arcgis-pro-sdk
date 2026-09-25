# COGOLineBuilder

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.COGO.html">COGO</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.COGOLineBuilder.yml" sourcestartlinenumber="1">A builder for creating a <xref href="ArcGIS.Desktop.Editing.COGO.COGOLine" data-throw-if-not-resolved="false"></xref> whose methods can be called on any thread.</p>


## Object Signature

```csharp
public sealed class COGOLineBuilder
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.COGOLineBuilder.yml" sourcestartlinenumber="1">Use the COGOLineBuilder class to to create a COGOLine for use in a <xref href="ArcGIS.Desktop.Editing.COGO.Traverse" data-throw-if-not-resolved="false"></xref>. The lines
can be straight lines (defined by a direction and distance) or circular arcs (defined by a <xref href="ArcGIS.Desktop.Editing.COGO.CircularArcDefinition" data-throw-if-not-resolved="false"></xref>)
or tangent curves (defined by a <xref href="ArcGIS.Desktop.Editing.COGO.TangentCurveDefinition" data-throw-if-not-resolved="false"></xref>).</p>
<p></p>
<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.COGOLineBuilder.yml" sourcestartlinenumber="7">The COGOLineBuilder methods can be called on any thread.</p>


## Members

### CreateCOGOCircularArc(CircularArcDefinition)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.COGOLineBuilder.yml" sourcestartlinenumber="1">Creates a circular arc <xref href="ArcGIS.Desktop.Editing.COGO.COGOLine" data-throw-if-not-resolved="false"></xref> for use in a <xref href="ArcGIS.Desktop.Editing.COGO.Traverse" data-throw-if-not-resolved="false"></xref></p>


```csharp
public static COGOLine CreateCOGOCircularArc(CircularArcDefinition arcDefinition)
```
### CreateCOGOCircularArc(TangentCurveDefinition)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.COGOLineBuilder.yml" sourcestartlinenumber="1">Creates a circular arc <xref href="ArcGIS.Desktop.Editing.COGO.COGOLine" data-throw-if-not-resolved="false"></xref> for use in a <xref href="ArcGIS.Desktop.Editing.COGO.Traverse" data-throw-if-not-resolved="false"></xref></p>


```csharp
public static COGOLine CreateCOGOCircularArc(TangentCurveDefinition tangentCurveDefinition)
```
### CreateCOGOStraightLine(double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.COGOLineBuilder.yml" sourcestartlinenumber="1">Creates a straight <xref href="ArcGIS.Desktop.Editing.COGO.COGOLine" data-throw-if-not-resolved="false"></xref> for use in a <xref href="ArcGIS.Desktop.Editing.COGO.Traverse" data-throw-if-not-resolved="false"></xref>. the line is specified us a direction and distance.</p>


```csharp
public static COGOLine CreateCOGOStraightLine(double direction, double distance)
```
### CreateCOGOStraightLineByClockwiseDeflectionAngle(double, bool, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.COGOLineBuilder.yml" sourcestartlinenumber="1">Creates a straight <xref href="ArcGIS.Desktop.Editing.COGO.COGOLine" data-throw-if-not-resolved="false"></xref> for use in a <xref href="ArcGIS.Desktop.Editing.COGO.Traverse" data-throw-if-not-resolved="false"></xref>. The line is specified using an angle relative to
a previous course and a distance.</p>


```csharp
public static COGOLine CreateCOGOStraightLineByClockwiseDeflectionAngle(double angle, bool fromBacksight, double distance)
```


