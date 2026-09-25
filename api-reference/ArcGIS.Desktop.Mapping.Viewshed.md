# Viewshed

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Viewshed.yml" sourcestartlinenumber="1">Viewsheds are used to conduct visibility analysis within a view frustrum of an observer point.
A wireframe of the view frustum is is created and geomtry within the frustrum is tinted to represent
the features visible to the observer or obstructed.</p>
<p>Viewsheds can be used to model real-world objects like cameras, human patrol agents, or radar stations.
</p>


## Object Signature

```csharp
public class Viewshed : ExploratoryAnalysis
```


## Members

### Viewshed(Camera, double, double, double, double)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.Viewshed.yml" sourcestartlinenumber="1">The default Viewshed constructor.</p>


```csharp
public Viewshed(Camera observer, double verticalAngle, double horizontalAngle, double minimumDistance, double maximumDistance)
```
### Viewshed(Viewshed)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.Viewshed.yml" sourcestartlinenumber="1">Copy constructor.  Useful creating a duplicate Viewshed to use in another MapView.</p>


```csharp
public Viewshed(Viewshed viewshed)
```
### GetMultipleCoverageColorAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Viewshed.yml" sourcestartlinenumber="1">Get the color used to tint geometry in the scene that is visible to more than one viewshed.  This affects all Viewshed objects in the active MapView.</p>


```csharp
public static Task<CIMColor> GetMultipleCoverageColorAsync()
```
### GetNotVisibleColorAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Viewshed.yml" sourcestartlinenumber="1">Get the color used to tint geometry in the scene that is within the view frustrum of the observer, but not visible.  This affects all Viewshed objects in the active MapView.</p>


```csharp
public static Task<CIMColor> GetNotVisibleColorAsync()
```
### GetObserver()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Viewshed.yml" sourcestartlinenumber="1">Get the Viewshed's Observer to query its position, heading, or pitch.</p>


```csharp
public Camera GetObserver()
```
### GetVisibleColorAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Viewshed.yml" sourcestartlinenumber="1">Get the color used to tint geometry in the scene that is visible to an observer.  This affects all Viewshed objects in the active MapView.</p>


```csharp
public static Task<CIMColor> GetVisibleColorAsync()
```
### GetWireframeColorAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Viewshed.yml" sourcestartlinenumber="1">Get the color used to paint the viewshed wireframes.  This affects all Viewshed objects in the active MapView.</p>


```csharp
public static Task<CIMColor> GetWireframeColorAsync()
```
### HorizontalAngle

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Viewshed.yml" sourcestartlinenumber="1">Gets or sets the Viewshed's horizontal angle in degrees</p>
<p>
Defines the Observer's horizontal field of view in degrees. Any scene content outside of this angle is disregarded.
</p>


```csharp
public double HorizontalAngle { get; set; }
```
### MaximumDistance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Viewshed.yml" sourcestartlinenumber="1">Gets or sets the Viewshed's maximum distance.</p>
<p>
Defines a far distance limit in meters. Any scene content farther than this value is disregarded.
</p>


```csharp
public double MaximumDistance { get; set; }
```
### MinimumDistance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Viewshed.yml" sourcestartlinenumber="1">Gets or sets the Viewshed's minimum distance.</p>
<p>
Defines a near distance limit in meters. Any scene content closer than this value is disregarded.
</p>


```csharp
public double MinimumDistance { get; set; }
```
### SetMultipleCoverageColorAsync(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Viewshed.yml" sourcestartlinenumber="1">Change the color used to tint geometry in the scene that is visible to more than one viewshed.  This affects all Viewshed objects in the active MapView.</p>


```csharp
public static Task SetMultipleCoverageColorAsync(CIMColor value)
```
### SetNotVisibleColorAsync(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Viewshed.yml" sourcestartlinenumber="1">Change the color used to tint geometry in the scene that is within the view frustrum of the observer, but not visible.  This affects all Viewshed objects in the active MapView.</p>


```csharp
public static Task SetNotVisibleColorAsync(CIMColor value)
```
### SetObserver(Camera)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Viewshed.yml" sourcestartlinenumber="1">Set the Viewshed's Observer to update its position, heading, or pitch. Must be in the target map's <xref href="ArcGIS.Core.Geometry.SpatialReference" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public void SetObserver(Camera observer)
```
### SetVisibleColorAsync(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Viewshed.yml" sourcestartlinenumber="1">Change the color used to tint geometry in the scene that is visible to an observer.  This affects all Viewshed objects in the active MapView.</p>


```csharp
public static Task SetVisibleColorAsync(CIMColor value)
```
### SetWireframeColorAsync(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Viewshed.yml" sourcestartlinenumber="1">Change the color used to paint the viewshed wireframes.  This affects all Viewshed objects in the active MapView.</p>


```csharp
public static Task SetWireframeColorAsync(CIMColor value)
```
### VerticalAngle

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Viewshed.yml" sourcestartlinenumber="1">Gets or sets the Viewshed's vertical angle in degrees</p>
<p>
Defines the Observer's vertical field of view in degrees. Any scene content outside of this angle is disregarded.
</p>


```csharp
public double VerticalAngle { get; set; }
```


