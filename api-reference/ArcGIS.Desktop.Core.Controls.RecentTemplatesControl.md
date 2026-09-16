# RecentTemplatesControl

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.Controls.html">Controls</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.RecentTemplatesControl.yml" sourcestartlinenumber="1">The RecentTemplatesControl provides a UI for displaying the pinned and recently opened ArcGIS Pro projects.</p>


## Object Signature

```csharp
public class RecentTemplatesControl : UserControl, IAnimatable, IFrameworkInputElement, IInputElement, ISupportInitialize, IQueryAmbient, IAddChild, IComponentConnector
```


## Members

### RecentTemplatesControl()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.RecentTemplatesControl.yml" sourcestartlinenumber="1">Default constructor</p>


```csharp
public RecentTemplatesControl()
```
### InitializeComponent()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.RecentTemplatesControl.yml" sourcestartlinenumber="1">InitializeComponent</p>


```csharp
public void InitializeComponent()
```
### IsBrowseTemplatesVisible

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.RecentTemplatesControl.yml" sourcestartlinenumber="1">Gets or sets if the browse templates button is visible.</p>


```csharp
public bool IsBrowseTemplatesVisible { get; set; }
```
### IsBrowseTemplatesVisibleProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.RecentTemplatesControl.yml" sourcestartlinenumber="1">Gets or sets if the browse templates button is visible.</p>


```csharp
public static readonly DependencyProperty IsBrowseTemplatesVisibleProperty
```
### IsTitleVisible

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.RecentTemplatesControl.yml" sourcestartlinenumber="1">Gets or sets if the title is visible.</p>


```csharp
public bool IsTitleVisible { get; set; }
```
### IsTitleVisibleProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.RecentTemplatesControl.yml" sourcestartlinenumber="1">Gets or sets if the title is visible.</p>


```csharp
public static readonly DependencyProperty IsTitleVisibleProperty
```
### PinnedTemplates

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.RecentTemplatesControl.yml" sourcestartlinenumber="1">Gets the list of pinned templates.</p>


```csharp
public IReadOnlyList<string> PinnedTemplates { get; }
```
### PinnedTemplatesProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.RecentTemplatesControl.yml" sourcestartlinenumber="1">Gets the list of pinned templates.</p>


```csharp
public static readonly DependencyProperty PinnedTemplatesProperty
```
### RecentTemplates

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.RecentTemplatesControl.yml" sourcestartlinenumber="1">Gets the list of recent templates.</p>


```csharp
public IReadOnlyList<string> RecentTemplates { get; }
```
### RecentTemplatesProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.RecentTemplatesControl.yml" sourcestartlinenumber="1">Gets the list of recent templates.</p>


```csharp
public static readonly DependencyProperty RecentTemplatesProperty
```
### SelectedTemplate

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.RecentTemplatesControl.yml" sourcestartlinenumber="1">Gets the selected template.</p>


```csharp
public string SelectedTemplate { get; }
```
### SelectedTemplateChanged

- Kind: event

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.RecentTemplatesControl.yml" sourcestartlinenumber="1">The SelectedTemplateChanged event is raised when a template in the RecentTemplatesControl is chosen.</p>


```csharp
public event RecentTemplatesControl.SelectedTemplateChangedEventHandler SelectedTemplateChanged
```
### SelectedTemplateProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.RecentTemplatesControl.yml" sourcestartlinenumber="1">Gets the selected template.</p>


```csharp
public static readonly DependencyProperty SelectedTemplateProperty
```
### ShowHorizontalScroll

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.RecentTemplatesControl.yml" sourcestartlinenumber="1">Gets or sets if or how the horizontal scrollbar will be displayed</p>


```csharp
public ScrollBarVisibility ShowHorizontalScroll { get; set; }
```
### ShowHorizontalScrollProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.RecentTemplatesControl.yml" sourcestartlinenumber="1">Gets or sets ShowHorizontalScroll</p>


```csharp
public static readonly DependencyProperty ShowHorizontalScrollProperty
```
### ShowVerticalScroll

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.RecentTemplatesControl.yml" sourcestartlinenumber="1">Gets or sets if or how the vertical scrollbar will be displayed</p>


```csharp
public ScrollBarVisibility ShowVerticalScroll { get; set; }
```
### ShowVerticalScrollProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.RecentTemplatesControl.yml" sourcestartlinenumber="1">Gets or sets ShowVerticalScroll</p>


```csharp
public static readonly DependencyProperty ShowVerticalScrollProperty
```


