# InspectorProvider

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.InspectorProvider.yml" sourcestartlinenumber="1">Provides a mechanism to customize attribute behavior within an inspector.</p>


## Object Signature

```csharp
public abstract class InspectorProvider
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Editing.InspectorProvider.yml" sourcestartlinenumber="1">Typically this would be used in conjunction with the <xref href="ArcGIS.Desktop.Editing.Attributes.Inspector.CreateEmbeddableControl" data-throw-if-not-resolved="false"></xref> method.
Override the provided methods to hide attributes, highlight attributes, make attributes non-editable, show custom aliases and provide custom validators
within the context of the attribute inspector grid.</p>


## Members

### InspectorProvider()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.InspectorProvider.yml" sourcestartlinenumber="1">Provides a mechanism to customize attribute behavior within an inspector.</p>


```csharp
protected InspectorProvider()
```
### AttributesOrder(IEnumerable&lt;Attribute&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.InspectorProvider.yml" sourcestartlinenumber="1">Gets the set of ordered attributes.  Override this to display attributes in a custom order.</p>


```csharp
public virtual IEnumerable<Attribute> AttributesOrder(IEnumerable<Attribute> attrs)
```
### BeginLoad(IEnumerable&lt;Attribute&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.InspectorProvider.yml" sourcestartlinenumber="1">Callback that occurs at the begining of the provider processing, prior to looping through the attribute set.
Overide this to perform work at the beginning of the process if there is some common work that can be performed once rather
than repeatedly for each attribute in the loop.</p>


```csharp
public virtual void BeginLoad(IEnumerable<Attribute> attrs)
```
### Create()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.InspectorProvider.yml" sourcestartlinenumber="1">Creates an inspector that uses this provider to override default behavior.  Multiple inspectors can be created using the same provider.</p>


```csharp
public Inspector Create()
```
### CustomName(Attribute)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.InspectorProvider.yml" sourcestartlinenumber="1">Gets a custom alias to be displayed for the attribute.  Override this to supply a custom alias.</p>


```csharp
public virtual string CustomName(Attribute attr)
```
### EndLoad()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.InspectorProvider.yml" sourcestartlinenumber="1">Callback that occurs at the end of the provider processing.   Overrides this to perform any cleanup required.</p>


```csharp
public virtual void EndLoad()
```
### IgnoreValidation(MapMember)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.InspectorProvider.yml" sourcestartlinenumber="1">Gets if validation is ignored on the Inspector attributes.  Default value is false.</p>


```csharp
public virtual bool IgnoreValidation(MapMember mapMember)
```
### IsDirty(Attribute)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.InspectorProvider.yml" sourcestartlinenumber="1">Gets if the attribute is dirty. Override this to provide custom Dirty behavior.</p>


```csharp
public virtual bool? IsDirty(Attribute attr)
```
### IsEditable(Attribute)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.InspectorProvider.yml" sourcestartlinenumber="1">Gets if the attribute is editable.  Override this to make attributes non-editable.</p>


```csharp
public virtual bool? IsEditable(Attribute attr)
```
### IsHighlighted(Attribute)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.InspectorProvider.yml" sourcestartlinenumber="1">Gets if the attribute is highlighted.  Override this to higlight an attribute.</p>


```csharp
public virtual bool? IsHighlighted(Attribute attr)
```
### IsVisible(Attribute)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.InspectorProvider.yml" sourcestartlinenumber="1">Gets if the attribute is visible.  Override this to hide attributes.</p>


```csharp
public virtual bool? IsVisible(Attribute attr)
```
### Recalculate()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.InspectorProvider.yml" sourcestartlinenumber="1">Force the inspector to request information from the inspector provider to recalculate and refresh.</p>


```csharp
protected void Recalculate()
```
### SharedFieldColumnSizeID()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.InspectorProvider.yml" sourcestartlinenumber="1">Gets a unique GUID for any inspector created from this provider. Use this to control the width of the first column (field name or alias) across multiple
inspector grids.  If multiple inspectors use the same GUID, then the inspector grids for each will appear with shared column widths.</p>


```csharp
public virtual Guid SharedFieldColumnSizeID()
```
### Validate(Attribute)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.InspectorProvider.yml" sourcestartlinenumber="1">Provides custom validation for an attribute. Return informationa, warning or error messages depending upon attribute values.</p>


```csharp
public virtual IEnumerable<Attribute.ValidationError> Validate(Attribute attr)
```


