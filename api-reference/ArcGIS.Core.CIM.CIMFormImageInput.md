# CIMFormImageInput

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormImageInput.yml" sourcestartlinenumber="1">Represents an attachment input that accepts image files.</p>


## Object Signature

```csharp
public class CIMFormImageInput : CIMFormAttachmentInput, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFormImageInput()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormImageInput.yml" sourcestartlinenumber="1">Represents an attachment input that accepts image files.</p>


```csharp
public CIMFormImageInput()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormImageInput.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFormImageInput.</p>


```csharp
public CIMFormImageInput Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormImageInput.yml" sourcestartlinenumber="1">Reconstructs the CIMFormImageInput with a specified state from a JSON encoding.</p>


```csharp
public static CIMFormImageInput FromJson(string json, JsonDeserializationSettings settings = null)
```
### InputMethod

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormImageInput.yml" sourcestartlinenumber="1">Gets or sets the supported input methods used to attach an image.</p>


```csharp
public FormElementInputMethod InputMethod { get; set; }
```
### MaxImageSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormImageInput.yml" sourcestartlinenumber="1">Gets or sets the number of pixels on the longest edge depending on orientation. Larger images will
be resized and aspect ratio is maintained. If 'maxImageSize' is Double.NaN, images will not be
resized.</p>


```csharp
public double MaxImageSize { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormImageInput.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormImageInput.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFormImageInput and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormImageInput.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


