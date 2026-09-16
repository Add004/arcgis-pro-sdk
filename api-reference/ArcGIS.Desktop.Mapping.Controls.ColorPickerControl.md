# ColorPickerControl

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Controls.html">Controls</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.ColorPickerControl.yml" sourcestartlinenumber="1">Use the ColorPickerControl to display colors for selection.</p>


## Object Signature

```csharp
public class ColorPickerControl : UserControl, IAnimatable, IFrameworkInputElement, IInputElement, ISupportInitialize, IQueryAmbient, IAddChild, IComponentConnector
```


## Members

### ColorPickerControl()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.ColorPickerControl.yml" sourcestartlinenumber="1">The color picker control constructor. This will be called via the parent control or window on which the ColorPickerControl is hosted.</p>


```csharp
public ColorPickerControl()
```
### ForceEyeDropperToolToHide

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.ColorPickerControl.yml" sourcestartlinenumber="1">Gets or sets if the eye dropper tool option is to hide.</p>


```csharp
public bool ForceEyeDropperToolToHide { get; set; }
```
### ForceEyeDropperToolToHideProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.ColorPickerControl.yml" sourcestartlinenumber="1">Gets or sets if the Eye Dropper tool option is to hide.</p>


```csharp
public static readonly DependencyProperty ForceEyeDropperToolToHideProperty
```
### InitializeComponent()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.ColorPickerControl.yml" sourcestartlinenumber="1">InitializeComponent</p>


```csharp
public void InitializeComponent()
```
### IsNoColorVisible

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.ColorPickerControl.yml" sourcestartlinenumber="1">Gets or sets if the &quot;No color&quot; option is visible.</p>


```csharp
public bool IsNoColorVisible { get; set; }
```
### IsNoColorVisibleProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.ColorPickerControl.yml" sourcestartlinenumber="1">Gets or sets if the &quot;No color&quot; option is visible.</p>


```csharp
public static readonly DependencyProperty IsNoColorVisibleProperty
```
### OnColorChanged()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.ColorPickerControl.yml" sourcestartlinenumber="1">This raises our 'public' event. Users can hook up delegates or use the SelectedColor
property</p>


```csharp
protected virtual void OnColorChanged()
```
### OnPopupClosed(EventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.ColorPickerControl.yml" sourcestartlinenumber="1">This raises our 'public' event.</p>


```csharp
protected virtual void OnPopupClosed(EventArgs e)
```
### OnPopupOpened(EventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.ColorPickerControl.yml" sourcestartlinenumber="1">This raises our 'public' event.</p>


```csharp
protected virtual void OnPopupOpened(EventArgs e)
```
### PopupClosed

- Kind: event

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.ColorPickerControl.yml" sourcestartlinenumber="1">The PopupClosed event occurs when the popup is closed.</p>


```csharp
public event EventHandler PopupClosed
```
### PopupOpened

- Kind: event

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.ColorPickerControl.yml" sourcestartlinenumber="1">The PopupOpened event occurs when the popup is opened.</p>


```csharp
public event EventHandler PopupOpened
```
### SelectedColor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.ColorPickerControl.yml" sourcestartlinenumber="1">Gets or sets the selected color in the control.</p>


```csharp
public CIMColor SelectedColor { get; set; }
```
### SelectedColorChanged

- Kind: event

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.ColorPickerControl.yml" sourcestartlinenumber="1">The SelectedColorChanged event is raised when the color selection is changed in the
control UI.</p>


```csharp
public event ColorChangedEventHandler SelectedColorChanged
```
### SelectedColorProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.ColorPickerControl.yml" sourcestartlinenumber="1">Gets or sets the selected color in the control.</p>


```csharp
public static readonly DependencyProperty SelectedColorProperty
```


