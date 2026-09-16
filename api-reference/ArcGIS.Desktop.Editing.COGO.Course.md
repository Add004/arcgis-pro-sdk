# Course

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.COGO.html">COGO</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.Course.yml" sourcestartlinenumber="1">Represents a course in a traverse.</p>


## Object Signature

```csharp
public sealed class Course
```


## Members

### COGOLine

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.Course.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Desktop.Editing.COGO.Course.COGOLine" data-throw-if-not-resolved="false"></xref> for this course.</p>


```csharp
public COGOLine COGOLine { get; }
```
### EntranceTangentDirection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.Course.yml" sourcestartlinenumber="1">Gets the entrance tangent direction for the course.  Value is in North Azimuth decimal degrees.</p>


```csharp
public double EntranceTangentDirection { get; }
```
### ExitTangentDirection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.Course.yml" sourcestartlinenumber="1">Gets the exit tangent direction for the course.  Value is in North Azimuth decimal degrees.</p>


```csharp
public double ExitTangentDirection { get; }
```
### IsDefinedAsTangentToPriorCourse

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.Course.yml" sourcestartlinenumber="1">Gets if the course is defined as tangent.  A course is defined as tangent if it is defined with a <xref href="ArcGIS.Desktop.Editing.COGO.TangentCurveDefinition" data-throw-if-not-resolved="false"></xref>
or if it is a straight line defined with a 0 deflection angle.</p>


```csharp
public bool IsDefinedAsTangentToPriorCourse { get; }
```
### IsTangent

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.Course.yml" sourcestartlinenumber="1">Gets if the course is tangent.</p>


```csharp
public bool IsTangent { get; }
```
### MapMember

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.Course.yml" sourcestartlinenumber="1">Ges the MapMember for the feature created for the course. This is populated only after
<xref href="ArcGIS.Desktop.Editing.EditOperation.CreateTraverse(ArcGIS.Desktop.Editing.COGO.Traverse%2cArcGIS.Desktop.Editing.Templates.EditingTemplate%2cSystem.Collections.Generic.Dictionary%7bSystem.String%2cSystem.Object%7d)" data-throw-if-not-resolved="false"></xref> has been called for the traverse.</p>


```csharp
public MapMember MapMember { get; }
```
### ObjectID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.Course.yml" sourcestartlinenumber="1">Gets the ObjectID for the feature created for the course. This is populated only after
<xref href="ArcGIS.Desktop.Editing.EditOperation.CreateTraverse(ArcGIS.Desktop.Editing.COGO.Traverse%2cArcGIS.Desktop.Editing.Templates.EditingTemplate%2cSystem.Collections.Generic.Dictionary%7bSystem.String%2cSystem.Object%7d)" data-throw-if-not-resolved="false"></xref> has been called for the traverse.</p>


```csharp
public long ObjectID { get; }
```


