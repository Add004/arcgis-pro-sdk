# ViewDome

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.ViewDome.yml" sourcestartlinenumber="1">View domes are used to conduct visibility analysis as a sphere extending out from an observer point.
A sphere is created representing the visiblity extent. The sphere is painted to represent that parts
of the sphere that are visible to the observer or obstructed.</p>
<p>View domes can be used to model real-world
objects such as a viewing platform or a radar station.
</p>


## Object Signature

```csharp
public class ViewDome : ExploratoryAnalysis
```


## Members

### ViewDome(Camera, double, double)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.ViewDome.yml" sourcestartlinenumber="1">The default ViewDome constructor.</p>


```csharp
public ViewDome(Camera observer, double minimumDistance, double maximumDistance)
```
### ViewDome(ViewDome)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.ViewDome.yml" sourcestartlinenumber="1">Copy constructor.  Useful creating a duplicate ViewDome to use in another MapView.</p>


```csharp
public ViewDome(ViewDome viewdome)
```
### GetNotVisibleColorAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ViewDome.yml" sourcestartlinenumber="1">Get the color used to paint the obstructed parts of ViewDome analysis.  This affects all ViewDome objects in the active MapView.</p>


```csharp
public static Task<CIMColor> GetNotVisibleColorAsync()
```
### GetObserver()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ViewDome.yml" sourcestartlinenumber="1">Get the ViewDome's Observer to query its position.</p>


```csharp
public Camera GetObserver()
```
### GetVisibleColorAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ViewDome.yml" sourcestartlinenumber="1">Get the color used to paint the visible parts of ViewDome analysis.  This affects all ViewDome objects in the active MapView.</p>


```csharp
public static Task<CIMColor> GetVisibleColorAsync()
```
### GetWireframeColorAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ViewDome.yml" sourcestartlinenumber="1">Get the color used to paint the sphere wireframe for ViewDomes.  This affects all ViewDome objects in the active MapView.</p>


```csharp
public static Task<CIMColor> GetWireframeColorAsync()
```
### MaximumDistance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ViewDome.yml" sourcestartlinenumber="1">Gets or sets the ViewDome's maximum distance.</p>
<p>
Defines a far distance limit and size of the view dome in meters. Any scene content far than this value is disregarded.
</p>


```csharp
public double MaximumDistance { get; set; }
```
### MinimumDistance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ViewDome.yml" sourcestartlinenumber="1">Gets or sets the ViewDome's minimum distance.</p>
<p>
Defines a near distance limit in meters. Any scene content closer than this value is disregarded.
</p>


```csharp
public double MinimumDistance { get; set; }
```
### SetNotVisibleColorAsync(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ViewDome.yml" sourcestartlinenumber="1">Change the color used to paint the obstructed parts of ViewDome analysis.  This affects all ViewDome objects in the active MapView.</p>


```csharp
public static Task SetNotVisibleColorAsync(CIMColor value)
```
### SetObserver(Camera)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ViewDome.yml" sourcestartlinenumber="1">Set the ViewDome's Observer to update its position. Must be in the target map's <xref href="ArcGIS.Core.Geometry.SpatialReference" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public void SetObserver(Camera observer)
```
### SetVisibleColorAsync(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ViewDome.yml" sourcestartlinenumber="1">Change the color used to paint the visible parts of ViewDome analysis.  This affects all ViewDome objects in the active MapView.</p>


```csharp
public static Task SetVisibleColorAsync(CIMColor value)
```
### SetWireframeColorAsync(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ViewDome.yml" sourcestartlinenumber="1">Change the color used to paint the sphere wireframe for ViewDomes.  This affects all ViewDome objects in the active MapView.</p>


```csharp
public static Task SetWireframeColorAsync(CIMColor value)
```


