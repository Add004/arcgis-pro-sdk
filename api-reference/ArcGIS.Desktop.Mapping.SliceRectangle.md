# SliceRectangle

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p>SliceRectangle objects are used to cut away geometry in the scene to reveal hidden or obstructed data to get
    new perspectives of your 3D data.</p>
<p>SliceRectangle objects are well-suited for performing cross-section views of buildings with interior data or subterranean data.
    </p>


## Object Signature

```csharp
public class SliceRectangle : Slice
```


## Members

### SliceRectangle(Camera, double, double, SliceRectangleCullDirection)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.SliceRectangle.yml" sourcestartlinenumber="1">The default SliceRectangle constructor.</p>


```csharp
public SliceRectangle(Camera transform, double width, double height, SliceRectangleCullDirection cullDirection)
```
### SliceRectangle(SliceRectangle)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.SliceRectangle.yml" sourcestartlinenumber="1">Copy constructor.  Useful creating a duplicate SliceRectangle to use in another MapView.</p>


```csharp
public SliceRectangle(SliceRectangle sliceRect)
```
### CullDirection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SliceRectangle.yml" sourcestartlinenumber="1">Gets or sets the SliceRectangle's culling direction.  This defines in
which direction to cut away geometry.</p>


```csharp
public SliceRectangleCullDirection CullDirection { get; set; }
```
### GetTransform()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SliceRectangle.yml" sourcestartlinenumber="1">Gets the SliceRectangle's Transform to query its position, heading, or pitch.</p>


```csharp
public Camera GetTransform()
```
### Height

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SliceRectangle.yml" sourcestartlinenumber="1">Gets or sets the SliceRectangle's height.</p>


```csharp
public double Height { get; set; }
```
### SetTransform(Camera)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SliceRectangle.yml" sourcestartlinenumber="1">Sets the SliceRectangle's Transform to update its position, heading, or pitch. Must be in the target map's <xref href="ArcGIS.Core.Geometry.SpatialReference" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public void SetTransform(Camera transform)
```
### Width

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SliceRectangle.yml" sourcestartlinenumber="1">Gets or sets the SliceRectangle's width.</p>


```csharp
public double Width { get; set; }
```


