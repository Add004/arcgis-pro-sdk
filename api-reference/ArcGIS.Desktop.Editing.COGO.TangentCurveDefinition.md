# TangentCurveDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.COGO.html">COGO</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.TangentCurveDefinition.yml" sourcestartlinenumber="1">Defines the parameters for a tangent curve in the context of a traverse.</p>


## Object Signature

```csharp
public sealed class TangentCurveDefinition : BaseCurveDefinition
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.TangentCurveDefinition.yml" sourcestartlinenumber="1">A tangent curve must be defined with a <xref href="ArcGIS.Desktop.Editing.COGO.BaseCurveDefinition.Radius" data-throw-if-not-resolved="false"></xref> and one of the following <xref href="ArcGIS.Desktop.Editing.COGO.BaseCurveDefinition.ChordLength" data-throw-if-not-resolved="false"></xref>,
<xref href="ArcGIS.Desktop.Editing.COGO.BaseCurveDefinition.CentralAngle" data-throw-if-not-resolved="false"></xref>, <xref href="ArcGIS.Desktop.Editing.COGO.BaseCurveDefinition.ArcLength" data-throw-if-not-resolved="false"></xref>.</p>
<p></p>
<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.TangentCurveDefinition.yml" sourcestartlinenumber="6">Once the tangent curve parameters have been defined, use the <xref href="ArcGIS.Desktop.Editing.COGO.COGOLineBuilder.CreateCOGOCircularArc(ArcGIS.Desktop.Editing.COGO.TangentCurveDefinition)" data-throw-if-not-resolved="false"></xref> method to create
a <xref href="ArcGIS.Desktop.Editing.COGO.COGOLine" data-throw-if-not-resolved="false"></xref>.  Once a line has been created, use <xref href="ArcGIS.Desktop.Editing.COGO.Traverse.AddCourse(ArcGIS.Desktop.Editing.COGO.COGOLine)" data-throw-if-not-resolved="false"></xref> to
add it to a traverse.</p>


## Members

### TangentCurveDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.TangentCurveDefinition.yml" sourcestartlinenumber="1">Default constructor.</p>


```csharp
public TangentCurveDefinition()
```
### IsValid()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.TangentCurveDefinition.yml" sourcestartlinenumber="1">Gets if the tangent curve definition is valid. That is, if the minimum set of values are defined.</p>


```csharp
public bool IsValid()
```


