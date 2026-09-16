# SymbolPickerControl

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Controls.html">Controls</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SymbolPickerControl.yml" sourcestartlinenumber="1">Use the SymbolPickerControl to display &quot;symbols&quot; (i.e <xref href="ArcGIS.Desktop.Mapping.StyleItem" data-throw-if-not-resolved="false"></xref>)
for selection.</p>


## Object Signature

```csharp
public class SymbolPickerControl : UserControl, IAnimatable, IFrameworkInputElement, IInputElement, ISupportInitialize, IQueryAmbient, IAddChild, INotifyPropertyChanged, IComponentConnector
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SymbolPickerControl.yml" sourcestartlinenumber="1">Use in conjunction with the <xref href="ArcGIS.Desktop.Mapping.Controls.SymbolSearcherControl" data-throw-if-not-resolved="false"></xref>
to provide a searching experience similar to the &quot;built-in&quot; symbol
picker shown on the Pro symbology dockpane</p>


## Members

### SymbolPickerControl()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SymbolPickerControl.yml" sourcestartlinenumber="1">Constructor for SymbolPickerControl.</p>


```csharp
public SymbolPickerControl()
```
### GroupingOption

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SymbolPickerControl.yml" sourcestartlinenumber="1">Gets and sets the option for how the style items will be grouped in the symbol picker.</p>


```csharp
public SymbolPickerGroupOption GroupingOption { get; set; }
```
### GroupingOptionProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SymbolPickerControl.yml" sourcestartlinenumber="1">Gets and sets the option for how the style items will be grouped in the picker</p>


```csharp
public static DependencyProperty GroupingOptionProperty
```
### InitializeComponent()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SymbolPickerControl.yml" sourcestartlinenumber="1">InitializeComponent</p>


```csharp
public void InitializeComponent()
```
### PickerStyleItems

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SymbolPickerControl.yml" sourcestartlinenumber="1">Gets and sets the list of style items to be shown in the symbol picker.</p>


```csharp
public ObservableCollection<StyleItem> PickerStyleItems { get; set; }
```
### PickerStyleItemsProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SymbolPickerControl.yml" sourcestartlinenumber="1">Gets and sets the list of style items to be shown in the Symbol Picker control.</p>


```csharp
public static DependencyProperty PickerStyleItemsProperty
```
### SelectedPickerStyleItem

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SymbolPickerControl.yml" sourcestartlinenumber="1">Gets and sets the list of style items to be shown in the symbol picker.</p>


```csharp
public StyleItem SelectedPickerStyleItem { get; set; }
```
### SelectedPickerStyleItemProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SymbolPickerControl.yml" sourcestartlinenumber="1">Gets and sets the list of style items to be shown in the symbol picker.</p>


```csharp
public static DependencyProperty SelectedPickerStyleItemProperty
```
### ShowOptionsDropDown

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SymbolPickerControl.yml" sourcestartlinenumber="1">Gets and sets whether to show the options burger button on the control.</p>


```csharp
public bool ShowOptionsDropDown { get; set; }
```
### ShowOptionsDropDownProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SymbolPickerControl.yml" sourcestartlinenumber="1">Gets and sets whether to show the options burger button on the control.</p>


```csharp
public static DependencyProperty ShowOptionsDropDownProperty
```
### ViewingOption

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SymbolPickerControl.yml" sourcestartlinenumber="1">Gets and sets the option for how the style items will be shown in the symbol picker.</p>


```csharp
public SymbolPickerViewOption ViewingOption { get; set; }
```
### ViewingOptionProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SymbolPickerControl.yml" sourcestartlinenumber="1">Gets and sets the option for how the style items will be shown in the picker</p>


```csharp
public static DependencyProperty ViewingOptionProperty
```


