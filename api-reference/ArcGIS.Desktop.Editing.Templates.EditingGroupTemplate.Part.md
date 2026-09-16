# EditingGroupTemplate.Part

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.Templates.html">Templates</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingGroupTemplate.Part.yml" sourcestartlinenumber="1">Contains information about each <xref href="ArcGIS.Desktop.Editing.Templates.EditingRowTemplate" data-throw-if-not-resolved="false"></xref> within an <xref href="ArcGIS.Desktop.Editing.Templates.EditingGroupTemplate" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class EditingGroupTemplate.Part : PropertyChangedBase
```


## Members

### Builder

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingGroupTemplate.Part.yml" sourcestartlinenumber="1">Gets this Part's BuilderMethod that is associated with the <xref href="ArcGIS.Desktop.Editing.Templates.EditingGroupTemplate.Part.Template" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public BuilderMethod Builder { get; }
```
### BuilderIcon

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingGroupTemplate.Part.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Desktop.Editing.Templates.EditingGroupTemplate.Part.Builder?text=Builder" data-throw-if-not-resolved="false"></xref>'s <xref href="ArcGIS.Desktop.Editing.Templates.BuilderMethod.Image?text=icon" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public ImageSource BuilderIcon { get; }
```
### Inspector

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingGroupTemplate.Part.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Desktop.Editing.Templates.EditingGroupTemplate.Part.Template?text=Template" data-throw-if-not-resolved="false"></xref>'s <xref href="ArcGIS.Desktop.Editing.Templates.EditingTemplate.Inspector?text=Inspector" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public Inspector Inspector { get; }
```
### IsBase

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingGroupTemplate.Part.yml" sourcestartlinenumber="1">Gets whether this Part contains the <xref href="ArcGIS.Desktop.Editing.Templates.EditingGroupTemplate.BaseTemplate?text=BaseTemplate" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public bool IsBase { get; }
```
### Parent

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingGroupTemplate.Part.yml" sourcestartlinenumber="1">Gets the containing EditingGroupTemplate.</p>


```csharp
public EditingGroupTemplate Parent { get; }
```
### Template

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingGroupTemplate.Part.yml" sourcestartlinenumber="1">Gets this Part's EditingRowTemplate.</p>


```csharp
public EditingRowTemplate Template { get; }
```
### ToString()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingGroupTemplate.Part.yml" sourcestartlinenumber="1">Gets text that describes the <xref href="ArcGIS.Desktop.Editing.Templates.EditingGroupTemplate.Part.Template" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Desktop.Editing.Templates.EditingGroupTemplate.Part.Builder" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public override string ToString()
```
### ToolTipIcon

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingGroupTemplate.Part.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Desktop.Editing.Templates.EditingGroupTemplate.Part.Template?text=Template" data-throw-if-not-resolved="false"></xref>'s icon for use as a tooltip.</p>


```csharp
public ImageSource ToolTipIcon { get; }
```
### ToolTipText

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingGroupTemplate.Part.yml" sourcestartlinenumber="1">Gets text from <xref href="ArcGIS.Desktop.Editing.Templates.EditingGroupTemplate.Part.ToString" data-throw-if-not-resolved="false"></xref> and adjusts it for use as a tooltip.</p>


```csharp
public string ToolTipText { get; }
```
### Values

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingGroupTemplate.Part.yml" sourcestartlinenumber="1">Gets the parameter values that are to be used in conjunction with the <xref href="ArcGIS.Desktop.Editing.Templates.EditingGroupTemplate.Part.Builder" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public Dictionary<string, object> Values { get; }
```


