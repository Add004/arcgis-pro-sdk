# SketchMode

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Extensions.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.SketchMode.yml" sourcestartlinenumber="1">Specifies different modes for the sketch to be in to modify the current sketch geometry.  See <xref href="ArcGIS.Desktop.Mapping.MapTool.SketchMode" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public enum SketchMode
```


## Members

### Arc

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.SketchMode.yml" sourcestartlinenumber="1">Adds new circular arc segments to the end of the sketch geometry.</p>


```csharp
Arc = 1
```
### Bezier

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.SketchMode.yml" sourcestartlinenumber="1">Adds new bezier curve segments to the end of the sketch geometry.</p>


```csharp
Bezier = 4
```
### DirectionDirection

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.SketchMode.yml" sourcestartlinenumber="1">Adds a new vertex at the intersection of two directions from two other points.</p>


```csharp
DirectionDirection = 18
```
### DirectionDistance

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.SketchMode.yml" sourcestartlinenumber="1">Adds a new vertex at the intersection of a direction from one point and a distance from another point.</p>


```csharp
DirectionDistance = 17
```
### DistanceDistance

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.SketchMode.yml" sourcestartlinenumber="1">Adds a new vertex to the sketch geometry at the intersection of two distances from two other points.</p>


```csharp
DistanceDistance = 15
```
### EndPointArc

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.SketchMode.yml" sourcestartlinenumber="1">Adds new circular arc segments to the end of the sketch geometry.</p>


```csharp
EndPointArc = 2
```
### Intersection

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.SketchMode.yml" sourcestartlinenumber="1">Adds a new vertex at the implied intersection of two segments.</p>


```csharp
Intersection = 16
```
### Line

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.SketchMode.yml" sourcestartlinenumber="1">Adds new line segments to the end of the sketch geometry.</p>


```csharp
Line = 0
```
### Midpoint

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.SketchMode.yml" sourcestartlinenumber="1">Adds a new segment to the sketch geometry at the midpoint between two points.</p>


```csharp
Midpoint = 7
```
### Move

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.SketchMode.yml" sourcestartlinenumber="1">Moves the sketch geometry</p>


```csharp
Move = 9
```
### RightLine

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.SketchMode.yml" sourcestartlinenumber="1">Adds a new segment to the end of the sketch geometry, constrained to right angles.</p>


```csharp
RightLine = 6
```
### Rotate

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.SketchMode.yml" sourcestartlinenumber="1">Rotates the sketch geometry</p>


```csharp
Rotate = 10
```
### Scale

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.SketchMode.yml" sourcestartlinenumber="1">Scales the sketch geometry</p>


```csharp
Scale = 11
```
### Stream

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.SketchMode.yml" sourcestartlinenumber="1">Adds a new path of streamed vertices to the end of the sketch geometry.</p>


```csharp
Stream = 8
```
### TangentArc

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.SketchMode.yml" sourcestartlinenumber="1">Adds new circular arc segments to the end of the sketch geometry, tangent to the last segment.</p>


```csharp
TangentArc = 3
```
### Trace

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.SketchMode.yml" sourcestartlinenumber="1">Adds a new traced pat to the end of the sketch geometry.</p>


```csharp
Trace = 5
```
### VertexDelete

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.SketchMode.yml" sourcestartlinenumber="1">Deletes vertices of the sketch.</p>


```csharp
VertexDelete = 14
```
### VertexInsert

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.SketchMode.yml" sourcestartlinenumber="1">Splits segments of the sketch geometry adding vertices.</p>


```csharp
VertexInsert = 13
```
### VertexMove

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.SketchMode.yml" sourcestartlinenumber="1">Modifies the location of vertices of the sketch geometry.</p>


```csharp
VertexMove = 12
```


