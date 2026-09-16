# GeometryControl

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.Controls.html">Controls</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.GeometryControl.yml" sourcestartlinenumber="1">The GeometryControl is a configurable control that provides a UI for displaying the vertices of a sketch geometry or a feature geometry.</p>


## Object Signature

```csharp
public class GeometryControl : UserControl, IAnimatable, IFrameworkInputElement, IInputElement, ISupportInitialize, IQueryAmbient, IAddChild, IComponentConnector
```


## Members

### GeometryControl()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.GeometryControl.yml" sourcestartlinenumber="1">Default constructor. This will be called via the parent control or window on
which the GeometryControl is hosted.</p>


```csharp
public GeometryControl()
```
### Geometry

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.GeometryControl.yml" sourcestartlinenumber="1">Gets and sets the geometry for which to show the vertices.  The Geometry property is only used in <xref href="ArcGIS.Desktop.Editing.Controls.GeometryMode.Geometry" data-throw-if-not-resolved="false"></xref> mode.</p>


```csharp
public Geometry Geometry { get; set; }
```
### GeometryMode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.GeometryControl.yml" sourcestartlinenumber="1">Gets and sets the mode of the control.  The mode indicates whether the control is displaying geometry vertices or sketch vertices.</p>


```csharp
public GeometryMode GeometryMode { get; set; }
```
### GeometryModeProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.GeometryControl.yml" sourcestartlinenumber="1">Dependency property for the GeometryMode.</p>


```csharp
public static readonly DependencyProperty GeometryModeProperty
```
### GeometryProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.GeometryControl.yml" sourcestartlinenumber="1">Dependency property for the Geometry whose vertices will be shown.</p>


```csharp
public static readonly DependencyProperty GeometryProperty
```
### InitializeComponent()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.GeometryControl.yml" sourcestartlinenumber="1">InitializeComponent</p>


```csharp
public void InitializeComponent()
```
### ShowSelectionTab

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.GeometryControl.yml" sourcestartlinenumber="1">Gets and sets whether the selection tab, and related detail, is visible or not. The default value is false</p>


```csharp
public bool ShowSelectionTab { get; set; }
```
### ShowSelectionTabProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.GeometryControl.yml" sourcestartlinenumber="1">Dependency property for the Geometry whose vertices will be shown.  The default value is false.</p>


```csharp
public static readonly DependencyProperty ShowSelectionTabProperty
```
### SketchLayer

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.GeometryControl.yml" sourcestartlinenumber="1">Gets and sets the sketch layer of the control.  The SketchLayer property is only used in <xref href="ArcGIS.Desktop.Editing.Controls.GeometryMode.Sketch" data-throw-if-not-resolved="false"></xref> mode.
The properties of the SketchLayer's feature class determines whether the GeometryControl displays Z, M values.</p>


```csharp
public BasicFeatureLayer SketchLayer { get; set; }
```
### SketchLayerProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.GeometryControl.yml" sourcestartlinenumber="1">Dependency property for the SketchLayer property.</p>


```csharp
public static readonly DependencyProperty SketchLayerProperty
```
### ViewMode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.GeometryControl.yml" sourcestartlinenumber="1">Gets and sets the current tab of the control.  Default value is <xref href="ArcGIS.Desktop.Editing.Controls.ViewMode.AllVertices" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public ViewMode ViewMode { get; set; }
```
### ViewModeProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.GeometryControl.yml" sourcestartlinenumber="1">Dependency property for the Geometry whose vertices will be shown.</p>


```csharp
public static readonly DependencyProperty ViewModeProperty
```


