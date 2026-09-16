# CIMFormSupportedAttachmentsInput

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormSupportedAttachmentsInput.yml" sourcestartlinenumber="1">Represents the kinds of supported files for attachment.</p>


## Object Signature

```csharp
public class CIMFormSupportedAttachmentsInput : CIMFormAttachmentInput, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFormSupportedAttachmentsInput()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormSupportedAttachmentsInput.yml" sourcestartlinenumber="1">Represents the kinds of supported files for attachment.</p>


```csharp
public CIMFormSupportedAttachmentsInput()
```
### AttachmentAssociationType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormSupportedAttachmentsInput.yml" sourcestartlinenumber="1">Gets or sets whether existing attachments should be associated with this element. 'Any'
will associate all existing attachments to this form element; this can be the only
'formAttachmentElement' within the form. 'ExactOrNone' will associate any attachments with the
associated 'keyword' and any attachments with no keyword defined; only one form element can have
this value defined. 'Exact' will associate only attachments that include the specific keyword.</p>


```csharp
public FormAttachmentAssociationType AttachmentAssociationType { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormSupportedAttachmentsInput.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFormSupportedAttachmentsInput.</p>


```csharp
public CIMFormSupportedAttachmentsInput Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormSupportedAttachmentsInput.yml" sourcestartlinenumber="1">Reconstructs the CIMFormSupportedAttachmentsInput with a specified state from a JSON encoding.</p>


```csharp
public static CIMFormSupportedAttachmentsInput FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormSupportedAttachmentsInput.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SupportedInputs

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormSupportedAttachmentsInput.yml" sourcestartlinenumber="1">Gets or sets the available inputs to add an attachment. (Nesting is not supported - CIMFormAttachmentInputs
should not be added to this collection.)</p>


```csharp
public CIMFormAttachmentInput[] SupportedInputs { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormSupportedAttachmentsInput.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFormSupportedAttachmentsInput and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormSupportedAttachmentsInput.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


