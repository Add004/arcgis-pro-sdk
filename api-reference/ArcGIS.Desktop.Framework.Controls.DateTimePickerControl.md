# DateTimePickerControl

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Controls.html">Controls</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.DateTimePickerControl.yml" sourcestartlinenumber="1">The DateTimePickerControl provides a UI for displaying or choosing a date/time.</p>


## Object Signature

```csharp
public class DateTimePickerControl : UserControl, IAnimatable, IFrameworkInputElement, IInputElement, ISupportInitialize, IQueryAmbient, IAddChild, IComponentConnector
```


## Members

### DateTimePickerControl()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.DateTimePickerControl.yml" sourcestartlinenumber="1">The datetime picker control constructor. This will be called via the parent control or window on which the DateTimePickerControl is hosted.</p>


```csharp
public DateTimePickerControl()
```
### CalendarMaxDate

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.DateTimePickerControl.yml" sourcestartlinenumber="1">Gets the calendar maximum date.</p>


```csharp
public DateTime CalendarMaxDate { get; }
```
### CalendarMinDate

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.DateTimePickerControl.yml" sourcestartlinenumber="1">Gets the calendar minimum date.</p>


```csharp
public DateTime CalendarMinDate { get; }
```
### InitializeComponent()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.DateTimePickerControl.yml" sourcestartlinenumber="1">InitializeComponent</p>


```csharp
public void InitializeComponent()
```
### IsNullAllowed

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.DateTimePickerControl.yml" sourcestartlinenumber="1">Gets or sets whether the <xref href="ArcGIS.Desktop.Framework.Controls.DateTimePickerControl.SelectedDate" data-throw-if-not-resolved="false"></xref> property can be set to null.</p>


```csharp
public bool IsNullAllowed { get; set; }
```
### IsNullAllowedProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.DateTimePickerControl.yml" sourcestartlinenumber="1">Gets the dependency property for IsNullAllowed which determines whether the <xref href="ArcGIS.Desktop.Framework.Controls.DateTimePickerControl.SelectedDate" data-throw-if-not-resolved="false"></xref> can be set to null.</p>


```csharp
public static readonly DependencyProperty IsNullAllowedProperty
```
### IsPopupOpen

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.DateTimePickerControl.yml" sourcestartlinenumber="1">Gets or sets whether the popup is open.</p>


```csharp
public bool IsPopupOpen { get; set; }
```
### IsPopupOpenProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.DateTimePickerControl.yml" sourcestartlinenumber="1">Gets the dependency property for IsPopupOpen which determines whether the popup is open.</p>


```csharp
public static readonly DependencyProperty IsPopupOpenProperty
```
### Mode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.DateTimePickerControl.yml" sourcestartlinenumber="1">Gets or sets the mode of the control.  See <xref href="ArcGIS.Desktop.Framework.Controls.DateTimeMode" data-throw-if-not-resolved="false"></xref> for the different possible values.</p>


```csharp
public DateTimeMode Mode { get; set; }
```
### ModeProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.DateTimePickerControl.yml" sourcestartlinenumber="1">Gets the dependency property for Mode which determines the display mode of the control.</p>


```csharp
public static readonly DependencyProperty ModeProperty
```
### NullDateText

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.DateTimePickerControl.yml" sourcestartlinenumber="1">Gets or sets the string value to display when the <xref href="ArcGIS.Desktop.Framework.Controls.DateTimePickerControl.SelectedDate" data-throw-if-not-resolved="false"></xref> value is null.</p>


```csharp
public string NullDateText { get; set; }
```
### NullDateTextProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.DateTimePickerControl.yml" sourcestartlinenumber="1">Gets the dependency property for NullDateText which sets the string value to display when the <xref href="ArcGIS.Desktop.Framework.Controls.DateTimePickerControl.SelectedDate" data-throw-if-not-resolved="false"></xref> value is null.</p>


```csharp
public static readonly DependencyProperty NullDateTextProperty
```
### Offset

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.DateTimePickerControl.yml" sourcestartlinenumber="1">Gets or sets the date Offset property.  This is only applicable if <xref href="ArcGIS.Desktop.Framework.Controls.DateTimePickerControl.Mode" data-throw-if-not-resolved="false"></xref> is set to <xref href="ArcGIS.Desktop.Framework.Controls.DateTimeMode.DateTimeOffset" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public TimeSpan? Offset { get; set; }
```
### OffsetProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.DateTimePickerControl.yml" sourcestartlinenumber="1">Gets the OffsetProperty.</p>


```csharp
public static readonly DependencyProperty OffsetProperty
```
### OnDateChanged()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.DateTimePickerControl.yml" sourcestartlinenumber="1">This raises our 'public' event for a dateTime change. Users can hook up delegates or use the SelectedDate dependency property.</p>


```csharp
protected virtual void OnDateChanged()
```
### OnDateOffsetChanged()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.DateTimePickerControl.yml" sourcestartlinenumber="1">This raises our 'public' event for a DateTimeOffset change. Users can hook up delegates or use the SelectedDate / Offset dependency properties.</p>


```csharp
protected virtual void OnDateOffsetChanged()
```
### OnPopupClosed(EventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.DateTimePickerControl.yml" sourcestartlinenumber="1">This raises our 'public' event when the date time picker is closed.</p>


```csharp
protected virtual void OnPopupClosed(EventArgs e)
```
### OnPopupOpened(EventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.DateTimePickerControl.yml" sourcestartlinenumber="1">This raises our 'public' event when the date time picker is opened.</p>


```csharp
protected virtual void OnPopupOpened(EventArgs e)
```
### PopupClosed

- Kind: event

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.DateTimePickerControl.yml" sourcestartlinenumber="1">The PopupClosed event occurs when the <xref href="ArcGIS.Desktop.Framework.Controls.DateTimePickerControl.IsPopupOpen" data-throw-if-not-resolved="false"></xref> property changes to false.</p>


```csharp
public event EventHandler PopupClosed
```
### PopupOpened

- Kind: event

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.DateTimePickerControl.yml" sourcestartlinenumber="1">The PopupOpened event occurs when the <xref href="ArcGIS.Desktop.Framework.Controls.DateTimePickerControl.IsPopupOpen" data-throw-if-not-resolved="false"></xref> property changes to true.</p>


```csharp
public event EventHandler PopupOpened
```
### SelectedDate

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.DateTimePickerControl.yml" sourcestartlinenumber="1">Gets or sets the DateTime value displayed in the control.</p>


```csharp
public DateTime? SelectedDate { get; set; }
```
### SelectedDateChanged

- Kind: event

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.DateTimePickerControl.yml" sourcestartlinenumber="1">The SelectedDateChanged event is raised when the datetime is changed in the control UI.</p>


```csharp
public event DateChangedEventHandler SelectedDateChanged
```
### SelectedDateProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.DateTimePickerControl.yml" sourcestartlinenumber="1">Gets the dependency property for the selected datetime.</p>


```csharp
public static readonly DependencyProperty SelectedDateProperty
```
### ShowDate

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.DateTimePickerControl.yml" sourcestartlinenumber="1">Gets or sets whether the control shows date.</p>


```csharp
[Obsolete("This property is obsolete. Use the Mode property instead.")]
public bool ShowDate { get; set; }
```
### ShowDateProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.DateTimePickerControl.yml" sourcestartlinenumber="1">Gets the dependency property for ShowDate which determines whether the control displays date.</p>


```csharp
[Obsolete("This property is obsolete. Use the Mode property instead.")]
public static readonly DependencyProperty ShowDateProperty
```
### ShowTextBox

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.DateTimePickerControl.yml" sourcestartlinenumber="1">Gets or sets whether a text box to display the date/time is shown next to the picker control.</p>


```csharp
public bool ShowTextBox { get; set; }
```
### ShowTextBoxProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.DateTimePickerControl.yml" sourcestartlinenumber="1">Gets the dependency property for ShowTextBox which controls whether a text box to display the date/time is shown next to the picker control.</p>


```csharp
public static readonly DependencyProperty ShowTextBoxProperty
```
### ShowTime

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.DateTimePickerControl.yml" sourcestartlinenumber="1">Gets or sets whether the control shows time.</p>


```csharp
[Obsolete("This property is obsolete. Use the Mode property instead.", false)]
public bool ShowTime { get; set; }
```
### ShowTimeProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.DateTimePickerControl.yml" sourcestartlinenumber="1">Gets the dependency property for ShowTime which determines whether the control displays time.</p>


```csharp
[Obsolete("This property is obsolete. Use the Mode property instead.", false)]
public static readonly DependencyProperty ShowTimeProperty
```
### TimeZoneID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.DateTimePickerControl.yml" sourcestartlinenumber="1">Gets or sets the TimeZoneID property.</p>


```csharp
public string TimeZoneID { get; set; }
```
### TimeZoneIDProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.DateTimePickerControl.yml" sourcestartlinenumber="1">Gets the dependency property for TimeZoneID.</p>


```csharp
public static readonly DependencyProperty TimeZoneIDProperty
```
### TimeZoneName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.DateTimePickerControl.yml" sourcestartlinenumber="1">Gets or sets the TimeZoneName property.  This is the string displayed in the UI to indicate a time zone for the dateTime.
Set in conjunction with <xref href="ArcGIS.Desktop.Framework.Controls.DateTimePickerControl.TimeZoneID" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public string TimeZoneName { get; set; }
```
### TimeZoneNameProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.DateTimePickerControl.yml" sourcestartlinenumber="1">Gets the dependency property for TimeZoneName.</p>


```csharp
public static readonly DependencyProperty TimeZoneNameProperty
```
### UseDefaultCalendar

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.DateTimePickerControl.yml" sourcestartlinenumber="1">Gets whether the control displays the default calendar.</p>


```csharp
public bool UseDefaultCalendar { get; }
```
### UseHijriCalendar

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.DateTimePickerControl.yml" sourcestartlinenumber="1">Gets whether the control displays the Hijri calendar.</p>


```csharp
public bool UseHijriCalendar { get; }
```


