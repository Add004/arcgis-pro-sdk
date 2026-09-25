# CIMFormFieldElement

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormFieldElement.yml" sourcestartlinenumber="1">Represents how a field in the dataset participates in the form.</p>


## Object Signature

```csharp
public class CIMFormFieldElement : CIMFormElement, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFormFieldElement()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormFieldElement.yml" sourcestartlinenumber="1">Represents how a field in the dataset participates in the form.</p>


```csharp
public CIMFormFieldElement()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormFieldElement.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFormFieldElement.</p>


```csharp
public CIMFormFieldElement Clone()
```
### Description

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormFieldElement.yml" sourcestartlinenumber="1">Gets or sets a string that describes the element in detail.</p>


```csharp
public string Description { get; set; }
```
### Domain

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormFieldElement.yml" sourcestartlinenumber="1">Gets or sets the domain to apply to this field. If defined, it takes precedence over domains
defined in field, type, or subtype.</p>


```csharp
public CIMFormDomain Domain { get; set; }
```
### EditableExpressionName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormFieldElement.yml" sourcestartlinenumber="1">Gets or sets the name of an Arcade expression that returns a boolean value. When this expression
evaluates to 'true', the element is editable. When the expression evaluates to 'false' the element
is not editable. If the referenced field is not editable, the editable expression is ignored and
the element is not editable.</p>


```csharp
public string EditableExpressionName { get; set; }
```
### FieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormFieldElement.yml" sourcestartlinenumber="1">Gets or sets a string containing the field name as defined by the layer or table.</p>


```csharp
public string FieldName { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormFieldElement.yml" sourcestartlinenumber="1">Reconstructs the CIMFormFieldElement with a specified state from a JSON encoding.</p>


```csharp
public static CIMFormFieldElement FromJson(string json, JsonDeserializationSettings settings = null)
```
### Hint

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormFieldElement.yml" sourcestartlinenumber="1">Gets or sets a string representing placeholder text. This only applies for input types that support
text or numeric entry.</p>


```csharp
public string Hint { get; set; }
```
### Input

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormFieldElement.yml" sourcestartlinenumber="1">Gets or sets the input user interface to use for the element.</p>


```csharp
public CIMFormInput Input { get; set; }
```
### Label

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormFieldElement.yml" sourcestartlinenumber="1">Gets or sets a string indicating what the element represents. If not supplied, the label is derived
from the alias property in the referenced field in the service.</p>


```csharp
public string Label { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormFieldElement.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RequiredExpressionName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormFieldElement.yml" sourcestartlinenumber="1">Gets or sets the name of an Arcade expression that returns a boolean value. When this expression
evaluates to 'true' and the element is visible, the element must have a valid value in order for
the feature to be created or edited. When the expression evaluates to 'false' the element is not
required. If no expression is provided, the default behavior is that the element is not required.
If the referenced field is non-nullable, the required expression is ignored and the element is
always required.</p>


```csharp
public string RequiredExpressionName { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormFieldElement.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFormFieldElement and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### ValueExpressionName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormFieldElement.yml" sourcestartlinenumber="1">Gets or sets the name of an Arcade expression that returns a date, number, or string value.
When this expression evaluates the value of the field will be updated to the result. This
expression is only evaluated when 'editableExpression' (if defined) is false but the field itself
allows edits.</p>


```csharp
public string ValueExpressionName { get; set; }
```
### VisibilityExpressionName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormFieldElement.yml" sourcestartlinenumber="1">Gets or sets the name of an Arcade expression that returns a boolean value. When this expression
evaluates to 'true', the element is displayed. When the expression evaluates to 'false' the element
is not displayed. If no expression is provided, the default behavior is that the element is
displayed. Care must be taken when defining a visibility expression for a non-nullable field i.e.
to make sure that such fields either have default values or are made visible to users so that they
can provide a value before submitting the form.</p>


```csharp
public string VisibilityExpressionName { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormFieldElement.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


