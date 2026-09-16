# BackstageTab

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Contracts.html">Contracts</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.BackstageTab.yml" sourcestartlinenumber="1">Represents a tab in the application backstage. This is an abstract class.</p>


## Object Signature

```csharp
public abstract class BackstageTab : PropertyChangedBase, INotifyPropertyChanged
```

## Remarks

<p>
    The Backstage is a full-screen user interface view that exposes additional functionality for the application and current project. The backstage consists of
    tabs and buttons. Each tab is scoped to a particular task and presents its own user interface. Buttons are simply commands that perform an operation and have
    no additional user interface in the backstage.
    </p>
<p>Backstage tabs are also contextual and will appear disabled if they specify a condition that has not been satisfied.
    </p>
<p>A custom BackstageTab has two components: a component class that derives from BackstageTab and a view class that derives from
    System.Windows.FrameworkElement, typically a System.Windows.Controls.UserControl. Backstage tabs must be defined in DAML.
    </p>
<table>
  <tbody>
    <tr>
      <th>DAML attributes</th>
    </tr>
    <tr>
      <td>id</td>
      <td>Required identifier.</td>
    </tr>
    <tr>
      <td>caption</td>
      <td>The tab label.</td>
    </tr>
    <tr>
      <td>keytip</td>
      <td>The access key for the tab in keytip mode.</td>
    </tr>
    <tr>
      <td>condition</td>
      <td>The DAML condition ID if the tab is contextual.</td>
    </tr>
    <tr>
      <td>separator</td>
      <td>Show a separator before the item.</td>
    </tr>
    <tr>
      <td>className</td>
      <td>Required class identifier. Optionally include namespace if not in default namespace.</td>
    </tr>
    <tr>
      <td>assembly</td>
      <td>Assembly name if not in the default assembly.</td>
    </tr>
    <tr>
      <td>publicKeyToken</td>
      <td>The necessary public key token if the assembly is strongly named.</td>
    </tr>
    <tr>
      <td>version</td>
      <td>The version of the dll if the assembly is strongly named.</td>
    </tr>
  </tbody>
</table>
<p></p>


## Members

### Caption

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.BackstageTab.yml" sourcestartlinenumber="1">Gets the caption (title) of the BackstageTab.</p>


```csharp
public string Caption { get; }
```
### Content

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.BackstageTab.yml" sourcestartlinenumber="1">Gets the content portion of the BackstageTab.</p>


```csharp
public FrameworkElement Content { get; }
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.BackstageTab.yml" sourcestartlinenumber="1">Gets the DAML string identifier for the BackstageTab.</p>


```csharp
public string ID { get; }
```
### InitializeAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.BackstageTab.yml" sourcestartlinenumber="1">Called whenever a BackstageTab is unselected.</p>


```csharp
protected virtual Task InitializeAsync()
```
### OnCreateContent()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.BackstageTab.yml" sourcestartlinenumber="1">Optional override to create the visible content of the control.</p>


```csharp
protected virtual FrameworkElement OnCreateContent()
```
### UninitializeAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.BackstageTab.yml" sourcestartlinenumber="1">Called whenever a BackstageTab is unselected.</p>


```csharp
protected virtual Task UninitializeAsync()
```


