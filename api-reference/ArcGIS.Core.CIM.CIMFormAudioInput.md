# CIMFormAudioInput

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormAudioInput.yml" sourcestartlinenumber="1">Represents an attachment input that accepts audio files.</p>


## Object Signature

```csharp
public class CIMFormAudioInput : CIMFormAttachmentInput, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFormAudioInput()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormAudioInput.yml" sourcestartlinenumber="1">Represents an attachment input that accepts audio files.</p>


```csharp
public CIMFormAudioInput()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormAudioInput.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFormAudioInput.</p>


```csharp
public CIMFormAudioInput Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormAudioInput.yml" sourcestartlinenumber="1">Reconstructs the CIMFormAudioInput with a specified state from a JSON encoding.</p>


```csharp
public static CIMFormAudioInput FromJson(string json, JsonDeserializationSettings settings = null)
```
### InputMethod

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormAudioInput.yml" sourcestartlinenumber="1">Gets or sets the supported input methods used to attach an audio file.</p>


```csharp
public FormElementInputMethod InputMethod { get; set; }
```
### MaxDuration

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormAudioInput.yml" sourcestartlinenumber="1">Gets or sets the maximum length of an attachment for this element, in seconds. If set (or defaulted) to -1,
there is no maximum.</p>


```csharp
public long MaxDuration { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormAudioInput.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormAudioInput.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFormAudioInput and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormAudioInput.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


