# SelectionControl

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.Controls.html">Controls</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.SelectionControl.yml" sourcestartlinenumber="1">The SelectionControl is a configurable control that provides a UI for displaying the current selection if a Nao in a tree view.</p>


## Object Signature

```csharp
public class SelectionControl : UserControl, IAnimatable, IFrameworkInputElement, IInputElement, ISupportInitialize, IQueryAmbient, IAddChild, IComponentConnector
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.SelectionControl.yml" sourcestartlinenumber="1">To configure the control assign the current <xref href="ArcGIS.Desktop.Editing.Controls.SelectionControl.Map" data-throw-if-not-resolved="false"></xref> to the <xref href="ArcGIS.Desktop.Editing.Controls.SelectionControl.Map" data-throw-if-not-resolved="false"></xref> proeprty.
When the <xref href="ArcGIS.Desktop.Editing.Controls.SelectionControl.Map" data-throw-if-not-resolved="false"></xref> property is set, the control will listen to the <xref href="ArcGIS.Desktop.Mapping.Events.MapSelectionChangedEvent" data-throw-if-not-resolved="false"></xref>
for that map and display the current selection set.</p>
<p></p>
<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.SelectionControl.yml" sourcestartlinenumber="7">Use the <xref href="ArcGIS.Desktop.Editing.Controls.SelectionControl.HighlightedItemsChanged" data-throw-if-not-resolved="false"></xref> event to determine when items in this control are
highlighted by the user. Alternatively use the <xref href="ArcGIS.Desktop.Editing.Controls.SelectionControl.HighlightedItems" data-throw-if-not-resolved="false"></xref> property to get or set items as highlighted.</p>
<p></p>
<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.SelectionControl.yml" sourcestartlinenumber="12">Combine this control with the <xref href="ArcGIS.Desktop.Editing.Controls.SelectionToolPickerControl" data-throw-if-not-resolved="false"></xref> and an Inspector embeddable control (see <xref href="ArcGIS.Desktop.Editing.Attributes.Inspector.CreateEmbeddableControl" data-throw-if-not-resolved="false"></xref>)
to build a simple version of the ArcGIS Pro Attributes windows.  When using the Inspector embeddable control, set the <xref href="ArcGIS.Desktop.Editing.Controls.SelectionControl.Inspector" data-throw-if-not-resolved="false"></xref> dependency property.
See the EditorInspectorUI Community Sample
<a href="https://github.com/Esri/arcgis-pro-sdk-community-samples/tree/master/Editing/EditorInspectorUI">here</a>.</p>


## Members

### SelectionControl()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.SelectionControl.yml" sourcestartlinenumber="1">Default constructor. This will be called via the parent control or window on
which the SelectionControl is hosted.</p>


```csharp
public SelectionControl()
```
### HighlightedItems

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.SelectionControl.yml" sourcestartlinenumber="1">Gets and sets the HighlightedItems property.</p>


```csharp
public SelectionSet HighlightedItems { get; set; }
```
### HighlightedItemsChanged

- Kind: event

<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.SelectionControl.yml" sourcestartlinenumber="1">Occurs when highlighted items in the selection control are changed.</p>


```csharp
public event EventHandler HighlightedItemsChanged
```
### HighlightedItemsProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.SelectionControl.yml" sourcestartlinenumber="1">Dependency property for the items to highlight in this selection control.</p>


```csharp
public static readonly DependencyProperty HighlightedItemsProperty
```
### InitializeComponent()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.SelectionControl.yml" sourcestartlinenumber="1">InitializeComponent</p>


```csharp
public void InitializeComponent()
```
### Inspector

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.SelectionControl.yml" sourcestartlinenumber="1">Gets and sets an Inspector associated with this selection control.</p>


```csharp
public Inspector Inspector { get; set; }
```
### InspectorProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.SelectionControl.yml" sourcestartlinenumber="1">Dependency property for an Inspector that can be associated with this selection control.</p>


```csharp
public static readonly DependencyProperty InspectorProperty
```
### Map

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.SelectionControl.yml" sourcestartlinenumber="1">Gets and sets the Map whose selection will be shown in this control.</p>


```csharp
public Map Map { get; set; }
```
### MapProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.SelectionControl.yml" sourcestartlinenumber="1">Dependency property for the Map whose selection will be shown in this control.</p>


```csharp
public static readonly DependencyProperty MapProperty
```


