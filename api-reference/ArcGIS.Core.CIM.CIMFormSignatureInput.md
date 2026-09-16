# CIMFormSignatureInput

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormSignatureInput.yml" sourcestartlinenumber="1">Represents an attachment input that captures and attaches signatures.</p>


## Object Signature

```csharp
public class CIMFormSignatureInput : CIMFormAttachmentInput, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFormSignatureInput()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormSignatureInput.yml" sourcestartlinenumber="1">Represents an attachment input that captures and attaches signatures.</p>


```csharp
public CIMFormSignatureInput()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormSignatureInput.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFormSignatureInput.</p>


```csharp
public CIMFormSignatureInput Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormSignatureInput.yml" sourcestartlinenumber="1">Reconstructs the CIMFormSignatureInput with a specified state from a JSON encoding.</p>


```csharp
public static CIMFormSignatureInput FromJson(string json, JsonDeserializationSettings settings = null)
```
### InputMethod

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormSignatureInput.yml" sourcestartlinenumber="1">Gets or sets the supported input methods used to attach a signature.</p>


```csharp
public FormElementInputMethod InputMethod { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormSignatureInput.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormSignatureInput.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFormSignatureInput and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormSignatureInput.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


