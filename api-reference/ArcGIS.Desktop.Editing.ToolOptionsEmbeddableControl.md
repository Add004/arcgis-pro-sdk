# ToolOptionsEmbeddableControl

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.ToolOptionsEmbeddableControl.yml" sourcestartlinenumber="1">helper class for constructing an <xref href="ArcGIS.Desktop.Framework.Controls.EmbeddableControl" data-throw-if-not-resolved="false"></xref> to be used with <xref href="ArcGIS.Desktop.Editing.ToolOptionsEmbeddableControl.ToolOptions" data-throw-if-not-resolved="false"></xref></p>


## Object Signature

```csharp
public abstract class ToolOptionsEmbeddableControl : EmbeddableControl
```


## Members

### ToolOptionsEmbeddableControl(XElement, bool)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.ToolOptionsEmbeddableControl.yml" sourcestartlinenumber="1">helper class for constructing an <xref href="ArcGIS.Desktop.Framework.Controls.EmbeddableControl" data-throw-if-not-resolved="false"></xref> to be used with <xref href="ArcGIS.Desktop.Editing.ToolOptionsEmbeddableControl.ToolOptions" data-throw-if-not-resolved="false"></xref></p>


```csharp
protected ToolOptionsEmbeddableControl(XElement options, bool canChangeOptions)
```
### CloseAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.ToolOptionsEmbeddableControl.yml" sourcestartlinenumber="1">Resets various properties as part of closing the embeddable control.</p>


```csharp
public override Task CloseAsync()
```
### GetToolOption&lt;T&gt;(string, T, T)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.ToolOptionsEmbeddableControl.yml" sourcestartlinenumber="1">Gets a tool option from the current ToolOptions</p>


```csharp
protected T GetToolOption<T>(string key, T defaultValue, T differentValue = default)
```
### HasMultipleTemplatesSelected

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ToolOptionsEmbeddableControl.yml" sourcestartlinenumber="1">Gets whether multiple templates are being edited.</p>


```csharp
protected bool HasMultipleTemplatesSelected { get; }
```
### HostIsActiveTemplatePane

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ToolOptionsEmbeddableControl.yml" sourcestartlinenumber="1">Gets if this tool options control is hosted within the active template pane (true) or the template properties (false).</p>


```csharp
protected bool HostIsActiveTemplatePane { get; }
```
### IsAutoOpen(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.ToolOptionsEmbeddableControl.yml" sourcestartlinenumber="1">Gets whether the tool options should auto open in the Active Template pane when the associated tool is activated.</p>


```csharp
public virtual bool IsAutoOpen(string toolID)
```
### IsDirty

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ToolOptionsEmbeddableControl.yml" sourcestartlinenumber="1">Gets and sets the dirty state of the tool options.</p>


```csharp
public virtual bool IsDirty { get; set; }
```
### IsValid

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ToolOptionsEmbeddableControl.yml" sourcestartlinenumber="1">Gets and sets the valid state of the tool options.</p>


```csharp
public virtual bool IsValid { get; set; }
```
### LoadFromToolOptions()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.ToolOptionsEmbeddableControl.yml" sourcestartlinenumber="1">Called at the end of <xref href="ArcGIS.Desktop.Editing.ToolOptionsEmbeddableControl.OpenAsync" data-throw-if-not-resolved="false"></xref>, implementations should obtain and interpret the options stored in the current <xref href="ArcGIS.Desktop.Editing.ToolOptionsEmbeddableControl.ToolOptions" data-throw-if-not-resolved="false"></xref>
using <xref href="ArcGIS.Desktop.Editing.ToolOptionsEmbeddableControl.GetToolOption%60%601(System.String%2c%60%600%2c%60%600)" data-throw-if-not-resolved="false"></xref></p>


```csharp
protected abstract Task LoadFromToolOptions()
```
### OnInitialize(IEnumerable&lt;ToolOptions&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.ToolOptionsEmbeddableControl.yml" sourcestartlinenumber="1">Occurs when a tool options control is initialized</p>


```csharp
public virtual void OnInitialize(IEnumerable<ToolOptions> optionsCollection, bool hostIsActiveTemplatePane)
```
### OpenAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.ToolOptionsEmbeddableControl.yml" sourcestartlinenumber="1">Calls <xref href="ArcGIS.Desktop.Editing.ToolOptionsEmbeddableControl.LoadFromToolOptions" data-throw-if-not-resolved="false"></xref> as part of final initialization as the embeddable control is opened.</p>


```csharp
public override Task OpenAsync()
```
### SelectorIcon

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ToolOptionsEmbeddableControl.yml" sourcestartlinenumber="1">Gets the icon to display when the tool options are displayed in the Active Template pane.</p>


```csharp
public virtual ImageSource SelectorIcon { get; }
```
### SetToolOption&lt;T&gt;(string, T)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.ToolOptionsEmbeddableControl.yml" sourcestartlinenumber="1">Sets a tool option within the current ToolOptions</p>


```csharp
protected void SetToolOption<T>(string key, T value)
```
### ToolOptions

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ToolOptionsEmbeddableControl.yml" sourcestartlinenumber="1">Gets a working copy of ToolOptions <xref href="ArcGIS.Desktop.Editing.ToolOptionsEmbeddableControl.ToolOptions" data-throw-if-not-resolved="false"></xref></p>


```csharp
protected ToolOptions ToolOptions { get; }
```


