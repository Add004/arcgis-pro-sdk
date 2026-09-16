# SymbolSearcherControl

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Controls.html">Controls</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SymbolSearcherControl.yml" sourcestartlinenumber="1">Use SymbolSearcherControl to search for StyleItems (Point/Line/Polygon symbols, colors, text symbols, etc.).  The Symbol Searcher Control can be used in conjunction with the <xref href="ArcGIS.Desktop.Mapping.Controls.SymbolPickerControl" data-throw-if-not-resolved="false"></xref> or alone to allow selecting a specific style item.
Optional Filters can be applied to the search including <xref href="ArcGIS.Desktop.Mapping.Controls.SymbolSearcherControl.SearchFilterType" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Desktop.Mapping.Controls.SymbolSearcherControl.SearchFilterStyle" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class SymbolSearcherControl : UserControl, IAnimatable, IFrameworkInputElement, IInputElement, ISupportInitialize, IQueryAmbient, IAddChild, INotifyPropertyChanged, IComponentConnector
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SymbolSearcherControl.yml" sourcestartlinenumber="1">Results are available via the <xref href="ArcGIS.Desktop.Mapping.Controls.SymbolSearcherControl.SearchResultStyleItems" data-throw-if-not-resolved="false"></xref>
property.<br>
Use the <xref href="ArcGIS.Desktop.Mapping.Controls.SymbolPickerControl" data-throw-if-not-resolved="false"></xref> to display search results
for a refined selection.</p>


## Members

### SymbolSearcherControl()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SymbolSearcherControl.yml" sourcestartlinenumber="1">Constructor for SymbolSearcherControl.</p>


```csharp
public SymbolSearcherControl()
```
### InitializeComponent()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SymbolSearcherControl.yml" sourcestartlinenumber="1">InitializeComponent</p>


```csharp
public void InitializeComponent()
```
### IsSearching

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SymbolSearcherControl.yml" sourcestartlinenumber="1">Gets whether the <xref href="ArcGIS.Desktop.Mapping.Controls.SymbolSearcherControl" data-throw-if-not-resolved="false"></xref> is searching the current
style or not</p>


```csharp
public bool IsSearching { get; }
```
### IsSearchingProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SymbolSearcherControl.yml" sourcestartlinenumber="1">Gets whether the SymbolSearchControl is searching (IsSearching is true) the current
style or not</p>


```csharp
public static DependencyProperty IsSearchingProperty
```
### OnSearchCompleted()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SymbolSearcherControl.yml" sourcestartlinenumber="1">Raise the SearchCompleted public event.</p>


```csharp
protected virtual void OnSearchCompleted()
```
### SearchCompletedEvent

- Kind: event

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SymbolSearcherControl.yml" sourcestartlinenumber="1">The SearchCompletedEvent event is raised when a search is completed.</p>


```csharp
public event SymbolSearcherControl.SearchCompletedEventHandler SearchCompletedEvent
```
### SearchFilterStyle

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SymbolSearcherControl.yml" sourcestartlinenumber="1">Gets and sets the <xref href="ArcGIS.Desktop.Mapping.Controls.SymbolSearcherSearchFilter" data-throw-if-not-resolved="false"></xref> as a filter to be applied to the <xref href="ArcGIS.Desktop.Mapping.Controls.SymbolSearcherControl" data-throw-if-not-resolved="false"></xref>'s next search.</p>


```csharp
public SymbolSearcherSearchFilter SearchFilterStyle { get; set; }
```
### SearchFilterStyleProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SymbolSearcherControl.yml" sourcestartlinenumber="1">Gets and sets a the SymbolSearcherSearchFilter as a filter to be applied to the <xref href="ArcGIS.Desktop.Mapping.Controls.SymbolSearcherControl" data-throw-if-not-resolved="false"></xref>'s next search.</p>


```csharp
public static DependencyProperty SearchFilterStyleProperty
```
### SearchFilterType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SymbolSearcherControl.yml" sourcestartlinenumber="1">Gets and sets the <xref href="ArcGIS.Desktop.Mapping.StyleItemType" data-throw-if-not-resolved="false"></xref> as a filter to be applied to the <xref href="ArcGIS.Desktop.Mapping.Controls.SymbolSearcherControl" data-throw-if-not-resolved="false"></xref>'s next search.</p>


```csharp
public StyleItemType SearchFilterType { get; set; }
```
### SearchFilterTypeProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SymbolSearcherControl.yml" sourcestartlinenumber="1">Gets and sets the <xref href="ArcGIS.Desktop.Mapping.StyleItemType" data-throw-if-not-resolved="false"></xref> as a filter to be applied to the <xref href="ArcGIS.Desktop.Mapping.Controls.SymbolSearcherControl" data-throw-if-not-resolved="false"></xref>'s next search.</p>


```csharp
public static DependencyProperty SearchFilterTypeProperty
```
### SearchOutputOptions

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SymbolSearcherControl.yml" sourcestartlinenumber="1">Gets and sets the SearchOutputOptions</p>


```csharp
public SymbolSearcherSearchOutputOptions SearchOutputOptions { get; set; }
```
### SearchOutputOptionsProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SymbolSearcherControl.yml" sourcestartlinenumber="1">Gets and sets the SearchOutputOptions</p>


```csharp
public static DependencyProperty SearchOutputOptionsProperty
```
### SearchPauseAutoSearch

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SymbolSearcherControl.yml" sourcestartlinenumber="1">Gets and sets a flag that pauses automatic searching on Filter Changes when the flag is true.</p>


```csharp
public bool SearchPauseAutoSearch { get; set; }
```
### SearchPauseAutoSearchProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SymbolSearcherControl.yml" sourcestartlinenumber="1">Gets and sets a flag that pauses automatic searching on Filter Changes when the flag is true.</p>


```csharp
public static DependencyProperty SearchPauseAutoSearchProperty
```
### SearchResultStyleItems

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SymbolSearcherControl.yml" sourcestartlinenumber="1">Gets the style search results for the symbol searcher</p>


```csharp
public ObservableCollection<StyleItem> SearchResultStyleItems { get; }
```
### SearchResultStyleItemsProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SymbolSearcherControl.yml" sourcestartlinenumber="1">Gets the style search results for the symbol searcher</p>


```csharp
public static DependencyProperty SearchResultStyleItemsProperty
```


