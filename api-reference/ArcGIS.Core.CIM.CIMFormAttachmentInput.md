# CIMFormAttachmentInput

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormAttachmentInput.yml" sourcestartlinenumber="1">Represents the kinds of attachements that may be uploaded via a form attachment
element. There are subclasses for audio, images, video, and so on.</p>


## Object Signature

```csharp
public abstract class CIMFormAttachmentInput : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFormAttachmentInput()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormAttachmentInput.yml" sourcestartlinenumber="1">Represents the kinds of attachements that may be uploaded via a form attachment
element. There are subclasses for audio, images, video, and so on.</p>


```csharp
protected CIMFormAttachmentInput()
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormAttachmentInput.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormAttachmentInput.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


