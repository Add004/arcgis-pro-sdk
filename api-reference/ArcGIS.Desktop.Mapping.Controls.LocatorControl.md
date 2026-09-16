# LocatorControl

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Controls.html">Controls</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.LocatorControl.yml" sourcestartlinenumber="1">The LocatorControl is a configurable control that provides a UI for geocoding a location.</p>


## Object Signature

```csharp
public class LocatorControl : UserControl, IAnimatable, IFrameworkInputElement, IInputElement, ISupportInitialize, IQueryAmbient, IAddChild, INotifyPropertyChanged, IComponentConnector
```


## Members

### LocatorControl()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.LocatorControl.yml" sourcestartlinenumber="1">Default constructor. This will be called via the parent control or window on
which the LocatorControl is hosted.</p>


```csharp
public LocatorControl()
```
### ConfigureControl

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.LocatorControl.yml" sourcestartlinenumber="1">Gets and sets the LocatorControlConfigureProperties to be used to configure the
LocatorControl.</p>


```csharp
public LocatorControlConfigureProperties ConfigureControl { get; set; }
```
### ConfigureControlProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.LocatorControl.yml" sourcestartlinenumber="1">DependencyProperty to which a LocatorControlConfigureProperties used to
configure the LocatorControl can be bound</p>


```csharp
public static readonly DependencyProperty ConfigureControlProperty
```
### InitializeComponent()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.LocatorControl.yml" sourcestartlinenumber="1">InitializeComponent</p>


```csharp
public void InitializeComponent()
```
### LocateIsEnabled

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.LocatorControl.yml" sourcestartlinenumber="1">Gets the enabled state of the LocatorControl.  The control is enabled after internal initialization has occurred.</p>


```csharp
public bool LocateIsEnabled { get; }
```
### LocatorChanged

- Kind: event

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.LocatorControl.yml" sourcestartlinenumber="1">The LocatorChanged event is raised when the locator providers are altered.  A change consists of one of the following :
locators are addded, locators are removed, locator order changes or their UseSuggestions, Enable flags are altered.</p>


```csharp
public event LocatorChangedEventHandler LocatorChanged
```
### OnSelectedGeocodeResultsChanged(List&lt;GeocodeResult&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.LocatorControl.yml" sourcestartlinenumber="1">Callback from SelectedCandidates_CollectionChanged</p>


```csharp
protected virtual void OnSelectedGeocodeResultsChanged(List<GeocodeResult> selectedResults)
```
### PropertyChanged

- Kind: event

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.LocatorControl.yml" sourcestartlinenumber="1">Register for property changed event notifications</p>


```csharp
public event PropertyChangedEventHandler PropertyChanged
```
### SelectedGeocodeResultsChanged

- Kind: event

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.LocatorControl.yml" sourcestartlinenumber="1">The SelectedGeocodeResultChanged event is raised when the geocode result selection is changed in the
control UI</p>


```csharp
public event SelectedGeocodeResultChangedEventHandler SelectedGeocodeResultsChanged
```


