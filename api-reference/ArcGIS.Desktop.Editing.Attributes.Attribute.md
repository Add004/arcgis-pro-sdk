# Attribute

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.Attributes.html">Attributes</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Attribute.yml" sourcestartlinenumber="1">Defines a single field and value (or composite of values) for the selected features.</p>


## Object Signature

```csharp
public sealed class Attribute : PropertyChangedBase
```

## Remarks

<p></p>


## Members

### AddValidate(Func&lt;IEnumerable&lt;ValidationError&gt;&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Attribute.yml" sourcestartlinenumber="1">Add custom validation functions for this attribute. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void AddValidate(Func<IEnumerable<Attribute.ValidationError>> f)
```
### AddValidateAsync(Func&lt;Task&lt;IEnumerable&lt;ValidationError&gt;&gt;&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Attribute.yml" sourcestartlinenumber="1">Add custom validation functions for this attribute.</p>


```csharp
public Task<bool> AddValidateAsync(Func<Task<IEnumerable<Attribute.ValidationError>>> f)
```
### CurrentDomain

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Attribute.yml" sourcestartlinenumber="1">Gets the current <xref href="ArcGIS.Desktop.Editing.Attributes.Domain?text=domain" data-throw-if-not-resolved="false"></xref> of this attribute.</p>


```csharp
public Domain CurrentDomain { get; }
```
### CurrentSubtype

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Attribute.yml" sourcestartlinenumber="1">Gets the current <xref href="ArcGIS.Desktop.Editing.Attributes.Subtype?text=subtype" data-throw-if-not-resolved="false"></xref> of this attribute.</p>


```csharp
public Subtype CurrentSubtype { get; }
```
### CurrentValue

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Attribute.yml" sourcestartlinenumber="1">Gets or sets the current value of this attribute.</p>


```csharp
public object CurrentValue { get; set; }
```
### DefaultValue

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Attribute.yml" sourcestartlinenumber="1">Gets the current default value of this attribute. If there is a current <xref href="ArcGIS.Desktop.Editing.Attributes.Subtype?text=subtype" data-throw-if-not-resolved="false"></xref>, it
returns the default <xref href="ArcGIS.Desktop.Editing.Attributes.Subtype?text=subtype" data-throw-if-not-resolved="false"></xref> value.</p>


```csharp
public object DefaultValue { get; }
```
### FieldAlias

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Attribute.yml" sourcestartlinenumber="1">Gets the field alias of this attribute.</p>


```csharp
public string FieldAlias { get; }
```
### FieldIndex

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Attribute.yml" sourcestartlinenumber="1">Gets the field index of this attribute.</p>


```csharp
public int FieldIndex { get; }
```
### FieldName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Attribute.yml" sourcestartlinenumber="1">Gets the field name of this attribute.</p>


```csharp
public string FieldName { get; }
```
### FieldType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Attribute.yml" sourcestartlinenumber="1">Gets the field type of this attribute.</p>


```csharp
public FieldType FieldType { get; }
```
### GetField()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Attribute.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Field?text=field" data-throw-if-not-resolved="false"></xref> of this attribute. Returns a field only if the data source is an Enterprise Geodatabase or File Geodatabase.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Field GetField()
```
### GetFormattedValue()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Attribute.yml" sourcestartlinenumber="1">Get the formatted value of this attribute. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetFormattedValue()
```
### GetFormattedValueAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Attribute.yml" sourcestartlinenumber="1">Get the formatted value of this attribute.</p>


```csharp
public Task<string> GetFormattedValueAsync()
```
### HasDomain

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Attribute.yml" sourcestartlinenumber="1">Gets whether this attribute has a current <xref href="ArcGIS.Desktop.Editing.Attributes.Domain?text=domain" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public bool HasDomain { get; }
```
### HasMultipleValues

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Attribute.yml" sourcestartlinenumber="1">Gets whether this attribute has multiple values.</p>


```csharp
public bool HasMultipleValues { get; }
```
### Index

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Attribute.yml" sourcestartlinenumber="1">Gets the layer index of this attribute.</p>


```csharp
public int Index { get; }
```
### IsDirty

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Attribute.yml" sourcestartlinenumber="1">Gets whether the attribute was modified.</p>


```csharp
public bool IsDirty { get; }
```
### IsEditable

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Attribute.yml" sourcestartlinenumber="1">Gets whether this attribute is marked editable.</p>


```csharp
public bool IsEditable { get; }
```
### IsGeometryField

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Attribute.yml" sourcestartlinenumber="1">Gets whether this attribute is a geometry field.</p>


```csharp
public bool IsGeometryField { get; }
```
### IsHighlighted

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Attribute.yml" sourcestartlinenumber="1">Gets whether this attribute is highlighted.</p>


```csharp
public bool IsHighlighted { get; }
```
### IsNullable

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Attribute.yml" sourcestartlinenumber="1">Gets whether this attribute value can be null.</p>


```csharp
public bool IsNullable { get; }
```
### IsRendererField

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Attribute.yml" sourcestartlinenumber="1">Gets whether this attribute is a renderer field.</p>


```csharp
public bool IsRendererField { get; }
```
### IsSubtype

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Attribute.yml" sourcestartlinenumber="1">Gets whether this attribute is a <xref href="ArcGIS.Desktop.Editing.Attributes.Subtype?text=subtype" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public bool IsSubtype { get; }
```
### IsSystemField

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Attribute.yml" sourcestartlinenumber="1">Gets whether this attribute is a system field.</p>


```csharp
public bool IsSystemField { get; }
```
### IsValid

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Attribute.yml" sourcestartlinenumber="1">Gets whether the attribute value is valid.</p>


```csharp
public bool IsValid { get; }
```
### IsVisible

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Attribute.yml" sourcestartlinenumber="1">Gets whether this attribute is visible.</p>


```csharp
public bool IsVisible { get; }
```
### Length

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Attribute.yml" sourcestartlinenumber="1">Gets the maximum length of this attribute.</p>


```csharp
public int Length { get; }
```
### MapMember

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Attribute.yml" sourcestartlinenumber="1">Gets the layer or Standalone table this attribute belongs to.</p>


```csharp
public MapMember MapMember { get; }
```
### OriginalValue

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Attribute.yml" sourcestartlinenumber="1">Gets the original value of this attribute.</p>


```csharp
public object OriginalValue { get; }
```
### Precision

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Attribute.yml" sourcestartlinenumber="1">Gets the precision of this attribute.</p>


```csharp
public int Precision { get; }
```
### Revert()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Attribute.yml" sourcestartlinenumber="1">Returns attribute back to it's original value. Clears <xref href="ArcGIS.Desktop.Editing.Attributes.Attribute.IsDirty?text=IsDirty" data-throw-if-not-resolved="false"></xref> value.</p>


```csharp
public void Revert()
```
### RevertAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Attribute.yml" sourcestartlinenumber="1">Returns attribute back to it's original value. Clears <xref href="ArcGIS.Desktop.Editing.Attributes.Attribute.IsDirty?text=IsDirty" data-throw-if-not-resolved="false"></xref> value.</p>


```csharp
public Task RevertAsync()
```
### SetValue(object)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Attribute.yml" sourcestartlinenumber="1">Set the value of this attribute.</p>


```csharp
public bool SetValue(object value)
```
### SetValueAsync(object)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Attribute.yml" sourcestartlinenumber="1">Set the value for this attribute.</p>


```csharp
public Task<bool> SetValueAsync(object value)
```
### Subtypes

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Attribute.yml" sourcestartlinenumber="1">Gets the list of <xref href="ArcGIS.Desktop.Editing.Attributes.Subtype?text=subtypes" data-throw-if-not-resolved="false"></xref> for this attribute.</p>


```csharp
public ReadOnlyObservableCollection<Subtype> Subtypes { get; }
```
### Validate()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Attribute.yml" sourcestartlinenumber="1">Allows addition of custom validation logic for this attribute. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool Validate()
```
### ValidateAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Attribute.yml" sourcestartlinenumber="1">An async method which allows addition of custom validation logic for this attribute.</p>


```csharp
public Task<bool> ValidateAsync()
```


