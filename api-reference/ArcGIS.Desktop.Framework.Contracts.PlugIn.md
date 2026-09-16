# PlugIn

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Contracts.html">Contracts</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.PlugIn.yml" sourcestartlinenumber="1">Represents the base class for most framework commands including <code>Button</code> and <code>Tool</code>. This is an abstract class.</p>


## Object Signature

```csharp
public abstract class PlugIn : PropertyChangedBase, INotifyPropertyChanged
```


## Members

### Caption

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.PlugIn.yml" sourcestartlinenumber="1">Gets or sets the command label as it appears in the ribbon and customize dialog.</p>


```csharp
public string Caption { get; set; }
```
### DisabledTooltip

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.PlugIn.yml" sourcestartlinenumber="1">Gets or sets the supplementary text that appears with the <code>Tooltip</code> only when the command is disabled.</p>


```csharp
public string DisabledTooltip { get; set; }
```
### Enabled

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.PlugIn.yml" sourcestartlinenumber="1">Gets or sets a boolean to specify whether the control is enabled.</p>


```csharp
public bool Enabled { get; set; }
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.PlugIn.yml" sourcestartlinenumber="1">Gets the DAML identifier.</p>


```csharp
public string ID { get; }
```
### LargeImage

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.PlugIn.yml" sourcestartlinenumber="1">Gets or sets the large representation of the command, this may be an image or a xaml element.</p>


```csharp
public object LargeImage { get; set; }
```
### OnUpdate()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.PlugIn.yml" sourcestartlinenumber="1">Called periodically by the framework once the tool has been created.</p>


```csharp
protected virtual void OnUpdate()
```
### SmallImage

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.PlugIn.yml" sourcestartlinenumber="1">Gets or sets the small representation of the command, this may be an image or a xaml element.</p>


```csharp
public object SmallImage { get; set; }
```
### Tooltip

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.PlugIn.yml" sourcestartlinenumber="1">Gets or sets a brief description of the command that appears in a small pop-up window when a user pauses the
mouse pointer over an element, such as over a Button.</p>


```csharp
public string Tooltip { get; set; }
```
### TooltipHeading

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.PlugIn.yml" sourcestartlinenumber="1">Gets or sets a one or two word label that appears above the tooltip.</p>


```csharp
public string TooltipHeading { get; set; }
```


