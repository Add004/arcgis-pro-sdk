# CoordinateSystemsDetailsControl

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Controls.html">Controls</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.CoordinateSystemsDetailsControl.yml" sourcestartlinenumber="1">The CoordinateSystemsDetailsControl displays the properties of a specified Spatial Reference.  Specify the spatial reference using the
SpatialReference property.</p>


## Object Signature

```csharp
public class CoordinateSystemsDetailsControl : UserControl, IAnimatable, IFrameworkInputElement, IInputElement, ISupportInitialize, IQueryAmbient, IAddChild, IComponentConnector
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.CoordinateSystemsDetailsControl.yml" sourcestartlinenumber="1">This can be used in conjunction with the <xref href="ArcGIS.Desktop.Mapping.Controls.CoordinateSystemsControl" data-throw-if-not-resolved="false"></xref> which provides a UI for choosing a spatial reference.</p>
<p></p><p></p><img src="images/ArcGIS.Desktop.Mapping/CoordinateSystemsDetailsControl.png" alt="Coordinate System Details">


## Members

### CoordinateSystemsDetailsControl()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.CoordinateSystemsDetailsControl.yml" sourcestartlinenumber="1">Create a new CoordinateSystemsDetailsControl instance.  This will be called via the parent control or window on which the CoordinateSystemsDetailsControl is hosted.</p>


```csharp
public CoordinateSystemsDetailsControl()
```
### InitializeComponent()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.CoordinateSystemsDetailsControl.yml" sourcestartlinenumber="1">InitializeComponent</p>


```csharp
public void InitializeComponent()
```
### ShowVerticalCSDetails

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.CoordinateSystemsDetailsControl.yml" sourcestartlinenumber="1">Gets and sets whether to show Vertical Coordinate System details</p>


```csharp
public bool ShowVerticalCSDetails { get; set; }
```
### ShowVerticalCSDetailsProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.CoordinateSystemsDetailsControl.yml" sourcestartlinenumber="1">Dependency property for the ShowVerticalCSDetails which controls whether
or not to show vertical coordinate system details</p>


```csharp
public static readonly DependencyProperty ShowVerticalCSDetailsProperty
```
### SpatialReference

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.CoordinateSystemsDetailsControl.yml" sourcestartlinenumber="1">Gets and sets the spatial reference for which to show the details</p>


```csharp
public SpatialReference SpatialReference { get; set; }
```
### SpatialReferenceProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.CoordinateSystemsDetailsControl.yml" sourcestartlinenumber="1">Dependency property for the SpatialReference whose details will be
shown</p>


```csharp
public static readonly DependencyProperty SpatialReferenceProperty
```


