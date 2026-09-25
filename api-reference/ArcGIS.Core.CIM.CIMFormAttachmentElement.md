# CIMFormAttachmentElement

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormAttachmentElement.yml" sourcestartlinenumber="1">Represents how one or more attachments can participate in the form. When present in the form, the user
has the ability to upload an attachment specific to the form element.</p>


## Object Signature

```csharp
public class CIMFormAttachmentElement : CIMFormElement, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFormAttachmentElement()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormAttachmentElement.yml" sourcestartlinenumber="1">Represents how one or more attachments can participate in the form. When present in the form, the user
has the ability to upload an attachment specific to the form element.</p>


```csharp
public CIMFormAttachmentElement()
```
### AllowUserRename

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormAttachmentElement.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the user is allowed to rename an attachment.</p>


```csharp
public bool AllowUserRename { get; set; }
```
### AttachmentInput

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormAttachmentElement.yml" sourcestartlinenumber="1">Gets or sets the input user interface to use for the attachment.</p>


```csharp
public CIMFormAttachmentInput AttachmentInput { get; set; }
```
### AttachmentKeyword

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormAttachmentElement.yml" sourcestartlinenumber="1">Gets or sets a string to identify the attachment(s). When a file is attached using the form, this
property is used to set the value of the keywords field for the attachment. When a form is
displaying existing attachments, this property is used to query attachments using an exact match on
the keywords field.</p>


```csharp
public string AttachmentKeyword { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormAttachmentElement.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFormAttachmentElement.</p>


```csharp
public CIMFormAttachmentElement Clone()
```
### Description

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormAttachmentElement.yml" sourcestartlinenumber="1">Gets or sets a string that describes the element in detail.</p>


```csharp
public string Description { get; set; }
```
### DisplayFilename

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormAttachmentElement.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the filename should be displayed. Default is 'false'.</p>


```csharp
public bool DisplayFilename { get; set; }
```
### EditableExpressionName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormAttachmentElement.yml" sourcestartlinenumber="1">Gets or sets the name of an Arcade expression that returns a boolean value. When this expression
evaluates to 'true', the element is editable. When the expression evaluates to 'false' the element
is not editable.</p>


```csharp
public string EditableExpressionName { get; set; }
```
### FilenameExpression

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormAttachmentElement.yml" sourcestartlinenumber="1">Gets or sets an Arcade expression that is evaluated to produce filenames for new attachments. If not
specified, a unique name will be generated using the 'AttachmentKeyword' and the current timestamp
when the attachment is added.</p>


```csharp
public string FilenameExpression { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormAttachmentElement.yml" sourcestartlinenumber="1">Reconstructs the CIMFormAttachmentElement with a specified state from a JSON encoding.</p>


```csharp
public static CIMFormAttachmentElement FromJson(string json, JsonDeserializationSettings settings = null)
```
### Label

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormAttachmentElement.yml" sourcestartlinenumber="1">Gets or sets a string value indicating what the element represents.</p>


```csharp
public string Label { get; set; }
```
### MaxAttachmentCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormAttachmentElement.yml" sourcestartlinenumber="1">Gets or sets the maximum number of attachments allowed for this element. If set (or defaulted) to -1,
there is no maximum.</p>


```csharp
public long MaxAttachmentCount { get; set; }
```
### MinAttachmentCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormAttachmentElement.yml" sourcestartlinenumber="1">Gets or sets the minimum number of attachments required for this element. If set (or defaulted) to 0,
no attachements are required.</p>


```csharp
public long MinAttachmentCount { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormAttachmentElement.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormAttachmentElement.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFormAttachmentElement and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseOriginalFilename

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormAttachmentElement.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the uploaded attachment's filename is preserved. If
'false', the name is updated based on 'FilenameExpression'. Default is 'true'.</p>


```csharp
public bool UseOriginalFilename { get; set; }
```
### VisibilityExpressionName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormAttachmentElement.yml" sourcestartlinenumber="1">Gets or sets the name of an Arcade expression that returns a boolean value. When this expression
evaluates to 'true', the element is displayed. When the expression evaluates to 'false' the element
is not displayed. If no expression is provided, the default behavior is that the element is
displayed.</p>


```csharp
public string VisibilityExpressionName { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormAttachmentElement.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


