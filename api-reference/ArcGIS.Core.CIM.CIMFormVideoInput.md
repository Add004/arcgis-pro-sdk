# CIMFormVideoInput

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormVideoInput.yml" sourcestartlinenumber="1">Represents an attachment input that accepts that a video file should be attached.</p>


## Object Signature

```csharp
public class CIMFormVideoInput : CIMFormAttachmentInput, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFormVideoInput()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormVideoInput.yml" sourcestartlinenumber="1">Represents an attachment input that accepts that a video file should be attached.</p>


```csharp
public CIMFormVideoInput()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormVideoInput.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFormVideoInput.</p>


```csharp
public CIMFormVideoInput Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormVideoInput.yml" sourcestartlinenumber="1">Reconstructs the CIMFormVideoInput with a specified state from a JSON encoding.</p>


```csharp
public static CIMFormVideoInput FromJson(string json, JsonDeserializationSettings settings = null)
```
### InputMethod

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormVideoInput.yml" sourcestartlinenumber="1">Gets or sets the supported input methods used to attach a video.</p>


```csharp
public FormElementInputMethod InputMethod { get; set; }
```
### MaxDuration

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormVideoInput.yml" sourcestartlinenumber="1">Gets or sets the defines the maximum length of an attachment for this element, in seconds. If set
(or defaulted) to -1, there is no maximum length.</p>


```csharp
public long MaxDuration { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormVideoInput.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormVideoInput.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFormVideoInput and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormVideoInput.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


