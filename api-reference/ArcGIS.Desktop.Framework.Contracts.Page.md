# Page

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Contracts.html">Contracts</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Page.yml" sourcestartlinenumber="1">Represents a page inside a property sheet. This is an abstract class.</p>


## Object Signature

```csharp
public abstract class Page : ViewModelBase, INotifyPropertyChanged
```

## Remarks

<p>
          Property sheets hold a collection of individual unrelated property pages. Each
          page contains controls for setting a group of related properties. A property sheet can be shown modal or modeless.
        </p>
        <p>
          Property sheets are purely declarative, they are defined only in DAML and have no corresponding managed class. Property
          pages, like <xref href="ArcGIS.Desktop.Framework.Contracts.Pane" data-throw-if-not-resolved="false"></xref>s and <xref href="ArcGIS.Desktop.Framework.Contracts.DockPane" data-throw-if-not-resolved="false"></xref>s, have both declarative and active
          components. The active portion of all property pages must derive from this class.
        </p>
        <p>
          Property pages only load when they become visible. They are not loaded when the sheet loads - the
          page has to be visited.
          When a page does load, its <xref href="ArcGIS.Desktop.Framework.Contracts.Page.IsLoading" data-throw-if-not-resolved="false"></xref> property is first set to true. Next, its
          <xref href="ArcGIS.Desktop.Framework.Contracts.Page.InitializeAsync" data-throw-if-not-resolved="false"></xref> function is executed. When the returned task completes, its
          IsLoading is reset to false.
        </p>
        <p>
          Property pages have the option of being conditional. If a condition has been specified for the page in DAML, the
          page will not appear with the sheet unless its condition is currently satisfied.
        </p>
        <p>
          Pages can also be grouped within a sheet by setting the sheet's 
<pre><code class="lang-csharp">hasGroups</code></pre>
 attribute to true
          and specifying a group heading by setting the page's 
<pre><code class="lang-csharp">group</code></pre>
 attribute.
        
        <p>
          When a property sheet is displayed with either <xref href="ArcGIS.Desktop.Framework.PropertySheet.Show(System.String%2cSystem.String%2cSystem.Object%5b%5d)" data-throw-if-not-resolved="false"></xref>
          or <xref href="ArcGIS.Desktop.Framework.PropertySheet.ShowDialog(System.String%2cSystem.String%2cSystem.Object%5b%5d)" data-throw-if-not-resolved="false"></xref>, data can be passed in as one of the arguments and
          this data can be accessed by all of its pages using the <xref href="ArcGIS.Desktop.Framework.Contracts.Page.Data" data-throw-if-not-resolved="false"></xref> property.
        </p>
        <p>
          The property sheet dialog includes a title bar and several buttons: OK, Cancel, and Apply. The
          Apply button is only presented when the sheet is modeless. The OK button remains enabled as long as all
          pages report that they are valid, see <xref href="ArcGIS.Desktop.Framework.Contracts.Page.IsValid" data-throw-if-not-resolved="false"></xref>.
          The Apply button enables once any page in the sheet sets its <xref href="ArcGIS.Desktop.Framework.Contracts.Page.IsModified" data-throw-if-not-resolved="false"></xref> property to true and all 
          page are valid. Once Apply or OK are clicked, each page that has set its IsModified flag to true will have its 
          <xref href="ArcGIS.Desktop.Framework.Contracts.Page.CommitAsync" data-throw-if-not-resolved="false"></xref> invoked. Similarly, if the Cancel button is clicked, their <xref href="ArcGIS.Desktop.Framework.Contracts.Page.CancelAsync" data-throw-if-not-resolved="false"></xref> is invoked.
        </p>
        <p>
          When a property sheet closes, each loaded page will have its <xref href="ArcGIS.Desktop.Framework.Contracts.Page.Uninitialize" data-throw-if-not-resolved="false"></xref> invoked.
        </p>


## Members

### Page()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Page.yml" sourcestartlinenumber="1">Represents a page inside a property sheet. This is an abstract class.</p>


```csharp
protected Page()
```
### CanReset

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Page.yml" sourcestartlinenumber="1">Gets a flag to notify the system that the page can be reset.</p>


```csharp
protected virtual bool CanReset { get; }
```
### CancelAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Page.yml" sourcestartlinenumber="1">Invoked when the cancel button on the property sheet has been clicked.</p>


```csharp
protected virtual Task CancelAsync()
```
### Caption

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Page.yml" sourcestartlinenumber="1">Gets or sets the page's label as presented in the property sheet.</p>


```csharp
public string Caption { get; set; }
```
### CommitAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Page.yml" sourcestartlinenumber="1">Invoked when the ok or apply button on the property sheet has been clicked.</p>


```csharp
protected virtual Task CommitAsync()
```
### Data

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Page.yml" sourcestartlinenumber="1">Gets or sets the data passed to the property sheet.</p>


```csharp
protected object[] Data { get; set; }
```
### HasError

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Page.yml" sourcestartlinenumber="1">Gets or sets a boolean notifying the application whether the page produced an error during commit. If any page errors, the property sheet will not close during commit.</p>


```csharp
protected bool HasError { get; set; }
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Page.yml" sourcestartlinenumber="1">Gets the page's DAML identifier.</p>


```csharp
public string ID { get; }
```
### InitializeAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Page.yml" sourcestartlinenumber="1">Invoked when a page loads because it has become visible inside the sheet.</p>


```csharp
protected virtual Task InitializeAsync()
```
### IsDefault

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Page.yml" sourcestartlinenumber="1">Gets or sets a boolean to notify the system that the page is in its default state.</p>


```csharp
protected bool? IsDefault { get; set; }
```
### IsEnabled

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Page.yml" sourcestartlinenumber="1">Gets or sets a boolean indicating if the page is currently enabled.</p>


```csharp
public bool IsEnabled { get; set; }
```
### IsLoading

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Page.yml" sourcestartlinenumber="1">Gets a boolean indicating if the page is currently loading.</p>


```csharp
public bool IsLoading { get; }
```
### IsModified

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Page.yml" sourcestartlinenumber="1">Gets or sets a boolean to notify the system that the page has been modified.</p>


```csharp
protected bool IsModified { get; set; }
```
### IsSelected

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Page.yml" sourcestartlinenumber="1">Gets or sets a boolean indicating if the page is currently selected.</p>


```csharp
public bool IsSelected { get; set; }
```
### IsValid

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Page.yml" sourcestartlinenumber="1">Gets or sets a boolean notifying the application whether the page is valid or not.</p>


```csharp
public bool IsValid { get; set; }
```
### Parent

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Page.yml" sourcestartlinenumber="1">Gets or sets parent page of the page, if the property sheet is using a tree representation.</p>


```csharp
protected Page Parent { get; }
```
### ReinitializeAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Page.yml" sourcestartlinenumber="1">Invoked when any Page in the sheet calls ReloadAsync.</p>


```csharp
protected virtual Task ReinitializeAsync()
```
### ReloadSheetAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Page.yml" sourcestartlinenumber="1">Triggers a ReinitializeAsync call in each loaded Page in the sheet.</p>


```csharp
public Task ReloadSheetAsync()
```
### ResetAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Page.yml" sourcestartlinenumber="1">Invoked when the reset button on the property sheet has been clicked.</p>


```csharp
protected virtual Task ResetAsync()
```
### Uninitialize()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Page.yml" sourcestartlinenumber="1">Invoked before a page is destroyed.</p>


```csharp
protected virtual void Uninitialize()
```
### ValidationMessage

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Page.yml" sourcestartlinenumber="1">Gets or sets a message about why the Page is invalid.</p>


```csharp
public string ValidationMessage { get; protected set; }
```


