# SliceCylinder

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p>SliceCylinder objects are used to cut away geometry in the scene to reveal hidden or obstructed data to get
    new perspectives of your 3D data.</p>
<p>SliceCylinder objects are well-suited for define temporary extents to reduce the amount of data on-screen.  They 
    can be used to model real-world scenarios like noise propagation from a highway.
    </p>


## Object Signature

```csharp
public class SliceCylinder : Slice
```


## Members

### SliceCylinder(Camera, double, double, SliceVolumeCullDirection)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.SliceCylinder.yml" sourcestartlinenumber="1">The default SliceCylinder constructor.</p>


```csharp
public SliceCylinder(Camera transform, double radius, double height, SliceVolumeCullDirection cullDirection)
```
### SliceCylinder(SliceCylinder)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.SliceCylinder.yml" sourcestartlinenumber="1">Copy constructor.  Useful creating a duplicate SliceCylinder to use in another MapView.</p>


```csharp
public SliceCylinder(SliceCylinder sliceCylinder)
```
### CullDirection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SliceCylinder.yml" sourcestartlinenumber="1">Gets or sets the SliceCylinder's culling direction.  This defines in
which direction to cut away geometry.</p>


```csharp
public SliceVolumeCullDirection CullDirection { get; set; }
```
### GetTransform()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SliceCylinder.yml" sourcestartlinenumber="1">Gets the SliceCylinder's Transform to query its position, heading, or pitch.</p>


```csharp
public Camera GetTransform()
```
### Height

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SliceCylinder.yml" sourcestartlinenumber="1">Gets or sets the SliceCylinder's height.</p>


```csharp
public double Height { get; set; }
```
### Radius

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SliceCylinder.yml" sourcestartlinenumber="1">Gets or sets the SliceCylinder's radius.</p>


```csharp
public double Radius { get; set; }
```
### SetTransform(Camera)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SliceCylinder.yml" sourcestartlinenumber="1">Sets the SliceCylinder's Transform to update its position, heading, or pitch. Must be in the target map's <xref href="ArcGIS.Core.Geometry.SpatialReference" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public void SetTransform(Camera transform)
```


