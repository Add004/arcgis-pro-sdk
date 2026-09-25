# TransformationsControl

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Controls.html">Controls</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.TransformationsControl.yml" sourcestartlinenumber="1">The TransformationsControl is a configurable control that provides
a UI for Transformation selection.</p>


## Object Signature

```csharp
public class TransformationsControl : UserControl, IAnimatable, IFrameworkInputElement, IInputElement, ISupportInitialize, IQueryAmbient, IAddChild, IComponentConnector
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.TransformationsControl.yml" sourcestartlinenumber="1">Optionally bind a TransformationsControlProperties instance to the TransformationsControl to
provide the desired configuration. Developers can use the SelectedTransformationNames property to
retrieve the names of the selected transformations and/or use a callback with the SelectedTransformationNamesChanged
event.</p>


## Members

### TransformationsControl()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.TransformationsControl.yml" sourcestartlinenumber="1">Default constructor. This will be called via the parent control or window on
which the TransformationsControl is hosted.</p>


```csharp
public TransformationsControl()
```
### ConfigureControl

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.TransformationsControl.yml" sourcestartlinenumber="1">Gets and sets the TransformationsControlProperties to be used to configure the
TransformationsControl</p>


```csharp
public TransformationsControlProperties ConfigureControl { get; set; }
```
### ConfigureControlProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.TransformationsControl.yml" sourcestartlinenumber="1">DependencyProperty to which a TransformationsControlProperties used to
configure the TransformationsControl can be bound</p>


```csharp
public static readonly DependencyProperty ConfigureControlProperty
```
### GetSelectedDatumTransformationsAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.TransformationsControl.yml" sourcestartlinenumber="1">Retrieve the DatumTransformations of the transformations selected in the TransformationsControl.</p>


```csharp
public Task<IEnumerable<DatumTransformation>> GetSelectedDatumTransformationsAsync()
```
### InitializeComponent()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.TransformationsControl.yml" sourcestartlinenumber="1">InitializeComponent</p>


```csharp
public void InitializeComponent()
```
### OnSelectedTransformationNamesChanged()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.TransformationsControl.yml" sourcestartlinenumber="1">This raises our 'public' event. Users can hook up delegates.</p>


```csharp
protected virtual void OnSelectedTransformationNamesChanged()
```
### SelectedTransformationNames

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.TransformationsControl.yml" sourcestartlinenumber="1">Gets the names of the transformations selected in the TransformationsControl</p>


```csharp
public IEnumerable<string> SelectedTransformationNames { get; }
```
### SelectedTransformationNamesChanged

- Kind: event

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.TransformationsControl.yml" sourcestartlinenumber="1">The SelectedTransformationNamesChanged event is raised when the collection of the names of the
valid selected transformations changed (transformation removed or non-null transformation selected).</p>


```csharp
public event EventHandler<SelectedTransformationNamesChangedEventArgs> SelectedTransformationNamesChanged
```
### SelectedTransformationNamesProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.TransformationsControl.yml" sourcestartlinenumber="1">Read-only dependency property for the names of the selected transformations</p>


```csharp
public static readonly DependencyProperty SelectedTransformationNamesProperty
```
### TransformationSelected

- Kind: event

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.TransformationsControl.yml" sourcestartlinenumber="1">The TransformationSelected event is raised when a transformation is selected in one of
the rows.</p>


```csharp
public event EventHandler<TransformationSelectedArgs> TransformationSelected
```


