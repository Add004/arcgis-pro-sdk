# LineOfSight

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.LineOfSight.yml" sourcestartlinenumber="1">LineOfSight are used to conduct visibility analysis for direct lines from an observer point to
one or more targets.</p>
<p>An observer and one or more targets are created with lines connecting the target(s) to the observer.
The line segements and targets are painted using the Visible and NotVisible colors if they can be seen by
the observer of if the view is obstructed.</p><p>Lines of sight can be used to model real-world objects like visibility to points of interest or rough
approximations for projectile trajectories.
</p>


## Object Signature

```csharp
public class LineOfSight : ExploratoryAnalysis
```


## Members

### LineOfSight(Camera, List&lt;Camera&gt;, double, double)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.LineOfSight.yml" sourcestartlinenumber="1">The default LineOfSight constructor.</p>


```csharp
public LineOfSight(Camera observer, List<Camera> targets, double minimumDistance, double maximumDistance)
```
### LineOfSight(LineOfSight)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.LineOfSight.yml" sourcestartlinenumber="1">Copy constructor.  Useful creating a duplicate LineOfSight to use in another MapView.</p>


```csharp
public LineOfSight(LineOfSight lineOfSight)
```
### GetNotVisibleColorAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LineOfSight.yml" sourcestartlinenumber="1">Get the color used to paint the line of sight lines for the segment and targets that are NOT
visible to their corresponding observer.  This affects all LineOfSight objects in the active MapView.</p>


```csharp
public static Task<CIMColor> GetNotVisibleColorAsync()
```
### GetObserver()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LineOfSight.yml" sourcestartlinenumber="1">Get the LineOfSight's Observer to query its position.</p>


```csharp
public Camera GetObserver()
```
### GetOutOfRangeColorAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LineOfSight.yml" sourcestartlinenumber="1">Get the color used to paint the line of sight lines for the segment and targets that are outside
of the minimum or maximum distance range to their corresponding observer.  This affects all LineOfSight objects in the active MapView.</p>


```csharp
public static Task<CIMColor> GetOutOfRangeColorAsync()
```
### GetVisibleColorAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LineOfSight.yml" sourcestartlinenumber="1">Get the color used to paint the line of sight lines for the segment and targets that
are visible to their corresponding observer.  This affects all LineOfSight objects in the active MapView.</p>


```csharp
public static Task<CIMColor> GetVisibleColorAsync()
```
### GetWireframeColorAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LineOfSight.yml" sourcestartlinenumber="1">Get the color used to paint the wireframe line that appears below elevated observers or targets.  This affects all LineOfSight objects in the active MapView.</p>


```csharp
public static Task<CIMColor> GetWireframeColorAsync()
```
### MaximumDistance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LineOfSight.yml" sourcestartlinenumber="1">Gets or sets the LineOfSight's maximum distance.</p>
<p>
Defines a far distance limit in meters. Any scene content closer than this value is disregarded.
</p>


```csharp
public double MaximumDistance { get; set; }
```
### MinimumDistance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LineOfSight.yml" sourcestartlinenumber="1">Gets or sets the LineOfSight's minimum distance.</p>
<p>
Defines a near distance limit in meters. Any scene content closer than this value is disregarded.
</p>


```csharp
public double MinimumDistance { get; set; }
```
### SetNotVisibleColorAsync(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LineOfSight.yml" sourcestartlinenumber="1">Change the color used to paint the line of sight lines for the segment and targets that are NOT
visible to their corresponding observer.  This affects all LineOfSight objects in the active MapView.</p>


```csharp
public static Task SetNotVisibleColorAsync(CIMColor value)
```
### SetObserver(Camera)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LineOfSight.yml" sourcestartlinenumber="1">Set the LineOfSight's Observer to update its position. Must be in the target map's <xref href="ArcGIS.Core.Geometry.SpatialReference" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public void SetObserver(Camera observer)
```
### SetOutOfRangeColorAsync(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LineOfSight.yml" sourcestartlinenumber="1">Change the color used to paint the line of sight lines for the segment and targets that are outside
of the minimum or maximum distance range to their corresponding observer.  This affects all LineOfSight objects in the active MapView.</p>


```csharp
public static Task SetOutOfRangeColorAsync(CIMColor value)
```
### SetVisibleColorAsync(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LineOfSight.yml" sourcestartlinenumber="1">Change the color used to paint the line of sight lines for the segment and targets that
are visible to their corresponding observer.  This affects all LineOfSight objects in the active MapView.</p>


```csharp
public static Task SetVisibleColorAsync(CIMColor value)
```
### SetWireframeColorAsync(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.LineOfSight.yml" sourcestartlinenumber="1">Change the color used to paint the wireframe line that appears below elevated observers or targets.  This affects all LineOfSight objects in the active MapView.</p>


```csharp
public static Task SetWireframeColorAsync(CIMColor value)
```
### Targets

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LineOfSight.yml" sourcestartlinenumber="1">Gets or sets the LineOfSight's targets list to update or query its target positions. Must be in the target map's <xref href="ArcGIS.Core.Geometry.SpatialReference" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public List<Camera> Targets { get; set; }
```


