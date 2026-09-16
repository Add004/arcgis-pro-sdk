# Camera

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Camera.yml" sourcestartlinenumber="1">Represents an object that defines the displayed content of a view via its viewing location and viewing direction.</p>


## Object Signature

```csharp
public class Camera
```

## Remarks

<p>Both 2D and 3D views define and manage what is being displayed using a camera object.
    	You can get the current camera for the view using the <xref href="ArcGIS.Desktop.Mapping.MapView.Camera" data-throw-if-not-resolved="false"></xref> property.</p>
<p>In 2D, the camera defines its <em>viewing location</em> using <xref href="ArcGIS.Desktop.Mapping.Camera.X" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Desktop.Mapping.Camera.Y" data-throw-if-not-resolved="false"></xref>. The values are in the same units as those defined by the camera's
    <xref href="ArcGIS.Desktop.Mapping.Camera.SpatialReference" data-throw-if-not-resolved="false"></xref>. This will be the center point of the 2D view's extent. The <em>viewing direction</em>, or rotation, of the map is defined using the
    camera's <xref href="ArcGIS.Desktop.Mapping.Camera.Heading" data-throw-if-not-resolved="false"></xref> property. The camera's <xref href="ArcGIS.Desktop.Mapping.Camera.Scale" data-throw-if-not-resolved="false"></xref> property then defines how far the view is zoomed in or out, and the 2D view will be able to display content
    for that area. You can also get the extent from the view using the <xref href="ArcGIS.Desktop.Mapping.MapView.Extent" data-throw-if-not-resolved="false"></xref> property.</p>
<p>In 3D, the camera defines its <em>viewing location</em> using <xref href="ArcGIS.Desktop.Mapping.Camera.X" data-throw-if-not-resolved="false"></xref>, <xref href="ArcGIS.Desktop.Mapping.Camera.Y" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Desktop.Mapping.Camera.Z" data-throw-if-not-resolved="false"></xref>. As with 2D, the values are stored in the same units as those defined by the
    camera's <xref href="ArcGIS.Desktop.Mapping.Camera.SpatialReference" data-throw-if-not-resolved="false"></xref>, with the additional possibility that XY units and Z units may be different. This will be the central position for the 3D view, as
    though a helicopter was hovering in that location. The <em>viewing direction</em> is defined by a combination of the <xref href="ArcGIS.Desktop.Mapping.Camera.Heading" data-throw-if-not-resolved="false"></xref>, <xref href="ArcGIS.Desktop.Mapping.Camera.Pitch" data-throw-if-not-resolved="false"></xref>, and <xref href="ArcGIS.Desktop.Mapping.Camera.Roll" data-throw-if-not-resolved="false"></xref> properties,
    which will rotate, tilt, and roll how the camera looks at the content around it, and the 3D view will be able to display content for the defined frustum.</p>


## Members

### Camera()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.Camera.yml" sourcestartlinenumber="1">Initialize a new instance of a Camera.</p>


```csharp
public Camera()
```
### Camera(double, double, double, double, SpatialReference, CameraViewpoint)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.Camera.yml" sourcestartlinenumber="1">Initialize a new instance of a Camera using properties common for a 2D view.</p>


```csharp
public Camera(double x, double y, double scale, double heading, SpatialReference spatialReference = null, CameraViewpoint viewpoint = CameraViewpoint.LookFrom)
```
### Camera(double, double, double, double, double, SpatialReference, CameraViewpoint)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.Camera.yml" sourcestartlinenumber="1">Initialize a new instance of a Camera using properties common for a 3D view.</p>


```csharp
public Camera(double x, double y, double z, double pitch, double heading, SpatialReference spatialReference = null, CameraViewpoint viewpoint = CameraViewpoint.LookFrom)
```
### Equals(Camera)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Camera.yml" sourcestartlinenumber="1">Determines whether the specified camera is equivalent to the current camera.</p>


```csharp
public bool Equals(Camera camera)
```
### Equals(object)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Camera.yml" sourcestartlinenumber="1">Determines whether the specified camera is equivalent to the current camera.</p>


```csharp
public override bool Equals(object obj)
```
### GetHashCode()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Camera.yml" sourcestartlinenumber="1">Serves as the default hash function.</p>


```csharp
public override int GetHashCode()
```
### Heading

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Camera.yml" sourcestartlinenumber="1">Gets or sets the Heading of the Camera, in degrees from North. 0 is North, 90 is West, 180 is South, -90 is East, etc. This property applies to both 2D and 3D views.</p>


```csharp
public double Heading { get; set; }
```
### Pitch

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Camera.yml" sourcestartlinenumber="1">Gets or sets the Pitch of the Camera, in degrees from horizontal. 0 is horizontal, 90 is looking directly up and -90 is looking directly down. This property applies to 3D views only.</p>


```csharp
public double Pitch { get; set; }
```
### Roll

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Camera.yml" sourcestartlinenumber="1">Gets or sets the Roll of the Camera, in degrees around the view vector. 0 is no roll, 45 rolls the right side down, -45 rolls the left side down. This property applies to 3D views only.</p>


```csharp
public double Roll { get; set; }
```
### Scale

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Camera.yml" sourcestartlinenumber="1">Gets or sets the Scale of the Camera, as a ratio of distance on the map to reality. This property applies to 2D views only.</p>


```csharp
public double Scale { get; set; }
```
### SpatialReference

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Camera.yml" sourcestartlinenumber="1">Gets or sets the Spatial Reference of the Camera. This property applies to both 2D and 3D views.</p>


```csharp
public SpatialReference SpatialReference { get; set; }
```
### Viewpoint

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Camera.yml" sourcestartlinenumber="1">Gets or sets the Viewpoint of the Camera. This property applies to both 2D and 3D views.</p>


```csharp
public CameraViewpoint Viewpoint { get; set; }
```
### ViewportHeight

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Camera.yml" sourcestartlinenumber="1">Gets or set the height of the viewport (in meters), required for consistent isometric camera positioning.</p>


```csharp
public double ViewportHeight { get; set; }
```
### ViewportWidth

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Camera.yml" sourcestartlinenumber="1">Gets or sets the width of the viewport (in meters), required for consistent isometric camera positioning.</p>


```csharp
public double ViewportWidth { get; set; }
```
### X

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Camera.yml" sourcestartlinenumber="1">Gets or sets the X position of the Camera, in the units of the camera's spatial reference. This property applies to both 2D and 3D views.</p>


```csharp
public double X { get; set; }
```
### Y

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Camera.yml" sourcestartlinenumber="1">Gets or sets the Y position of the Camera, in the units of the camera's spatial reference. This property applies to both 2D and 3D views.</p>


```csharp
public double Y { get; set; }
```
### Z

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Camera.yml" sourcestartlinenumber="1">Gets or sets the Z position of the Camera, in the units of the camera's spatial reference. This property applies to 3D views only.</p>


```csharp
public double Z { get; set; }
```


