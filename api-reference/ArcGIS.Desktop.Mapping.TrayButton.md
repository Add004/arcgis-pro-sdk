# TrayButton

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.TrayButton.yml" sourcestartlinenumber="1">Represents a button that can be added to the ArcGIS Pro Tray.</p>


## Object Signature

```csharp
public abstract class TrayButton : ViewModelBase, IDisposable
```

## Remarks

<p>This base class can be used to create buttons that appear in the tray area of every <xref href="ArcGIS.Desktop.Mapping.MapView" data-throw-if-not-resolved="false"></xref>
     and <xref href="ArcGIS.Desktop.Layouts.LayoutView" data-throw-if-not-resolved="false"></xref>.
     It provides virtual methods that can be overridden to perform actions during the life cycle of this button.</p>
<p>Specify the type of desired button by setting <xref href="ArcGIS.Desktop.Mapping.TrayButton.ButtonType" data-throw-if-not-resolved="false"></xref> within either an overridden constructor or <xref href="ArcGIS.Desktop.Mapping.TrayButton.Initialize" data-throw-if-not-resolved="false"></xref>.
     After Initialize has been invoked, the underlying UI Button will be fixed for the lifetime of the associated view.</p>
<p> If ButtonType has been set to <xref href="ArcGIS.Desktop.Mapping.TrayButtonType.Button" data-throw-if-not-resolved="false"></xref>
     then <xref href="ArcGIS.Desktop.Mapping.TrayButton.ClickCommand" data-throw-if-not-resolved="false"></xref> should also be set - it will be invoked whenever the UI button is clicked.</p>
<p> If ButtonType has been set to <xref href="ArcGIS.Desktop.Mapping.TrayButtonType.ToggleButton" data-throw-if-not-resolved="false"></xref>
     then <xref href="ArcGIS.Desktop.Mapping.TrayButton.OnButtonChecked" data-throw-if-not-resolved="false"></xref> will be invoked whenever the UI button's Checked state is changed.</p>
<p> If ButtonType has been set to <xref href="ArcGIS.Desktop.Mapping.TrayButtonType.PopupToggleButton" data-throw-if-not-resolved="false"></xref>
     then <xref href="ArcGIS.Desktop.Mapping.TrayButton.OnButtonChecked" data-throw-if-not-resolved="false"></xref> will be invoked whenever the UI button's Checked state is changed.  In addition, a
     customizable popup window will be displayed whenever the mouse is hovered over the button.
     Override <xref href="ArcGIS.Desktop.Mapping.TrayButton.ConstructPopupContent" data-throw-if-not-resolved="false"></xref> to provide the content that will be displayed in the popup.</p>
<p> To add to the tray of a MapView, add a TrayButton component to the "esri_mapping_MapTrayButtons" category within DAML.</p>
<p> To add to the tray of a LayoutView, add a TrayButton component to the "esri_layouts_LayoutTrayButtons" category within DAML.</p>


## Members

### TrayButton()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.TrayButton.yml" sourcestartlinenumber="1">Default constructor for TrayButton.</p>


```csharp
protected TrayButton()
```
### ButtonType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TrayButton.yml" sourcestartlinenumber="1">Gets or sets the type of TrayButton.</p>


```csharp
public TrayButtonType ButtonType { get; protected set; }
```
### CanAutoClose

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TrayButton.yml" sourcestartlinenumber="1">Gets or sets whether or not a Popup can automatically close when user moves the mouse outside the bounds of the popup.</p>


```csharp
public bool CanAutoClose { get; set; }
```
### ClickCommand

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TrayButton.yml" sourcestartlinenumber="1">Gets or sets an associated Command that is invoked whenever the corresponding UI Button is clicked.</p>


```csharp
public RelayCommand ClickCommand { get; protected set; }
```
### ClosePopup()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TrayButton.yml" sourcestartlinenumber="1">Helper method, provides a way to programmatically close the popup.</p>


```csharp
protected void ClosePopup()
```
### ConstructPopupContent()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TrayButton.yml" sourcestartlinenumber="1">Constructs a ContentControl that will be displayed as the Content within a popup window.</p>


```csharp
protected virtual ContentControl ConstructPopupContent()
```
### DisabledTooltip

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TrayButton.yml" sourcestartlinenumber="1">Gets the DAML disabledTooltip content property of this <xref href="ArcGIS.Desktop.Mapping.TrayButton" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public string DisabledTooltip { get; }
```
### Dispose()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TrayButton.yml" sourcestartlinenumber="1">When invoked, ensures <xref href="ArcGIS.Desktop.Mapping.TrayButton.Dispose(System.Boolean)" data-throw-if-not-resolved="false"></xref> is invoked only once.</p>


```csharp
public void Dispose()
```
### Dispose(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TrayButton.yml" sourcestartlinenumber="1">Invoked when the enclosing View is closed and disposed.</p>


```csharp
protected virtual void Dispose(bool isDisposing)
```
### Finalize()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TrayButton.yml" sourcestartlinenumber="1">Represents a button that can be added to the ArcGIS Pro Tray.</p>


```csharp
protected override void Finalize()
```
### FlipImageRTL

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TrayButton.yml" sourcestartlinenumber="1">Gets a boolean indicating if this <xref href="ArcGIS.Desktop.Mapping.TrayButton" data-throw-if-not-resolved="false"></xref> requires it's images to flipped on RTL.</p>


```csharp
public bool FlipImageRTL { get; }
```
### FocusView()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TrayButton.yml" sourcestartlinenumber="1">Helper method, provides a way to give focus to the current View.</p>


```csharp
protected void FocusView()
```
### HasSeparator

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TrayButton.yml" sourcestartlinenumber="1">Gets a boolean indicating if this <xref href="ArcGIS.Desktop.Mapping.TrayButton" data-throw-if-not-resolved="false"></xref> has a separator defined by the DAML separator content property.</p>


```csharp
public bool HasSeparator { get; }
```
### HelpURI

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TrayButton.yml" sourcestartlinenumber="1">Gets the DAML helpURI property of this <xref href="ArcGIS.Desktop.Mapping.TrayButton" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public string HelpURI { get; }
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TrayButton.yml" sourcestartlinenumber="1">Gets the DAML ID of this <xref href="ArcGIS.Desktop.Mapping.TrayButton" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public string ID { get; }
```
### Initialize()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TrayButton.yml" sourcestartlinenumber="1">Invoked straight after construction, and after all DAML settings have been loaded.</p>


```csharp
protected virtual void Initialize()
```
### IsBusy

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TrayButton.yml" sourcestartlinenumber="1">Gets if the tray button is busy.</p>


```csharp
public bool IsBusy { get; protected set; }
```
### IsChecked

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TrayButton.yml" sourcestartlinenumber="1">Gets or sets whether or not this <xref href="ArcGIS.Desktop.Mapping.TrayButton" data-throw-if-not-resolved="false"></xref> is Checked.</p>


```csharp
public bool IsChecked { get; set; }
```
### IsEnabled

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TrayButton.yml" sourcestartlinenumber="1">Gets or sets whether or not this <xref href="ArcGIS.Desktop.Mapping.TrayButton" data-throw-if-not-resolved="false"></xref> is enabled.</p>


```csharp
public bool IsEnabled { get; protected set; }
```
### IsVisibleOnView()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TrayButton.yml" sourcestartlinenumber="1">Gets whether or not this TrayButton is visible in the tray for the current <xref href="ArcGIS.Desktop.Mapping.TrayButton.Pane" data-throw-if-not-resolved="false"></xref></p>


```csharp
public virtual bool IsVisibleOnView()
```
### LargeImage

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TrayButton.yml" sourcestartlinenumber="1">Gets the DAML largeImage content property of this <xref href="ArcGIS.Desktop.Mapping.TrayButton" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public object LargeImage { get; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TrayButton.yml" sourcestartlinenumber="1">Gets the DAML name content property of this <xref href="ArcGIS.Desktop.Mapping.TrayButton" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public string Name { get; }
```
### OnButtonChecked()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TrayButton.yml" sourcestartlinenumber="1">Callback for when the value of <xref href="ArcGIS.Desktop.Mapping.TrayButton.IsChecked" data-throw-if-not-resolved="false"></xref> is changed.</p>


```csharp
protected virtual void OnButtonChecked()
```
### OnButtonLoaded()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TrayButton.yml" sourcestartlinenumber="1">Occurs when the corresponding UI Button has been added to the UI and the View is ready for use.</p>


```csharp
protected virtual void OnButtonLoaded()
```
### OnHidePopup()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TrayButton.yml" sourcestartlinenumber="1">Occurs when the popup is closed (but not disposed).</p>


```csharp
protected virtual void OnHidePopup()
```
### OnShowPopup()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TrayButton.yml" sourcestartlinenumber="1">Occurs when the popup is opened.</p>


```csharp
protected virtual void OnShowPopup()
```
### Pane

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TrayButton.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Desktop.Mapping.TrayButton.Pane" data-throw-if-not-resolved="false"></xref> that contains this TrayButton's Tray.</p>


```csharp
protected Pane Pane { get; }
```
### SetCancelMessage(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TrayButton.yml" sourcestartlinenumber="1">Sets a cancel message for the tray button.</p>


```csharp
protected void SetCancelMessage(string msg)
```
### SetCheckedNoCallback(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TrayButton.yml" sourcestartlinenumber="1">Helper method available to allow changing the value of <xref href="ArcGIS.Desktop.Mapping.TrayButton.IsChecked" data-throw-if-not-resolved="false"></xref> without an immediate callback to <xref href="ArcGIS.Desktop.Mapping.TrayButton.OnButtonChecked" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
protected void SetCheckedNoCallback(bool isChecked)
```
### SetWarningMessage(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.TrayButton.yml" sourcestartlinenumber="1">Sets a warning message for the tray button.</p>


```csharp
protected void SetWarningMessage(string msg)
```
### SmallImage

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TrayButton.yml" sourcestartlinenumber="1">Gets or sets the SmallImage property of this <xref href="ArcGIS.Desktop.Mapping.TrayButton" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public object SmallImage { get; protected set; }
```
### Tooltip

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TrayButton.yml" sourcestartlinenumber="1">Gets the DAML tooltip content property of this <xref href="ArcGIS.Desktop.Mapping.TrayButton" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public string Tooltip { get; }
```
### TooltipHeading

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TrayButton.yml" sourcestartlinenumber="1">Gets the DAML tooltipHeading content property of this <xref href="ArcGIS.Desktop.Mapping.TrayButton" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public string TooltipHeading { get; }
```


