# AttributeTabEmbeddableControl

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.Attributes.html">Attributes</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.AttributeTabEmbeddableControl.yml" sourcestartlinenumber="1">Class for constructing an <xref href="ArcGIS.Desktop.Framework.Controls.EmbeddableControl" data-throw-if-not-resolved="false"></xref> that is to be hosted on a custom tab in the Attributes dockpane.</p>


## Object Signature

```csharp
public abstract class AttributeTabEmbeddableControl : EmbeddableControl
```


## Members

### AttributeTabEmbeddableControl(XElement, bool)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.AttributeTabEmbeddableControl.yml" sourcestartlinenumber="1">Class for constructing an <xref href="ArcGIS.Desktop.Framework.Controls.EmbeddableControl" data-throw-if-not-resolved="false"></xref> that is to be hosted on a custom tab in the Attributes dockpane.</p>


```csharp
protected AttributeTabEmbeddableControl(XElement options, bool canChangeOptions)
```
### Applies(MapMember)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.AttributeTabEmbeddableControl.yml" sourcestartlinenumber="1">Gets if this control (and it's tab) apply to this MapMember.  The default value is false.</p>


```csharp
public virtual bool Applies(MapMember mapMember)
```
### ApplyAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.AttributeTabEmbeddableControl.yml" sourcestartlinenumber="1">Task to apply any edits in the loaded row. The defualt behavior is to call <xref href="ArcGIS.Desktop.Editing.Attributes.Inspector.ApplyAsync" data-throw-if-not-resolved="false"></xref> for any loaded row.
Override this method to provide your specific implementation of applying edits if additional customization is required.</p>


```csharp
public virtual Task ApplyAsync()
```
### CancelAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.AttributeTabEmbeddableControl.yml" sourcestartlinenumber="1">Task to cancel any edits in the loaded row.  The default behavior is to call <xref href="ArcGIS.Desktop.Editing.Attributes.Inspector.CancelAsync" data-throw-if-not-resolved="false"></xref> for any loaded row.
Override this method to provide your implementation of canceling edits if additional customization is required.</p>


```csharp
public virtual Task CancelAsync()
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.AttributeTabEmbeddableControl.yml" sourcestartlinenumber="1">Gets the DAML ID of this <xref href="ArcGIS.Desktop.Editing.Attributes.AttributeTabEmbeddableControl" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public string ID { get; }
```
### Inspector

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.AttributeTabEmbeddableControl.yml" sourcestartlinenumber="1">Gets the inspector containing the row(s) highlighted in the attributes treeview.</p>


```csharp
public Inspector Inspector { get; }
```
### IsDefault

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.AttributeTabEmbeddableControl.yml" sourcestartlinenumber="1">Gets if the tab is the default tab displayed when a row is selected in the Attribute treeview.  Default value is false.</p>


```csharp
public virtual bool IsDefault { get; }
```
### IsDirty

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.AttributeTabEmbeddableControl.yml" sourcestartlinenumber="1">Gets if this control is dirty.  Defaults to the IsDirty of the <xref href="ArcGIS.Desktop.Editing.Attributes.AttributeTabEmbeddableControl.Inspector" data-throw-if-not-resolved="false"></xref> otherwise false.</p>


```csharp
public virtual bool IsDirty { get; }
```
### IsMapMemberHighlighted

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.AttributeTabEmbeddableControl.yml" sourcestartlinenumber="1">Gets if the mapMember is highlighted in the attributes treeview.</p>


```csharp
public bool IsMapMemberHighlighted { get; }
```
### IsValid

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.AttributeTabEmbeddableControl.yml" sourcestartlinenumber="1">Gets if this control is valid?  Defaults to the HasValidEdits of the <xref href="ArcGIS.Desktop.Editing.Attributes.AttributeTabEmbeddableControl.Inspector" data-throw-if-not-resolved="false"></xref> otherwise false.</p>


```csharp
public virtual bool IsValid { get; }
```
### LoadFromFeaturesAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.AttributeTabEmbeddableControl.yml" sourcestartlinenumber="1">Called when attributes from one or more rows have been loaded into the Inspector.</p>


```csharp
public abstract Task LoadFromFeaturesAsync()
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.AttributeTabEmbeddableControl.yml" sourcestartlinenumber="1">Gets the DAML name content property of this <xref href="ArcGIS.Desktop.Editing.Attributes.AttributeTabEmbeddableControl" data-throw-if-not-resolved="false"></xref>.
This is displayed as the tab Title.</p>


```csharp
public string Name { get; }
```
### ShowAutoApplyControls

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.AttributeTabEmbeddableControl.yml" sourcestartlinenumber="1">Gets if the &quot;auto apply edit&quot; controls are displayed at the bottom of the tab.  Default value is true.</p>


```csharp
public virtual bool ShowAutoApplyControls { get; }
```
### SupportsMultiples

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.AttributeTabEmbeddableControl.yml" sourcestartlinenumber="1">Gets if this control (and it's tab) support selection of multiple rows in the Attribute treeview.  Default value is false.</p>


```csharp
public virtual bool SupportsMultiples { get; }
```


