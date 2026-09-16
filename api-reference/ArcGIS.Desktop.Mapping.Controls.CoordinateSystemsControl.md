# CoordinateSystemsControl

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Controls.html">Controls</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.CoordinateSystemsControl.yml" sourcestartlinenumber="1">The CoordinateSystemsControl is a configurable control that provides
a UI for Spatial Reference selection.</p>


## Object Signature

```csharp
public class CoordinateSystemsControl : UserControl, IAnimatable, IFrameworkInputElement, IInputElement, ISupportInitialize, IQueryAmbient, IAddChild, IComponentConnector
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.CoordinateSystemsControl.yml" sourcestartlinenumber="1">Optionally bind a CoordinateSystemControlProperties instance to the CoordinateSystemsControl to
provide the desired configuration. A map, spatial reference, and show-vertical-coordinate-systems flag
can be set. Developers can bind to the SelectedSpatialReference dependency property to receive selected
spatial reference changed notifications and/or use a callback with the SelectedSpatialReferenceChanged event.</p>
<pre><code sourcefile="api/ArcGIS.Desktop.Mapping.Controls.CoordinateSystemsControl.yml" sourcestartlinenumber="6">        &lt;p&gt;&lt;/p&gt;&lt;p&gt;&lt;/p&gt;&lt;img src=&quot;images/ArcGIS.Desktop.Mapping/CoordinateSystemsControl.png&quot; alt=&quot;Coordinate System Picker&quot; /&gt;
</code></pre>


## Members

### CoordinateSystemsControl()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.CoordinateSystemsControl.yml" sourcestartlinenumber="1">Default constructor. This will be called via the parent control or window on
which the CoordinateSystemsControl is hosted.</p>


```csharp
public CoordinateSystemsControl()
```
### ConfigureControl

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.CoordinateSystemsControl.yml" sourcestartlinenumber="1">Gets and sets the CoordinateSystemsControlProperties to be used to configure the
CoordinateSystemsControl</p>


```csharp
public CoordinateSystemsControlProperties ConfigureControl { get; set; }
```
### ConfigureControlProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.CoordinateSystemsControl.yml" sourcestartlinenumber="1">DependencyProperty to which a CoordinateSystemsControlProperties used to
configure the CoordinateSystemsControl can be bound</p>


```csharp
public static readonly DependencyProperty ConfigureControlProperty
```
### InitializeComponent()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.CoordinateSystemsControl.yml" sourcestartlinenumber="1">InitializeComponent</p>


```csharp
public void InitializeComponent()
```
### OnSpatialReferenceChanged()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.CoordinateSystemsControl.yml" sourcestartlinenumber="1">This raises our 'public' event. Users can hook up delegates or use the SpatialReference
property</p>


```csharp
protected virtual void OnSpatialReferenceChanged()
```
### SelectedSpatialReference

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.CoordinateSystemsControl.yml" sourcestartlinenumber="1">Gets the spatial reference selected in the CoordinateSystemsControl</p>


```csharp
public SpatialReference SelectedSpatialReference { get; }
```
### SelectedSpatialReferenceChanged

- Kind: event

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.CoordinateSystemsControl.yml" sourcestartlinenumber="1">The SpatialReferenceChanged event is raised when the SpatialReference selection is changed in the
control UI</p>


```csharp
public event SpatialReferenceChangedEventHandler SelectedSpatialReferenceChanged
```
### SelectedSpatialReferenceProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.CoordinateSystemsControl.yml" sourcestartlinenumber="1">Read-only dependency property for the selected SpatialReference</p>


```csharp
public static readonly DependencyProperty SelectedSpatialReferenceProperty
```


