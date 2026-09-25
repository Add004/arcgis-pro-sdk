# SliceBox

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p>SliceBox objects are used to cut away geometry in the scene to reveal hidden or obstructed data to get
    new perspectives of your 3D data.</p>
<p>SliceBox objects are well-suited for define temporary extents to reduce the amount of data on-screen.
    </p>


## Object Signature

```csharp
public class SliceBox : Slice
```


## Members

### SliceBox(Camera, double, double, double, SliceVolumeCullDirection)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.SliceBox.yml" sourcestartlinenumber="1">The default SliceBox constructor.</p>


```csharp
public SliceBox(Camera transform, double width, double height, double depth, SliceVolumeCullDirection cullDirection)
```
### SliceBox(SliceBox)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.SliceBox.yml" sourcestartlinenumber="1">Copy constructor.  Useful creating a duplicate SliceBox to use in another MapView.</p>


```csharp
public SliceBox(SliceBox sliceBox)
```
### CullDirection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SliceBox.yml" sourcestartlinenumber="1">Gets or sets the SliceBox's culling direction.  This defines in
which direction to cut away geometry.</p>


```csharp
public SliceVolumeCullDirection CullDirection { get; set; }
```
### Depth

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SliceBox.yml" sourcestartlinenumber="1">Gets or sets the SliceBox's depth.</p>


```csharp
public double Depth { get; set; }
```
### GetTransform()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SliceBox.yml" sourcestartlinenumber="1">Gets the SliceBox's Transform to query its position, heading, or pitch.</p>


```csharp
public Camera GetTransform()
```
### Height

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SliceBox.yml" sourcestartlinenumber="1">Gets or sets the SliceBox's height.</p>


```csharp
public double Height { get; set; }
```
### SetTransform(Camera)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SliceBox.yml" sourcestartlinenumber="1">Sets the SliceBox's Transform to update its position, heading, or pitch. Must be in the target map's <xref href="ArcGIS.Core.Geometry.SpatialReference" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public void SetTransform(Camera transform)
```
### Width

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SliceBox.yml" sourcestartlinenumber="1">Gets or sets the SliceBox's width.</p>


```csharp
public double Width { get; set; }
```


