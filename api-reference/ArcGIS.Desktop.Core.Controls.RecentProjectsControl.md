# RecentProjectsControl

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.Controls.html">Controls</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.RecentProjectsControl.yml" sourcestartlinenumber="1">The RecentProjectsControl provides a UI for displaying the pinned and recently opened ArcGIS Pro projects.</p>


## Object Signature

```csharp
public class RecentProjectsControl : UserControl, IAnimatable, IFrameworkInputElement, IInputElement, ISupportInitialize, IQueryAmbient, IAddChild, IComponentConnector
```


## Members

### RecentProjectsControl()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.RecentProjectsControl.yml" sourcestartlinenumber="1">Default constructor</p>


```csharp
public RecentProjectsControl()
```
### InitializeComponent()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.RecentProjectsControl.yml" sourcestartlinenumber="1">InitializeComponent</p>


```csharp
public void InitializeComponent()
```
### IsBrowseProjectsVisible

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.RecentProjectsControl.yml" sourcestartlinenumber="1">Gets or sets if the browse project button is visible. Default value is true.</p>


```csharp
public bool IsBrowseProjectsVisible { get; set; }
```
### IsBrowseProjectsVisibleProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.RecentProjectsControl.yml" sourcestartlinenumber="1">Gets or sets if the browse project button is visible. Default value is true.</p>


```csharp
public static readonly DependencyProperty IsBrowseProjectsVisibleProperty
```
### IsFilterVisible

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.RecentProjectsControl.yml" sourcestartlinenumber="1">Gets or sets if the filter is visible. Default value is true.</p>


```csharp
public bool IsFilterVisible { get; set; }
```
### IsFilterVisibleProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.RecentProjectsControl.yml" sourcestartlinenumber="1">Gets or sets if the filter is visible. Default value is true.</p>


```csharp
public static readonly DependencyProperty IsFilterVisibleProperty
```
### IsSortVisible

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.RecentProjectsControl.yml" sourcestartlinenumber="1">Gets or sets if the sort button is visible. Default value is true.</p>


```csharp
public bool IsSortVisible { get; set; }
```
### IsSortVisibleProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.RecentProjectsControl.yml" sourcestartlinenumber="1">Gets or sets if the sort button is visible. Default value is true.</p>


```csharp
public static readonly DependencyProperty IsSortVisibleProperty
```
### IsTitleVisible

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.RecentProjectsControl.yml" sourcestartlinenumber="1">Gets or sets if the title is visible. Default value is true.</p>


```csharp
public bool IsTitleVisible { get; set; }
```
### IsTitleVisibleProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.RecentProjectsControl.yml" sourcestartlinenumber="1">Gets or sets if the title is visible. Default value is true.</p>


```csharp
public static readonly DependencyProperty IsTitleVisibleProperty
```
### IsViewTypesVisible

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.RecentProjectsControl.yml" sourcestartlinenumber="1">Gets or sets if the view type buttons are visible. Default value is true.</p>


```csharp
public bool IsViewTypesVisible { get; set; }
```
### IsViewTypesVisibleProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.RecentProjectsControl.yml" sourcestartlinenumber="1">Gets or sets if the view type buttons are visible. Default value is true.</p>


```csharp
public static readonly DependencyProperty IsViewTypesVisibleProperty
```
### PinnedProjects

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.RecentProjectsControl.yml" sourcestartlinenumber="1">Gets the list of pinned projects. The project path can be a path to a local project or the fully qualified url to a portal project item.</p>


```csharp
public IReadOnlyList<string> PinnedProjects { get; }
```
### PinnedProjectsProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.RecentProjectsControl.yml" sourcestartlinenumber="1">Gets the list of pinned projects.</p>


```csharp
public static readonly DependencyProperty PinnedProjectsProperty
```
### RecentProjects

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.RecentProjectsControl.yml" sourcestartlinenumber="1">Gets the list of recent projects. The project path can be a path to a local project or the fully qualified url to a portal project item.</p>


```csharp
public IReadOnlyList<string> RecentProjects { get; }
```
### RecentProjectsProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.RecentProjectsControl.yml" sourcestartlinenumber="1">Gets the list of recent projects.</p>


```csharp
public static readonly DependencyProperty RecentProjectsProperty
```
### SelectedProject

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.RecentProjectsControl.yml" sourcestartlinenumber="1">Gets the selected project.</p>


```csharp
public string SelectedProject { get; }
```
### SelectedProjectChanged

- Kind: event

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.RecentProjectsControl.yml" sourcestartlinenumber="1">The SelectedProjectChanged event is raised when a project in the RecentProjectsControl is chosen.</p>


```csharp
public event RecentProjectsControl.SelectedProjectChangedEventHandler SelectedProjectChanged
```
### SelectedProjectProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.RecentProjectsControl.yml" sourcestartlinenumber="1">Gets the selected project.</p>


```csharp
public static readonly DependencyProperty SelectedProjectProperty
```
### ShowHorizontalScroll

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.RecentProjectsControl.yml" sourcestartlinenumber="1">Gets or sets if or how the horizontal scrollbar will be displayed</p>


```csharp
public ScrollBarVisibility ShowHorizontalScroll { get; set; }
```
### ShowHorizontalScrollProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.RecentProjectsControl.yml" sourcestartlinenumber="1">Gets or sets ShowHorizontalScroll</p>


```csharp
public static readonly DependencyProperty ShowHorizontalScrollProperty
```
### ShowVerticalScroll

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.RecentProjectsControl.yml" sourcestartlinenumber="1">Gets or sets if or how the vertical scrollbar will be displayed</p>


```csharp
public ScrollBarVisibility ShowVerticalScroll { get; set; }
```
### ShowVerticalScrollProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.RecentProjectsControl.yml" sourcestartlinenumber="1">Gets or sets ShowVerticalScroll</p>


```csharp
public static readonly DependencyProperty ShowVerticalScrollProperty
```
### ViewType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.RecentProjectsControl.yml" sourcestartlinenumber="1">Gets or sets the view type. Default value is ViewType.List.</p>


```csharp
public ViewType ViewType { get; set; }
```
### ViewTypeProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.RecentProjectsControl.yml" sourcestartlinenumber="1">Gets or sets the view type. Default value is ViewType.List.</p>


```csharp
public static readonly DependencyProperty ViewTypeProperty
```


