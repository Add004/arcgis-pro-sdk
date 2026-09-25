# GridOptions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.GridOptions.yml" sourcestartlinenumber="1">Reference grid options for a map.</p>


## Object Signature

```csharp
public class GridOptions
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.GridOptions.yml" sourcestartlinenumber="1">The reference grid is an overlay comprising configurable
horizontal and vertical grid lines for aligning features and visualizing
distances as you modify or create features. The reference grid is available
on the status bar of the Pro UI at the bottom of the active map or scene.
Refer to <a href="https://pro.arcgis.com/en/pro-app/latest/help/editing/enable-the-editing-grid.htm"></a>
for more information.</p>


## Members

### DynamicScaling

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.GridOptions.yml" sourcestartlinenumber="1">Gets and sets whether or not the grid display uses Dynamic scaling</p>


```csharp
public bool DynamicScaling { get; set; }
```
### GetGridOrigin()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GridOptions.yml" sourcestartlinenumber="1">Gets the current grid origin</p>


```csharp
public Coordinate3D GetGridOrigin()
```
### GetGridRotation()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GridOptions.yml" sourcestartlinenumber="1">Gets the current rotation angle of the grid</p>


```csharp
public double GetGridRotation()
```
### GetGridSpacing()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GridOptions.yml" sourcestartlinenumber="1">Gets the grid spacing in the output <xref href="ArcGIS.Desktop.Mapping.GridOptions.GridSpacingUnits" data-throw-if-not-resolved="false"></xref></p>


```csharp
public double GetGridSpacing()
```
### GetGridSpacingMeters()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GridOptions.yml" sourcestartlinenumber="1">Gets the grid spacing in meters</p>


```csharp
public double GetGridSpacingMeters()
```
### GetSpacing()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GridOptions.yml" sourcestartlinenumber="1">Gets the grid spacing in the grid spacing distance units</p>


```csharp
public double GetSpacing()
```
### GetSpacingInMeters()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GridOptions.yml" sourcestartlinenumber="1">Gets the grid spacing in meters</p>


```csharp
public double GetSpacingInMeters()
```
### GridFillColor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.GridOptions.yml" sourcestartlinenumber="1">Gets and sets the grid fill color</p>


```csharp
public CIMColor GridFillColor { get; set; }
```
### GridLineColor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.GridOptions.yml" sourcestartlinenumber="1">Gets and sets the color of the grid lines</p>


```csharp
public CIMColor GridLineColor { get; set; }
```
### GridMajorInterval

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.GridOptions.yml" sourcestartlinenumber="1">Gets and sets the major grid interval count</p>


```csharp
public int GridMajorInterval { get; set; }
```
### GridScaleInBeyond

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.GridOptions.yml" sourcestartlinenumber="1">Gets and sets the minimum display scale at which the grid will be visible in a 2d map</p>


```csharp
public double GridScaleInBeyond { get; set; }
```
### GridScaleOutBeyond

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.GridOptions.yml" sourcestartlinenumber="1">Gets and sets the maximum display scale at which the grid will be visible in a 2d map</p>


```csharp
public double GridScaleOutBeyond { get; set; }
```
### GridSpacingUnits

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.GridOptions.yml" sourcestartlinenumber="1">Gets and sets the units for the grid spacing</p>


```csharp
public LinearUnit GridSpacingUnits { get; set; }
```
### InferFromGridEnabled

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.GridOptions.yml" sourcestartlinenumber="1">Gets and sets whether the cursor/mouse pointer will snap perpendicular
to a grid line from a previous vertex</p>


```csharp
public bool InferFromGridEnabled { get; set; }
```
### IsGridFillOn

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.GridOptions.yml" sourcestartlinenumber="1">Gets and sets whether or not the grid fill will be used</p>


```csharp
public bool IsGridFillOn { get; set; }
```
### IsGridFillPlane

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.GridOptions.yml" sourcestartlinenumber="1">Gets and sets whether the fill will be applied to the grid planes</p>


```csharp
public bool IsGridFillPlane { get; set; }
```
### IsGridLatticeOn

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.GridOptions.yml" sourcestartlinenumber="1">Gets and sets whether or not the grid lattice is on.</p>


```csharp
public bool IsGridLatticeOn { get; set; }
```
### IsGridLines

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.GridOptions.yml" sourcestartlinenumber="1">Gets whether the grid will use lines or points</p>


```csharp
public bool IsGridLines { get; set; }
```
### IsHorizontalPlaneOn

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.GridOptions.yml" sourcestartlinenumber="1">Gets and sets whether or not a horizontal plane will be shown on the grid</p>


```csharp
public bool IsHorizontalPlaneOn { get; set; }
```
### IsVerticalLeftPlaneOn

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.GridOptions.yml" sourcestartlinenumber="1">Gets and sets whether or not a vertical plane will be shown to the left of the grid</p>


```csharp
public bool IsVerticalLeftPlaneOn { get; set; }
```
### IsVerticalRightPlaneOn

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.GridOptions.yml" sourcestartlinenumber="1">Gets and sets whether or not a vertical plane will be shown to the right of the grid</p>


```csharp
public bool IsVerticalRightPlaneOn { get; set; }
```
### Reset(Map)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GridOptions.yml" sourcestartlinenumber="1">Resets the grid options to original default values</p>


```csharp
public void Reset(Map map)
```
### RotateWithMap

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.GridOptions.yml" sourcestartlinenumber="1">Gets and sets whether the grid will rotate with the map</p>


```csharp
public bool RotateWithMap { get; set; }
```
### SetGridOrigin(Coordinate2D)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GridOptions.yml" sourcestartlinenumber="1">Sets the origin of the grid.</p>


```csharp
public void SetGridOrigin(Coordinate2D origin2D)
```
### SetGridOrigin(Coordinate3D)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GridOptions.yml" sourcestartlinenumber="1">Sets the origin of the grid.</p>


```csharp
public void SetGridOrigin(Coordinate3D origin3D)
```
### SetGridRotation(double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GridOptions.yml" sourcestartlinenumber="1">Set the grid rotation</p>


```csharp
public void SetGridRotation(double angleInDegrees)
```
### SetGridSpacing(double, LinearUnit)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GridOptions.yml" sourcestartlinenumber="1">Sets the grid spacing and grid spacing units</p>


```csharp
public void SetGridSpacing(double spacing, LinearUnit spacingUnit)
```
### SetGridSpacingInMeters(double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GridOptions.yml" sourcestartlinenumber="1">Sets the grid spacing in meters.</p>


```csharp
public void SetGridSpacingInMeters(double spacingInMeters)
```
### SnapToGridEnabled

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.GridOptions.yml" sourcestartlinenumber="1">Gets and sets whether the cursor/mouse pointer will snap to
grid lines and grid intersections based on the active snap settings</p>


```csharp
public bool SnapToGridEnabled { get; set; }
```


