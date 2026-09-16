# MapMemberIDSetControl

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.Controls.html">Controls</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.MapMemberIDSetControl.yml" sourcestartlinenumber="1">The MapMemberIDSetControl is a configurable control that provides a UI for displaying a fixed set of rows or features using a
<xref href="ArcGIS.Desktop.Editing.Controls.MapMemberIDSetControl.MapMemberIDSet" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class MapMemberIDSetControl : UserControl, IAnimatable, IFrameworkInputElement, IInputElement, ISupportInitialize, IQueryAmbient, IAddChild, IComponentConnector
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.MapMemberIDSetControl.yml" sourcestartlinenumber="1">To configure the control assign the current <xref href="ArcGIS.Desktop.Editing.Controls.MapMemberIDSetControl.Map" data-throw-if-not-resolved="false"></xref> to the <xref href="ArcGIS.Desktop.Editing.Controls.MapMemberIDSetControl.Map" data-throw-if-not-resolved="false"></xref> proeprty and a
<xref href="ArcGIS.Desktop.Editing.Controls.MapMemberIDSetControl.MapMemberIDSet" data-throw-if-not-resolved="false"></xref> to the <xref href="ArcGIS.Desktop.Editing.Controls.MapMemberIDSetControl.MapMemberIDSet" data-throw-if-not-resolved="false"></xref> proeprty.</p>
<p></p>
<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.MapMemberIDSetControl.yml" sourcestartlinenumber="6">Use the <xref href="ArcGIS.Desktop.Editing.Controls.MapMemberIDSetControl.HighlightedItemsChanged" data-throw-if-not-resolved="false"></xref> event to determine when items in this control are
highlighted by the user. Alternatively use the <xref href="ArcGIS.Desktop.Editing.Controls.MapMemberIDSetControl.HighlightedItems" data-throw-if-not-resolved="false"></xref> property to get or set items as highlighted.</p>
<p></p>


## Members

### MapMemberIDSetControl()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.MapMemberIDSetControl.yml" sourcestartlinenumber="1">Default constructor. This will be called via the parent control or window on
which the MapMemberIDSetControl is hosted.</p>


```csharp
public MapMemberIDSetControl()
```
### HighlightedItems

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.MapMemberIDSetControl.yml" sourcestartlinenumber="1">Gets and sets the HighlightedItems property.</p>


```csharp
public MapMemberIDSet HighlightedItems { get; set; }
```
### HighlightedItemsChanged

- Kind: event

<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.MapMemberIDSetControl.yml" sourcestartlinenumber="1">Occurs when highlighted items in the selection control are changed.</p>


```csharp
public event EventHandler HighlightedItemsChanged
```
### HighlightedItemsProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.MapMemberIDSetControl.yml" sourcestartlinenumber="1">Dependency property for the items to highlight in this selection control.</p>


```csharp
public static readonly DependencyProperty HighlightedItemsProperty
```
### InitializeComponent()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.MapMemberIDSetControl.yml" sourcestartlinenumber="1">InitializeComponent</p>


```csharp
public void InitializeComponent()
```
### Inspector

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.MapMemberIDSetControl.yml" sourcestartlinenumber="1">Gets and sets an Inspector associated with this selection control.</p>


```csharp
public Inspector Inspector { get; set; }
```
### InspectorProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.MapMemberIDSetControl.yml" sourcestartlinenumber="1">Dependency property for an Inspector that can be associated with this selection control.</p>


```csharp
public static readonly DependencyProperty InspectorProperty
```
### Map

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.MapMemberIDSetControl.yml" sourcestartlinenumber="1">Gets and sets the Map whose content will be shown in this control.</p>


```csharp
public Map Map { get; set; }
```
### MapMemberIDSet

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.MapMemberIDSetControl.yml" sourcestartlinenumber="1">Gets and sets the MapMemberIDSet which will be shown in this control.</p>


```csharp
public MapMemberIDSet MapMemberIDSet { get; set; }
```
### MapMemberIDSetProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.MapMemberIDSetControl.yml" sourcestartlinenumber="1">Dependency property for the MapMemberIDSet to be shown in this control.</p>


```csharp
public static readonly DependencyProperty MapMemberIDSetProperty
```
### MapProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.MapMemberIDSetControl.yml" sourcestartlinenumber="1">Dependency property for the Map whose content will be shown in this control.</p>


```csharp
public static readonly DependencyProperty MapProperty
```


