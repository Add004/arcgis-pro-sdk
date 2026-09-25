# SliceSphere

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p>SliceSphere objects are used to cut away geometry in the scene to reveal hidden or obstructed data to get
    new perspectives of your 3D data.</p>
<p>SliceSphere objects are well-suited for define temporary extents to reduce the amount of data on-screen.
    </p>


## Object Signature

```csharp
public class SliceSphere : Slice
```


## Members

### SliceSphere(Camera, double, SliceVolumeCullDirection)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.SliceSphere.yml" sourcestartlinenumber="1">The default SliceSphere constructor.</p>


```csharp
public SliceSphere(Camera transform, double radius, SliceVolumeCullDirection cullDirection)
```
### SliceSphere(SliceSphere)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.SliceSphere.yml" sourcestartlinenumber="1">Copy constructor.  Useful creating a duplicate SliceSphere to use in another MapView.</p>


```csharp
public SliceSphere(SliceSphere sliceSphere)
```
### CullDirection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SliceSphere.yml" sourcestartlinenumber="1">Gets or sets the SliceSphere's culling direction.  This defines in
which direction to cut away geometry.</p>


```csharp
public SliceVolumeCullDirection CullDirection { get; set; }
```
### GetTransform()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SliceSphere.yml" sourcestartlinenumber="1">Gets the SliceSphere's Transform to query its position, heading, or pitch.</p>


```csharp
public Camera GetTransform()
```
### Radius

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SliceSphere.yml" sourcestartlinenumber="1">Gets or sets the SliceSphere's radius.</p>


```csharp
public double Radius { get; set; }
```
### SetTransform(Camera)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SliceSphere.yml" sourcestartlinenumber="1">Sets the SliceSphere's Transform to update its position, heading, or pitch. Must be in the target map's <xref href="ArcGIS.Core.Geometry.SpatialReference" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public void SetTransform(Camera transform)
```


