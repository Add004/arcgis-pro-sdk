# PropertySheet

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.PropertySheet.yml" sourcestartlinenumber="1">A window that allows the user to view and edit the properties of an item.</p>


## Object Signature

```csharp
public static class PropertySheet
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

### Apply()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.PropertySheet.yml" sourcestartlinenumber="1">Commits the changes.</p>


```csharp
public static void Apply()
```
### Cancel()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.PropertySheet.yml" sourcestartlinenumber="1">Closes the property sheet and discards any edits.</p>


```csharp
public static void Cancel()
```
### Close()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.PropertySheet.yml" sourcestartlinenumber="1">Close the property sheet.</p>


```csharp
public static void Close()
```
### IsVisible

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.PropertySheet.yml" sourcestartlinenumber="1">Gets boolean value of true if any property sheet is currently visible.</p>


```csharp
public static bool IsVisible { get; }
```
### OK()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.PropertySheet.yml" sourcestartlinenumber="1">Closes the property sheet and applies all edits.</p>


```csharp
public static void OK()
```
### Page(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.PropertySheet.yml" sourcestartlinenumber="1">Returns the <xref href="ArcGIS.Desktop.Framework.PropertySheet.Page(System.String)" data-throw-if-not-resolved="false"></xref> associated with the specified DAML identifier in the current sheet.</p>


```csharp
public static Page Page(string id)
```
### Show(string, string, params object[])

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.PropertySheet.yml" sourcestartlinenumber="1">Opens the specified property sheet and returns without waiting for the newly opened window to close.</p>


```csharp
public static void Show(string id, string defaultPageID = "", params object[] parameters)
```
### ShowDialog(string, string, Action, string, params object[])

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.PropertySheet.yml" sourcestartlinenumber="1">Show the property sheet with the specified id and title</p>


```csharp
public static bool? ShowDialog(string id, string title, Action applyCallback, string defaultPageID = "", params object[] parameters)
```
### ShowDialog(string, string, params object[])

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.PropertySheet.yml" sourcestartlinenumber="1">Opens the specified property sheet and returns only when the newly opened window is closed.</p>


```csharp
public static bool? ShowDialog(string id, string defaultPageID = "", params object[] parameters)
```
### ShowDialog(string, string, string, params object[])

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.PropertySheet.yml" sourcestartlinenumber="1">Opens the specified property sheet and returns only when the newly opened window is closed.</p>


```csharp
public static bool? ShowDialog(string id, string title, string defaultPageID = "", params object[] parameters)
```
### Title

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.PropertySheet.yml" sourcestartlinenumber="1">Gets or sets the title of the current property sheet.</p>


```csharp
public static string Title { get; set; }
```


