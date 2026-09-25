# SelectionToolPickerControl

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.Controls.html">Controls</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.SelectionToolPickerControl.yml" sourcestartlinenumber="1">Use the SelectionToolPickerControl to display the group of selection tools in a single control.</p>


## Object Signature

```csharp
public class SelectionToolPickerControl : UserControl, IAnimatable, IFrameworkInputElement, IInputElement, ISupportInitialize, IQueryAmbient, IAddChild, IComponentConnector
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.SelectionToolPickerControl.yml" sourcestartlinenumber="1">The control consists of a command link button which displays the current selection tool
along with guiding text depending upon whether a selection exists in the current map or not.
The button has a dropdown which displays the set of selection tools.
Use the command link button to activate the current select tool or the dropdown to change the
current selection tool.</p>
<p></p>
<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.SelectionToolPickerControl.yml" sourcestartlinenumber="9">The list of tools displayed is defined in &quot;esri_mapping_selectToolPalette&quot; and matches the
list of selection tools displayed on the Map or Edit ribbon tab.</p>


## Members

### SelectionToolPickerControl()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.SelectionToolPickerControl.yml" sourcestartlinenumber="1">The select tool picker control constructor. This will be called via the parent control or window on which the SelectionToolPickerControl is hosted.</p>


```csharp
public SelectionToolPickerControl()
```
### InitializeComponent()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.SelectionToolPickerControl.yml" sourcestartlinenumber="1">InitializeComponent</p>


```csharp
public void InitializeComponent()
```
### Map

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.SelectionToolPickerControl.yml" sourcestartlinenumber="1">Gets and sets the map of the control.</p>


```csharp
public Map Map { get; set; }
```
### MapProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.SelectionToolPickerControl.yml" sourcestartlinenumber="1">Dependency property for the Map.</p>


```csharp
public static readonly DependencyProperty MapProperty
```


