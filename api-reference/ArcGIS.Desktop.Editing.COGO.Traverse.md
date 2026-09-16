# Traverse

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.COGO.html">COGO</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.Traverse.yml" sourcestartlinenumber="1">Represents a traverse.</p>


## Object Signature

```csharp
public sealed class Traverse
```


## Members

### Traverse(SpatialReference)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.Traverse.yml" sourcestartlinenumber="1">Creates a new empty traverse with no courses.</p>


```csharp
public Traverse(SpatialReference sr)
```
### Traverse(SpatialReference, IEnumerable&lt;COGOLine&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.Traverse.yml" sourcestartlinenumber="1">Creates a traverse with courses specified by the <code class="paramref">cogoLines</code>.</p>


```csharp
public Traverse(SpatialReference sr, IEnumerable<COGOLine> cogoLines)
```
### AddCourse(COGOLine)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.Traverse.yml" sourcestartlinenumber="1">Adds a new COGO line to the traverse. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void AddCourse(COGOLine cogoLine)
```
### AddCourseAsync(COGOLine)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.Traverse.yml" sourcestartlinenumber="1">Adds a new COGO line to the traverse.</p>


```csharp
public Task AddCourseAsync(COGOLine cogoLine)
```
### AddCourses(IEnumerable&lt;COGOLine&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.Traverse.yml" sourcestartlinenumber="1">Adds a set of COGO lines to the traverse. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void AddCourses(IEnumerable<COGOLine> cogoLines)
```
### AddCoursesAsync(IEnumerable&lt;COGOLine&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.Traverse.yml" sourcestartlinenumber="1">Adds a set of COGO lines to the traverse.</p>


```csharp
public Task AddCoursesAsync(IEnumerable<COGOLine> cogoLines)
```
### Adjust(TraverseAdjustmentMethod)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.Traverse.yml" sourcestartlinenumber="1">Performs an adjustment of the traverse using the specified adjustment method.
Following the adjustment use <xref href="ArcGIS.Desktop.Editing.COGO.Traverse.AdjustmentResults" data-throw-if-not-resolved="false"></xref> to obtain the adjustment results.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Adjust(TraverseAdjustmentMethod adjustmentMethod)
```
### AdjustAsync(TraverseAdjustmentMethod)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.Traverse.yml" sourcestartlinenumber="1">Performs an adjustment of the traverse using the specified adjustment method.
Following the adjustment use <xref href="ArcGIS.Desktop.Editing.COGO.Traverse.AdjustmentResults" data-throw-if-not-resolved="false"></xref> to obtain the adjustment results.</p>


```csharp
public Task AdjustAsync(TraverseAdjustmentMethod adjustmentMethod)
```
### AdjustmentResults

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.Traverse.yml" sourcestartlinenumber="1">Gets the traverse adjustment results.</p>


```csharp
public TraverseAdjustmentResults AdjustmentResults { get; }
```
### CalculateCoordinates()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.Traverse.yml" sourcestartlinenumber="1">Calculates the coordinates of the traverse directly from the COGO on the traverse courses.</p>


```csharp
public IReadOnlyList<Coordinate2D> CalculateCoordinates()
```
### CanAdjust(TraverseAdjustmentMethod)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.Traverse.yml" sourcestartlinenumber="1">Determines if the traverse can be adjusted with the specified adjustment method.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool CanAdjust(TraverseAdjustmentMethod adjustmentMethod)
```
### CanAdjustAsync(TraverseAdjustmentMethod)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.Traverse.yml" sourcestartlinenumber="1">Determines if the traverse can be adjusted with the specified adjustment method.</p>


```csharp
public Task<bool> CanAdjustAsync(TraverseAdjustmentMethod adjustmentMethod)
```
### CanCalculateCoordinates()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.Traverse.yml" sourcestartlinenumber="1">Determines if coordinates can be calculated for the traverse using COGO.</p>


```csharp
public bool CanCalculateCoordinates()
```
### ClosingPoint

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.Traverse.yml" sourcestartlinenumber="1">Gets and sets the closing point of the traverse.</p>


```csharp
public MapPoint ClosingPoint { get; set; }
```
### ConstantScaleFactor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.Traverse.yml" sourcestartlinenumber="1">Gets the constant scale factor to be used in ground to grid calculations for the traverse.</p>


```csharp
public double ConstantScaleFactor { get; }
```
### CourseCount

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.Traverse.yml" sourcestartlinenumber="1">Gets the number of courses in the traverse.</p>


```csharp
public int CourseCount { get; }
```
### Courses

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.Traverse.yml" sourcestartlinenumber="1">Gets the list of courses in the traverse.</p>


```csharp
public IReadOnlyList<Course> Courses { get; }
```
### DirectionOffset

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.Traverse.yml" sourcestartlinenumber="1">Gets the angle in decimal degrees to be used in ground to grid calculations for the traverse.</p>


```csharp
public double DirectionOffset { get; }
```
### Export(TraverseExportOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.Traverse.yml" sourcestartlinenumber="1">Exports the traverse to the ArcMap Traverse file format.  This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Export(TraverseExportOptions options)
```
### ExportAsync(TraverseExportOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.Traverse.yml" sourcestartlinenumber="1">Exports the traverse to the ArcMap Traverse file format.</p>


```csharp
public Task ExportAsync(TraverseExportOptions options)
```
### GetClosure()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.Traverse.yml" sourcestartlinenumber="1">Gets the traverse closure. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public TraverseClosure GetClosure()
```
### GetClosureAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.Traverse.yml" sourcestartlinenumber="1">Gets the traverse closure.</p>


```csharp
public Task<TraverseClosure> GetClosureAsync()
```
### GetCourseGeometries()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.Traverse.yml" sourcestartlinenumber="1">Gets the polyline geometries for the traverse courses. These can be an empty list if the traverse is not well defined.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<Polyline> GetCourseGeometries()
```
### GetPolygonGeometry()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.Traverse.yml" sourcestartlinenumber="1">Gets the traverse polygon geometry. This can be null if the traverse is not well defined.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Polygon GetPolygonGeometry()
```
### GroundToGridCorrection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.Traverse.yml" sourcestartlinenumber="1">Gets and sets the <xref href="ArcGIS.Core.CIM.CIMGroundToGridCorrection" data-throw-if-not-resolved="false"></xref> for the traverse course information.  To apply the corrections
during calculations ensure <xref href="ArcGIS.Desktop.Editing.COGO.Traverse.UseGroundToGridCorrections" data-throw-if-not-resolved="false"></xref> is true, and <xref href="ArcGIS.Core.CIM.CIMGroundToGridCorrection.Enabled" data-throw-if-not-resolved="false"></xref>
is true.</p>


```csharp
public CIMGroundToGridCorrection GroundToGridCorrection { get; set; }
```
### Import(string, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.Traverse.yml" sourcestartlinenumber="1">Imports an ArcMap traverse file and creates a <xref href="ArcGIS.Desktop.Editing.COGO.Traverse" data-throw-if-not-resolved="false"></xref>.  This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static Traverse Import(string inputFilePath, SpatialReference sr)
```
### ImportAsync(string, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.Traverse.yml" sourcestartlinenumber="1">Imports an ArcMap traverse file and creates a <xref href="ArcGIS.Desktop.Editing.COGO.Traverse" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static Task<Traverse> ImportAsync(string inputFilePath, SpatialReference sr)
```
### IsValid()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.Traverse.yml" sourcestartlinenumber="1">Gets if the traverse is valid; i.e. it is well defined.</p>


```csharp
public bool IsValid()
```
### PolygonMapMember

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.Traverse.yml" sourcestartlinenumber="1">Ges the MapMember for the polygon feature created for the traverse. This is populated only after
<xref href="ArcGIS.Desktop.Editing.EditOperation.CreateTraverse(ArcGIS.Desktop.Editing.COGO.Traverse%2cArcGIS.Desktop.Editing.Templates.EditingTemplate%2cSystem.Collections.Generic.Dictionary%7bSystem.String%2cSystem.Object%7d)" data-throw-if-not-resolved="false"></xref> has been called for the traverse.</p>


```csharp
public MapMember PolygonMapMember { get; }
```
### PolygonObjectID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.Traverse.yml" sourcestartlinenumber="1">Gets the ObjectID for the polygon feature created for the traverse. This is populated only after
<xref href="ArcGIS.Desktop.Editing.EditOperation.CreateTraverse(ArcGIS.Desktop.Editing.COGO.Traverse%2cArcGIS.Desktop.Editing.Templates.EditingTemplate%2cSystem.Collections.Generic.Dictionary%7bSystem.String%2cSystem.Object%7d)" data-throw-if-not-resolved="false"></xref> has been called for the traverse.</p>


```csharp
public long PolygonObjectID { get; }
```
### StartPoint

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.Traverse.yml" sourcestartlinenumber="1">Gets and sets the start point of the traverse.</p>


```csharp
public MapPoint StartPoint { get; set; }
```
### UseGroundToGridCorrections

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.Traverse.yml" sourcestartlinenumber="1">Gets and sets whether the course information should have the ground to grid corrections applied.  Default value is false.</p>


```csharp
public bool UseGroundToGridCorrections { get; set; }
```


