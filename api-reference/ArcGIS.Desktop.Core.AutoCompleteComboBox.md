# AutoCompleteComboBox

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.AutoCompleteComboBox.yml" sourcestartlinenumber="1">AutoCompleteComboBox.xaml</p>


## Object Signature

```csharp
public class AutoCompleteComboBox : ComboBox, IAnimatable, IFrameworkInputElement, IInputElement, ISupportInitialize, IQueryAmbient, IAddChild, IContainItemStorage, IComponentConnector
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Core.AutoCompleteComboBox.yml" sourcestartlinenumber="1">This combo box and other supporting classes in this file were ported from the control by the same same in the ArcGIS.Desktop.Sharing project.
Behavior that is very similar to what can be found in the sharing location section of the sharing pane was needed for the PortalProjectInfoView.</p>


## Members

### AutoCompleteComboBox()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.AutoCompleteComboBox.yml" sourcestartlinenumber="1">AutoCompleteComboBox.xaml</p>


```csharp
public AutoCompleteComboBox()
```
### InitializeComponent()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.AutoCompleteComboBox.yml" sourcestartlinenumber="1">InitializeComponent</p>


```csharp
public void InitializeComponent()
```
### OnApplyTemplate()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.AutoCompleteComboBox.yml" sourcestartlinenumber="1">AutoCompleteComboBox.xaml</p>


```csharp
public override void OnApplyTemplate()
```
### OnItemsSourceChanged(IEnumerable, IEnumerable)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.AutoCompleteComboBox.yml" sourcestartlinenumber="1">AutoCompleteComboBox.xaml</p>


```csharp
protected override void OnItemsSourceChanged(IEnumerable oldValue, IEnumerable newValue)
```
### Setting

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.AutoCompleteComboBox.yml" sourcestartlinenumber="1">AutoCompleteComboBox.xaml</p>


```csharp
public AutoCompleteComboBoxSetting Setting { get; set; }
```
### SettingProperty

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.AutoCompleteComboBox.yml" sourcestartlinenumber="1">AutoCompleteComboBox.xaml</p>


```csharp
public static DependencyProperty SettingProperty { get; }
```


