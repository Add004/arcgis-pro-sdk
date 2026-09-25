# EmbeddableControl

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Controls.html">Controls</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.EmbeddableControl.yml" sourcestartlinenumber="1">Represents a control that can be hosted in multiple locations.</p>


## Object Signature

```csharp
public class EmbeddableControl : ViewModelBase, INotifyPropertyChanged, IDisposable
```


## Members

### EmbeddableControl(XElement, bool)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.EmbeddableControl.yml" sourcestartlinenumber="1">Creates a new instance of the EmbeddableControl</p>


```csharp
protected EmbeddableControl(XElement options, bool canChangeOptions)
```
### CanChangeOptions

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.EmbeddableControl.yml" sourcestartlinenumber="1">Gets and sets whether or not the EmbeddedControl can change its options.</p>


```csharp
public virtual bool CanChangeOptions { get; set; }
```
### CanCommit

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.EmbeddableControl.yml" sourcestartlinenumber="1">Gets if the control can perform a <xref href="ArcGIS.Desktop.Framework.Controls.EmbeddableControl.CommitAsync" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public virtual bool CanCommit { get; }
```
### CloseAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.EmbeddableControl.yml" sourcestartlinenumber="1">Occurs when the controls is closed.</p>


```csharp
public virtual Task CloseAsync()
```
### CommitAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.EmbeddableControl.yml" sourcestartlinenumber="1">Occurs when control is executed or has changes to its options to be commited.</p>


```csharp
public virtual Task CommitAsync()
```
### Create(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.EmbeddableControl.yml" sourcestartlinenumber="1">Creates an instance of an EmbeddableControl and its View in a ViewModel-View fashion.</p>


```csharp
public static Tuple<EmbeddableControl, UserControl> Create(string damlID)
```
### Create(string, string, XElement, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.EmbeddableControl.yml" sourcestartlinenumber="1">Creates an instance of an EmbeddableControl and its View in a ViewModel-View fashion.</p>


```csharp
public static Tuple<EmbeddableControl, UserControl> Create(string damlID, string category, XElement options, bool canChangeOptions = false)
```
### OnOptionsChanged()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.EmbeddableControl.yml" sourcestartlinenumber="1">Occurs when the options are updated.</p>


```csharp
protected virtual void OnOptionsChanged()
```
### OpenAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.EmbeddableControl.yml" sourcestartlinenumber="1">Occurs when the control is hosted.</p>


```csharp
public virtual Task OpenAsync()
```
### Options

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Controls.EmbeddableControl.yml" sourcestartlinenumber="1">Gets or sets the configuration options.</p>


```csharp
public XElement Options { get; set; }
```


